## Adafruit STEMMA Non-Latching Mini Relay PCB

<a href="http://www.adafruit.com/products/4409"><img src="assets/4409.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit STEMMA Non-Latching Mini Relay. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4409

### Description

STEMMA plug-and-play parts make your next project soldering-free! This is the STEMMA Non-Latching Mini Relay. It gives you power to control, and control over power. Put simply, you can now turn on and off lamps, fans, solenoids, and other small appliances that run on up to 250VAC or DC power using any microcontroller or microcomputer, with ease.

No worrying about flyback diodes, level shifting, pin protection. The STEMMA board takes care of all that for you. You can use it with any 3V or 5V microcontroller/microcomputer.  To use with a breadboard, Raspberry Pi or Arduino, pair with a JST 3-pin to breadboard cable. If you want to use with a Circuit Playground or micro:bit, we have a cable with alligator clips.

* This  board has a single Signal pin (the white wire). Normally, the relay's COM pin is connected mechanically to the NC pin and the NO pin is disconnected.
* When the Signal pin is pulled high, the relay switches and the internal switch changes so that the COM pin is mechanically connected to the NO pin and NC is then disconnected
* When the relay is active, a red LED is lit, and about 50mA of current from the red power wire is used to keep the coil switched on. Note, if power is lost, the relay will go back 'open'.
* The connects for the relay are the white tubular thing at the far end of the PCB. You can poke wire into the holes, they will automatically grip onto wire that is 24AWG to 18AWG. Once you poke the wire in, give it a light pull to verify its clamped. To release the wire, use a thin screwdriver or pen to press on the button on the top while pulling the wire out.

You can switch up to 2A of resistive current at 30VDC or ~40VAC or lower. At 110VDC you can switch up to 0.3A, at 120VAC up to 0.5A, and at 250VAC you can switch up to 0.6A. Check the datasheet for the relay for the exact switching capacity, and of course, for reactive/inductive loads you will need to de-rate. This isn't a relay you can use to turn on and off your washer/dryer, stick to 60W or less.

Each STEMMA board comes with a fully assembled and tested PCB but no cable. No soldering is required to use it. There's an optional second switch on the side of the PCB, if you get a 3-pin terminal block you can solder that in place, but its optional.

Please note: If using with high voltages (> 24V) use care and common sense! High voltages require experience, and are only for use by engineers who are comfortable with guidelines and know how to use safely!
### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
