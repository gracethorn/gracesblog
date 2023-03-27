# March 22 In Class Notes

INPUT LINK OF ROB'S VIDEO

## How to Make a PCB prototype using the Carbide Nomad CnC

**FUSION 360**- *where 3D modeling takes place, professional software*

### Gerber

each **Gerber** is *one layer* of your board

**NC drill file** places and poits on board *where drill bit needs to be*

**G code** *language* for **CNC machines*

### NC file

insure **units are the same**, *in millimeters*

**Offset** will bring it away from corner

- knowing exacly where it is for where you cut

FIX: *have zero as offset it will be easier over, ou can choose starting point*

**Thickness is important** so it *doesn't cut through too much* and so it *doesn't barely scratch surface*

Copper Carbite

- flipped/mirrored
- shows the bottom of the board

Gerber file

- view from the top of board

V bit-  v shaped bit, cuts down to make correct cut width

Cuts *trouph around circuit*

you can *increase size for more isolation*

Copper Carbide **only has drill bits**, **can't make slots**

LAYERS

- holes
- paths
- board outline

SAVE & EXPORT

While you can export another Gerber, let it create in Carbide Copper

- can save all the G code filse together as one

- or you can save them seperately into a zip file (this always feels safer)

WHY NOT TO USE COPPER CARBIDE

- weird shaped boards

- any slots

- lots of diff size hold

- cutting in one pass is a little to much for machine or what you are looking for

OTHER PROGRAMS

- easy EDA browser

- keycad (notibaly good)

Circuit board form: one side copper, other side fiber glass

*design rules check*- just makes sure you are not breaking any rules, anything too small or things too close together

*factory check* make sure they **can** make it before being sent over

Distance between circuit pins *how far pins on sensors, and ho far breadboard pnis are*

- 2.54 millimeter

- .1 inch

## MAKE A CIRCUIT

**Clean and rub surface** to *roughen texture*, get rid of *finger prints*, *solder will want to roll off of it*

501 60 degree V

You **can** make *big holes* to fit things, but **slots** will allow things to *fit perfectly and cleanly*

WHERE THINGS ARE: **end mills** (cut out the board) and are on *top of the cutter*, most **other circuit things* are in *metal drawer cabinet under cutter*

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

BIG PROBLEM *the spindle did not turn on while cutting and did not cut into the materil, reason to not trust Copper Carbine* might just use other program Rob knows

EDA PRogram we **will** use : *http/mods.eda.mit.edu/*

EXTRA NOTES:

Needs something big to happen? IoT Power Relay, control standard outlet devices with a microcontroller

Valclav Jira Kenetic Sculptures

** Sensor Kat used RFID reader
