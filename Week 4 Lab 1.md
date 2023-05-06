# Week 4 LCD Display and Sensors Labs

## Lab 1 LCD Display

Learnt o *wire up and use* alphanumeric **LCD display**

- blacklit and displays 2 rows 16 characters each

### LCD INTRO

**VSS**- pin connects to *ground*

**VDD**- pin connects to *+5 power supply*

**VO**- pin *adjusts LCD contrast*

**RS**- *register select* pin controls *LCD memory*

**R/W**- *Read/Write* pin selects *reading/writing mode*

**E**- *enabling* pin, when given low-level energy, *executes LDC relevant instruct

**D0-D7**- pins*read and write*data

**A and K**- pins control*LED backlight*

- LCD need **six Arduino pins**, *all digital outputs*
- **5V** and **GND** connections

DONT FORGET!

- long yellow lead *links* **wiper** of the **pot** to **pin 3*
- **'*POT*'**- controls *contrast* of display 

comments: *had some issues connecting my LCD at first which slowed me down, along with forgetting to push certain code*

## Sensors Lab

Use what you leanred about LCD display and set up from last lab, using Arduino UNO to read temperature using temp/humidity sensor & ultrasonic proximity sensor

- **DHT**- *Digital Temperature and Humidity Sensor*
  
Use code from last lab *as a start*, then *disect and translate* the code to **do what you want**
