# Copt37

![COPT37](https://i.imgur.com/puf3pA6.jpeg)

A 37-key keyboard with English and Coptic keycap legends. [Vial](https://get.vial.today/) compatible.

* Keyboard Maintainer: [Starry Knight](https://github.com/astarryknight)
* Hardware Supported: rp2040 (using the adafruit kb2040), firmware written for ATmega32U4
* Hardware Availability: Amazon (https://amazon.com) & Digikey (https://https://www.digikey.com/)

Make example for this keyboard (after setting up your build environment):

    make copt37:default

Flashing example for this keyboard:

    make copt37:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
