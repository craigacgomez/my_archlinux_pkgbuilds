# My Personal Collection Arch Linux PKGBUILDS

    1. chromium-incognito : Opens Chromium in incognito mode by default
    2. firefox-private : Opens Firefox in private browsing mode by default
    3. drop-caches : Systemd timer to drop kernel VM caches every 15 minutes
    4. network-hardening : Sysctl tweaks for network hardening (Sourced from various websites including the Archlinux Wiki)
    5. udev-zram : Swap on zRAM using a udev rule (https://wiki.archlinux.org/index.php/Improving\_performance#Swap_on_zRAM_using_a_udev_rule)
    6. openprinting-ppds-postscript-lanier : PostScript OpenPrinting PPDs for Lanier printers provided by Ricoh (http://www.openprinting.org/driver/Postscript-Lanier)
    7. openprinting-ppds-pxlcolor-lanier : PCL XL (PXLColor) OpenPrinting PPDs for Lanier printers provided by Ricoh (http://www.openprinting.org/driver/pxlcolor-Lanier)
    8. thunar : Tunar (XFCE File Manager) with an upstream patch to attempt to fix the move files crash (https://github.com/xfce-mirror/thunar/commit/029012f4c39d9d3d9ae617491a69f76f54a4192f)
    9. xflock4-light-locker : Locks the screen using Light Locker in XFCE using the default xflock4 command
    10. flashpluin-beta : Beta version 23 of the Abobe Flash Player NPAPI plugin (http://labs.adobe.com/downloads/flashplayer.html)
    11. harmony-music-player : An I-Tunes like music player built using Electron with local files support and cloud music support like Google Play Music and Amazon Prime Music (http://getharmony.xyz)


# Details:
    1. These packages are for Arch and Arch-based distributions
    2. None of the packages provided here are prebuilt packages. You have to build them using makepkg.
       To build and install a packages, download all files in that folder and build using makepkg -sci.
       You must have the packages group 'base-devel' installed.
    3. If you choose to use them, you are solely responsible for any consqeuences or negative impacts.
       They are, however, not untested as I personally use them.
       It is always a good idea to understand the details of any unofficial packages (including the ones I provide here) before using them.
       