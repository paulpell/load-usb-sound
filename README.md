load-usb-sound
==============

script to load the firmware for supported usb audio cards on linux

Requirements
------------

The script uses madfuload, which is found [here](http://sourceforge.net/projects/usb-midi-fw/files/madfu-firmware/1.2/). I had troubles with version 1.2, so I used 0.9. asoundconf from ALSA is needed to set the sound card, and perl is used to read some values.
In addition, you will need the firmware for your card. They are available for a few devices in madfuload-1.2.tar.gz.
