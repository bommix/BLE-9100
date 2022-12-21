# Welcome to my project BLE-9100

How to Flash?

Use esptool.

First of all, please install esptool from here: https://github.com/espressif/esptool
Download the latest binary file
Now you need to open the BLE-9100 and find the ESP32 Chip.
The Groundcable to th -Pin of the Battery
The TX Cable to RX-Pin of and the RX Cable to the Tx-Pin of the ESP(Pin 34,35).
<img src="https://raw.githubusercontent.com/AchimPieters/esp32-homekit-camera/master/Images/ESP32-VROOM-32D-PINOUT.png">
<br>
like in the Photo.
Put in the Batterys and execute this command:

esptool.py write_flash 0x0 ./BLE-9100_XXX.bin

and Done :-)
