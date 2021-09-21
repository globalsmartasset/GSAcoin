
Debian
====================
This directory contains files used to package gsad/gsa-qt
for Debian-based Linux systems. If you compile gsad/gsa-qt yourself, there are some useful files here.

## globalsmartasset: URI support ##


gsa-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gsa-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gsa-qt binary to `/usr/bin`
and the `../../share/pixmaps/gsa128.png` to `/usr/share/pixmaps`

gsa-qt.protocol (KDE)

