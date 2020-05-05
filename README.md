# ESP8266_2rele_ArduinoCode


## Check ROM size
esptool.py --port COM4 flash_id

## Erase flash
esptool.py --port COM3 erase_flash

## Flash ... exaple is for D1 Mini Pro ... flsh_size 16MB not working !!!
esptool.py --port COM4 --baud 115200 write_flash --flash_size=4MB --flash_mode qio 0x00000 C:\path\esp8266-20200421-v1.12-388-g388d419ba.bin
