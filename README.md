# REminiscence

REminiscence port for Vita.

# Requirements

A Vita system capable of running homebrew.

Data files in folder `ux0:/data/RMSC00001/DATA`

You can also copy rs.cfg to `ux0:/data/RMSC00001/` to change some REminiscence settings.

# Button configuration

Arrow Keys:     move Conrad

×:              use the current inventory object / confirm menu selection

○:              talk / use / run / shoot

□:              display the inventory / skip cutscene

△:              take gun out

Start:          display the options

## Compiling

Get [DolceSDK](https://github.com/DolceSDK/doc)

Get [SDL2-vita](https://github.com/isage/SDL-mirror/tree/vita-2.0.12) (This is a required version until it gets included in DolceSDK)

`make -f Makefile.vita`
