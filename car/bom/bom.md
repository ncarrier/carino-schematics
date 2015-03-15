# Bill of materials

## Description

This documentation lists all the electronic parts used for build the carino car.
For the mechanical parts, please refer to the models project and the relevant
sub-directory.  
Be warned that at the time of writing, no fully functional prototype has been
built, with every function fully tested. So this BOM must be considered as a
draft until the first binary release for the car.  
Prices don't include shipping fees and are only an indication to estimate the
final total. Links to shops are provided for help, and no relation do exist
between the carino project and any of the vendors proposed. The default quantity
for each part is 1.

## List of parts

### pcduino nano 3

* [where to buy][pcduino-store]
* price: 39$

### 5M Pixel CSI Camera for pcDuino3

* [where to buy][pcduino-store]
* price: 15.90$

### a micro SD card

The firmware's size is approximately 80MB, which is much above the minimal size
of the SD cards in the market, so any model should be ok, provided the pcduino
accept it. It is planned to use the remaining free space to store the videos
recorded by the user. Prices can go as low as 4~5€ for a 4GB no name class 10
SD card.

### TRENDnet TEW-624UB

* [where to buy][ldlc-wifi]
* price: 14€90

### Motors

#### Servos - sg90

* quantity: 3
* [where to buy][sg90-store]  
  *no need to buy 10, but I ordered there and was satisfied...*
* 21.10$ for 10

### Various electronic parts

* 45 male header pins:
    * 3x 3 pins male headers \[J1 J2 J3\]
    * 2x 2 pins male headers \[M1 M2\]
    * 1x Arduino shield male headers, that is 1x6, 2x8, 1x10 pins male headers
* 1x micro USB plug, (for the shield's power supply) model TBD [JP1]
* 2x yellow LEDs L-7113YT \[LED3 LED4\]
* 2x red LEDs L-7113ID-12V \[LED1 LED2\]
* 4x 220Ω resistors \[R1 R2 R3 R4\]
* 1x 10kΩ resistor \[R1\]
* 1x LDR-VT90N2 photocell \[R6\]
* 3x 100μF aluminium electrolytic capacitor \[C1 C2 C3\]
* 1x H-brigde L293D \[IC1\]
* 1x BC547 Transistor \[Q1\]
* 1x PKM17EPP-4001-B0 Piezo capsule \[J4\]

Plus wires, heat shrinkable tubes...

## License

    This file is part of the Carino project documentation.
    Copyright (C) 2015
      Nicolas CARRIER <carrier dot nicolas0 at gmail dot com>
    See the file doc/README.md for copying conditions

[ldlc-wifi]:http://www.ldlc.com/fiche/PB00061149.html
[pcduino-store]:http://store.linksprite.com/pcduino3-nano/
[sg90-store]:http://www.ebay.com/itm/Brand-New-10-Pcs-SG90-Micro-Servo-9g-RC-Parts-Fit-RC-Plane-Helicopter-/221387468701?ssPageName=ADME:L:OU:FR:3160
