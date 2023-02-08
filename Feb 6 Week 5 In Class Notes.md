# Feb 6: Week 5 In-Class

**build clean** -if you were building half way and wanted to stop and start over

**ctrl P** - opens programs

* ex: PlatformIO:Build

## Looking over lab

### Changing Fahrenheit to Celcius

Code:

"*float FTemp = (temperature x 1.8) + 32*"

* will do order of operations but parentheses will help organize

* did it inside if statement right before it prints, final step change units

## New Stuff

### Template Repo

Found repo, create on in your acount and use all files in repo as starting point

### HTMLs

Head and Body section

**p5**, javascript, layer on top of Javascript, so you dont have to use it on its own,

*Javascript* is to **p5**, as *C++* is to **PlatformIO**

**sketch.js** is where the code we write will be

-default file on website *indext.html*

### Relationship Between Files

#### index.html

-> referenceing **style.css** (file info and how you format page)

* content in html, css for style
  
-> **ps.js** (function that we use, ex: circle formula)

-> **sketch.js** (code that we wrote, ex:code to draw circle)

*css* is a way to *format*

#### function setup() vs draw()

*setup*- once when page loads

* if i want them to be used throughout and apply to all following functions
  
*draw*- over and over again, as many times it can, ~60 times a sec

* will only apply to the local functions

variable **mouse x** - mouse position

*let*- allows you to create variable

* ex: let x increase over time (x=x+1)

**Browser Consol** (ctrl+shift+J)

### Hooking Up to Arduino

web **serial.js** needed to do *serial stuff*

bunch of serial functions used to serial stuff in **sketch.js** and **serial.js**

"InData"- *input & organization of data*

"Array"- *variable with a list*

* every program language has concept of array and ability to list
