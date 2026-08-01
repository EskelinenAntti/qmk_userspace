# QMK Userspace

QMK keymaps for my keyboards.

## QMK setup

1. Run the normal `qmk setup` procedure if you haven't already done so -- see [QMK Docs](https://docs.qmk.fm/#/newbs) for details.
1. Enable userspace in QMK config using `qmk config user.overlay_dir="$(realpath qmk_userspace)"`

## Flashing

1. `qmk flash -kb your_keyboard -km your_keymap`

Alternatively, if you configured your build targets above, you can use `qmk userspace-compile` to build all of your userspace targets at once.

