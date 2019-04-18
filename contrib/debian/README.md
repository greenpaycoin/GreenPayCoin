
Debian
====================
This directory contains files used to package GreenPayCoind/GreenPayCoin-qt
for Debian-based Linux systems. If you compile GreenPayCoind/GreenPayCoin-qt yourself, there are some useful files here.

## GreenPayCoin: URI support ##


GreenPayCoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install GreenPayCoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your GreenPayCoinqt binary to `/usr/bin`
and the `../../share/pixmaps/GreenPayCoin128.png` to `/usr/share/pixmaps`

GreenPayCoin-qt.protocol (KDE)

