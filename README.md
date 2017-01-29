# ESP-12F-Flasher
Programmer for ESP-12F modules. 

![Alt text](/Hardware/Flasher_V1/Project%20Outputs%20for%20Flasher_V1/PCB.png?raw=true "PCB")

## To have boards made:
Send the .zip file to your board house of choice (PCBWay, Dirty PCB, OshPark, etc.)
All gerbers are located in [here](/Hardware/Flasher_V1/Project%20Outputs%20for%20Flasher_V1)

## Other notes:
The programmer was meant to be used with POGO Pins, specifically [these](https://www.amazon.com/gp/product/B00BG6JJZY)
The two large holes are meant for screws if you would like to fix the programmer to a jig.

GPIO 0 is always tied to ground on the programmer, meaning once you place the module on the programmer it will ONLY boot in flash mode. The programmer is meant to be exactly that, a programmer. The primary use case being if you want to flash a module and then install it in some assembly, you can do so without the need to tie solder jumpers to your module.
