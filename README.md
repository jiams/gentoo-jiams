gentoo-jiams
============

the overlay for my custom ebuilds

How to use this overlay
========================


Add https://raw.github.com/jiams/gentoo-jiams/master/gentoo-jiams.xml to overlays section in /etc/layman/layman.cfg.

Or read the instructions on the Gentoo Wiki, then invoke the following:

layman -f -a gentoo-jiams
After performing those steps, the following should work (or any other package from this overlay):

sudo emerge -av xxx
