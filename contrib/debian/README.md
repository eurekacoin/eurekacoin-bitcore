
Debian
====================
This directory contains files used to package eurekacoind/eurekacoin-qt
for Debian-based Linux systems. If you compile eurekacoind/eurekacoin-qt yourself, there are some useful files here.

## eurekacoin: URI support ##


eurekacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eurekacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eurekacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

eurekacoin-qt.protocol (KDE)

