
Debian
====================
This directory contains files used to package securyptod/securypto-qt
for Debian-based Linux systems. If you compile securyptod/securypto-qt yourself, there are some useful files here.

## securypto: URI support ##


securypto-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install securypto-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your securyptoqt binary to `/usr/bin`
and the `../../share/pixmaps/securypto128.png` to `/usr/share/pixmaps`

securypto-qt.protocol (KDE)

