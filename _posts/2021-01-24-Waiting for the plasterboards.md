While waiting for the plasterboards (they will arrive next Tuesday) I've been thinking about the radio panel. I am still not really comfortable in using the knobs alone to select the frequencies, so I've been thinking about using a numeric keypad instead.

![Numeric keypad](assets/custom radio panel design.png)

As you can see I would need 14 digital pins; too many for my nano and even uno. I may lose the on/off switch or one of the swap buttons. Instead I can have one swap button, which will swap whatever mode is selected (com1 or com2). Downside is that one needs to switch coms in order to switch from standby to active frequency for that particular setting, which is not really nice (it would take you away from the frequency that you had been using).

Also, using these switches, it will not be possible to select listing to both channels.

So, instead I may drop a row of buttons in the numeric keypad. I thought about introducing a memory function, where you could select from a list of recently used frequencies, but if that's not possible, then maybe not.
Last option is to go for a Arduino Leonard of course. That one has 20 digital pins, which would open all the options above.

All of this would mean of course that it is a truly custom radio panel, made to my liking. But there's an elegancy to that too..

Haven't made up my mind yet, about any of this...

## Update
After some Googling I decided against building a keypad myself. There are some good alternatives off the shelf that will save me from some soldering.

![Keypad](assets/keypad.jpg)

I opted for the keypads from [az-delivery.de](https://www.az-delivery.de/en/collections/alle-produkte/products/4x4-matrix-numpad), which in a bundle of five come to less than €5,00. That's a price I won't be soldering for ;-)