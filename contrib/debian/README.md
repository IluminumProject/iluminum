
Debian
====================
This directory contains files used to package iluminumd/iluminum-qt
for Debian-based Linux systems. If you compile iluminumd/iluminum-qt yourself, there are some useful files here.

## iluminum: URI support ##


iluminum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install iluminum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your iluminum-qt binary to `/usr/bin`
and the `../../share/pixmaps/iluminum128.png` to `/usr/share/pixmaps`

iluminum-qt.protocol (KDE)

