---
title: 'ICYMI: Supercharged Supercon with CircuitPython, Quoth the Raven MOAR
PYTHON! #Python #ICYMI #Adafruit #CircuitPython #PythonHardware @circuitpython @micropython @ThePSF @Adafruit'
date: 2019-10-16T14:36:00+01:00
draft: false
---

ICYMI (In case you missed it) – Tuesday’s Python on Microcontrollers Newsletter from [AdafruitDaily.com](https://www.adafruitdaily.com/) went out – if you missed it, [subscribe now!](https://www.adafruitdaily.com/)

The next newsletter goes out in a week and being subscribed the best way to keep up with all things Python for hardware.

Over 6,700 subscribers worldwide!

MicroPython slithers its way to Feather!
========================================

[![MPSTM32](https://cdn-blog.adafruit.com/uploads/2019/10/101519stm32mp.jpg)](https://www.adafruit.com/product/4382)

MicroPython running on a [Feather STM32](https://www.adafruit.com/product/4382) – [GitHub](https://github.com/micropython/micropython/commit/06ae818f9360e83284c64614144f1ad00998a739) & [YouTube](https://youtu.be/ssz5SNH0QDY).

Scanning and advertising – BLE with CircuitPython update
--------------------------------------------------------

[![Scan BLE](https://cdn-blog.adafruit.com/uploads/2019/10/101519blecpx.jpg)](https://youtu.be/iHfd31qDTmw)

Scanning and advertising – BLE with CircuitPython update! Proximity based color demo using four Circuit Playground Bluefruit boards, [Tweets](https://twitter.com/tannewt/status/1182103930097958912) [here](https://twitter.com/tannewt/status/1182806194378833920) and [YouTube](https://youtu.be/iHfd31qDTmw). Here’s a bit more about it from Scott:

> _“Last week I was heads down on BLE scanning and advertising. It’s the first phase of BLE and is incredibly powerful on it’s own. By advertising data directly, one can control a bunch of other devices all at once. I showed a simple demo of one device changing the color of another and then a more complex demo where multiple devices are advertising and multiple are scanning. By moving the scanning devices closer to different advertisers, the color changes to the nearest._
> 
> _To support this, I’ve swapped the scan result from a list to an iterator, added RSSI filtering and added advertising structure prefix filtering. These early filters reduce the number of Python level memory allocations and simplify the user code._
> 
> _On the library side, I’ve modeled the BLE API after the CircuitPython Register library which uses the Python descriptor protocol to make defining advertisements declarative with easy to reuse components. This week, I’m moving onto advertising designed to facilitate connections and ensuring all of the existing demos Dan has done still work.”_

Make a Bluetooth-controlled Color Changing Jack-o-Lantern Pumpkin
-----------------------------------------------------------------

[![BT Pumpkin](https://cdn-blog.adafruit.com/uploads/2019/10/101519bt.jpg)](https://youtu.be/ClxNJK9FfwU)

In this video, Maker Melissa show you how to take a 3D Printed FAB365 Pumpkin and Adafruit Circuit Playground Bluefruit and add the ability to change the color with your smartphone or Apple Watch. This was printed in Prusament Vanilla White PLA at the recommended settings for the model. Melissa used the Jack-o-lantern with the translucent face, but a carved face version is also available – [YouTube](https://youtu.be/ClxNJK9FfwU).

CircuitPython powered earrings
------------------------------

[![CPearrings](https://cdn-blog.adafruit.com/uploads/2019/10/101519cpearrings.gif)](https://twitter.com/NYCPyLadies/status/1182336739999961089)

Check out [Felice’s](https://twitter.com/codelovingyogi) homemade earrings, made with CircuitPython – [Twitter](https://twitter.com/NYCPyLadies/status/1182336739999961089).

Interactive CircuitPython Poster from CodeNSolder
-------------------------------------------------

[![CPPoster](https://cdn-blog.adafruit.com/uploads/2019/10/101519cpposter.jpg)](https://twitter.com/iAyanPahwa/status/1183017937591947264)

[![CPPoster](https://cdn-blog.adafruit.com/uploads/2019/10/101519teamcodensolder.jpg)](https://twitter.com/iAyanPahwa/status/1183017937591947264)

Congrats to [the team](https://twitter.com/iAyanPahwa/status/1183019501794684928) in New Delhi City for a fantastic interactive CircuitPython poster – [Twitter](https://twitter.com/iAyanPahwa/status/1183017937591947264).

Supercon – Supercharge Your Hardware (Old and New) with CircuitPython
---------------------------------------------------------------------

[![Supercon](https://cdn-blog.adafruit.com/uploads/2019/10/101519hadscscott.png)](https://hackaday.com/2019/10/11/latest-dose-of-hardware-talks-headed-to-supercon/)

[Latest Dose Of Hardware Talks Headed To Supercon – Hackaday](https://hackaday.com/2019/10/11/latest-dose-of-hardware-talks-headed-to-supercon/).

> The tickets have sold out even as the list of incredible speakers grows. Today we bring you the third dose of talks you’ll see at the [Hackaday Superconference](https://www.eventbrite.com/e/2019-hackaday-superconference-tickets-60129236164?aff=1004com) in November — whether you were lucky enough to grab a ticket, or will be watching the livestream, these eight will be speaking on topics from algorithmically-augmented live music performance to the hardware that captures the real world for display in VR and from leveraging the power of lookup tables to harnessing our engineering talent in a way that truly enriches humanity. If you missed the two speaker announcements that have already come out, [go back](https://hackaday.com/2019/09/27/heres-your-first-look-at-the-talks-of-the-2019-hackaday-superconference/) and [take a look](https://hackaday.com/2019/10/04/more-supercon-talks-taking-the-hardware-world-by-storm/) at those as well as [the workshops](https://hackaday.com/2019/10/02/get-hands-on-at-supercon-workshop-tickets-now-available-2/) being held during Supercon.

AND, big news!

**Supercharge Your Hardware (Old and New) with CircuitPython by Scott Shawcroft**

> _“CircuitPython makes programming hardware easier than ever by bringing the popular Python language to modern, inexpensive 32-bit microcontrollers. This doesn’t need to be limited to modern hardware though. By pairing a modern microcontroller running CircuitPython and a vintage computer, such as a GameBoy or Yamaha piano keyboard, you can unlock the unique characteristics of these vintage devices. In this talk, you’ll learn the basics of how CircuitPython makes coding easy, how it works under the hood, and how to extend CircuitPython with C. As an example, we’ll supercharge a Nintendo’s GameBoy with CircuitPython. By the end of the talk, you’ll be able to supercharge your own hardware project with CircuitPython.”_

Adafruit will have some team members at Supercon and some special hardware surprises thanks to Digi-Key!

PyConDE in Berlin photos!
-------------------------

[![SprintPyConDE](https://cdn-blog.adafruit.com/uploads/2019/10/101519_SprintPyConDE.jpg)](https://github.com/SamsungResearchUK-IoT-Meetup/multimode_sensor_platform/wiki)

[![SprintPyConDE](https://cdn-blog.adafruit.com/uploads/2019/10/101519_Boards.jpg)](https://github.com/SamsungResearchUK-IoT-Meetup/multimode_sensor_platform/wiki)

[![SprintPyConDE](https://cdn-blog.adafruit.com/uploads/2019/10/101519_AR_Sensor.png)](https://github.com/SamsungResearchUK-IoT-Meetup/multimode_sensor_platform/wiki)

Lots of fun was had during PyConDE last week. Especially at the Sprints, where participants used the MicroPython **pyboard D and accessories** to build a Multimode Sensor Platform with AR. The full project can be found on [GitHub](https://github.com/SamsungResearchUK-IoT-Meetup/multimode_sensor_platform/wiki). Thank you [Christine!](https://github.com/tine3700)

[![PyLadies](https://cdn-blog.adafruit.com/uploads/2019/10/101519pyladies.jpg)](https://twitter.com/PyLadiesHH/status/1183056425456680961)

And speaking of PyConDE, here are some tweets from PyLadies at the event (Adafruit was a sponsor) – [Twitter](https://twitter.com/PyLadiesHH/status/1183056425456680961).

Sponsor arturo182 on GitHub
---------------------------

[![arturo182](https://cdn-blog.adafruit.com/uploads/2019/10/101519serpente.jpg)](https://github.com/users/arturo182/sponsorship)

Arturo creates open source hardware and shares it on [GitHub](https://github.com/arturo182). In addition to the standard KiCad files, Arturo also shares schematics, renders of the boards, and additional files. Lots of Python on hardware!

[![arturo182](https://cdn-blog.adafruit.com/uploads/2019/10/101519art2.jpg)](https://github.com/users/arturo182/sponsorship)

You’ve [seen the work](https://hackaday.io/arturo182), the [real-time Tweets of work in progress](https://twitter.com/arturo182), and now you can sponsor Arturo on GitHub (we did) – [GitHub](https://github.com/users/arturo182/sponsorship).

CircuitPython-compatible StringCar M0 Express and StringCar M4 Express boards
-----------------------------------------------------------------------------

[![StringCar](https://cdn-blog.adafruit.com/uploads/2019/10/101519stringcar01.png)](https://learn.adafruit.com/users/HarpDude)

[![StringCar](https://cdn-blog.adafruit.com/uploads/2019/10/101519stringcar02.png)](https://learn.adafruit.com/users/HarpDude)

From [CGrover](https://learn.adafruit.com/users/HarpDude), a CircuitPython-compatible StringCar update!

> _“Here is the updated M0 version that’s currently in process at OSH Park + OSH Stencils, and an M4 version that will be sent to the OSHs next week. The objective is to create a string car racer that can autonomously learn about its environment and adjust tradeoffs for speed and battery longevity. The CircuitPython versions of the StringCar controllers make it really easy to add and interactively adjust performance features such as motor and battery efficiency, end-of-string collision avoidance, string length calculation, and predictive braking. Also, being able to watch its own battery status means that it’ll always return to the home end of the string rather than forcing me to get up from the lawn chair to manually retrieve the car from somewhere along the string. Besides being facile for adding and testing new features in real-time, CircuitPython also supports libraries that abstract string car functions, simplifying the primary code module to make it easier for novice programmers to get involved in customizing their own string car racer. Moving to the M0 and M4 versions challenged my PCB and software development skill sets significantly. Adafruit’s documentation and learning guides made the journey a bit easier. Bryan (siddacious) was exceptionally helpful and encouraging.”_

Quoth the Raven MOAR PYTHON
---------------------------

[![Raven](https://cdn-blog.adafruit.com/uploads/2019/10/101519raven.jpg)](https://www.instagram.com/p/B3VcE9UFZqd/?igshid=10sd4lcnwdqaq)

Laser-bird knows when it’s sleeping, knows when you’re awake! An animatronic raven made with CircuitPython – [Instagram](https://www.instagram.com/p/B3VcE9UFZqd/?igshid=10sd4lcnwdqaq).

AWS DeepRacer arrived – Runs on Python
--------------------------------------

[![AWS DeepRacer](https://cdn-blog.adafruit.com/uploads/2019/10/101519awsdeepracer_adafruit.jpg)](https://blog.adafruit.com/2019/10/11/aws-deepracer-arrived-runs-on-python-adafruit-awscloud-awsdeepracer-deepracer/)

[AWS DeepRacer](https://aws.amazon.com/deepracer/) is an autonomous 1/18th scale race car driven by reinforcement learning, 3D racing simulator, and global racing league. You can build your own RL model for AWS DeepRacer using the AWS DeepRacer 3D racing simulator. Building a model requires basic Python programming skills. [We picked one up](https://blog.adafruit.com/2019/10/11/aws-deepracer-arrived-runs-on-python-adafruit-awscloud-awsdeepracer-deepracer/) and will get [Blinka](https://circuitpython.org/blinka) on it shortly.

Python powered Mini PiTFT – 135×240 Color TFT Add-on for Raspberry Pi
---------------------------------------------------------------------

[![ Mini PiTFT](https://cdn-blog.adafruit.com/uploads/2019/10/101519MiniPiTFT.gif)](https://www.adafruit.com/product/4393)

Mini PiTFT – 135×240 Color TFT Add-on for Raspberry Pi – If you’re looking for the most compact li’l color display for a Raspberry Pi (most likely a Pi Zero) project, this might be just the thing you need!

[The Mini PiTFT – 135×240 Color TFT Add-on for Raspberry Pi](https://www.adafruit.com/product/4393) is your little TFT friend, ready to snap onto any and all Raspberry Pi computers, to give you a little display. The Mini PiTFT comes with a full color 240×135 pixel IPS LCD display with great visibility at all angles. The TFT uses only the SPI port so it’s very fast, and we leave plenty of pins remaining available for buttons, LEDs, sensors, etc. It’s also nice and compact so it will fit into any case.

This display is super small, only about 1.14″ diagonal, but since it is an IPS display, it’s very readable with high contrast and visibility. We had a little space on the top so we give you two tactile buttons on GPIO pins so you can create a simple user interface. On the bottom we have a Qwiic/STEMMA QT connector for I2C sensors and device so you can plug and play any of our STEMMA QT devices.

Using the display is very easy, we have a kernel driver and Python library for the ST7789 chipset. You can set it up as a console output so you can have text and user interface through the Raspberry Pi OS or you can draw images, text, whatever you like, using the Python imaging library. Our tests showed ~15 FPS update rates so you can do animations or simple video.

Comes completely pre-assembled and tested, so you don’t need to do anything but plug it in and install our Python code! Works with any Raspberry Pi computer – [Adafruit](https://www.adafruit.com/product/4393).

ADABOX holiday edition with CircuitPython
-----------------------------------------

[![ADABOX 14](https://cdn-blog.adafruit.com/uploads/2019/10/101519adabox.jpg)](https://www.adafruit.com/adabox)

ADABOX 14 is the holiday edition, it will be CircuitPython powered, we will run out before the holidays so sign up now, it can be just for you, or given as a gift – [ADABOX](https://www.adafruit.com/adabox).

Open Hardware month, a post a day all month long!
-------------------------------------------------

[![OHM2019](https://cdn-blog.adafruit.com/uploads/2019/10/101519ohm2019ard.jpg)](ttps://blog.adafruit.com/?s=%23ohm2019)

It’s [open hardware month](https://ohm.oshwa.org/) and we’re posting about Open Source hardware past, present, and future – all month long (pictured above, the first Arduino). Follow along at the Adafruit blog with the tag/search: [#OHM2019](https://blog.adafruit.com/?s=%23ohm2019). Topics so far include:

*   [The first 2 orders at Adafruit… now up to 2,161,166 orders](https://blog.adafruit.com/2019/10/13/the-first-2-orders-at-adafruit-now-up-to-2161166-orders-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg/) – Day 13, 10/13/2019.
*   [Photos of the first Arduino (2005)](https://blog.adafruit.com/2019/10/12/photos-of-the-first-arduino-2005-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg-arduino-arduino-wiringproject/) – Day 12, 10/12 2019.
*   [In 2010 there were 13 Open Source Hardware companies that were making $1 million or more](https://blog.adafruit.com/2019/10/11/in-2010-there-were-13-open-source-hardware-companies-that-were-making-1-million-or-more-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-oreillymedia-foocamp/)… – Day 11, 10/11/2019
*   [Opening Hardware 2010 at Eyebeam in NYC](https://blog.adafruit.com/2019/10/10/opening-hardware-2010-at-eyebeam-in-nyc-eyebeamnyc-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware/) – Day 10, 10/10/2019.
*   [The Open Source Gift Guide, the early years](https://blog.adafruit.com/2019/10/10/the-open-source-gift-guide-the-early-years-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware/) – Day 9, 10/9/2019 (posted it on 10/10/2019, whoops)
*   [Before the iPhone, before the Raspberry Pi, before Amazon Echo Show, there was Chumby](https://blog.adafruit.com/2019/10/08/before-the-iphone-before-the-raspberry-pi-before-amazon-echo-show-there-was-chumby-chumby-chumby-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware/) – Day 8, 10/8/2019.
*   [Mitch Altman Open-source hardware pioneer](https://blog.adafruit.com/2019/10/07/mitch-altman-open-source-hardware-pioneer-maltman23-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg/) – Day 7, 10/7/2019.
*   [The Open Source logo(s)](https://blog.adafruit.com/2019/10/06/the-open-source-logos-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg/) – Day 6, 10/6/2019.
*   [Open Source Hardware events all month long, EVENTS!](https://blog.adafruit.com/2019/10/05/open-source-hardware-events-all-month-long-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg/) – Day 5, 10/5/2019.
*   [Open Source Hardware Certifications and more!](https://blog.adafruit.com/2019/10/04/open-source-hardware-certifications-and-more-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg-mweinberg2d-make-realsexycyborg/) – Day 4, 10/4/2019.
*   [Teuthis Open Source MP3 Player 2001 – Daisy by Raphael Abrams](https://blog.adafruit.com/2019/10/03/teuthis-open-source-mp3-player-2001-daisy-by-raphael-abrams-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg-nycresistor/) – Day 3, 10/3/2019.
*   [What is the Open-Source Hardware Definition?](https://blog.adafruit.com/2019/10/02/what-is-the-open-source-hardware-definition-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg/) – Day 2, 10/2/2019.
*   [Open hardware summit – Limor “Ladyada” Fried keynote 2010](https://blog.adafruit.com/2019/10/01/open-hardware-summit-limor-ladyada-fried-keynote-2010-adafruit-ohm2019-oshwa-ohsummit-opensource-opensourcehardware-opensourceorg/) – Day 1, 10/1/2019.

News from around the web!
-------------------------

[![AD5689](https://cdn-blog.adafruit.com/uploads/2019/10/101519AD5689.jpg)](https://github.com/theacodes/Winterbloom_AD5689)

Thea Flowers made a CircuitPython driver for the Analog Devices AD5689 16-bit DAC – [GitHub](https://github.com/theacodes/Winterbloom_AD5689).

Speaking of drivers, [Dan](https://twitter.com/cogliano/status/1183420469313179649) wrote one too! Below is a CircuitPython driver for the MCP9600 thermocouple I2C amplifier. In addition to the MCP9600 breakout, you will also need a thermocouple, which can be found in the Adafruit store. The MCP9600 supports several thermocouple types for different temperature ranges. The “K” type is the default, with a range of -200C to +1372C – [GitHub](https://github.com/adafruit/Adafruit_CircuitPython_MCP9600).

[![EZ Make](https://cdn-blog.adafruit.com/uploads/2019/10/101519ezmake.jpg)](https://twitter.com/cogliano/status/1183772880460550146)

More testing today of Dan Cogliano’s EZ Make oven controller – [Twitter](https://twitter.com/cogliano/status/1183772880460550146).

[![FT232H](https://cdn-blog.adafruit.com/uploads/2019/10/101519bigles.jpg)](https://bigl.es/microcontroller-monday-adafruit-ft232h-circuitpython/)

Microcontroller Monday – the Adafruit FT232H – CircuitPython – [bigl.es](https://bigl.es/microcontroller-monday-adafruit-ft232h-circuitpython/).

[![100 CPX Bluefruit](https://cdn-blog.adafruit.com/uploads/2019/10/101519cpxble.jpg)](https://twitter.com/gallaugher/status/1181285150757474305)

Professor John Gallaugher and 100 Circuit Playground Bluefruit boards for students – [Twitter](https://twitter.com/gallaugher/status/1181285150757474305). _“Time to mint some new Pythonistas”_

[![CPX SG](https://cdn-blog.adafruit.com/uploads/2019/10/101519cpxsg.jpg)](https://www.instagram.com/p/B3d2Wqtlmz4/?igshid=1p5wa0b728j3k)

Circuit Playground Express heading to the Singapore Maker Faire extravaganza 2019 – [Instagram](https://www.instagram.com/p/B3d2Wqtlmz4/?igshid=1p5wa0b728j3k).

[![Shelf lighting](https://cdn-blog.adafruit.com/uploads/2019/10/101519shelf.jpg)](https://www.instagram.com/p/B3W0aaFpfU-/?igshid=lrere64pvq5b)

Joey is working on some under-shelf lighting using CircuitPython – [Instagram](https://www.instagram.com/p/B3W0aaFpfU-/?igshid=lrere64pvq5b).

[![Green Serpente](https://cdn-blog.adafruit.com/uploads/2019/10/101519greensp.jpg)](https://twitter.com/OmzloElec/status/1182388355100762113)

A Serpente with micro-USB. And it’s green – [Twitter](https://twitter.com/OmzloElec/status/1182388355100762113).

[![apex](https://cdn-blog.adafruit.com/uploads/2019/10/101519apex.jpg)](https://aip.scitation.org/doi/10.1063/1.5118855)

[Some Adafruit breakouts made it to space](https://aip.scitation.org/doi/10.1063/1.5118855)! apex: A new commercial off-the-shelf on-board computer platform for sounding rockets. Looks like: Raspberry Pi Zero with camera, Adafruit LSM9DS1 9-DOF, DS3231 RTC, ADS1015 ADC 4 channel amp, and a BME280 Temp/Humidity/Pressure sensor. Interesting note… They used ESP32-Pico-D4’s and _“As storage media, Samsung Evo Plus µSD cards have been chosen, due to their predecessor usage on the ISS AstroPi program7 and their X-ray proof, waterproof, magnetism, and heat resistant design”_

[![CPX fashion](https://cdn-blog.adafruit.com/uploads/2019/10/101519cpxf.jpg)](https://twitter.com/k_sensenbrenner/status/1181740713509343232)

6th graders designing smart clothing with the Circuit Playground Express – [Twitter](https://twitter.com/k_sensenbrenner/status/1181740713509343232).

[![NCD](https://cdn-blog.adafruit.com/uploads/2019/10/101519ncdiot.jpg)](https://ncd.io/)

NCD IoT connected products. We did not know about [these folks](https://ncd.io/about-us/), this [looks interesting](https://ncd.io/).

[![DebugandDump](https://cdn-blog.adafruit.com/uploads/2019/10/101519debuganddump.jpg)](https://twitter.com/StackSmashing/status/1183076481045585921)

Debug’n’Dump – FT232H based and supports JTAG, SWD, I2C, SPI (and SPI flashes) and UART – [Twitter](https://twitter.com/StackSmashing/status/1183076481045585921).

[![PowerWing](https://cdn-blog.adafruit.com/uploads/2019/10/101519powerwing.jpg)](https://www.tindie.com/products/loopresearch/powerwing-6-36v-power-supply-featherwing/)

PowerWing: 6-36V Power Supply FeatherWing. Supplies 5V at up to 1A from 6-36V in a FeatherWing form factor – [Tindie](https://www.tindie.com/products/loopresearch/powerwing-6-36v-power-supply-featherwing/).

[![Pikachu](https://cdn-blog.adafruit.com/uploads/2019/10/101519pikachu.gif)](https://twitter.com/cscottnet/status/1181583095314735105)

Cool 6 year old with a Monster M4sk Pikachu – [Twitter](https://twitter.com/cscottnet/status/1181583095314735105).

[![boochow](https://cdn-blog.adafruit.com/uploads/2019/10/101519st7735-dupterm.jpg)](https://blog.boochow.com/article/tft-lcd-console-mp-dupterm.html)

[![boochow](https://cdn-blog.adafruit.com/uploads/2019/10/101519st7735-vscroll.jpg)](https://blog.boochow.com/article/micropython-st7735-vertical-scroll.html)

Two really good posts over at boochow: [Output MicroPython REPL to TFT LCD](https://blog.boochow.com/article/tft-lcd-console-mp-dupterm.html) and [Scroll function added to MicroPython ST7735 driver](https://blog.boochow.com/article/micropython-st7735-vertical-scroll.html).

[![TensorFlow](https://cdn-blog.adafruit.com/uploads/2019/10/101519tfbb.gif)](https://learn.adafruit.com/tensorflow-in-your-browser-object-detection-with-bounding-boxes)

TensorFlow in your browser: Object Detection with Bounding Boxes. Watch TensorFlow identify and box everyday objects using your phone or computer’s camera – [learn.adafruit.com](https://learn.adafruit.com/tensorflow-in-your-browser-object-detection-with-bounding-boxes)

Turn your micro:bit into fireflies, using broadcast and Bluetooth to [simulate](https://ncase.me/fireflies/) fireflies with synchronous flashing – [Twitter](https://twitter.com/stevenpfloyd/status/1182820852951408640?s=11).

If the global supply chain collapses by 2030, Collapse OS is there to help soften the blow, it’s a Z80 kernel and a collection of programs, tools and documentation that allows you to assemble an OS – [collapseos.org](https://collapseos.org/) & [GitHub](https://github.com/hsoft/collapseos).

Introducing Partner Governance – [ARM embed](https://os.mbed.com/blog/entry/mbed-governance-techcon/).

[![Orange Pi Zero](https://cdn-blog.adafruit.com/uploads/2019/10/101519orangepi.jpg)](https://lemariva.com/blog/rss/orange-pi-zero-lts-upgraded-alternative-old-raspberry-pis)

Orange Pi Zero LTS: An ‘upgraded’ alternative to the old Raspberry Pis – [LeMaRiva](https://lemariva.com/blog/rss/orange-pi-zero-lts-upgraded-alternative-old-raspberry-pis).

[![DMG-CPU](https://cdn-blog.adafruit.com/uploads/2019/10/101519dmgcpu.png)](https://github.com/furrtek/DMG-CPU-Inside)

36 pages of reverse-engineered schematics for the original Game Boy chip (minus CPU) – [GitHub](https://github.com/furrtek/DMG-CPU-Inside).

[![Flash](https://cdn-blog.adafruit.com/uploads/2019/10/101519flash.jpg)](https://www.vice.com/en_us/article/d3awk7/flash-is-responsible-for-the-internets-most-creative-era)

Flash Is Responsible for the Internet’s Most Creative Era, [VICE](https://www.vice.com/en_us/article/d3awk7/flash-is-responsible-for-the-internets-most-creative-era) and [WIRED](https://www.wired.co.uk/article/history-of-macromedia-flash). An upcoming book: [Web Design. The Evolution of the Digital World 1990–Today](https://www.taschen.com/pages/en/catalogue/graphic_design/all/04690/facts.web_design_the_evolution_of_the_digital_world_1990today.htm). And here’s a [history of FLASH](http://www.moedae.com/blog/history-of-flash). Fun side note, Flash on mobile devices is indirectly responsible for a lot of our work now on low-cost electronic devices with screens.

Sniffle is a sniffer for Bluetooth 5 and 4.x (LE) using TI CC1352/CC26x2 hardware – [GitHub](https://github.com/nccgroup/sniffle).

[![Susan Kare](https://cdn-blog.adafruit.com/uploads/2019/10/101519susankare.jpg)](https://www.smithsonianmag.com/innovation/how-susan-kare-designed-user-friendly-icons-for-first-macintosh-180973286/)

How Susan Kare Designed User-Friendly Icons for the First Macintosh. The graphic designer is receiving a Lifetime Achievement Award from Cooper Hewitt for her recognizable computer icons, typefaces and graphics – [Smithsonian](https://www.smithsonianmag.com/innovation/how-susan-kare-designed-user-friendly-icons-for-first-macintosh-180973286/).

[![Nobel Prize](https://cdn-blog.adafruit.com/uploads/2019/10/101519nobel.jpg)](https://www.nobelprize.org/prizes/chemistry/2019/summary/)

The Nobel Prize in Chemistry 2019 was awarded jointly to John B. Goodenough, M. Stanley Whittingham and Akira Yoshino “for the development of lithium-ion batteries.” via The Nobel Prize in Chemistry 2019. NobelPrize.org. Nobel Media AB 2019. Sun. 13 Oct 2019 – [Noble Prize](https://www.nobelprize.org/prizes/chemistry/2019/summary/).

[![Not human](https://cdn-blog.adafruit.com/uploads/2019/10/101519nothuman.jpg)](https://www.businessinsider.com/clothes-accessories-that-outsmart-facial-recognition-tech-2019-10)

These clothes use outlandish designs to trick facial recognition software into thinking you’re not a human – [Business Insider](https://www.businessinsider.com/clothes-accessories-that-outsmart-facial-recognition-tech-2019-10).

I Read About “Design For Trust” So You Don’t Have To – [Simply Secure](https://simplysecure.org/blog/design-trust).

Ken Thompson’s Unix password – [leah blogs](https://leahneukirchen.org/blog/archive/2019/10/ken-thompson-s-unix-password.html).

[![Testing BLE](https://cdn-blog.adafruit.com/uploads/2019/10/101519punch.jpg)](https://punchthrough.com/bluetooth-low-energy-peripheral-testing/)

Testing Bluetooth Low Energy Peripherals using a Python Script – [Punch Through](https://punchthrough.com/bluetooth-low-energy-peripheral-testing/).

[![Tiny TTN Mapper](https://cdn-blog.adafruit.com/uploads/2019/10/101519TTN.jpg)](https://www.hackster.io/fablabeu/gps-mapper-for-the-things-network-ttn-lorawan-584ed7)

Tiny TTN Mapper ready for the wild – how to build yours – [hackster.io](https://www.hackster.io/fablabeu/gps-mapper-for-the-things-network-ttn-lorawan-584ed7)

Bel is a spec for a new dialect of Lisp, written in itself. It consists of two text files meant to be read in parallel: [a guide](https://sep.yimg.com/ty/cdn/paulgraham/bellanguage.txt?t=1570888282&) to the Bel language, and the [Bel source](https://sep.yimg.com/ty/cdn/paulgraham/bel.bel?t=1570888282&). For those who just want to see some code examples, there’s a [file](https://sep.yimg.com/ty/cdn/paulgraham/belexamples.txt?t=1570888282&) of those – [Bel](http://paulgraham.com/bel.html).

[![PyTorch and TensorFlow usage in 2019](https://cdn-blog.adafruit.com/uploads/2019/10/101519becca.png)](https://blog.adafruit.com/2019/10/11/pytorch-and-tensorflow-usage-in-2019-pytorch-tensorflow-machinelearning-datascience-artificialintelligence-chhillee/)

PyTorch and TensorFlow usage in 2019 by Becca – [Adafruit](https://blog.adafruit.com/2019/10/11/pytorch-and-tensorflow-usage-in-2019-pytorch-tensorflow-machinelearning-datascience-artificialintelligence-chhillee/).

[![icons](https://cdn-blog.adafruit.com/uploads/2019/10/101519icons.jpg)](https://icons8.com/icons/ios-glyphs)

Free iOS Glyph Icons – [icons8.com](https://icons8.com/icons/ios-glyphs), and [ICONSVG](https://iconsvg.xyz/).

[![Cardboard](https://cdn-blog.adafruit.com/uploads/2019/10/101519cardboard.jpg)](https://twitter.com/kjarrett/status/1182230656383934469)

Kevin is compiling a collection of cardboard attachment technique examples – [Twitter](https://twitter.com/kjarrett/status/1182230656383934469) & [Google Drive](https://drive.google.com/drive/folders/1ui2d1dGuA7Ry4IDbEXhZi_7GX2yGvbaH).

[![Imagineering](https://cdn-blog.adafruit.com/uploads/2019/10/101519imagineering.jpg)](https://www.khanacademy.org/humanities/hass-storytelling/imagineering-in-a-box)

[Imagineering in a Box!](https://www.khanacademy.org/humanities/hass-storytelling/imagineering-in-a-box)

> _“Have you ever wondered how theme parks come to life? Disney Imagineers from hundreds of career disciplines around the world share how they use a wide range of skills – from story development and conceptual design, to math, physics and engineering – that all come together to create immersive experiences. Imagineering in a Box allows you to explore different aspects of theme park design, from characters to ride development, as you design a theme park of your very own.”_

The videos are here – [YouTube](https://www.youtube.com/channel/UC4DavIB24rEr5waVY5AgZLg). The ONLY thing missing is the hardware to do this, we’ll email Disney and see if they want a CircuitPython + CRICKIT for these lessons!

[![Robot bat](https://cdn-blog.adafruit.com/uploads/2019/10/101519robobat.jpg)](https://www.ri.cmu.edu/event/ri-seminar-seth-hutchinson-georgia-tech-professor-kuka-chair-for-robotics-2019-10-04/)

[Design, Modeling and Control of a Robot Bat:](https://www.ri.cmu.edu/event/ri-seminar-seth-hutchinson-georgia-tech-professor-kuka-chair-for-robotics-2019-10-04/) From Bio-inspiration to Engineering Solutions – [YouTube](https://youtu.be/kuR42omde-I).

[![Xaxxon OpenLIDAR Sensor](https://cdn-blog.adafruit.com/uploads/2019/10/101519xaxxon_openlidar_sensor.jpg)](http://www.xaxxon.com/xaxxon/openlidar#openhardware)

The Xaxxon OpenLIDAR Sensor is a rotational laser scanner with open software and hardware, intended for use with autonomous mobile robots and simultaneous-location-and-mapping (SLAM) applications – [xaxxon](http://www.xaxxon.com/xaxxon/openlidar#openhardware).

Publicly available Human Activity Recognition Datasets – [GitHub](https://github.com/mmalekzadeh/motion-sense/blob/master/Public_HAR_Data.md).

[![GHI](https://cdn-blog.adafruit.com/uploads/2019/10/101519ghi.jpg)](https://www.youtube.com/watch?v=6Maexq245lY)

MFGday GHI Electronics & BrainPad – [YouTube](https://www.youtube.com/watch?v=6Maexq245lY).

[![Streamlit](https://cdn-blog.adafruit.com/uploads/2019/10/101519streamlit.gif)](https://towardsdatascience.com/coding-ml-tools-like-you-code-ml-models-ddba3357eace)

Turn Python Scripts into Beautiful ML Tools … [Introducing Streamlit, an app framework built for ML engineers](https://towardsdatascience.com/coding-ml-tools-like-you-code-ml-models-ddba3357eace).

[![PiML](https://cdn-blog.adafruit.com/uploads/2019/10/101519piml.jpg)](https://projects.raspberrypi.org/en/pathways/scratch-machine-learning)

Machine learning projects for Scratch with Raspberry Pi – [projects.raspberrypi.org](https://projects.raspberrypi.org/en/pathways/scratch-machine-learning)

[![Raspberry Pi Handheld 3D Scanner](https://cdn-blog.adafruit.com/uploads/2019/10/101519piscan.jpg)](https://youtu.be/E_22Ate_5nw)

Raspberry Pi Handheld 3D Scanner, [overview](https://eleccelerator.com/pi-handheld-3d-scanner/) and [YouTube](https://youtu.be/E_22Ate_5nw).

[![Retro ESP3](https://cdn-blog.adafruit.com/uploads/2019/10/101519retro32.gif)](https://github.com/retro-esp32/RetroESP32)

Retro ESP32 is a turbo charged Odroid Go Launcher, Emulator and ROM Manager – [GitHub](https://github.com/retro-esp32/RetroESP32).

[![Sandance](https://cdn-blog.adafruit.com/uploads/2019/10/101519sandance.gif)](https://marketplace.visualstudio.com/items?itemName=msrvida.vscode-sanddance)

SandDance for VSCode, by using easy-to-understand views, SandDance helps you find insights about your data, which in turn help you tell stories supported by data, build cases based on evidence, test hypotheses, dig deeper into surface explanations, support decisions for purchases, or relate data into a wider, real world context – [marketplace.visualstudio.com](https://marketplace.visualstudio.com/items?itemName=msrvida.vscode-sanddance)

[![cookies](https://cdn-blog.adafruit.com/uploads/2019/10/101519billboard3.png)](https://github.com/jakejarvis/awesome-shodan-queries)

A collection of interesting, funny, and depressing search queries to plug into Shodan, IoT search engine – [GitHub](https://github.com/jakejarvis/awesome-shodan-queries). That is a bank that has a LED signs for free cookies.

A Code Glitch May Have Caused Errors In More Than 100 Published Studies – [Motherboard](https://www.vice.com/en_us/article/zmjwda/a-code-glitch-may-have-caused-errors-in-more-than-100-published-studies).

urllib3 just reached 1 BILLION downloads, it’s the third package on [PyPI](https://pypi.org/) to do so, the other two being six and pip – [PeyPy](https://pepy.tech/project/urllib3) via [Twitter](https://twitter.com/sethmlarson/status/1182710786436882435). Using PeyPy we looked up [Blinka](https://pypi.org/project/Adafruit-Blinka/): [we’re over 142,000 downloads](https://pepy.tech/project/adafruit-blinka)!

[![4H Week](https://cdn-blog.adafruit.com/uploads/2019/10/1015194h.jpg)](https://blog.adafruit.com/2019/10/11/national-4-h-week-national4hweek-4h-4-h-circuit-playground-express-is-in-stock-and-on-sale-today-use-code-national4hweek-on-checkout-inspirekidstodo-4hyouthinaction-4h-4hgrowshere/)

It was [National 4-H Week last week](https://blog.adafruit.com/2019/10/11/national-4-h-week-national4hweek-4h-4-h-circuit-playground-express-is-in-stock-and-on-sale-today-use-code-national4hweek-on-checkout-inspirekidstodo-4hyouthinaction-4h-4hgrowshere/) …

> _“It is believed that the first official ‘Club Week’ was proclaimed by Governor Christianson in Minnesota in 1926 when he established April 18-24 as ‘Club Week’ to promote the work of the Boys and Girls Clubs in that state, as reported in the April-May, 1926 issue of National Boys and Girls Club News.”_

Check out the [Tweets](https://twitter.com/hashtag/National4HWeek?src=hashtag_click&f=live) and don’t forget, there is a special [Python-powered 4-H edition of Circuit Playground Express](https://www.adafruit.com/product/4180)!

[![maker to market](https://cdn-blog.adafruit.com/uploads/2019/10/101519startups.jpg)](https://startupsmagazine.co.uk/)

From maker to market How ‘Ladyada’, Founder of Adafruit, developed Circuit Playground, [Startup Magazine](https://startupsmagazine.co.uk/), and [PDF](https://cdn-blog.adafruit.com/uploads/2019/10/StartupsSurvivalGuideDigital.pdf).

[![Python Release Cycle](https://cdn-blog.adafruit.com/uploads/2019/10/101519pythonrelease.jpg)](https://python-release-cycle.glitch.me/)

[Python Release Cycle](https://python-release-cycle.glitch.me/) – Made by: @di\_codes [Made with](https://developers.google.com/chart/interactive/docs/gallery/ganttchart), [source](https://devguide.python.org/devcycle/), and [more](https://devguide.python.org/#status-of-python-branches).

[PyCon US 2020](https://us.pycon.org/2020/) is opening applications for financial aid. They are accepting applications through January 31, 2020. To apply, first set up an account on the site, and then you will be able to fill out the application through your dashboard. The financial aid program aims to bring many folks to PyCon by limiting the maximum grant amount per person; this way PyCon can offer support to more people based on individual need. The financial aid program reimburses direct travel costs including transportation, hotel, and childcare, as well as offering discounted or waived registration tickets. For complete details, see our FAQ, and contact pycon-aid@python.org with further questions – [PyCon blog](https://pycon.blogspot.com/2019/10/financial-aid-launches-for-pycon-us-2020.html).

#ICYDNCI What was the most popular, most clicked link, in [last week’s newsletter](https://www.adafruitdaily.com/2019/10/08/happy-ada-lovelace-day-thank-you-mitsuharu-aoyama-and-more-python-adafruit-circuitpython-pythonhardware-circuitpython-micropython-thepsf-adafruit/)? [Ada Lovelace Day](https://findingada.com/).

[![AdaiOS](https://cdn-blog.adafruit.com/uploads/2019/10/1015adaday.jpg)](https://twitter.com/gallaugher/status/1181318585291026433)

Speaking of [Ada Lovelace Day](https://blog.adafruit.com/tag/ald19/), Professor John and students made this great iOS app celebrating women in tech as part of their first exam – [Twitter](https://twitter.com/gallaugher/status/1181318585291026433). Looks like a Ladyada made it in there, thank you!

PyDev of the Week: Elana Hashman from [Mouse vs Python](https://www.blog.pythonlibrary.org/2019/10/14/pydev-of-the-week-elana-hashman/)

CircuitPython Weekly for October 14th, 2019 [on YouTube](https://youtu.be/sGLswv_yHxk)

Made with Mu
------------

Does Mu work with the new mac OSX Catalina? Yes! With a note from Ntoll the creator… [Daily builds are here](http://mu-builds.s3-website.eu-west-2.amazonaws.com/?prefix=)…

> _“the update to OSX Catalina breaks Mu in dark and high-contrast modes (text remains black, so can’t be seen). It’s still fine for “day” mode, although code colouration might not work properly. I tested things this morning and it’s down to the version of Qt packaged with the 1.0.2 version being old. I hope to release a new alpha version early next week that fixes the issue. BTW, the only reason it’s called “alpha” is because the \*new\* features may not be finished or finalised. Alpha versions of Mu still have to pass all the tests and things we do for a regular release. Just letting you know in case you get folks on your forums or support channels asking.”_

Why Mu? Mu tries to make it as easy as possible to get started with programming but aims to help you graduate to “real” development tools soon after. Everything in Mu is the “real thing” but presented in as simple and obvious way possible. It’s like the toddling stage in learning to walk: you’re finding your feet and once you’re confident, you should move on and explore! Put simply, Mu aims to foster autonomy. Try out Mu today! – [codewith.mu](https://codewith.mu/)

Coming Soon
-----------

[![Panel](https://cdn-blog.adafruit.com/uploads/2019/10/101519panel.png)](https://www.adafruit.com/new)

It’s pumpkin spice season! And that means sending out circuit board panels. This is the one going out now. Lots of testers, but also some new designs to keep an eye out for! Can you guess what some of them are?

[![case](https://cdn-blog.adafruit.com/uploads/2019/10/101519badgecase01.jpg)](https://www.adafruit.com/?q=pybadge)

[![case](https://cdn-blog.adafruit.com/uploads/2019/10/101519badgecase02.jpg)](https://www.adafruit.com/?q=pybadge)

A new case is coming soon for the [PyBadge](https://www.adafruit.com/?q=pybadge).

[![Edge badge](https://cdn-blog.adafruit.com/uploads/2019/10/101519bcbadge.jpg)](https://www.adafruit.com/new)

BrainCraft (EDGE) badge Version 2 is coming along!

[![FT232H](https://cdn-blog.adafruit.com/uploads/2019/10/101519ft232h.jpg)](https://youtu.be/jgbUCkcGIZ4)

Testing the Adafruit FT232H board with NeoPixels on Windows PC – Did you know it’s possible to drive NeoPixels from an FT232H? Yes! This lets us control these low cost LEDs from any computer with a USB port, like a Mac or Windows PC – direct from Python! This could make for some cool, inexpensive, easy to build interactive art projects – [YouTube](https://youtu.be/jgbUCkcGIZ4).

New Learn Guides!
-----------------

[Circuit Playground Bluetooth Cauldron](https://learn.adafruit.com/cpx-cauldron) from [Noe and Pedro](https://learn.adafruit.com/users/pixil3d)

Updated Guides – Now With More Python!
--------------------------------------

**You can use CircuitPython libraries on Raspberry Pi!** We’re updating all of our CircuitPython guides to show how to wire up sensors to your Raspberry Pi, and load the necessary CircuitPython libraries to get going using them with Python. We’ll be including the updates here so you can easily keep track of which sensors are ready to go. Check it out!

[Adafruit 15×7 CharliePlex FeatherWing](https://learn.adafruit.com/adafruit-15x7-7x15-charlieplex-led-matrix-charliewing-featherwing)

[Adafruit CharliePlex LED Matrix Bonnet](https://learn.adafruit.com/adafruit-charlieplex-bonnet/)

[Adafruit BMP388 – Precision Barometric Pressure and Altimeter](https://learn.adafruit.com/adafruit-bmp388/python-circuitpython)

[MLX90393 Wide-Range 3-Axis Magnetometer](https://learn.adafruit.com/mlx90393-wide-range-3-axis-magnetometer)

[Adafruit NeoTrellis](https://learn.adafruit.com/adafruit-neotrellis)

[Adafruit PN532 RFID/NFC Breakout and Shield](https://learn.adafruit.com/adafruit-pn532-rfid-nfc)

[Adafruit Seesaw](https://learn.adafruit.com/adafruit-seesaw-atsamd09-breakout)

[Adafruit 16-Channel PWM/Servo HAT & Bonnet for Raspberry Pi](https://learn.adafruit.com/adafruit-16-channel-pwm-servo-hat-for-raspberry-pi/overview)

[Monochrome OLED Breakouts](https://learn.adafruit.com/monochrome-oled-breakouts/python-wiring)

[Adafruit GPIO Expander Bonnet for Raspberry Pi](https://learn.adafruit.com/gpio-expander-bonnet/)

[Adafruit MAX31856 Universal Thermocouple Amplifier](https://learn.adafruit.com/adafruit-max31856-thermocouple-amplifier)

[Introducing Adafruit Trellis](https://learn.adafruit.com/adafruit-trellis-diy-open-source-led-keypad)

[TMP006 Infrared Sensor Breakout](https://learn.adafruit.com/infrared-thermopile-sensor-breakout)

[ADXL345 Digital Accelerometer](https://learn.adafruit.com/adxl345-digital-accelerometer)

CircuitPython Libraries!
------------------------

[![CircuitPython Libraries](https://cdn-blog.adafruit.com/uploads/2019/10/101519blinka.png)](https://circuitpython.org/libraries)

CircuitPython support for hardware continues to grow. We are adding support for new sensors and breakouts all the time, as well as improving on the drivers we already have. As we add more libraries and update current ones, you can keep up with all the changes right here!

For the latest drivers, download the [Adafruit CircuitPython Library Bundle](https://circuitpython.org/libraries).

If you’d like to contribute, CircuitPython libraries are a great place to start. Have an idea for a new driver? File an issue on [CircuitPython](https://github.com/adafruit/circuitpython/issues)! Interested in helping with current libraries? Check out [this GitHub issue on CircuitPython](https://github.com/adafruit/circuitpython/issues/1246) for an overview of the State of the CircuitPython Libraries, updated each week. We’ve included open issues from the library issue lists, and details about repo-level issues that need to be addressed. We have a guide on [contributing to CircuitPython with Git and Github](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github) if you need help getting started. You can also find us in the #circuitpython channel on the [Adafruit Discord](https://adafru.it/discord). Feel free to contact Kattni (@kattni) with any questions.

You can check out this [list of all the CircuitPython libraries and drivers available](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/blob/master/circuitpython_library_list.md).

The current number of CircuitPython libraries is **187**!

**Updated Libraries!**

Here’s this week’s updated CircuitPython libraries:

*   [Adafruit\_CircuitPython\_AdafruitIO](https://github.com/adafruit/Adafruit_CircuitPython_AdafruitIO)
*   [Adafruit\_CircuitPython\_MiniMQTT](https://github.com/adafruit/Adafruit_CircuitPython_MiniMQTT)
*   [Adafruit\_CircuitPython\_MCP3xxx](https://github.com/adafruit/Adafruit_CircuitPython_MCP3xxx)
*   [Adafruit\_CircuitPython\_NeoPixel](https://github.com/adafruit/Adafruit_CircuitPython_NeoPixel)
*   [Adafruit\_CircuitPython\_ESP32SPI](https://github.com/adafruit/Adafruit_CircuitPython_ESP32SPI)
*   [Adafruit\_CircuitPython\_FancyLED](https://github.com/adafruit/Adafruit_CircuitPython_FancyLED)
*   [Adafruit\_CircuitPython\_RGB\_Display](https://github.com/adafruit/Adafruit_CircuitPython_RGB_Display)

**PyPI Download Stats!**

We’ve written a special library called Adafruit Blinka that makes it possible to use CircuitPython Libraries on [Raspberry Pi and other compatible single-board computers](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux/). Adafruit Blinka and all the CircuitPython libraries have been deployed to PyPI for super simple installation on Linux! Here are the top 10 CircuitPython libraries downloaded from PyPI in the last week, including the total downloads for those libraries:

Library

Last Week

Total

Adafruit-Blinka

1515

43559

Adafruit\_CircuitPython\_BusDevice

888

23418

Adafruit\_CircuitPython\_MCP230xx

503

8147

Adafruit\_CircuitPython\_NeoPixel

178

5671

Adafruit\_CircuitPython\_Register

174

6294

Adafruit\_CircuitPython\_PCA9685

122

4394

Adafruit\_CircuitPython\_Motor

116

4635

Adafruit\_CircuitPython\_ServoKit

113

3367

Adafruit\_CircuitPython\_RGB\_Display

113

584

Adafruit\_CircuitPython\_MotorKit

109

2381

What is the team up to?
-----------------------

**Bryan**

[![Bryan](https://cdn-blog.adafruit.com/uploads/2019/10/101519bryan01.png)](https://circuitpython.org/)

[![Bryan](https://cdn-blog.adafruit.com/uploads/2019/10/101519bryan02.png)](https://circuitpython.org/)

_“Over the past week I’ve been working on drivers for the LSM303AGR Accelerometer+Magnetometer by ST which is similar to but not quite the same as the LSM303DLH. Both sensors actually have two separate chips inside with different I2C addresses. Other than the AGR being significantly smaller (2x2mm!) it has a different onboard magnetometer. The two sensors now share code for the accelerometer and have separate libraries for their magnetometers. While testing the G-range settings of the new accelerometer (by whacking it with a pen of course), I found that the range settings were not sicking. After a few hours of head scratching and consulting an oracle (my logic analyzer), I discovered a bug in an underlying library that was clobbering the range setting bits while setting some adjacent bits in the same register. The bug has been fixed, things work correctly. Not today bugs, not today!”_

**Dan**

_“I’m continuing to work on some code refactoring needed to add BLE bonding. Originally some refactoring implied a whole chain of changes that became too complicated. I’ve now refactored the refactoring so I can do it in discrete pieces. I’m also implementing a way to read the microcontroller supply voltage from CircuitPython so you can detect when the input voltage goes low enough that the 3.3V regulator can no longer output 3.3V. This would mean, for instance, that the battery level is getting too low to run safely any more.”_

**Kattni**

_“This week, we’re diving back into updating guides with CircuitPython and Python Usage. Thanks to [Adafruit Blinka](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux/circuitpython-raspi), you can use CircuitPython libraries on Linux computers such as the Raspberry Pi. Last year, we went through all of the existing CircuitPython libraries and published them to PyPI for use on Linux. We updated a huge number of guides with both CircuitPython and Python Usage. However, there are still a huge number left. (We have a lot of guides!) This week began with updating the [Trellis guide](https://learn.adafruit.com/adafruit-trellis-diy-open-source-led-keypad/python-circuitpython), and continued with the [TMP006 guide](https://learn.adafruit.com/infrared-thermopile-sensor-breakout). Now we’re jumping back into the project right where we left off, with MAX31856, ADXL345, and the MPR121 HAT and shield up next. All updated guides will be added to the newsletter and blogged. If you’re interested in using Adafruit hardware on your Raspberry Pi or other compatible single board computer, keep an eye out for these updates!”_

**Lucian**

_“I’ve spent the last week working on some bug fixes, UART and DAC support. UART will require a significantly different structure than the other_ busio _peripherals like I2C and SPI, since it needs to constantly be ready to receive new data even when the user isn’t expecting it. This is especially important for GPS devices, so the feature has been put on hold until the GPS FeatherWing arrives. In the meantime, I’ve wrapped up DAC support for the STM32 boards that support it, such as the Feather STM32F405 and the Pyboard. Once both features are merged, I’ll be moving on to some much needed cleanup of the STM32 port, and a dramatic expansion of the number of STM32 boards supported with CircuitPython. I’m also looking forward to fully testing the big pile of FeatherWings on my desk, and working on some spooky halloween projects.”_

**Melissa**

[![Melissa](https://cdn-blog.adafruit.com/uploads/2019/10/101519gizmom.jpg)](https://learn.adafruit.com/adafruit-tft-gizmo)

[![Melissa](https://cdn-blog.adafruit.com/uploads/2019/10/101519tftm.jpg)](https://learn.adafruit.com/adafruit-tft-gizmo)

_“This week I finished up writing the TFT Gizmo Learn guide. You can check the guide [here](https://learn.adafruit.com/adafruit-tft-gizmo). After that, I wrote three demos for connecting external breakouts and PiTFTs up to the Raspberry Pi. The demos are meant to be used among all of the different color displays. I started with the 2.2” TFT Breakout and am doing a sweep among all of the guides to add some Python code to it. If your favorite breakout or PiTFT display guide doesn’t already have the Python code, be sure to keep an eye out for some updates.”_

Upcoming events!
----------------

[![Hacktoberfest](https://cdn-blog.adafruit.com/uploads/2019/10/101519hacktober.jpg)](https://hacktoberfest.digitalocean.com)

Hacktoberfest is open to everyone in the global community. Whether you’re a developer, student learning to code, event host, or company of any size, you can help drive growth of open source and make positive contributions to an ever-growing community. All backgrounds and skill levels are encouraged to complete the challenge – [https://hacktoberfest.digitalocean.com](hacktoberfest.digitalocean.com)

[![Open source hardware month](https://cdn-blog.adafruit.com/uploads/2019/10/101519oshwmonth.jpg)](https://www.oshwa.org/2019/07/26/october-is-open-hardware-month-2/)

[October is Open Hardware Month @ Open Source Hardware Association](https://www.oshwa.org/2019/07/26/october-is-open-hardware-month-2/).

> _“October is Open Hardware Month! Check out the [Open Hardware Month website](http://ohm.oshwa.org/). Host an event, find a local event, or [certify](https://certification.oshwa.org/) your hardware to support Open Source Hardware. We are providing resources and asking you, the community, to host small, local events in the name of open source hardware. Tell us about your October event by [filling out the form below](https://docs.google.com/forms/d/e/1FAIpQLSfjvJmcRXbpgjRACgY_BbaDzQZRa6wxEcP-xwaBpC0X6mvsPw/viewform). Your event will be featured on [OSHWA’s Open Hardware Month page](http://ohm.oshwa.org/) (provided you have followed OSHWA’s rules listed on the [“Do’s and Don’ts”](http://ohm.oshwa.org/dos-and-donts/) page).”_

[Read more](https://www.oshwa.org/2019/07/26/october-is-open-hardware-month-2/), [Tweet for speakers in 2020](https://twitter.com/ohsummit/status/1154881782677831680), and Open Hardware Month @ [http://ohm.oshwa.org/](http://ohm.oshwa.org/)

[![TensorFlow World](https://cdn-blog.adafruit.com/uploads/2019/10/101519tfworld.jpg)](https://conferences.oreilly.com/tensorflow/tf-ca)

October 28–31, 2019. Be part of the ML revolution. Santa Clara, California, USA. TensorFlow is powering everything from data centers to edge devices, across industries from finance to advanced healthcare. And now, with TensorFlow 2.0 and the evolving ecosystem of tools and libraries, it’s doing it all so much easier – [TensorFlow World](https://conferences.oreilly.com/tensorflow/tf-ca).

[![Hackaday Superconference](https://cdn-blog.adafruit.com/uploads/2019/10/101519supercon.jpg)](https://hackaday.io/superconference/)

Hackaday Superconference is November 15th, 16th, and 17th in Pasadena, California, USA. The Hackaday Superconference is returning for another 3 full days of technical talks, badge hacking, and hands-on workshops: [Eventbrite](https://www.eventbrite.com/e/hackaday-superconference-2019-tickets-60129236164?aff=0626com) & [hackaday.io](https://hackaday.io/superconference/)

[![Pycon 2020](https://cdn-blog.adafruit.com/uploads/2019/10/101519pycon.png)](https://us.pycon.org/2020/)

April 15-23, 2020, Pittsburgh, Pennsylvania, USA – The PyCon 2020 conference, which will take place in Pittsburgh, is the largest annual gathering for the community using and developing the open-source Python programming language. It is produced and underwritten by the Python Software Foundation, the 501(c)(3) nonprofit organization dedicated to advancing and promoting Python. Through PyCon, the PSF advances its mission of growing the international community of Python programmers – [PyCon 2020](https://us.pycon.org/2020/).

Latest releases
---------------

CircuitPython’s stable release is [4.1.0](https://github.com/adafruit/circuitpython/releases/latest) and its unstable release is [5.0.0-alpha.4](https://github.com/adafruit/circuitpython/releases). New to CircuitPython? Start with our [Welcome to CircuitPython Guide](https://learn.adafruit.com/welcome-to-circuitpython).

[20191014](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) is the latest CircuitPython library bundle.

[v1.11](https://micropython.org/download) is the latest MicroPython release. Documentation for it is [here](http://docs.micropython.org/en/latest/pyboard/).

[3.7.4](https://www.python.org/downloads/) is the latest Python release. The latest pre-release version is [3.8.0rc1](https://www.python.org/download/pre-releases/).

[1.4k Stars](https://github.com/adafruit/circuitpython/stargazers) Like CircuitPython? [Star it on GitHub!](https://github.com/adafruit/circuitpython)

Call for help – CircuitPython messaging to other languages!
-----------------------------------------------------------

[![Hello world](https://cdn-blog.adafruit.com/uploads/2019/10/101519helloworld.jpg)](https://github.com/adafruit/circuitpython/issues/1098)

We [posted on the Adafruit blog](https://blog.adafruit.com/2018/08/15/help-bring-circuitpython-messaging-to-other-languages-circuitpython/) about bringing CircuitPython messaging to other languages, one of the exciting features of CircuitPython 4.x is translated control and error messages. Native language messages will help non-native English speakers understand what is happening in CircuitPython even though the Python keywords and APIs will still be in English. If you would like to help, [please post](https://github.com/adafruit/circuitpython/issues/1098) to the main issue on GitHub and join us on [Discord](https://adafru.it/discord).

We made this graphic with translated text, we could use your help with that to make sure we got the text right, please check out the text in the image – if there is anything we did not get correct, please let us know. Dan sent me this [handy site too](http://helloworldcollection.de/#Human).

jobs.adafruit.com – Find a dream job, find great candidates!
------------------------------------------------------------

[![jobs.adafruit.com](https://cdn-blog.adafruit.com/uploads/2019/10/101519jobs.jpg)](https://jobs.adafruit.com/)

[jobs.adafruit.com](https://jobs.adafruit.com/) has returned and folks are posting their skills (including CircuitPython) and companies are looking for talented makers to join their companies – from Digi-Key, to Hackaday, Microcenter, Raspberry Pi and more.

14,450 thanks!
--------------

[![14,450](https://cdn-blog.adafruit.com/uploads/2019/10/10151914kdiscord.jpg)](https://adafru.it/discord)

[![Adafruit Discord](https://discordapp.com/api/guilds/327254708534116352/embed.png?style=banner3)](https://discord.gg/adafruit)

The Adafruit Discord community, where we do all our CircuitPython development in the open, reached over 14,450 humans, thank you! Join today! [https://adafru.it/discord](https://adafru.it/discord)

ICYMI – In case you missed it
-----------------------------

[![ICYMI](https://cdn-blog.adafruit.com/uploads/2019/10/101519icymi.jpg)](https://www.youtube.com/playlist?list=PLjF7R1fz_OOXRMjM7Sm0J2Xt6H81TdDev)

The wonderful world of Python on hardware! This is our first video-newsletter-podcast that we’ve started! The news comes from the Python community, Discord, Adafruit communities and more. It’s part of the weekly newsletter, then we have a segment on ASK an ENGINEER and this is the video slice from that! The complete Python on Hardware weekly videocast [playlist is here](https://www.youtube.com/playlist?list=PLjF7R1fz_OOXRMjM7Sm0J2Xt6H81TdDev).

This video podcast is on [iTunes](https://itunes.apple.com/us/podcast/python-on-hardware/id1451685192?mt=2), [YouTube](https://www.youtube.com/playlist?list=PLjF7R1fz_OOXRMjM7Sm0J2Xt6H81TdDev), [IGTV (Instagram TV](https://www.instagram.com/adafruit/channel/)), and [XML](https://itunes.apple.com/us/podcast/python-on-hardware/id1451685192?mt=2).

[Weekly community chat on Adafruit Discord server CircuitPython channel – Audio / Podcast edition](https://itunes.apple.com/us/podcast/circuitpython-weekly-meeting/id1451685016) – Audio from the Discord chat space for CircuitPython, meetings are usually Mondays at 2pm ET, this is the audio version on [iTunes](https://itunes.apple.com/us/podcast/circuitpython-weekly-meeting/id1451685016), Pocket Casts, [Spotify](https://adafru.it/spotify), and [XML feed](https://adafruit-podcasts.s3.amazonaws.com/circuitpython_weekly_meeting/audio-podcast.xml).

And lastly, we are working up a single destination for all things podcast-able here – [podcasts.adafruit.com](https://podcasts.adafruit.com/)

Codecademy “Learn Hardware Programming with CircuitPython”
----------------------------------------------------------

[![Codecademy CircuitPython](https://cdn-blog.adafruit.com/uploads/2019/10/101519codecademy_python.png)](https://www.codecademy.com/learn/learn-circuitpython?utm_source=adafruit&utm_medium=partners&utm_campaign=circuitplayground&utm_content=pythononhardwarenewsletter)

Codecademy, an online interactive learning platform used by more than 45 million people, has teamed up with the leading manufacturer in STEAM electronics, Adafruit Industries, to create a coding course, “Learn Hardware Programming with CircuitPython”. The course is now available in the [Codecademy catalog](https://www.codecademy.com/learn/learn-circuitpython?utm_source=adafruit&utm_medium=partners&utm_campaign=circuitplayground&utm_content=pythononhardwarenewsletter).

Python is a highly versatile, easy to learn programming language that a wide range of people, from visual effects artists in Hollywood to mission control at NASA, use to quickly solve problems. But you don’t need to be a rocket scientist to accomplish amazing things with it. This new course introduces programmers to Python by way of a microcontroller — CircuitPython — which is a Python-based programming language optimized for use on hardware.

CircuitPython’s hardware-ready design makes it easier than ever to program a variety of single-board computers, and this course gets you from no experience to working prototype faster than ever before. Codecademy’s interactive learning environment, combined with Adafruit’s highly rated Circuit Playground Express, present aspiring hardware hackers with a never-before-seen opportunity to learn hardware programming seamlessly online.

Whether for those who are new to programming, or for those who want to expand their skill set to include physical computing, this course will have students getting familiar with Python and creating incredible projects along the way. By the end, students will have built their own bike lights, drum machine, and even a moisture detector that can tell when it’s time to water a plant.

Visit Codecademy to access the [Learn Hardware Programming with CircuitPython](https://www.codecademy.com/learn/learn-circuitpython?utm_source=adafruit&utm_medium=partners&utm_campaign=circuitplayground&utm_content=pythononhardwarenewsletter) course and Adafruit to purchase a [Circuit Playground Express](https://www.adafruit.com/product/3333).

Codecademy has helped more than 45 million people around the world upgrade their careers with technology skills. The company’s online interactive learning platform is widely recognized for providing an accessible, flexible, and engaging experience for beginners and experienced programmers alike. Codecademy has raised a total of $43 million from investors including Union Square Ventures, Kleiner Perkins, Index Ventures, Thrive Capital, Naspers, Yuri Milner and Richard Branson, most recently raising its $30 million Series C in July 2016.

Contribute!
-----------

The CircuitPython Weekly Newsletter is a CircuitPython community-run newsletter emailed every Tuesday. The complete [archives are here](https://www.adafruitdaily.com/category/circuitpython/). It highlights the latest CircuitPython related news from around the web including Python and MicroPython developments. To contribute, edit next week’s draft [on GitHub](https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts) and [submit a pull request](https://help.github.com/articles/editing-files-in-your-repository/) with the changes. Join our [Discord](https://adafru.it/discord) or [post to the forum](https://forums.adafruit.com/viewforum.php?f=60) for any further questions.