I finished the selection of the function of the radio panel, changing the frequencies and swapping between Standby and Active frequencies.

[![Radio panel works](assets/radio-panel works.png)](https://youtu.be/Iog_6I5dCxw)

I decided to use two display instead of one. I didn't like the 'cramped' space. I might even add a total of four displays, may need to do some calculation if there will be enough pins for that. I bought a couple of I2C converter panels, but am having some trouble in soldering them properly. I still have a lot to learn with regards to soldering.

Therefor I focused on the software today and made some real progress. Bar the unit tests, I think the code for selecting the mode of the panel, changing frequencies and swapping between Active and Standby is production ready. I will probably do some refactoring for the button code to make it more robust and reusable, but that should be a small task.

I bought myself a new soldering kit. The one I chose is convenient since it is wireless, but it is not hot enough and the battery lasts only 30 minutes or so. That is bothering me big time, so yet another investment made today on some new soldering gear.

Very shortly my WiFi adapter boards should arrive so I can start implementing the WiFi based communication. The next couple of tasks will be focus on connecting to SimConnect. Stay tuned for more updates later on that...