## Temperature-Monitoring-System-Using-Proteus-NSU-CSE-331-Project
          Contact: kaysarul.apurba@northsouth.edu
### Project Tittle: Temperature Monitoring System Using  with pic microcontroller and lcd
### Project Members:
    1.   Kaysarul Anas Apurba (1811257642)
    2.   Tanvir Sadat (1812796742)

### Contents:
    •	Introduction
    •	Object Overview
    •	Background and Motivation
    •	Methodology
    •	Tools Description
    •	Work Description
    •	PROJECT DIAGRAMS AND PHYSICAL DESIGN
    •   Simulation Results
    •	References

### Introduction:
A temperature controller is a system that monitors and controls the temperature of a room or any other location under consideration, bringing the temperature down if it is greater than necessary. A microcontroller-based automated temperature controller is presented in this study. Discrete components like as clocks, counters, decoder drivers, and thermistor temperature sensors are employed in most temperature controllers and associated systems built before. Some, on the other hand, employed microcontrollers with an external analogue to digital converter. However, these devices took up a lot of space, were heavier, used a lot of power, and were less adaptable, thus changing the system required replacing hardware components

### Project Objective:
The system is built around a PIC18f452 microcontroller, which is connected to an LM35DZ temperature sensor, an LCD, and switching transistors and relays. The hardware and software components of the system design are separated. The temperature of a specific room is sensed by the LM35DZ temperature sensor, which is then sent to the PIC18f452 microcontroller, which decodes it and compares it to a predefined temperature value stored in it. Depending on the outcome of the comparison, the microcontroller switches on/off a heater or a fan. The temperature of the room is displayed on the LCD as it is measured. This design used predetermined temperature settings of 26 degrees Celsius as the lowest and 29 degrees Celsius as the maximum. It's built around the PIC18f452 microcontroller. The temperature of a specific room is sensed by the LM35DZ temperature sensor, which is then sent to the PIC18f452 microcontroller, which decodes it and compares it to a predefined temperature value stored in it. The system switches on the heater when the room temperature is below 26 0C and switches on the fan when the temperature is over 29 0C, with the measured room temperature shown on the LCD correspondingly.

### Methodology:
This chapter explains how the system was developed and built in great detail. There are two primary components to the system. The virtual component of the systems, the circuit diagram, circuit simulation, and creating the PCB layout are discussed in the software development and hardware development sections, respectively. The hardware development is primarily concerned with the physical component. The power supply, temperature sensor, PIC18f452 microcontroller, display, and switching components make up the hardware design. With the aid of the program codes encoded in it, the PIC18f452, as the system's heart, regulates the system's actions in software design. The PIC18f452 source code is written in one of the most common high-level programming languages, especially C. This is owing to the simplicity with which it may be programmed compared to assembly language. The software is then compiled into hex (object code) for the microcontroller to utilize.
### Block Diagram: 
 <img src="images/Circuit_Diagram.png" width="220" height="240" >

### Hardware Requirements:
•	PIC18f452 * 1
•	Potentiometer/Variable
•	LM35- Temperature Sensor
•	LM016 - LCD display
•	+5 power – voltage source
•	ground

### Proteus Design:

 <img src="images/Final_Project.png" width="220" height="240" >

### Code Explanation: 
  <img src="images/Code.png"width="220" height="240" >
  

### References:
1.https://www.youtube.com/watch?v=kqyaRmZ9RMU&t=2s” - Nelson Darwin Pak Tech Channel

