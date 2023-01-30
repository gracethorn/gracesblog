# Jan 23 In Class Notes

## Coding Topics

### Intro

Low level language- closer to what chip and computer understand (C++)

High level language- easier to understand (arduino)

ASCII number system- ex. A=41

### Storing Data

bit

* either 0 or 1 (binary)

byte

* 8 bits
* [][][][][][][][]
* 8 spots, each spot is 1 or 0
* ex. 01101101
* range is 0-255 (256 possible)

How we store information of any kind

### Variables and Datatypes

* **bool**- true or false
* **byte**- unsigned, no + or -, (0-255)
* char- signed (-127 ... 127)
* **int**- integer, signed word (-32k ... 32k)
* **signed long**- good for storing time (0-4M)
* float- has decimal places, floating numbers (least efficient, try to **avoid & work around floats**, arduino doesnt know and you will need other program)

### Bit Chart

4 - nibble
8 - byte
16 - word (0 ~ 65,000)
32 - long
32 - float
64 - double long

Stay in realm of **8 bits**, same as **micro controller**

-Actual chip does addition, subtraction, multiplication, but **not division** (x .5 rather than divide by 2)

**"cont"**-variable that **doesn't change**

### How To Declare Vlaue

"byte sensorValue=0;"

### Functions

"name()" **parenthesis = function**

-there are functions that just **do** something

* "ind = random();"
* "*store in here* = *run this function* ();"

and

-functions that just **give something back**

* "void" doesn't return anything

-; (semicolon) at end of statement

#### Variety in Functions

-some dont need info, just ()
-some need parameters (#,#) (upper, lower)
-while others optional

#### Scope of Variables

Global

* can access anytime
* often at beggining for reference throughout
* ex. "byte sensorValue = 0"

Local

* only used in function
* within function brakets "{ and }"

#### If, Then, Else Statement

##### AKA Boolean Expression

ex. "if (age > 16)

* age is the variable

Longer Boolean

"if (age > 16 && age < 55)

* "&&" and
* "||" or
* "==" compare

"else {"

(otherwise)

-Also called **"conditional"**

-Be sure to **define functions and variables**
