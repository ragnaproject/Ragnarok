
Debian
====================
This directory contains files used to package ragnarokd/ragnarok-qt
for Debian-based Linux systems. If you compile ragnarokd/ragnarok-qt yourself, there are some useful files here.

## ragnarok: URI support ##


ragnarok-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ragnarok-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ragnarokqt binary to `/usr/bin`
and the `../../share/pixmaps/ragnarok128.png` to `/usr/share/pixmaps`

ragnarok-qt.protocol (KDE)

