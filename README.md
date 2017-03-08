# IKEA Lamp PS 2014 Hack

I own an [IKEA PS 2014 Sphere
Lamp](http://www.ikea.com/us/en/catalog/products/60251123/) and of course the
first thing that comes to your mind is "I want to automate it" and "I want
blinky multicolor leds". Suprise, I'm not the only one with this idea and I
took some inspiration from [David Bliss
Blogpost](http://davidbliss.com/2014/11/18/transforming-sphere-lamp/) about his
ideas.

I didn't want to have any CAT5 cables, etc. so here is my Version.

## Features
* 106 individual adressable RGB LEDs (WS2812B)
* Automated Open/Closing via stepper motor
* Wifi and Cloud (uuuuh) connected (Particle.io)

## Images
Its a lamp!

## BOM
* 1x Sparkcore now called [Particle Photon](https://www.particle.io/products/hardware/photon-wifi-dev-kit)
* 1x [EasyDriver Board](http://www.schmalzhaus.com/EasyDriver/)
* 6x [Adafruit NeoPixel 1/4 Ring](https://www.adafruit.com/products/1768)
* 1x [Adafruit NeoPixel Small Ring](https://www.adafruit.com/products/1463)

## Adapter Board
Since I wanted a nice adapter board for the components I created one.
It is hosted at OSH Park: [Ikea PS Lamp Hack Board](Ikea PS Lamp Hack Board)
[Boardfile](https://644db4de3505c40a0444-327723bce298e3ff5813fb42baeefbaa.ssl.cf1.rackcdn.com/uploads/project/design/mwmNWtN2/design.brd) 

<a href="https://oshpark.com/shared_projects/mwmNWtN2"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>

## Hacks
* Endstop must be connected to the Photon Pins (missing silkscreen captions)
* Elko added to the data pins of the neopixels

## Whats inside this repo?
The firmware for the Photon is hosted in the Particle.io Cloud. I want a backup over here.
In addition I will add a server component for triggering weather events and make it easier to control it.

## License
For gods sake, do whatever you want. MIT.
