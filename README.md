# Voltage-convertor-circuit-from-32-V-to-24-V-12-V-9-V-5-V-3.3-V


## Table of contents
* [Introduction](#Introduction)
* [Technologies](#technologies)
* [Components required](#Components-required)
* [Connections](#Connections)
* [Block diagram & simulation ](#Block-diagram-&-simulation)



## Introduction

 this projects for working with standard power supply 32V , 
 while certain electronic devices, components, IC’s,   sensors ,
 motors or microcontrollers designed to work on 12V , 9V , 5V ,3.3V DC supply
 as a power source.so we will made a circuit supply several voltiges 
 
  


## Technologies
Project is created with:
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

![Screenshot 2022-08-30 061251](https://user-images.githubusercontent.com/64277741/187340677-abcdcf13-0e64-4d81-938a-cb310b58be10.png)
 Figure (1): The circuit diagram and connection 
