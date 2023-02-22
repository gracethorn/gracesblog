# Week 5 Lab 1 Sensor Changes

## Reading the Joystick Potentiometers

CREATE PIO FILE & INPUT CODE FROM LAB

**Lab Question:** "Try to guess what the results will be before you upload?"

**Answer:** *I am not too sure of the range but I can assume that when the joystick is stationary it will be in the middle of the range and depending on direction the number will shift closer towards x or y accordingly.*

![Reading the Joystick Code](/images/Joystick%20code%201.jpg)

### Observations of Joystick Output

**Stationary:** (513,511)

**Up:** (513,0)

**Down:** (513,1023)

**Left:**(0,513)

**Right:** (1023,513)

**When Joystick is pushed:** nothing, numbers just chake from slight movement

**Range:** 0-1023 since Arduino has a *10-bit Analog-to-Digital Converter (ADC)*

**Thoughts:** *While I didnt quite know what to expect, I was very interested to see the relationship between x and y depending on the direction the joystick is pushed. I can visualize it the axises of the numbers correlating to the physical joystick much more clearly. Left and up being the lowest at 0 and right and down having hte highest value of 1023.*

**Lab Question:** if the x and y values arent identicalwhen joystick is at rest, can you guess why?

**Answer/Guess*:***since 1023 is not evently divisible by 2 and Arduino does not like decimals, also the sensor is not perfect and im sure under and over compensates doing the best it can, is anything truly balances and equal?*

## Reading the Switch

**Pullup Resistor** *INPUT_PULLUP*

Code Used: *pinMode (switchPin, INPUT_PULLUP);*

Without Pullup Resistor:

* Switch connected directly to ground and arduino
* when button is pressed Arduino will read as LOW (0 Volts)
* when button isnt pressed it is unclear & inconsistent, neither connected to ground (LOW) or 5V (HIGH)
* the pin is "floating"

With Pullup Resistor:

* when button isnt pressed pin will read HIGH

Note: *Microcontroller chip includes internal pullup to avoid this common enough issue*

ADD SWITCH/PUSHBUTTON TO LIST OF VALUES DISPLAYED

![Push Button Code](/images/joystick%20code%202.jpg)

### Code Observations: Switch/push button value is binary, 0 (LOW) or 1 (HIGH)

## Responding to Chnages in the State of a Sensor

CHANGE PROGRAM SO MESSAGE IS SENT WHEN THERE IS CHANGE IN VALUE

(*Rather than a nonstop stream*)

Two Ways:

* Digital input of push button
* Analogue joystick axis inputs

### Button Changes

![Button Chnages Code](/images/joystick%203.jpg)

New code should send message *only when button state changes*

**Lab Question:** Do you get multiple messages even though you push the button once? Why do you think that is?

**Answer:** Two messages per button push, one for the push and another for the release, both are *changes* in the sensor

**ISSUE** *I am stuck on how exaclty I would change to code to only send mesage when state goes from HIGH to LOW, what exacly does ! mean again*

### Analogue Input Threshold

SEND MESSAFE THE MOMENT ANALOGUE INPUT PASSES CERTAIN THRESHOLD

Can be useful w **light or temperature sensor**, we will try with *joystick x-axis*

![Alt text](../images/joystick%20code%204%20success.jpg)

**Observations:** *Holding the joy stick in the direction does not cause continuous flow of messages, when moving it rapidly it must be moves back towards middle, below value of 800 (chosen threshold) slight changes are not enough, I an=m sure a larger threshold would allow*
