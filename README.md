# jdwm
My fork of dwm, an extremely fast, small, and dynamic window manager for X.

## Applied Patches
- [Single Tagset](https://dwm.suckless.org/patches/single_tagset/)
- [Focus on Click](https://dwm.suckless.org/patches/focusonclick/)
- [Swallow](https://dwm.suckless.org/patches/swallow/)
- [Hide Vacant Tags](https://dwm.suckless.org/patches/hide_vacant_tags/)
- [Tag Labels](https://dwm.suckless.org/patches/taglabels/)
- [Status2d](https://dwm.suckless.org/patches/status2d/)

## Installation
Enter the following command to build and install dwm (if necessary as root):

`make clean install`


## Running dwm
Add the following line to your .xinitrc to start dwm using startx:

`exec dwm`

## Configuration
The configuration of dwm is done by creating a custom config.h and (re)compiling the source code.
