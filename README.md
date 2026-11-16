# Compress

Compress is a free video compressor for Android. It makes the videos on a phone smaller without a difference you can see, at the full picture size, and carries on with the screen off. The work is done on the phone, so videos are never uploaded. It has no adverts, no accounts and no paid version.

This repository holds the app's public website and its source code.

## Website

- [Home page](https://customgpter.github.io/compress/)
- [How it compares with other video compressors](https://customgpter.github.io/compress/compare.html)
- [Release notes](https://customgpter.github.io/compress/releases.html)
- [More apps from the same developer](https://customgpter.github.io/compress/more-apps.html)
- [Privacy policy](https://customgpter.github.io/compress/privacy.html)
- [Terms of use](https://customgpter.github.io/compress/terms.html)
- [Licences and credits](https://customgpter.github.io/compress/licences.html)

The latest version of the app is on the [Releases page](https://github.com/CustomGPTer/compress/releases/latest).

The site is plain HTML and CSS with no scripts, cookies or tracking, and is served by GitHub Pages from the `main` branch.

## Source code

The Android app is in the [`android`](android) folder. It is written in Kotlin with Jetpack Compose, and builds with `./gradlew assembleDebug` given JDK 21 and the Android SDK. [`android/README.md`](android/README.md) says more.

The Max quality engine runs FFmpeg with the x264 and x265 encoders. The built program is in the source tree, the script that builds it is in [`android/native`](android/native), and the encoders' own source code is attached to each release as `compress-encoder-sources.zip`.

## Licence

Copyright &copy; 2026 Jonathan Jackson

Compress is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. It is distributed in the hope that it will be useful, but without any warranty. See [`LICENSE`](LICENSE).

## Contact

For a question about the app, a problem, or anything about your data, [open an issue](https://github.com/CustomGPTer/compress/issues). Issues are public, so please leave personal details out.
