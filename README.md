# ARCCore

The ARC Core is a small, pre programmed, low power board designed to run RGB LEDs. It is ideal for portable devices such as game consoles using 3.3V - 5V (ideally 5V).

![Front of board](/assets/coref.png)
![Back of board](/assets/coreb.png)

It is designed to be used on ARC RGB LED flex pcbs inside Game Boy consoles. The core is removable from these LED boards, aiming to reduce electronics waste by reprograming it

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
