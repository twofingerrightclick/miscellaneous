## My computer has been called a lot of names. A spy machine, a 007 prop, a forward operating base, but more often, sarcastically a laptop.   

![What is it?](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-IMG_0007-2.jpg "What is it?")

When shopping for a new development laptop for work, I realized that laptops are great, but with current PC technology, bigger is still better. It occurred to me that I could possibly devise a compromise between Desktop power and Laptop mobility. After a quick google for "portable PC" and finding this [excellent build on reddit](https://imgur.com/a/R0D0Aac "excellent build by on reddit"), I was hooked on the idea.

I had an old MacBook that I was keeping around for parts and realized that I could employ its screen and power button. I found a display driver for the screen from Ali Express and I gained a little confidence that I could make this work. I researched the other PC parts, and recorded measurements, before shopping for the smallest rugged hard-shell case I thought would fit them, but not give me too much trouble with space. It still came down to millimeters with almost every part and its placement, but overall, I was fortunately close enough with my estimations.

![Perfect Fit](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-perfect-fit.jpg "Perfect Fit")
*Except I bought too tall of RAM! I decide to modify the heat sink rather than getting another set.*

![Modifying the heat sink](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-modify-heatsink.jpg "Modifying the heat sink")

I sketched up several iterations of designs, of how I could mount the hardware in the case, with the criteria of making everything easy to remove and replace for future upgrades and repairs. 

I fashioned L shaped brackets for mounting the PSU and the motherboard out of a steel bar, and painstakingly bent wood framing ties for the display mounts.

![L brackets to mount to the back of the case](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-lbracket.jpg "L brackets to mount to the back of the case")
*The motherboard is mounted to the back of the case with L brackets.*

![Front standoffs](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-standoffs.jpg "Front standoffs")
*The front portion is mounted with standoffs.*

![The core components mounted!](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-progress.jpg "The core components mounted!")
*The entire build can be disassembled in about 15 minutes, as it is solely comprised of wing nuts and Phillips heads bolts. *

The build started in March, and I quickly realized the state of the GPU market. I gave Twitter bots a go for a while, but realized that it was going to be unprofitable in terms of time. I still always tried at the online Best Buy drops.

I initially assembled the build without the GPU. The Intel UHD Graphics 630 was plenty sufficient for driving the three-display setup that I use at IntelliTect, and software development is pretty much solely a CPU process. The GPU would be a personal addition for digital video and photo work that I enjoy.

![PSU and Display driver](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-display-psu.jpg "PSU and Display driver")
*PSU with display driver that conveniently mounted nicely on top.*

A few months later, I saw that Best Buy was doing in store drops. I asked my wife if she wanted to have a Best Buy date night with me, and to my pleasant surprise she joined me. We brought are double sleeping bag and pad and managed to get a few hours of sleep, after chatting with other members of the line about games and their GPU buying horror stories (dare I say KWEST). I was stoked to get the RTX 3070 that I had be hoping for as per my design specs!

![Some people drove 3hrs.](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-bestbuy.jpg "Some people drove 3hrs.")
*Fellow line members.*

![Best Buy Inn](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-accomadations.jpg "Best Buy Inn")
*Our accommodations for the night in front of our Thermo King camper.*

With the card in at long last in hand, I took more precise measurements and designed a mount for the card in Fusion360. Kevin Bost here at IntelliTect printed the parts for me with excellent print quality. I chose PETG which has a glass transition phase at 80 °C which I figure was good enough for the mounts design.

![The gpu mount](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-mount.jpg "The gpu mount")
*The GPU mount. A 20cm riser cable is used to connect the GPU.*

After several versions of the mounts, a final design was reached, and the card went in with minimal trouble to complete the build! 

https://intellitect.com/wp-content/uploads/2021/10/6mb-austen-pc.gif
![setting up the workstation](https://intellitect.com/wp-content/uploads/2021/10/6mb-austen-pc.gif "setting up the workstation")
*Setting up the workstation!*

The PC performs well and handles large software projects well as I hoped. It recently was tested with a project that requires running five docker containers as well as five web servers to run integration tests locally. The 32GB of ram comes in handy here. 

![No adapters needed](https://intellitect.com/wp-content/uploads/2021/10/IMG_0195.jpg "No adapters needed")
*It may be bigger than a laptop, but no adapters are required.*

The one weakness of the build is the surface area of the CPU’s slim heat sink. The 2000rpm Noctua fan (chosen for its quietness) can only handle the full load of the notoriously toasty 10th gen i7 for a short time before throttling occurs. I also have a louder 3000rpm version that can handle the load for a bit longer, but again software development tasks typically don't require extended 100 percent CPU usage. It only becomes a concern when running all core rendering processes, where I sometimes under clock to 4.5GHz to keep the CPU thermally happy. The 10th gen i7 is very difficult to cool with only 120mm of fan. Typically, it needs a 240mm AIO unit or a very beefy air heatsink, and either would have taken significant more design work to accommodate for the build. If make another version in the future I think I will use water cooling piped to a single 240mm radiator.

I think that if the design was cleaned up, and engineered for consumers, it could actually be a viable product for some types of industries, or at least a with gamers. Let me know what you think in the comments. Thank you for checking out my build.

![the final product](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-IMG_0180.jpg "the final product")

![The guts](https://intellitect.com/wp-content/uploads/2021/10/austen-pc-IMG_0182.jpg "The guts")

## Specs
- Gigabyte Aorus z490i
- Nvidia RTX 3070 FE
- Crucial Ballistix 32GB 2666 Mhz
- Corsair SF600
- Noctua NF-F12 iPPC 3000 PWM, Heavy Duty Cooling Fan
- ID-COOLING IS-60 heat sink
- Nanuk 920 Hard Case
