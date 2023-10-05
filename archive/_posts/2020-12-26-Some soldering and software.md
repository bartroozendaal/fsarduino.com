## Soldering
Today I finished a bit of soldering I started yesterday. I'm preparing for a rather large buttonbox, the buttons for which I will receive in about 14 days or so. I ordered quite a selection of buttons to choose from and I don't know which will be the best. So, I want to have a way where I can easily switch out some buttons, without the need to re-soldering anything.

![Some soldering](assets/Soldering.jpg)

I came up with a solution where I make all the necessary connections on a board, leaving jumper cables available to connect the actual buttons. I don't know if it will work and is convenient, but at least it has given me some practice in soldering. I still need to complete the lines, but I'm not sure yet how I will do that. I really want to solder the lines, but after trying I think I needs some extra Flux to do that. But, I overspent already quite a bit, and Flux is not cheap, so I'll think about it a bit more. I might opt to just use some cables to connect the lines.

## Software
I also spent some time on the software for the interface service. Since I want to support WiFi and Serial communication, I decided on a couple of things:

- I will use a separated Reader and Writer for the communication to the Arduino. There will be two implementations for each: one for the serial communication and one for the WiFi communication. Which will be used, is set in the configuration of the service.
- The Arduino can send commands to either push data, or request data. The reader will get the command, and have a [Command Broker](https://en.wikipedia.org/wiki/Command_pattern) handle that.
- The same will go for the SimConnect interface. That too will use a reader and writer (in this case just one implementation for each, as there is only one version of the SimConnect interface).

![Main flow](assets/Sketch.png)

Using this setup it will be a simple matter of reading a command, handling it, and optionally send information using a writer. The architecture of the software will be quite simple to be honest.

The architecture also helps me to start implementing, even without a WiFi-board on my Uno (they should arrive before 31 December). 