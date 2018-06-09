
Debian
====================
This directory contains files used to package apollond/apollon-qt
for Debian-based Linux systems. If you compile apollond/apollon-qt yourself, there are some useful files here.

## apollon: URI support ##


apollon-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install apollon-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your apollonqt binary to `/usr/bin`
and the `../../share/pixmaps/apollon128.png` to `/usr/share/pixmaps`

apollon-qt.protocol (KDE)

