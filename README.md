# KeyCoats

The idea is to emulate to some extent the functionality that the [QMK firmware](https://github.com/qmk/qmk_firmware) offers but on normal keyboards.
This is to allow one to bring your layout around without the keyboard.
You'll just need an USB keyboard and to plug this thing in the middle.
Then maybe perhaps somehow I'll end up arriving to something like Cryham's [KC4](https://github.com/cryham/kc4/)

The layouts are configured in the config folder, to insert in the Teensy before running.
Layer0 defines the keys for the successive layers, the other layers contain the remapped keys.
(e.g. We use INSERT to use Layer 4 and control the display)

I'm using the ILI9341 just like Cryham, mainly for the fast SPI option

# TODOs

+ Display					In progress
+ Keyboard-controlled Display menu		In progress
+ Key Macros
+ Tap/hold keys
+ Mouse Settings
+ Host mount microSD to modify			Possibly not needed, will investigate further 
+ Move to EEPROM, use SD for updates		Almost done

# You probably also need this:

[Teensy pinout](https://www.pjrc.com/teensy/pinout.html#:~:text=Teensy%204.1)

[Ili9341 pinout](https://thesolaruniverse.files.wordpress.com/2021/03/092_figure_04_96_dpi.png)

# Latest changes

- Adding feature for loading from EEPROM, skeleton for future upgrade without MicroSD, still not working though
- Added layer 4 with display keys, starting to build a menu
- Waiting for the EEPROM as well, so that we can save the config file in flash instead, possibly even multiple layouts. Will use the internal one in the meanwhile.
- Need to find a distributor in Europe that presolders Teensy's PSRAM and flash as well, or learn to solder SMD perhaps, if i can get those chips shipped here

# First picture of the thing
![Thing](./images/IMG_0420.jpg)
![Thing2](./images/IMG_0430.jpg)