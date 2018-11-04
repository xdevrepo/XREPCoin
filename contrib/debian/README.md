
Debian
====================
This directory contains files used to package XREPd/XREP-qt
for Debian-based Linux systems. If you compile XREPd/XREP-qt yourself, there are some useful files here.

## XREP: URI support ##


XREP-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install XREP-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to XREP the paths in
the .desktop file or copy or symlink your XREPqt binary to `/usr/bin`
and the `../../share/pixmaps/XREP128.png` to `/usr/share/pixmaps`

XREP-qt.protocol (KDE)

