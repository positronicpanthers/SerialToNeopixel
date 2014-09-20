SerialToNeopixel

Takes serial input with led number and rgb values and sets rgb of neopixels accordingly


The input should match the following format:

P6:255,255,255

P7:0,0,255


The first line sets LED number 6 to be bright white and the second line sets LED number 7 to be bright blue.

Keep in mind:

-that neopixel library is needed! (found at https://github.com/adafruit/Adafruit_NeoPixel)

-that pin numbers are subject to change

-that number of neopixels is subject to change
