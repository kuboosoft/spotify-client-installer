spotify-client-installer
========================

A Open Source Spotify installer for Fedora

This script avoids the need to illegally redistribute Spotify binaries without add the .deb to Source: into .spec/rpm/src.rpm; installing it along with some hacks to provide the necessary libraries where Spotify expects them to be.

Currently only Fedora 20 is supported.

Requires:	desktop-file-utils ffmpeg-compat alsa-lib glibc libXScrnSaver qtwebkit

Requires:	nspr nss nss-util systemd-libs openssl-libs openssl0.9.8-spotify libgcrypt xterm wget binutils
