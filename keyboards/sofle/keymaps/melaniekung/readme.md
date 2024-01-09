# QMK Keyboard Firmware

## Documentations

* [Sofle Docs](https://josefadamcik.github.io/SofleKeyboard/build_guide.html)
* [QMK Docs](https://docs.qmk.fm)
* [QMK Config Test](https://config.qmk.fm/#/test)

## Compile to .uf2

`qmk compile -kb sofle/rev1 -km melaniekung -e CONVERT_TO=promicro_rp2040`

## Flash sofle split keyboard

* Plug in keyboard (TRRS then USB-C).
* Open Finder.
* Press the reset button on the left keyboard.
* Notice the new drive detected.
* Drag/drop `sofle_rev1_melaniekung_promicro_rp2040.uf2` into the new drive.
* Left OLED will flash, indicating that it's done.
