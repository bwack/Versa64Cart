
![logo](v1.2&#32;(eagle)/pictures/logo.png)

<p align="center"><img src="v1.2&#32;(eagle)/pictures/DSC_0501-2.JPG" alt="boardimage_v1_2" width="500"/></p>

Versa64Cart is designed to be a modern easy-to-use cartridge development board for Commodore 64 and Commodore 128 hobbyists and hackers. The versatile design of the PCB allows for flexible implementation of various cartridge types. Whether it’s a simple cartridge backup of an 8k game or a switchable multi-program diagnostic cartridge, Versa64Cart has you covered.

Supported EPROMS are: 27C64 (8k), 27C128 (16k), 27C256 (32k), 27C512 (64k).
Please see the documentation for more information.


# Eagle and KiCad design files
I have put the rev 1.1 in a separate folder in case someone wants to use the kicad files as a template.
Rev. 1.2 was designed by Sven Peterson in eagle. It is a complete redrawn schematic and layout.

# changes
## 1.4
- Change: card edge connector with pads like in v1.1

## 1.3
- Change: Cartridge enclosure support
  - Moved IC socket away from edge
  - Moved diode group away from edge
  - Bom: Use right angle pin headers. The straight ones are too tall.
  
## 1.2
- A reset button
- Jumpers accessible on outer edge.*
- Solder jumpers at the top layer
- New documentation
- Designed in Eagle
* Remember to turn off the computer before changing the jumpers.

![boardimages](v1.2&#32;(eagle)/pictures/Versa64Cart_scan_both_sides.jpg)

## 1.1 and 1.0

- Designed in KiCad based on simple64cart eagle files
- Support retro innovation cartridge enclosure (allthough pins too high)
- Moved IC sockets further from edge
- Added 16k game support
- Added dip switch and jumpers
- Added Documentation

# Versa64Cart on YouTube

https://www.youtube.com/results?search_query=Versa64Cart
