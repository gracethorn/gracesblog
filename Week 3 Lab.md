# Jan 29 Week 3 Lab: Electronic Objects

Lab covers how to use analog outputs to the Arduino Uno R3

## Serial Output

Asynchronus Serial Communication

Open *Serial Monitor* -> electirc plug, Ctrl+Shift+P

## Voltage Divider

![Voltage Divider Image](Images/week%203%20lab%20resistor.jpg)

## Showing Volts Instead

Work out where float line needs to be in code.
Change Serial.println() fuction to print *voltage* rather than the *reading* variable.

**Then**, once that works, these three lines replace the current "println" :

"Serial.print(reading);

Serial.print(",");

Serial.println(voltage);"

- Note: Serial.print() used in first two lines differ than Serial.println() on last line, see how these functions differ

![Float Code](Images/week%203%20lab%20float.jpg)

## Potentiometer

## Controlling the Brightness of sn LED

![LED Breadboard](Images/Week%203%20lab%20LED.jpg)

![Control LED Brightness Code](Images/brightness%20code.jpg)

## Light Sensor

Average (Untampered)- ~70

Low (Shadow)- ~22

High (Flashlight)- ~139

![Light Sensor n Buzzer on Breadboard](Images/week%203%20lab%20buzzer.jpg)

## Thermistor Side Note

Works similar to light sensor, with resistence changing with temperature instead of light.
