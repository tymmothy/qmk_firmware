# handwired/dactyl_manuform/6x6/keymaps/tymmothy

* Keymap shifted up one (numbers at top) vs default
* Hardware Supported: *Promicro*
* Uses EE_HANDS (use avrdude-split-left / avrdude-split-right bootloader)

To build using QMK CLI:
    qmk compile -kb handwired/dactyl_manuform/6x6 -km tymmothy

To flash:
    qmk flash -kb handwired/dactyl_manuform/6x6 -km tymmothy -bl avrdude-split-left
    qmk flash -kb handwired/dactyl_manuform/6x6 -km tymmothy -bl avrdude-split-right

Make example for this keyboard (after setting up your build environment):

    make handwired/dactyl_manuform/6x6:tymmothy
