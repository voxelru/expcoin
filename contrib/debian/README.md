
Debian
====================
This directory contains files used to package expcoind/expcoin-qt
for Debian-based Linux systems. If you compile expcoind/expcoin-qt yourself, there are some useful files here.

## expcoin: URI support ##


expcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install expcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your expcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/expcoin128.png` to `/usr/share/pixmaps`

expcoin-qt.protocol (KDE)

