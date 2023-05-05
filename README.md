# ARCCore

The ARC Core is a small, pre programmed, low power board designed to run RGB LEDs. It is ideal for portable devices such as game consoles using 3.3V - 5V (ideally 5V).
![alt text](https://github.com/nataliethenerd/picohatpad/blob/0d090fafd6f77bb56b488985600c669083d9b0a3/IMG_1465.jpg)

### Features
- RP2040
- 3.3V Buck Converter
- Can power up to 10 WS2812B RGB LEDs

### How to use
1. Connect the chain of WS2812B LED's data in pin to the DIN pin on the ARC Core

2. Connect the 5V and GND to the LED chain and also a power source

3. Connect three buttons, one to each A, B and C. One side of the button needs to be connected to the ARC Core's GND pin

4. Control the LEDs as you would on the Game Boy.


A and C changes the colour

B and C changes the brightness

A and B saves the settings
