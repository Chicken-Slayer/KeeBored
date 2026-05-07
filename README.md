# KeeBored
A mechanical keyboard designed and built from scratch, that has media controls, macro keys, and a custom OLED display (who doesn't love OLED displays). Why have a separate macropad and keyboard when you can have both in one?

## How it works:
The keyboard has 105 keys, along with one rotary encoder. It is powered by a raspberry Pi Pico, in which the keys are arranged in a 14x8 matrix, with the rest of the GPIO pins used to connect a rotary encoder and an OLED Display. Therefore, we achieve maximum efficiency by utilising all the available IO. The firmware is (to be) coded in Python, using KMK firmware. 

## PCB:
Here's the schematic:
![Schematic](assets\schematic.jpg)
