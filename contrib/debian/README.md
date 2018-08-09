
Debian
====================
This directory contains files used to package Cryptocashbackd/Cryptocashback-qt
for Debian-based Linux systems. If you compile Cryptocashbackd/Cryptocashback-qt yourself, there are some useful files here.

## Cryptocashback: URI support ##


Cryptocashback-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Cryptocashback-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Cryptocashbackqt binary to `/usr/bin`
and the `../../share/pixmaps/Cryptocashback128.png` to `/usr/share/pixmaps`

Cryptocashback-qt.protocol (KDE)

