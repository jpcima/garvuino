Garvuino Manual
Garvalf
2017-09-13


# Garvuino 

Thank you for your interest in Garvuino! The Garvuino is a PCB board for creating musics, sounds and chiptunes, either through programmation, soundtracker or live recording (midi).

It's open-source hardware, so you can modify, hack, have fun with it without restriction.

## Assembly the board 

If you got the board through a kit, soldering it should be pretty simple as there are only basic components. 

If you have no clue about how to solder, this guide might be of some use for you: https://www.makerspaces.com/how-to-solder/

Solder the resistors and capacitors first for example, then the jumpers, socket, led, switch, crystal and audio jack. In any case, the sd card reader should be soldered after all of this, but it's also adviced to solder the midi DIN5 connecter last, otherwise you might find it difficult to solder the sd card reader.

There is a little error on the version 1.09 / 2017-08 of the PCB board, which I've fixed with a wire.

## Flashing the board 

This board is supposed to work extensively with the Arduino IDE (http://arduino.cc/). You must download it and use it for developping, changing sounds and engines. The only exception is if you only intend to use the board as a AY player, then you can just change the tunes on the SD card.
