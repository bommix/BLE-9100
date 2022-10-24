# Welcome to my project BLE-9100

How to Flash?

Use esptool.

First of all, please install esptool from here: https://github.com/espressif/esptool
Download the latest binary file
Connected your BLE-9100 to your computer like in the Photo.
Execute this command:

esptool.py write_flash 0x0 ./BLE-9100_XXX.bin