# ZMK Config

Hi! You've reached my custom config for my six-column wireless Corne.

This builds off my own [custom ZMK fork](https://github.com/lazerwalker/zmk) that merges in several non-standard features not yet upstreamed into core ZMK. Check out the README of that fork for more info on specific branches:

- Plover-HID (to enable stenography suport)
- Retro-tap (to enable home row mods and autoshift at the same time)

It also includes my own custom implementation of the Ardux one-handed layout, based off of the 'official' [zmk-ardux](https://github.com/arduxio/zmk-ardux), to allow dual-handed Artsey in a single layer (e.g. both the left and right halves simultaneously implement Ardux). Parameterizing it to work with other keyboards is certainly doable, but was more work than I wanted to put in at this time, so my `ardux.dtsi` file would require modifications to be used with a board other than a 6-column Corne.

I'm not including any diagrams of the actual layout, since it's in flux.