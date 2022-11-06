# 2K+2K Keypad

## Description

A 2K+2K keypad designed for playing osu!mania.
Keypads connected using FPC connector
With switches hot-swappable design.

## Getting Started

### Fourm Post

* [osu!Development (EN)](https://osu.ppy.sh/community/forums/topics/1671536)
* osu!Development (CH)- Not yet post

### What you will need

* Knowlege about PCB and Schematic design
* Some C or C++ programming skill
* Soldering skill
* Buying lots of materials
* Debuggin and debugging

### Making PCB

* PCB files in the "1.Hardware" directory
* I used EasyEDA to design the PCB
* Check the board design more then twice before you send it to manufacture
* Use JLCPCB or any other PCB factory to print the PCB

## Soldering

After you get your PCB manufactured, solder them correctly, remember to clean up the board after soldering it.

## Programming

You should read DataSheet of the IC chip first and know what you are doing before programming it.

In the PCB design file, you should be able to see "CN1" ports on the PCB, that is where you are going to program the IC chip, it connected to serial of the chip.
![alt text](https://i.imgur.com/gKbxRll.png)
Before you start programming, short the "J3", so the chip enters BOOT0 mode.
After you programmed the chip, desolder "J3"
![alt text](https://i.imgur.com/SpQad8V.png)

## Assembling

After you done the above, check you should have these things:
* 4 Cutted pieces of Soldered PCB 
  * Left Bottom
  * Left Top
  * Right Bottom
  * Right Top
* 1 FPC connector
* 8 M2\*8 screw, 8 M2\*4 Coppor Pillars
* 4 Switches

Now Assemble them!

## Done
![alt text](https://i.imgur.com/bT56V7d.jpeg)
![alt text](https://i.imgur.com/mUKZj2P.jpeg)
![alt text](https://i.imgur.com/ahhXuX6.jpeg)

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the [GPL] License - see the LICENSE.md file for details
