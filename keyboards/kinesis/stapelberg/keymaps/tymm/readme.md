To use QMK DFU bootloader

make kinesis/stapelberg:tymm:production

and use the generated bootloader file:
avrdude -p usb1286 -c  avrisp2 -Uflash:w:../kinesis_stapelberg_tymm_production.hex:i

Fuses should be set to E: f2 H: 99 L: 5e
see https://www.engbedded.com/conffuse/

Loading:
qmk flash -kb kinesis/stapelberg -km tymm

