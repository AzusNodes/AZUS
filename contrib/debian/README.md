
Debian
====================
This directory contains files used to package azusd/azus-qt
for Debian-based Linux systems. If you compile azusd/azus-qt yourself, there are some useful files here.

## azus: URI support ##


azus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install azus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your azus-qt binary to `/usr/bin`
and the `../../share/pixmaps/azus128.png` to `/usr/share/pixmaps`

azus-qt.protocol (KDE)

