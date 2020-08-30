# hp-netscan
Modified version of xaviermiller's hp "scan to folder" scripts over at https://forums.gentoo.org/viewtopic-t-1061884-start-0.html
With inclusions taken from Nicolas Bernaerts over at http://www.bernaerts-nicolas.fr/linux/75-debian/266-debian-hp-aio-scan-to-folder-server

I did not write the originals. The LICENSE file is only present because it asked me to put one there.
These scripts are tweaked for my configuration. They almost certainly won't work for you without modification.

Requires HPLIP, sane-utils, and imagemagick. HPLIP setup is a .py file, must be run with -i. Quit before setting up fax (not needed).
Service, once registered, must be started with "service hp-netscan start" and enabled with "systemctl enable hp-netscan".
*Might* require a reboot first.
