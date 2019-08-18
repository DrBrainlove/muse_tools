# muse_tools
discontinued Muse SDK &amp; research tools

This repo holds some of the tools that can be used to access the bluetooth stream
on a Muse 1 EEG headset.

## Backstory
Sometime in 2017, Interaxon decided to not put any more energy in SDK development
and changed their model a software subscription model. However, the basic command-line
utilities from before still work with older Muses.

## Installation

LX and [`MuseConnect.java`](https://github.com/DrBrainlove/Mimsy/blob/master/MuseConnect.pde) need to have `muse-io` installed, can still get SDK from here:
https://sites.google.com/a/interaxon.ca/muse-developer-site/download

## Connecting Muse device to a computer

Connect the muse device to controlling computer via bluetooth
[more info needed!]

Once the package has been installed, you should be able to see muse commands available.
In Mac OSX, the files are mapped to `/Applications/Muse/muse-*`


Load muse OSC output in command line with:
```
muse-io --preset 14 --osc osc.udp://localhost:5000
```