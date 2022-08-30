# Voltage-convertor-circuit-from-32-V-to-24-V-12-V-9-V-5-V-3.3-V


## Table of contents
* [Introduction](#Introduction)
* [Technologies](#technologies)
* [Components required](#Components-required)
* [Connections](#Connections)
* [Block diagram & simulation ](#Block-diagram-&-simulation)



## Introduction
 this circuit 
  


## Technologies
Project is created with:
* Arduino IDE 1.8.19 [To Downloud](https://www.arduino.cc/en/software)
* Proteus [To Downloud](https://www.labcenter.com/simulation/)
	
## Components required

    1. 1X 10uF capacitor
    2. 1X 22uF capacitor
    3. 1X IC LM1117T- 3.3v 
    4. 4X 330nF capacitor 
    5. 4X 100nF capacitor 
    6. Battery 32 V
    7. 1X LM7824CT , LM7812CT, LM7809CT and LM7805CT
    
    
    

    
## Connections

### 1. Unipolar Stepper with ULN2003

     connecting LM7824CT  pinINPUT to 32 V battery  and 330nF  capacitor then all conecteing with GND
     , pin GND to GND and pinOUTPUT to 100nF capacitor then to GND .
     
     connecting  LM7812CT pinINPUT to 24 V output and 330nF  capacitor then all conecteing with GND
     , pin GND to GND and pinOUTPUT to 100nF capacitor then to GND .
 
     connecting  LM7809CT pinINPUT to 12 V output and 330nF  capacitor then all conecteing with GND
     , pin GND to GND and pinOUTPUT to 100nF capacitor then to GND .
     
     connecting LM7805CT pinINPUT to 9 V output and 330nF  capacitor then all conecteing with GND
     , pin GND to GND and pinOUTPUT to 100nF capacitor then to GND .
     
     connecting IC LM1117T- 3.3v  pinINPUT to 5 V output and 10uF  capacitor then all conecteing with GND
     , pin GND to GND and pinOUTPUT to 22uF capacitor then to GND .
     
     
     
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

