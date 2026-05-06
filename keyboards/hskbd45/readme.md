<<<<<<< HEAD
# hskbd45

![hskbd45](imgur.com image replace me!)

*A short description of the keyboard/project*

* Keyboard Maintainer: [hakumaru12](https://github.com/hakumaru12)
* Hardware Supported: *The PCBs, controllers supported*
* Hardware Availability: *Links to where you can find this hardware*

Make example for this keyboard (after setting up your build environment):

    make hskbd45:default

Flashing example for this keyboard:

    make hskbd45:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
=======
HSKBD45 — QMK keyboard source

This folder contains the QMK keyboard definition and VIA keymap for HSKBD45 (Pro Micro).

Files:
- keyboard.json — metadata
- keymaps/via/* — VIA keymap
- rules.mk — build options
>>>>>>> 08399f13fc68ed8011ed16941ca2ba23021bf2ae
