gentoo-overlay
==============

Overlay for Gentoo/Linux packages

The following packages are available in this overlay:

* simplescreenrecorder - http://www.maartenbaert.be/simplescreenrecorder)

## Installing
This overlay is not official and not available in layman.
To use this repository you need to add it manually.

Modify /etc/layman/layman.cfg. Modify the overlays part to (if you don't already have other repository sources):

    overlays  : http://www.gentoo.org/proj/en/overlays/repositories.xml
                http://anders-larsson.github.io/gentoo-overlay/repositories.xml
