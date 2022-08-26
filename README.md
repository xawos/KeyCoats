# KeyMapper

The idea is to emulate to some extent the functionality that the QMK firmware offers but on normal keyboards.
This is to allow one to bring your layout around without the keyboard.
You'll just need an USB keyboard and to plug this thing in the middle.

The layouts are configured in the config folder, to insert in the Teensy before running.
Layer0 defines the keys for the successive layers, the other layers contain the remapped keys.

# TODOs

+ ~~Display~~
+ Keyboard-controlled Display menu
+ Key Macros
+ Tap/hold keys
+ Mouse Settings
+ Host mount microSD to modify 
+ Copy config to internal storage and use that if sd card is not present (i.e. sd card is used for "reprogramming")

# You probably also need this:

[Teensy pinout](https://www.pjrc.com/teensy/pinout.html#:~:text=Teensy%204.1)
[Ili9341 pinout](https://thesolaruniverse.files.wordpress.com/2021/03/092_figure_04_96_dpi.png)

# First picture of the thing
![Thing](./IMG_0420.jpg)
