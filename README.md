# piprint
RaspberryPi Thermal Printer

Adafruit Thermal Printer
Serial BAUD 19200

RaspberryPi (old version with 26 PIN GPIO)
Pimoroni Blinkt
2 arcade buttons


Thermal printer
Power - 5V but needs up to 1.5A supply. Using usb splitter to power PI and Printer

Raspberry Pi config. 
raspbian lite
Need to disable serial console (raspi-config) as by default it pumps out on serial. 

TTY on GPIO pins is /dev/ttyAMA0
BCM 14 and 15. GPIO 8 and 10

Test printer with 
"

