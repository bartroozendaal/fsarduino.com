Since Air Manager doesn't support I2C displays from script, I need to create a small sketch (so not 'native' Air Manager script) to get information from Air Manager on a display. I'm using a Arduino Nano for that. My instrument (which will not have a display), will be driven by a native script, that talks to the Nano with the display. Takes me two Arduino's to accomplish this, but that's fine. The Nano is cheap enough to do that.

[![Uno talks to Nano](assets/uno talks to nano.png)](https://www.youtube.com/watch?v=vtjbWVuWKmY)

Unfortunately Air Manager doesn't support I2C devices, but has implemented a 'communication protocol' to have devices talk to each other. The documentation is, well, not once you understand the principles, it's easy to implement.

Tonight I created the proof of concept shown in the video, to see if I could use this set up for my radio panel. It does, and now I have even more ports to play with. From the previous experiments I have some nice classes for the Arduino, which now come handy.

I also decided to set up a more permanent testing board using a prototyping shield. It has a fixed button, two leds and I added a rotary encoder. It has its own display, which I am not using for this experiment obviously, but which comes handy to display debug information.

I'm really getting the hang of this stuff. Also very glad I decided to choose for Air Manager. Saves me a lot of time, well worth the 60 euros.