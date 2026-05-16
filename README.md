# SplitKB Aurora Helix
An ergonomic split keyboard with ortholinear grid layout, using Aurora Helix from ![splitkb.com](https://splitkb.com)


Here are the 3D design files for the keyboard case, including the
- top plates,
- controller covers,
- bottom plates,
- and also molds for casting the bottom plates from epoxy.

There's the complete 3D model in a FreeCAD file, the exported parts in STL files, and also Bambu Studio project files ready to print on a bambu printer.


# Build log
![Picture.](./Pictures/01.jpg)
Arrived.

![Picture.](./Pictures/02.jpg)
Low row cut off. Using Kapton tape to hold the MillMax sockets and components in place.

![Picture.](./Pictures/03.jpg)
Soldered.

![Picture.](./Pictures/04.jpg)
Adding spacers between the plates in order to make a tight stack. Later discarded in order to cut off some height and to use a 3D printed case.

![Picture.](./Pictures/05.jpg)
It's working, yay! But... is it perfect?

![Picture.](./Pictures/06.jpg)
Making it lower. Used pins instead of pin headers on the controller daughterboard. Changed the diodes and resistors to surface-mount versions. Scraped new pads for the I2C pull-up resistors on the bottom side.

![Picture.](./Pictures/07.jpg)
Replace TRRS connector: use 2x2 header pins/sockets with 0.1" spacing (Dupont connectors). Only 3 contacts were required, but in hindsight, using all 4 contacts would have been better (with one corner chamfered). The tolerances turned out to be much better than anticipated. Also didn't have a 3D printer at the time, it would have helped a lot. That's why there isn't any jigs modeled, sorry.

![Picture.](./Pictures/08.jpg)
Soldered the wires.

![Picture.](./Pictures/09.jpg)
Making the pin receptacle. Inserted the pins into the sockets through crepe masking tape and poured some epoxy glue on it. Then filed down to the right shape.

![Picture.](./Pictures/10.jpg)
Shielding with 0.005"/0.127mm copper foil sheet.

![Picture.](./Pictures/11.jpg)
Finished cable with plugs at the ends: bent and glued the shield in place.

![Picture.](./Pictures/12.jpg)
Used the plugs as jigs for the receptacles' shields.

![Picture.](./Pictures/13.jpg)
Used masking tape to ensure enough clearance for the plugs to fit. It was maybe even a bit too much.

![Picture.](./Pictures/14.jpg)
Aligned the connectors.

![Picture.](./Pictures/15.jpg)
Epoxy \<3

![Picture.](./Pictures/16.jpg)

![Picture.](./Pictures/17.jpg)
Time for the extension cable. The connector legs were too small and fragile to be soldered one at a time (one broken connector proved that), so had to try something else.

![Picture.](./Pictures/18.jpg)

![Picture.](./Pictures/19.jpg)
Glued the sides together. This mess turns into beautiful routing.

![Picture.](./Pictures/20.jpg)
The host facing end receptacle connector. The 5.1K pull-down resistors in CC pins advertise max 3A (\@5V) power draw without Power Delivery. D+ and D- lines of opposite sides can be combined when using USB 2.0 speeds.


![Picture.](./Pictures/21.jpg)
Ready to solder to the connectors.

![Picture.](./Pictures/22.jpg)
Used a LOT of flux and solder blobs with a bit too large soldering iron tip, then cleaned everything with IPA.

![Picture.](./Pictures/23.jpg)

![Picture.](./Pictures/24.jpg)
The client end plug connector.
<br>
![Picture.](./Pictures/25.jpg)
The wires ended up being 15mm too long. At least they fit.

![Picture.](./Pictures/26.jpg)
Adding shield. Aluminium foil had too weak connection when just wrapped around and it couldn't be soldered.

![Picture.](./Pictures/27.jpg)
The ground wire is unjacketed and connects to the aluminium foil just enough. The Kapton tape was too thick.

![Picture.](./Pictures/28.jpg)
Growing the blob with epoxy. The link cable connector is about to be shut.

![Picture.](./Pictures/29.jpg)
The connector blob gets its dimensions with trial and error, epoxy and filing. If I ever need to do this again, I will definitely use a 3D printer.

![Picture.](./Pictures/30.jpg)<br>
The blob screwed in place. Kapton tape on the main PCB and on the underside of the controller.

![Picture.](./Pictures/31.jpg)<br>
 Printed the mold and poured epoxy to make the bottom plate. Gosh, PLA was hard to peel off.

The rest of the prints are not that interesting. Almost one spool's worth of calibration, trial and error (my first print project ever). 0.1 ... 0.2mm was a good spacing for nested or facing objects. Ironing was best done in the direction of the layer lines. Always first preview what the printer will actually do.

![Picture.](./Pictures/32.jpg)
First version of the bottom plate. Something caused matt stripes/waves, research is still in progress. To be continued...



