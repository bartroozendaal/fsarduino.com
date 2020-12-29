TLDR; Update already after a few minutes in. I'm super impressed by [PlatformIO](https://docs.platformio.org/en/latest/what-is-platformio.html). Best integration in VsCode I have seen so far for any tool. Super glad I found this.

---

I'm ready to start the serious part of the software development. I'm done with tinkering with my code to figure out how things work. I'm far from being an expert on the Arduino and C++ (I'm still rusty), but I now know enough of what I want the software to do to start and I need to start setting things up in a proper way.

![Unit testing](assets/software-bug.jpg)

There's a couple of things I realized:
- I want to support multiple boards. I've got some Uno's, also bought a Nano and some clones.
- I want unit tests. Uploading the software and fiddling to figure out if my code works takes too much time. I want to have unit tests to properly test my software, even before uploading.
- Preferably I want my unit tests to run before merging my develop branch.

I'm now looking at [PlatformIO](https://docs.platformio.org/en/latest/what-is-platformio.html). It says it's aiming at the professional embedded engineers, so it should be able to do all those things. At least there is a whole section on unit testing on their site, which is my main goal today. I took the day off from work (this is a really quiet period of the year at work) so should have plenty of time to dig into PlatformIO. Let's see if this works out...