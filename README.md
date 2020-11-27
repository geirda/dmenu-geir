# dmenu-geir 5.0

Patches included:

* lineheight

This build of dmenu uses the following font:

* hack

Hack font is usually found in your distro's repo. For Debian-based systems:

	$ sudo apt install fonts-hack

For Arch-based systems:

	$ pacman -S ttf-hack

## Installation

Clone this repo and compile from source:

	$ git clone https://github.com/geirda/dmenu-geir.git
	$ cd dmenu-geir
	$ sudo make clean install

## For Arch users:

Download the file PKGBUILD, create and install the package:

	$ wget https://raw.githubusercontent.com/geirda/dmenu-geir/main/PKGBUILD
	$ makepkg -i

Precompiled packages for Arch: https://github.com/geirda/Arch/tree/master/suckless/dmenu/


![suckless](https://raw.githubusercontent.com/geirda/Arch/master/suckless/suckless.png)
