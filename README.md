<img src="images/superfly-front-page.jpg" width=1024>

# Superfly Extruder
### A Compact BMG Conversion

The Superfly is a compact extruder designed to reuse the excellent dual drive gears of the beloved BMG extruder.
As with the BMG, the Superfly is a dual-drive geared extruder with a 3:1 gear ratio. It is designed with the following characteristics in mind:
- compact and light
- short filament path
- balanced center of gravity
- easy to source hardware
- support both NEMA 17 and round NEMA 14 motors
- easy to print

Here are some pictures so that you can get a good idea of what the Superfly looks like:

<img src="images/superfly-nema14.png" width=460><img src="images/superfly-nema17.png" width=460>
<img src="images/perspective/front-left.png" width=460><img src="images/perspective/bottom-right.png" width=460>
<img src="images/printed/front-left.jpg" width=460><img src="images/printed/front-right.jpg" width=460>

The weight of the printed parts for the Superfly comes in at a Flyweight class at less than 11 gram.
The following shows the Superfly printed in PLA+ with 4 walls and plently of infill:
<img src="images/weight/superfly.jpg" width=640>

For reference, the weight of the printed parts is almost exactly the same as the Sherpa Mini with the same slicer settings:
<img src="images/weight/comparison-2.jpg" width=640>

Fully assembled without motors, the Superfly comes in at around 30-31 gram.
<img src="images/weight/with_gears.jpg" width=640>

### Parts
You will need the follwing parts of your BMG:
- the drive shaft with the large plastic gear attached
- the drive gear, this is the gear that is attached to the drive shaft
- the idler gear, its shaft, and the two needle bearings inside, these are the parts attached to the tension arm
- 2 x MR85 bearings that the drive shaft runs on
- Thumbscrew and spring (the washer is optional)
- The motor gear, if you're planning on using a NEMA 17 motor

These parts can be removed without any damage to your BMG, so you can go back to your BMG if you need to later on. If you don't already have a BMG, there are also stores that sell only these internal parts, which should be cheaper than buying a new BMG only to salvage its innards.

In addition to the BMG parts, you will also need the following hardwares:
- an M3 nut for securing the thumbscrew
- 4 x M3 screws for mounting (6mm-12mm depending on your motor and mounting needs).

If you're going to be running a reverse-bowden, you'll also need:
- an embeded bowden collet
- ptfe tubing

For the motor, as mentioned above, both NEMA 17 and the round NEMA 14 motors are supported. A scalable motor spacer is provided (see **Printing the Motor Spacer** below) to help compensate for the differences in your motor's shaft length, so there's a good chance that you might already have a compatible motor on hand.

### Printed Parts
There are only 4 parts that you need to print:
- the **main housing** holds the drive gear assembly and one of the MR85 bearings
- the **back housing** holds the other MR85 bearing and keep the drive gear assembly in the main housing
- the **tensioner** holds the ider gear pressed to the drive gear with the tension from the spring and thumbscrew
- the **motor spacer**, see details below:

#### Printing the Motor Spacer
The motor spacer is an optional part designed to go between the main housing and the motor to allow you to use motors with shaft longer than 15mm. Any longer than 15mm, the shaft can hit the feeding hole where the PTFE tube collet is attached.
<img src="images/assembly/motor_shaft.jpg" width=640>

So, if you're using a motor with 20mm shaft, you will need to scale the provided spacer to the thickness of around 4.5-5mm before printing. Here's how the extruder looks with and without the spacer:

<img src="images/options/nema17_with_spacer.png" width=460><img src="images/options/nema17.png" width=460>

Additionally, some variations of the drive shaft are known to be a bit long and may protrude beyond the back housing:
<img src="images/assembly/gear_shaft.jpg" width=640>

If this is the case for you, then you will need a spacer to make sure that the shaft is not pushing against the motor's body. Finally, if you are using a NEMA 14 motor and you'd prefer to save weight, you can grind away the protruding portion of the drive shaft, this is commonly done on other similar round NEMA 14 based extruder like the Sherpa Mini. Here's how the extruder looks with a round NEMA 14 motor:

<img src="images/options/nema14.png" width=460>

#### Printing Recommendation:
All parts are printable in under 3 hours and should be an easy print for most modern printers. The following are some recommendations to help increase your chance of success:
- The main housing should be printed "face down" as oriented in the STL, the model is designed to minimize supports in this orientation.
- Supports are only needed for the main housing where the two motor mount holes are. Other overhangs and bridges are very printable.
- Raft should be enabled for the main housing unless you're very confident in your bed-adhesion.
- The tensioner should be printed with plenty of walls and infill to make sure that it doesn't break under stress.
- As with most mechanical prints, your printer should be capable of producing parts with decent dimensional accuracy. If you found that your printed parts are too tight, try the "extra_clearance" version of the main housing instead.

#### Post Print:
- Clean up holes with drills
- Check that all parts fit together and sand if necessary.

### Assembly
Assembly is very straight forward. The following images should a good enough guide for you to see how all the parts fits together:
<img src="images/assembly/assembly-1.png" width=1024>
<img src="images/assembly/assembly-2.png" width=1024>

Here is what your main housing should look like before and after assembly:
<img src="images/assembly/housing-empty.png" width=460><img src="images/assembly/housing.png" width=460>

And here is what the tensioner arm should look like once assembled:

<img src="images/assembly/tensioner.png" width=460>

One thing to make sure of during assembly is to make sure that the drive gear line-up correctly with the filament path. This is best done by inserting a piece of filament as guide before tightening the drive gear fully. Once the drive gear is positioned correctly, when there is a filament moving in the slot the idler gear will align itself to match the position of the drive gear. This is also true for all extruders equipped with BMG gears or other similar dual-drive systems.

<img src="images/assembly/line_up_teeth.jpg" width=460><img src="images/assembly/filament_as_guide.jpg" width=460>
