
Debian
====================
This directory contains files used to package chavezcoind/chavezcoin-qt
for Debian-based Linux systems. If you compile chavezcoind/chavezcoin-qt yourself, there are some useful files here.

## chavezcoin: URI support ##


chavezcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install chavezcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your chavezcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/chavezcoin128.png` to `/usr/share/pixmaps`

chavezcoin-qt.protocol (KDE)

