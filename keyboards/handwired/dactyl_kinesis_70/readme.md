# handwired/dactyl_kinesis_70

![handwired/dactyl_kinesis_70](imgur.com image replace me!)

* 70 key version of dactyl_kinesis*

* Keyboard Maintainer: [tymmothy](https://github.com/tymmothy)
* Hardware Supported: *Elite-C using software serial*
* Hardware Availability: *Custom*

Make example for this keyboard (after setting up your build environment):

    make handwired/dactyl_kinesis_70:default

Flashing example for this keyboard:

    make handwired/dactyl_kinesis_70:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard.  Note this is called (5,0) on the right half, which is the upper right key
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
