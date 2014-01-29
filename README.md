spotify-client-installer
========================

A Open Source installer for Spotify for Fedora

This script avoids the need to illegally redistribute Spotify binaries by downloading the Linux client .deb from repository.spotify.com, installing it along with some evil hacks to provide the necessary libraries where Spotify expects them to be.

Currently only Fedora 20 is supported.

Requires:	desktop-file-utils ffmpeg-compat alsa-lib glibc libXScrnSaver qtwebkit

Requires:	nspr nss nss-util systemd-libs openssl-libs openssl0.9.8-spotify libgcrypt xterm wget binutils
