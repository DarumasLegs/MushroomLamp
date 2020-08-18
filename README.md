# MushroomLamp
Code for mushroom lamp (https://www.reddit.com/r/FastLED/comments/i375fm/psychedelic_mushroom_lamp/)

Button: First button press turns the lights on and begins the slow changing of the colors, second button press freezes the lights in their current state, and the third button press turns the lights off.

There are 4 variables which can be configured and are as follows:

NUM_LEDS        : Total no of LEDS present in the LED strip of device
PIN             : Physical pin on Teesny connected to datain pin of LEDS
button_pin      : Physcial pin on Teensy connected to pushbutton
transitiondelay : This is the delay between the transition of color and the values is in milliseconds range.
