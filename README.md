# Arduino Strip Shield
Schematics for a LED strip driver Arduino shield. Good for up to 1A! Can be used with 12V light strips, 12V RGB strips, and 5V neopixel strips.

WARNING: If you want to use the power from the VIN pin to power your neopixel strip, you will need a step-down voltage regulator from 12V to 5V before connecting your neopixel strip because the PWR pin supplies power directly from the DC jack. Connecting a 5V power supply to the DC jack will NOT work because it needs 7-12V to feed into the Arduino.

Remember to disconnect DC power when connecting the programming header just to be safe.

Use RTClib to use the RTC, and Radiohead to use the NRF24L01

D3: Power (PWM)
D4: Neopixel
D5: Red
D6: Green
D9: Blue


# To test
* Connect 5V DC power and USB power. Board should be powered.
* Jump VIN to 5V if 5V DC supply, and cut the VIN connection. Board should be powered.
