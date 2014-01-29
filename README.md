spotify-client-installer
========================

A Open Source Spotify installer for Fedora

This script avoids the need to illegally redistribute Spotify binaries without add the .deb to Source:,  into ".spec"/rpm/src.rpm; installing it along with some hacks to provide the necessary libraries where Spotify expects them to be.

Currently only Fedora 20 is supported.

Requires:	desktop-file-utils ffmpeg-compat alsa-lib glibc libXScrnSaver qtwebkit

Requires:	nspr nss nss-util systemd-libs openssl-libs openssl0.9.8-spotify libgcrypt xterm wget binutils


INSTALLATION

su -c 'yum -y install http://sourceforge.net/projects/postinstaller/files/fedora/releases/20/x86_64/updates/spotify-client-0.9.4.183.g644e24e.428-2.fc20.noarch.rpm/'



SOURCE RPM

http://sourceforge.net/projects/postinstaller/files/fedora/releases/20/SRPM/spotify-client-0.9.4.183.g644e24e.428-2.fc20.src.rpm

