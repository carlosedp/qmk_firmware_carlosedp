# QMK Firmware for the Epomaker TH40

This firmware is for the Epomaker TH40, a 40% mechanical keyboard. It is based on QMK Firmware and includes custom keymaps and features.

The files were collected and fixed to provide a working QMK firmware for the Epomaker TH40.

àfter setting up your build environment, you can compile and flash the firmware using the following commands:

    make epomaker/th40:default

or

    qmk compile -kb epomaker/th40 -km default

A precompiled bin file and the VIA mapping are available in the `releases` section of this repository.
