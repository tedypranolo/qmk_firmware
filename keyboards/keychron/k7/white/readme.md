# Keychron K7 White

Hardware Supported: SN32F260

Make example for this keyboard (after setting up your build environment):

    make keychron/k7/white:ansi

This keyboard uses a stripped down version of SN32F248B, which can be
found in the K7 RGB version. Mind it is far more easily to brick this
keyboard than its beefer sibling; SWD due to board design is
unusable. Use [bootloader](https://github.com/SonixQMK/sonix-keyboard-bootloader).

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
