
Debian
====================
This directory contains files used to package lilid/lili-qt
for Debian-based Linux systems. If you compile lilid/lili-qt yourself, there are some useful files here.

## lili: URI support ##


lili-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lili-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your liliqt binary to `/usr/bin`
and the `../../share/pixmaps/lili128.png` to `/usr/share/pixmaps`

lili-qt.protocol (KDE)

