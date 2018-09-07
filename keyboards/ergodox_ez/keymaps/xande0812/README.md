keymap
===========

## How to build

    cd /path/to/qmk_firmware
    # fish
    docker run -e keymap=xande0812 -e keyboard=ergodox_ez --rm -v (pwd):/qmk:rw edasque/qmk_firmware
