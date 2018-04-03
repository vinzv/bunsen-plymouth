# bunsen-plymouth
BunsenLabs Beam plymouth theme

## Screenshot
![Screenshot BunsenLabs Beam](https://raw.github.com/vinzv/bunsen-plymouth/master/screenshot.png?raw=true "Screenshot BunsenLabs Beam")

## How to use

* ``cd /usr/share/plymouth/themes/``
* ``sudo git clone https://github.com/vinzv/bunsen-plymouth-one.git bunsenlabs-beam``
* ``sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/bunsenlabs-beam/bunsenlabs-beam.plymouth 100``
* ``sudo update-alternatives --config default.plymouth``
* ``sudo update-initramfs -u -k all``

## Authors
* Written by: Alberto Milone <alberto.milone@canonical.com>
* Adapted to budgie-remix by: HEXcube <hexcubed@gmail.com> and David Mohammed <foss.freedom@gmail.com>
* Adapted to TUXEDO Computers by: Vinzenz Vietzke <tux@tuxedocomputers.com>
* Adapted for BunsenLabs by: Vinzenz Vietzke <vinz@vinzv.de>
* Based on the example provided with the "script plugin" written by Charlie Brej <cbrej@cs.man.ac.uk>
* Question stuff written by Markus Waas <mail@markuswaas.de>
