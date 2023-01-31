# Jan 29 Week 3 Lab: Electronic Objects

Lab covers how to use analog outputs to the Arduino Uno R3

## Serial Output

Asynchronus Serial Communication

Open *Serial Monitor* -> electirc plug, Ctrl+Shift+P

## Voltage Divider

![Voltage Divider Image](Images/week%203%20lab%20resistor.jpg)

Make sure dividers and wire are in **same verticle row**

GND to (+)

5A to (-)

## Showing Volts Instead

Work out where float line needs to be in code.

Change "Serial.println()" fuction to print *voltage* rather than the *reading* variable.

*Then*, once that works, these three lines replace the current "println" :

**Serial.print(reading);**

**Serial.print(",");**

**Serial.println(voltage);**

- *Note*: **Serial.print()** used in first two lines differ than **Serial.println()** on last line, see how these functions differ

![Float Code](Images/week%203%20lab%20float.jpg)

Issue: *Could not figure out where float code belogned without defining error popping up no matter where i tried, but retried in morning and worked*

## Potentiometer

**Like a resistor** whose **value changes** when you t**urn the knob**

**Value(Ohms):** 10k

Middle leg is called "wiper", serves as VOut (*output voltage of divider*)

Turning the knob causes resistence on one side of wiper to go up and the other to go down.

- VOut will move closer to 5V or 0V depending on which way knob is turned

## Controlling the Brightness of an LED

![LED Breadboard](Images/Week%203%20lab%20LED.jpg)

![Control LED Brightness Code](Images/brightness%20code.jpg)

## Light Sensor

Breadboard

![Light Sensor n Buzzer on Breadboard](Images/week%203%20lab%20buzzer.jpg)

Average (*Untampered*)- **~70**

Low (*Shadow*)- **~22**

High (*Flashlight*)- **~139**

## Thermistor Side Note

Works similar to light sensor, with *resistence changing with temperature* instead of light.
