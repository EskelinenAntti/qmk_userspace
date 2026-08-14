# QMK Userspace

QMK keymaps for my keyboards.

## Keymaps

### Voyager

Customized and simplified iteration of my [Oryx Keymap](https://configure.zsa.io/voyager/layouts/LzDWL/latest/0). The main customization which is not possible in Oryx is disabling flow tap for `f` and `j` keys when either is used as shift for faster typing experience.

## QMK setup

1. Run the normal `qmk setup` procedure if you haven't already done so -- see [QMK Docs](https://docs.qmk.fm/#/newbs) for details.
1. Enable userspace in QMK config using `qmk config user.overlay_dir="$(realpath qmk_userspace)"`

## Flashing

1. `qmk flash -kb zsa/voyager -km eskelinenantti`

Alternatively, if you configured your build targets above, you can use `qmk userspace-compile` to build all of your userspace targets at once.

