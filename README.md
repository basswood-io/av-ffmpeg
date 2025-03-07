# av-ffmpeg

This project provides binary builds of FFmpeg and its dependencies for Cython projects. These builds are used in order to provide binary wheels, allowing users to easily install software without perform error-prone compilations.

The builds are provided for several platforms:
 - Linux (x86\_64, i686, aarch64)
 - macOS (x86\_64, arm64)
 - Windows (AMD64)

## Features
Currently FFmpeg 7.1.1 is built with the following packages enabled for all platforms:

- gmp 6.3.0
- xml2 2.9.13
- xz 5.6.3
- aom 3.11.0
- dav1d 1.4.1
- libsvtav1 3.0.0
- lame 3.100
- ogg 1.3.5
- opus 1.5.2
- speex 1.2.1
- twolame 0.4.0
- vorbis 1.3.7
- vpx 1.14.0
- png 1.6.45
- webp 1.5.0
- openh264 2.5.0
- fdk\_aac 2.0.3

The following additional packages are also enabled on Linux:

- gnutls 3.8.1
- nettle 3.9.1
- unistring 1.2

