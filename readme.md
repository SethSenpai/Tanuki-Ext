# Tanuki-Ext OLED edition

The Tanuki-Ext is a redesign of the original [Tanuki Keyboard](https://github.com/SethSenpai/Tanuki). There were a few things about the original design that were preventing me from using it while coding and doing CAD. Most of all was the lack of dedicated arrow cluster. 

![Picture of the Tanuki-Ext](/Img/DSC_1305.jpg)

The Tanuki-Ext fixes these issues and aims to create and even more open and accessible keyboard platform to experiment with by moving its firmware over to [CircuitPython](https://circuitpython.org/) and [KMKfw](http://kmkfw.io/). This allows you to access and modify your code without the need for extra programs, compilers or debuggers making it very approachable.

![Picture of the Tanuki-Ext](/Img/DSC_1307.jpg)

## Layout
Like the original Tanuki keyboard the design has a split spacebar. Holding down the left spacebar brings you to the lower layer for numbers. Holding down the right spacebar brings you to the top layer for symbols. Never move your fingers from the homerow ever again!

![Layout overview](/Img/keyboard-layout.png)

Both the firmware and design files of the Tanuki are distributed under GNU GPLv3 and are able to be used for commercial under [specific conditions](https://choosealicense.com/licenses/gpl-3.0/).

## Assembly

Assembling the device is quite straight forward. Create the casing from the files in the `Case` folder. Grab a hold of A `PCB` or handwire the keyboard using an [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/). Put on the backplate and close the whole thing up with 4 bolts. Check out the individual folders for further instructions. 

## Keycaps
Normally a full 104 key keycap set should have enough keys to cover the keyboard properly. Just to be sure I've made a list of the needed keycaps below.

| Size | Amount |
| ---- | ------ |
| 2u | 2 |
| 1u | 37 |
| 1.25u | 8 |

I find the most comfortable keycap profile to be DSA or XDA keycaps since I don't need to worry about the keycap height being all over the place due to the uncommon layout of the Tanuki-Ext. 