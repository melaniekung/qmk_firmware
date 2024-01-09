# QMK Keyboard Firmware

## Documentations

* [Sofle Docs](https://josefadamcik.github.io/SofleKeyboard/build_guide.html)
* [QMK Docs](https://docs.qmk.fm)
* [QMK Config Test](https://config.qmk.fm/#/test)

## Compile to .uf2

`qmk compile -kb sofle/rev1 -km melaniekung -e CONVERT_TO=promicro_rp2040`

## Flash sofle split keyboard

`qmk flash -kb sofle/rev1 -km melaniekung -e CONVERT_TO=promicro_rp2040`

* Unlug in keyboard (USB-C).
* Press and hold the reset button on the right keyboard.
* Plugin in keyboard (while holding the reset button).