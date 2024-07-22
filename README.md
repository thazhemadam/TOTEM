<picture align="center">
  <source media="(prefers-color-scheme: dark)" srcset="/docs/images/TOTEM_logo_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="/docs/images/TOTEM_logo_bright.svg">
  <img alt="TOTEM logo" src="/docs/images/TOTEM_logo_dark.svg">
</picture>

<h1 align="center"><pre>T O T E M  v 0 . 0 7 r a c k e r</pre></h1>

TOTEM is a 38 key column-staggered choc split keyboard. It is meant to be used with a SEEED XIAO BLE or RP2040.
It was created by [GEIST](https://github.com/GEIGEIGEIST) for the SEEED XIAO keyboard contest[^1].

TOTEM v0.07racker (pronounced *TOTEM Tracker*) is a variant of the original TOTEM, retrofitted to accomodate a trackpoint module[^2].

## LAYOUT

![TOTEM layout](/docs/images/TOTEM_layout.svg)

## TRACKPOINT

The TOTEM v0.07racker is designed to be compatible with a [2-piece trackpoint](https://deskthority.net/wiki/TrackPoint_Hardware#2-piece_Trackpoint) hardware module.
In particular, with the [SK8707-06](https://www.sprintek.com/en/products/pointing_stick/SK8707-06.aspx) trackpoint module in mind.

However, given that most [trackpoint hardware](https://deskthority.net/wiki/TrackPoint_Hardware#2-piece_Trackpoint) can be operated with similar
pins made available, you should be able to use another trackpoint hardware variant as well, assuming you (hand)wire the respective pinout appropriately.

## PCB

[Here](/PCB/) you can find the KiCad files and Gerbers for the TOTEM.

## CASE

You can use the TOTEM without a case, but [here](/case/) you can find one I made for it.

## BUILD GUIDE
  
The build guide for the TOTEM can be found [here](/docs/buildguide.md).

## FIRMWARE

[QMK config](https://github.com/GEIGEIGEIST/qmk-config-totem) for the TOTEM (wired using the XIAO RP2040)\
[ZMK config](https://github.com/GEIGEIGEIST/zmk-config-totem) for the TOTEM (wireless using the XIAO BLE)

## PHOTOS

This is the TOTEM in a black resin case

![TOTEM black resin](/docs/images/TOTEM_black_perspective.jpg)\
![TOTEM black resin](/docs/images/TOTEM_black_top.jpg)\
![TOTEM black resin](/docs/images/TOTEM_black_bottom.jpg)

## CREDITS

### INSPIRATION

I've added the additional pinky key to make the TOTEM compatible with the layout boards like the [Balbuzard](https://github.com/brow/balbuzard) by [Tom Brow](https://github.com/brow) and the [Osprette](https://github.com/smores56/osprette) by [Sam Mohr](https://github.com/smores56) use, where you put the keybinding of the top left and right keys on an outer pinky key.

### HELP FIXING THINGS

People who helped me create this board and fix stuff

#### PCB

- [Marco "Bob"](https://github.com/GroooveBob)

#### CASE

- [Freya](https://github.com/freya-irl)
- [Bubbleology](https://github.com/bubbleology)

#### FIRMWARE

- [Cem Aksoylar](https://github.com/caksoylar)
- [Grinnie](https://github.com/regicidalplutophage)
- [Alaa Saad Mansour](https://github.com/AlaaSaadAbdo)
- [pekudzu](https://github.com/pekudzu)

If you build a TOTEM I would be pretty happy to see some pictures. And if you want to leave me a tip you can do this [here](https://ko-fi.com/geigeigeist) (but please don't feel pressured)

[^1]: [Here](https://www.hackster.io/geist/totem-a-tiny-splitkeyboard-with-splay-cb2e43) you can read about GEIST's process of making it.
[^2]: https://deskthority.net/wiki/TrackPoint_Hardware#2-piece_Trackpoint
