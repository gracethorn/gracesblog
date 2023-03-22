# March 22 In Class Notes

INPUT LINK OF ROB'S VIDEO

## How to Make a PCB prototype using the Carbide Nomad CnC

**FUSION 360**- *where 3D modeling takes place, professional software*

gerber

each gerber is one layer of your board

ncdrill file places and poits on board here drill bit needs to be

g code language for cnc machines

ncfile

insure units are the same, in millimeters

offset will bring it away from corner
knowing exacly where it is for where you cut

fix: *have zero as offset it will be easier over, ou can choose starting point*

thickness is important so it does cut through too much and so it doesnt barely scratch surface

Copper carbite is flipped/mirrored, and shows the bottom of the board

gerber file is from the top

vbit-  v shaped bit, cuts down to make correct cut width

cuts trouph around circuit
you can increase sixe for more isolation

coppercarbide only had drill bits, cant make slots

board outline

while you can export another gerber, let it create in carbide copper

can save all the gcode filse together as one

or you can save them seperately into a zip file, this always feels safer

WHY NOT TO USE COPPER CARBIDE

weird shaped boards

any slots

lots of diff size hold

cutting in one pass is a little to much for machine or what you are looking for

OTHER PROGRAMS

easy EDA browser

keycad

Circuit board

one side copper

other side fiber glass

design rules check- just makes sure you are not breaking nay rules, too small or things too close together

factory check, make sure they can make it before being sent over

distance between circuit pins *how far pins on sensors, and ho far breadboard pnis are*

2.54 millimeter

.1 inch

## MAKE A CIRCUIT

You can clean and rub surface to roughen texture, get rid of finger prints, solder will want to roll off of it

501 60 degree V

you can make big holes to fit things, but slots will allow things to fit perfectly and cleanly

end mills cut out the board and are on top of the cutter, other most circuit things are in metal drawer cabinet under the cutter

end mills are extrememly sharp and fragile, be aware when tkain gout so it doesnt cut you or fall and break

make sure to close machine

quarter inch before the cutting part

use wrenches, small on top big on bottom, no need to do super tight, just snug

You want it to start inside the material not right on the edge, especially when there is no offset, establish X and Ys

Do not use fast setting near the material

once things are lines up, loosen bit got it to ease down and such the material

Fun Tip: there is a bit of resistence to untighten, this is non purpose to keep it from falling, but you can work with it

when finishes adjusting set everything at zero and run

load new tool to rerecognize the new position

use spindle to test if it is touching, check for dust if it cuts through
