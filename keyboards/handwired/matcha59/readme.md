# Matcha59

(Image and description from original [Thingiverse](https://www.thingiverse.com/thing:4850429) page)
![matcha59](https://i.imgur.com/lKmb1yE.jpeg)

A handwired Planck/Preonic alternative with rotary encoder and 4-degree incline!

* Keyboard Maintainer: [robtech21](https://github.com/robtech21)
* Hardware Supported: Any ATMega32U4 Pro Micro

[Handwire Diagram](https://imgur.com/VjmtWK0) from original Keyboard Firmware Builder config

<br></br>
## Building

Make example for this keyboard (after setting up your build environment):

    make handwired/matcha59:default

Or for VIA support:

    
    make handwired/matcha59:via

Flashing example for this keyboard:

    make handwired/matcha59:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available