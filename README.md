## Intro

This is a breakout board for low pin count SMD components : 0402 0603 0805 1206 SOT23 SOT223 SOT323.

Before that when you wanted to breadboard some SMD components it was a bit tricky :

![Before](https://github.com/DeuxVis/HaveSome_PCB/blob/master/Doc/thumb_BeforeHavingSome.jpg?raw=true "Before having some...")

Now you can use those tiny pretty easy to solder adapters :

![After](https://github.com/DeuxVis/HaveSome_PCB/blob/master/Doc/thumb_V1.0_OSHPark.jpg?raw=true "Ready to prototype !")

## Example uses

See some [sample usages](https://hackaday.io/project/10412-hacker-breakout-board-for-most-popular-smd#menu-details)

## Motivation

This breakout board is usefull to prototype with SMD components by allowing to plug those in a breadboard - or any matching 0.1" spaced pins, like some arduino family boards for instance.

It is derived from the [Awesome PCB project](https://hackaday.io/project/10412-hacker-breakout-board-for-most-popular-smd) by Simon.

My motivation for redesigning it from scratch was to :

*   Learn Kicad.
*   Allow people to order those boards for themselves, as Simon did not "yet" release his files.
*   I need to use some of those.

## Documentation

Not much yet, some pictures in the Doc subfolder.
You can probably use some informations in the [pdf from awesomepcb](http://www.awesomepcb.com/wp-content/uploads/2015/06/0603_0805_1206_SOT23_SOT223_0402_SOT323_rev01_documentation-PCB.pdf) although that board is somewhat different.

## Changelog

### V1.1

Status : still untested.

* Trying to let PCBs.io manufacturing process actually produce vias by not burying them under a pad.
* Beefier traces, especially on center pin - thanks to original Awsome PCB designer Simon for the suggestion on hackaday.io.
* Beefier vias for better current/heat transfer.
* Linked pad 2 and 4 of SOT223 for footprint compatible packages which lack the middle pin. 
* Added silkscreen annotations of pads to pins id matching - thanks to warhawk-avg on hackaday.io for the suggestion.

### V1.0

Status : tested and working but might be bugged depending on PCB manufacturer, vias between top and bottom heatsink surface may not be produced.

## License

![CC BY-NC-SA logo](https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png "CC BY-NC-SA 3.0")

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-nc-sa/3.0/) License - aka CC BY-NC-SA 3.0.

I chose non commercial because the idea is not mine and I don't want someone ripping off sales from [the original publisher](http://www.awesomepcb.com/product-category/pcb-bread-board-tools/).

