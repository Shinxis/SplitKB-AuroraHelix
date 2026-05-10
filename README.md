# SplitKB Aurora Helix
An ergonomic split keyboard with ortholinear grid layout, using Aurora Helix from [splitkb.com](https://splitkb.com)<br><br>
Here are the 3D design files for the keyboard case, including the top plates, bottom plates, controller covers, and molds for casting the bottom plates from epoxy.<br>
There's the complete 3D model in a FreeCAD file, the exported parts in STL files, and also Bambu Studio project files ready to print on a bambu printer.<br>
<br>
<br>
# Build log
Arrived.<br>
![Picture.](./Pictures/01.jpg)<br>
Using Kapton tape to hold the MillMax sockets and components in place.<br>
![Picture.](./Pictures/02.jpg)<br>
Soldered.<br>
![Picture.](./Pictures/03.jpg)<br>
Adding spacing between the plates to make a tight stack.<br>
![Picture.](./Pictures/04.jpg)<br>
It's working, yay! But... is it perfect?<br>
![Picture.](./Pictures/05.jpg)<br>
Making it lower by using pins instead of a pin header on the controller daughterboard.<br>
![Picture.](./Pictures/06.jpg)<br>
Replace TRRS connector: use 2x2 header pins/sockets with 0.1" spacing (Dupont connectors). Only 3 contacts were needed, but in hindsight, using all 4 contacts would have been better. The tolerances turned out to be much better than anticipated. Also didn't have a 3D-printer at the time, it would have helped a lot. That's why there's not any jigs modeled, sorry.<br>
![Picture.](./Pictures/07.jpg)<br>
Soldered the wires.<br>
![Picture.](./Pictures/08.jpg)<br>
Making the pin receptacle. Inserted the pins into the sockets through crepe masking tape and poured some epoxy glue on top. Then filed down to the right shape.<br>
![Picture.](./Pictures/09.jpg)<br>
Shielding from 0.005"/0.127mm copper foil sheet.<br>
![Picture.](./Pictures/10.jpg)<br>
Finished cable with plugs at the ends: bent and glued the shielding in place.<br>
![Picture.](./Pictures/11.jpg)<br>
Used the plugs as jigs for the receptacle shieldings.<br>
![Picture.](./Pictures/12.jpg)<br>
Used masking tape to ensure enough clearance for the plugs to fit. It was maybe even a bit too much.<br>
![Picture.](./Pictures/13.jpg)<br>
Aligned the connectors.<br>
![Picture.](./Pictures/14.jpg)<br>
Epoxy \<3<br>
![Picture.](./Pictures/15.jpg)<br>
![Picture.](./Pictures/16.jpg)<br>
Time for the extension cable. The connector legs were too small and fragile to be soldered one at a time (one broken connector proved that), so had to try something else.<br>
![Picture.](./Pictures/17.jpg)<br>
![Picture.](./Pictures/18.jpg)<br>
Glued the sides together. This mess turns into beautiful routing.<br>
![Picture.](./Pictures/19.jpg)<br>
The host facing end receptacle connector. The 5.1K pull-down resistors in CC pins advertise max 3A (\@5V) power draw without Power Delivery. D+ and D- lines of opposite sides can be combined when using USB 2.0 speeds.<br>
![Picture.](./Pictures/20.jpg)<br>
Ready to solder to the connectors.<br>
![Picture.](./Pictures/21.jpg)<br>
Used a lot of flux and solder blobs with a bit too large soldering iron tip, then cleaned everything with IPA.
![Picture.](./Pictures/22.jpg)<br>
![Picture.](./Pictures/23.jpg)<br>
The client end plug connector.<br>
![Picture.](./Pictures/24.jpg)<br>
![Picture.](./Pictures/25.jpg)<br>
Adding shielding. Aluminium foil had too weak connection when just wrapped around and it couldn't be soldered.<br>
![Picture.](./Pictures/26.jpg)<br>
The ground wire is unshielded and connects to the aluminium foil just enough. The Kapton tape was too thick.
![Picture.](./Pictures/27.jpg)<br>
Growing the blob with epoxy. The link cable connector is about to be shut.<br>
![Picture.](./Pictures/28.jpg)<br>
The connector blob get its dimensions with trial and error, epoxy and filing. If I ever need to do this again, I will definitely use a 3D-printer.<br>
![Picture.](./Pictures/29.jpg)<br>
The blob screwed in place. Kapton tape on the main PCB and on the underside of the controller.<br>
![Picture.](./Pictures/30.jpg)<br>
Printed the mold and poured epoxy to make the bottom plate. Gosh, PLA was hard to peel off.<br>
![Picture.](./Pictures/31.jpg)<br>
First version of the bottom plate. Something caused matt stripes/waves, likely residue from dishwashing detergent. To be continued...<br>
![Picture.](./Pictures/32.jpg)<br>


