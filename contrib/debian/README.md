
Debian
====================
This directory contains files used to package mnpostreed/mnpostree-qt
for Debian-based Linux systems. If you compile mnpostreed/mnpostree-qt yourself, there are some useful files here.

## mnpostree: URI support ##


mnpostree-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mnpostree-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mnpostree-qt binary to `/usr/bin`
and the `../../share/pixmaps/mnpostree128.png` to `/usr/share/pixmaps`

mnpostree-qt.protocol (KDE)

