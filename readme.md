1. git clone --recurse-submodules git@github.com:qmk/qmk_firmware.git
2. qmk setup -H [pwd]
3. add keymaps from this repo [cp -R ../qmk/* .]
4. compile and enjoy
*  `make crkbd:janvanrensbergen`
* `make planck/rev6:janvanrensbergen`
* `qmk compile -kb gmmk/gmmk2/p96/ansi -km janvanrensbergen` or `make gmmk/gmmk2/p96/ansi:janvanrensbergen`


