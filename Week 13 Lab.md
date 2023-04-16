# Week 13 Lab (IR Remote % Servos))

*In this lab*...

Experiment with remote and servo and dapt program so remote controls servo

## IR Remote

1. Clone *IRremote_demo repo*
2. Read through & make notes of questions(?)

Challenges:

- get romote, to turn on built-in LED
- power button toggle LED state
- up & down toggle affects LED brightness
- get LED to flash specfic amount? use remote ot change color?

## Servo

Creat Platform IO from scratch (*inatall **Servo library Michael M.***)

Servo > Arduino

- Brown > GND
- Red > SV
- Yellow > D9

Input code and make note of questions, *did it do what you thought?*

Challenges:

- try out (copy & paste) different programs from downloaded Servo library

Warnings:

- if you were to connect more than one servo, you want to use a different power supply to avoid **burn out** on volt regulator
- always remember *if you have multipe power supplies in curcuit, grounds hsould be connected!*

## IR Remote & Servo

Go back to *original cloned repo* & adapt so servo moves to spec. dest. depeding on **remote button**

Challenge:

- get servo to move *1 degree* further when pressing *up and down* buttons
- add ability to press << to 0 & >> to 10 to 180

Makes sense to use *branch here* while experimenting

## Go Over in Class

volitile- this is a veriable that gets invloved in the interrupt

interrupt- fuction triggered when something happens

- ex:"if signal on arduino changes, triggers functions", pin change interrupt
- timer interrupt- every so often gets triggered
- work during delays

asiliscope shows power over time

hex numbers- ex: #102 < decimal, 66 < hex. color numbers RGB are hex numbers

operators: and, or, not (!)

ledState = !ledState; (toggle LED)
