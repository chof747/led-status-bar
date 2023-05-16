## Status bar with RGB Leds

This is a breakout board containing 5 WS2812B compatible RGB Leds that can be used to display some kind of status information or for other presentation stuff

It contains the following elements:

- 5 WS2812B compatible surface mount RGB leds
- MOSFETs acting as signal level shifters so it can be triggered by a 3V3 signal while the LEDs are powered by a higher voltage
- By-pass capacitors for each LED according to the data sheets
- A 4-pin header so that it can be connected to VDD (e.g. 5V) and VREF (e.g. 3v3), GND and a data line
  (1 - VDD, 2- Data, 3 - VREF, 4 - GND)
- It contains an outbound connector to daisy chain boards

## Revision History:

- **v1.0**: Initial version (filed for fabrication: 19.04.2023, assembled 14.5.2023)
- **v1.1**: Corrected revision including fixed version for level shifting and an outbound connector

