# thera 75 V2
A 75% keyboard

TODO add image


### Features

TODO

* Fixed the via support, which never worked for me

### Additional Information
* Keyboard Maintainer: [fpn](https://github.com/fpn/qmk_firmware)
* Hardware Supported: thera75v2 hotswap PCB
* Hardware Availability: [creatkeebs.com](https://createkeebs.com/collections/thera75-v2)

### Entering Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the ESC key at (0,0) in the matrix (the top left key) and plug in the keyboard
* Physical reset button: Press the `RESET` button on the back of the PCB.
* Keycode in layout: Press the key mapped to `QK_BOOT` if it is available.

### Building the Firmware
Build the via firmware for this keyboard (after setting up your build environment):

  qmk compile -kb creatkeebs/therav2 -km via

Flash the firmware:

  qmk flash -kb creatkeebs/therav2 -km vi

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
