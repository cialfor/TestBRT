
Debian
====================
This directory contains files used to package barthord/barthor-qt
for Debian-based Linux systems. If you compile barthord/barthor-qt yourself, there are some useful files here.

## barthor: URI support ##


barthor-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install barthor-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your barthorqt binary to `/usr/bin`
and the `../../share/pixmaps/barthor128.png` to `/usr/share/pixmaps`

barthor-qt.protocol (KDE)

