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
  Road B Left Turn Green
  
![Road_B_Left_Turn_Green](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/f770dacf-5349-4250-8ded-1fbe8d60662e)

--------------------------------------------------------------------------------------------------------------------------------------------------

  Road B Green light and Left Turn yellow
  
![Road_B_Green_Left_Turn_Yellow](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/3871c446-506c-41fd-b28c-c7af502acb9c)

--------------------------------------------------------------------------------------------------------------------------------------------------

 
  Road B All Yellow
  
![Road_B_All_Yellow](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/d100f91b-76d7-4ca5-abf1-4b2a94d62176)

--------------------------------------------------------------------------------------------------------------------------------------------------

 
  All Red
  
![All_Red](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/9c2d3cb3-72c5-4aa3-8616-470fc9f4a010)

--------------------------------------------------------------------------------------------------------------------------------------------------

 
  Road A Left Turn Green
  
![Road_A_Left_Turn_Green](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/663a6895-e3a6-474e-95ca-d7be39c7b851)

--------------------------------------------------------------------------------------------------------------------------------------------------

 
  Road A Green light and Left Turn yellow
  
![Road_A_Green_Left_Turn_Yellow](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/e690320e-ca7f-45eb-a674-4c6689033808)

--------------------------------------------------------------------------------------------------------------------------------------------------

 
  Road B All Yellow
  
![Road_A_All_Yellow](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/a4c3e773-0247-40a2-9314-661d3d8509cc)

--------------------------------------------------------------------------------------------------------------------------------------------------

 
  All Red
  
![All_Red](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/9c2d3cb3-72c5-4aa3-8616-470fc9f4a010)

--------------------------------------------------------------------------------------------------------------------------------------------------


![2-digit 7-segment](https://github.com/CEStafford01/tt06-verilog-template/assets/161381577/5f8f1d9d-d290-4972-ba90-fc7082f8aa02)

Connect a two digit seven-segment PMOD display to outputs 0-7, GND, and 3.3v 

## External hardware

two digit seven-segment PMOD display
