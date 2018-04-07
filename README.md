# nanolux
Nanolux analyze mono audio signal from line-in 3.5mm jack or internal microphone and create sound-visualizations on WS2812B style LED strip.

1. Microcontroller Esperiff ESP32 Module with Bluetooth & Wireless Connectivity.
2. 5V direct power or 3.3V lipo battery.
3. Audio input automatically switches between internal microphone or 3.5mm jack if jack is plugged in or not.
4. 3.5mm jack supports both instrument or line level (e.g. needs to support piezo drum trigger/guitar input or a regular line level input).
5. MicroUSB for programming and 5v power.
6. Breakout for 5V LED strip (Power, Data, GND) (connector TBD)
7. 3 small push button rotary encoders for user interface.
8. Onboard WS2812B IC for status indicator (has separate data pinout than the LED breakout).
9. Schematic will merge the following designs:
⋅⋅*Adafruit Feather ESP32 [Product Link](https://www.adafruit.com/product/3405) (Schematic)
⋅⋅*Sparkfun MSGEQ7 Spectrum Shield (using 1 MSGEQ7) [Product Link](https://www.sparkfun.com/products/13116) (Schematic)
⋅⋅*Sparkfun MEMS Microphone Breakout - INMP401 [Product Link](https://www.sparkfun.com/products/9868) (Schematic)

