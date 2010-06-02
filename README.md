Freetronics ProtoShieldBasic
==============================
Copyright 2010 Freetronics Pty Ltd  
Freetronics site:  <www.freetronics.com>  
Freetronics email: <info@freetronics.com>  

A minimalist general-purpose prototyping shield for the Arduino
Duemilanove, TwentyTen, and other compatible boards based on the same
header format.

This design is intended to maximise prototyping area by extending the
plain pads right to the ends of the board, which also makes it easier
to fit horizontal PCB-mount sockets that need to overlap the edge.

Note that this design is intended for simple fabrication and assembly,
and does not have many of the features of other prototyping shields
such as the "ProtoShield" (also available from Freetronics) such as
general-purpose LEDs.

Features:

 * Pads for reset button connected to Arduino reset pin.
 * Pads for 100nF smoothing capacitor.
 * Pads for "power on" LED and current-limiting resistor.
 * Parts overlay on both the top and the bottom so you can see what you
   are connecting without having to keep turning the board over.

More information is available on our product page at:

  http://www.freetronics.com/products/protoshieldbasic

The "docs" folder within this repository includes a handy copy of the
schematic in PDF format and image(s) of the pcb.


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to Projects -> eagle -> ProtoShieldBasic.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
