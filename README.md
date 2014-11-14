tinyisp-micro
=============

My USBTinyISP (with an ATTiny44)

Available from OSH Park here:
	https://oshpark.com/shared_projects/ijclv4pr

BOM Is pretty cheap.  Check the kicad folder for more info.

Firmware is slightly modified from the regular USBTinyISP.

I recommend flashing using the .hex file provided in:
	firmware/spi/main.hex.

Flash the AVR by conneting the "PGM" pin and another programmer.

Don't forget fuses!!!

Once flashed, disconnect the "pgm" option and connect the "REG" option.


