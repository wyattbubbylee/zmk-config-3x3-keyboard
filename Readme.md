# Ninepad

This is my zmk config for my handwired ninepad macropad

* layer 0: default - window switcher - layer picker
* layer 1: media
* layer 2: bluetooth
* layer 3: minecraft_1
* layer 4: minecraft_2
* layer 5: arrows
* layer 6: empty
* layer 7: reset
* layer 8: numbers
* layer 9: empty



<img alt="ninepad-assembled" src="https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/1b9f3e36-a67f-4df2-be81-cfdf64c11aa5" width="500"> 

<img alt="ninepad-plate-switched" src="https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/067a16ae-0a70-47f3-8edc-3711ca4944b4" width="500"> 

> (Left) fully assembled ninepad
> (Right) plate with switches inserted ready for wiring


## Getting back to default

No matter what layer you are in, holding 7 (top left) will bring you to the 7th
layer (reset).  Now tap 9 (to right) and you will go back to the default layer.

## layer 0: default - window switcher - layer picker

Once plugged in you will be brought to the default layer.  Tapping on any key
in this layer will press Left Gui (Super) plus the corresponding number.  I
have my window manager set up so that this will take you to workspace 1-9.

Double tapping any key on this layer will take you to the layer with the corresponding number
layer 1-9.

![image](https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/b2686296-a0b8-46b0-a3e7-09c734bd95a6)


## layer 1: media

This layer has media keys, play/pause, next track, previous track, and volume.

![image](https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/4f2d1d47-e979-4140-bf64-5bc599b0864e)

## layer 2: bluetooth

This layer has bluetooth select profile for 1-4, bluetooth clear, backlight
toggle, and rgb toggle.

![image](https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/6323286a-a4c9-4f46-9c50-444228f91d61)

## layer 3: minecraft_1

This layer is for minecraft.  It has wasd, q, e, shift, control, and space.
Holding space will take you to minecraft_2.

![image](https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/0bf4a8c9-2561-40b4-9ea0-72ae92746b93)


## layer 4: minecraft_2

This layer has less critical minecraft keys, b, f5, f3, esc, f, and grave.

![image](https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/1b27eceb-a088-496d-8cfe-3cc5c52e322d)

## layer 5: arrows

This layer is for navigation, it has arrows, page up, page down, home, end, and escape.

![image](https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/512128d0-d6c0-45ee-92bd-66c069c8fd7f)


## layer 6: empty

This layer is left unused.

## layer 7: reset

This is a critical layer that allows me to hold 7 and tap nine from any layer to get back to layer zero.  Notice the &to 0, this is what does that.

![image](https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/435d2295-54e5-458e-bbcb-32c9f889cf4f)

## layer 8: numbers

numbers 1-9

![image](https://github.com/WaylonWalker/zmk-config-ninepad/assets/22648375/b6a17ea7-1f71-43db-9e12-86328c7092fb)

## layer 9: empty

This layer is left unused.
