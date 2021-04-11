I wasn't happy, again, with the wiring mess. So I decided, again, to redo the wiring. From the start of this project I knew I would learn along the way. From a software perspective I had the learn about embedded programming. From the hardware perspective I knew I had to learn a lot about soldering and wiring. 

| How it started                        | How it's going                      |
| ------------------------------------- | ----------------------------------- |
| ![How it started](assets/started.jpg) | ![How it's going](assets/going.jpg) |

This time I'm happy. There are a lot less cables, it isn't a mess at all. I ordered a proto shield for the Arduino 2560 I'm using for this setup.

I also changed the display. I'm not using a I2C shield anymore. It takes a couple of more pins, but at least it is possible to control the backlight using a pot meter. Also, I have some more options in displaying the text, scrolling it, et cetera.

Another benefit is that I can make use of Air Manager only lua-scripts to read the buttons and rotary encoders. No need to write my own code for the Arduino. I've learned a lot, but it's just a bit easier to use Air Manager only.