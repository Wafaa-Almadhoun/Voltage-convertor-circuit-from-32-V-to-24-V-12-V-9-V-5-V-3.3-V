# Voltage-convertor-circuit-from-32-V-to-24-V-12-V-9-V-5-V-3.3-V


## Table of contents
* [Introduction](#Introduction)
* [Technologies](#technologies)
* [Components required](#Components-required)
* [Connections](#Connections)
* [Block diagram & simulation ](#Block-diagram-&-simulation)



## Introduction
Stepper motors are an ideal choice for accurately moving and positioning mechanical devices. Using techniques like microstepping the position of the motor shaft can be controlled with a great deal of precision, stepper Motors are used in a wide variety of devices ranging from 3D printers and CNC machines to DVD drives, heating ducts, and even analog clocks , stepper motors are DC motors that rotate in precise increments or “steps”.

  ,We will cover several topics : 👍 


 1. Unipolar Stepper with ULN2003.
 2. Bipolar Stepper with L293D Motor Driver IC.
 3. BIG Stepper Motors NEMA 23 Bipolar with DM860A Microstep Driver . 
  


## Technologies
Project is created with:
* Arduino IDE 1.8.19 [To Downloud](https://www.arduino.cc/en/software)
* Proteus [To Downloud](https://www.labcenter.com/simulation/)
	
## Components required
### 1. Unipolar Stepper with ULN2003 
    1. Arduino UNO
    2. 1 – 28BYJ-48 Unipolar Stepper
    3. jumper wirs
    4. driver board ULN2003
    5. bettrey  5 and 12 volt 
    6. breadboard
    

    
## Connections

### 1. Unipolar Stepper with ULN2003

     connecting ULN2003 pin1 to pin 8 in Ardunio
     connecting ULN2003 pin2 to pin 9 in Ardunio
     connecting ULN2003 pin3 to pin 10 in Ardunio
     connecting ULN2003 pin4 to pin 11 in Ardunio
     connecting ULN2003 pin16 to pin1 in stepper
     connecting ULN2003 pin15 to pin2 in stepper
     connecting ULN2003 pin14 to pin3 in stepper
     connecting ULN2003 pin13 to pin4 in stepper
     connecting ULN2003 pin9 and the 2 2VDD pin in stepper motor to 12v battery 
     Connect ground to ground
     
 
     
## Block diagram & simulation
### 1. Unipolar Stepper with ULN2003 . [see here](https://github.com/Wafaa-Almadhoun/Stepper-motor-using-Arduino-UNO-R3-/blob/main/stepper%20using%20ULN2003.pdsprj)
##### Slow - 4-step CW sequence to observe lights on driver board
![1](https://user-images.githubusercontent.com/64277741/179306291-f9684758-deaf-4828-9520-757a142ba537.PNG)
Figure (1): Stepper Motor at 90 degree after 1-step CW sequence
![2](https://user-images.githubusercontent.com/64277741/179307189-82e1089f-4cbb-403a-b78c-a4c990c24522.PNG)
Figure (2): Stepper Motor at 180 degree after 2-step CW sequence
![3](https://user-images.githubusercontent.com/64277741/179307421-bbcf698d-139f-4d30-aae9-9546c057fb68.PNG)
Figure (3): Stepper Motor at 270 degree after 3-step CW sequence
![4](https://user-images.githubusercontent.com/64277741/179307644-0f9d39bf-591d-45a1-b9c4-d38ec8528d7d.PNG)
Figure (4): Stepper Motor at 342 degree after 4-step CW sequence
##### Rotate CW 1/2 turn slowly
![5](https://user-images.githubusercontent.com/64277741/179308867-85dbccdc-5070-4164-82c7-9776d4b09fc9.PNG)
Figure (5): Rotate CW 1/2 turn slowly
##### Rotate CCW 1/2 turn quickly
![6](https://user-images.githubusercontent.com/64277741/179309329-1eed85e5-3f0d-48a3-b2be-3d9a40e71869.PNG)
Figure (6): Rotate CCW 1/2 turn quickly

