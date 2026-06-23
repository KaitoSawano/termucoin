
Debian
====================
This directory contains files used to package termucoind/termucoin-qt
for Debian-based Linux systems. If you compile termucoind/termucoin-qt yourself, there are some useful files here.

## termucoin: URI support ##


termucoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install termucoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your termucoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/termucoin128.png` to `/usr/share/pixmaps`

termucoin-qt.protocol (KDE)

