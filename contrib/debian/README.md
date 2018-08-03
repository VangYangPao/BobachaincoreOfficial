
Debian
====================
This directory contains files used to package bobachaind/bobachain-qt
for Debian-based Linux systems. If you compile bobachaind/bobachain-qt yourself, there are some useful files here.

## bobachain: URI support ##


bobachain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bobachain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bobachain-qt binary to `/usr/bin`
and the `../../share/pixmaps/bobachain128.png` to `/usr/share/pixmaps`

bobachain-qt.protocol (KDE)

