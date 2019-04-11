
Debian
====================
This directory contains files used to package excoind/excoin-qt
for Debian-based Linux systems. If you compile excoind/excoin-qt yourself, there are some useful files here.

## excoin: URI support ##


excoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install excoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your excoinqt binary to `/usr/bin`
and the `../../share/pixmaps/excoin128.png` to `/usr/share/pixmaps`

excoin-qt.protocol (KDE)

