# Welcome to my project BLE-9100

How to Flash?

Use esptool.

First of all, please install esptool from here: https://github.com/espressif/esptool
Download the latest binary file
Now you need to open the BLE-9100 and find the ESP8266EX Chip.
Now you have to solder the 3.3V Cable to Pin XX.
The Groundcable to th -Pin of the Battery
The TX Cable to RX-Pin of and the RX Cable to the Tx-Pin of the ESP.
<img src="https://wiki.tinkernet.ca/images/7/75/ESP8266-Pinout.jpeg">
like in the Photo.
Execute this command:

esptool.py write_flash 0x0 ./BLE-9100_XXX.bin

and Done :-)