<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project is a cycling traffic light for a two road intersection with left-hand turn lanes. 
The progam runs through a cycle of phases being; All red, Left turn road B, Road B green and left turn yellow, all road B yellow, All red, Left turn road A, Road A green and left turn yellow, all road A yellow,... and so on, in repeat. 
Where road b is the road running "vertically" through the displasy and road A is the road running "horizontally" through the display.
The signals are represented on a 2 digit display (2 seven-segment displays). 

## How to test

Connect a two digit seven-segment PMOD display to outputs 0-7, GND, and 3.3v 

## External hardware

two digit seven-segment PMOD display
