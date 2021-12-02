# Introduction
   The blink program uses the LED (light-emitting diode) built into Maker Board to flash on and off.Blinking a LED with a delay. Atmega32 is a very popular high performance 8 bit AVR Microcontroller.There are several ways of making a blinking LED circuit. Using relays, transistors, orcomponents like an inverter, a 555 Timer or a microcontroller.

# Objective
   The main objective is to blink the led using ATmega328 and a switch to controll two LED's.
   
# Features
   It has simple features.
       
    1.It can switch off the LED's when switch is in off state.
    2.It can switch on the LED's when switch is in on state.
    
    # 4W's and 1 H's
   ## Why
    1.To blink two LED's using a switch using ATmega328.
    
   ## When
    1.In schools and colleges it can be implemented in mini projects.
    
   ## Where
    1.LED blinking circuit can be used as vehicle indicator.
    
   ## Who
    1.It can be used by all who knows the basics of embedded.
    
   ## How
    1.By loading the program in ATmega328.
    2..By using softwares
    
   # SWOT Analysis
    
   ## Strengths
    1.Cost effective.
    2.simplw
    
   ## Weakness
    1.Basic program.
    
   ## Opportunities
    1.By adding more components we can make the Program more complex.
    
   ## Threats
    1.There are advanced programs which are simple to learn is out already.
    
# High Level Requirements
| Id    	| Description     	| Status      	|
|-------	|-----------------	|-------------	|
| HLR_1 	| Microcontroller 	| Implemented 	|
| HlR_2 	| Swtich          	| Implemented 	|
| HLR_3 	| Two LED         	| Implemented 	|
| HLR_4 	| Software        	| Implemented 	|

# Low Level Requirements
| Id    	| Description              	| Status      	|
|-------	|--------------------------	|-------------	|
| LLR_1 	| ATmega328                	| Implemented 	|
| LLR_2 	| Swtich                   	| Implemented 	|
| LLR_3 	| Two LED                  	| Implemented 	|
| LLR_4 	| Visual studio & SimulIDE 	| Implemented 	|

## Behavior Diagram
![led diagram](https://user-images.githubusercontent.com/94593380/144365190-76d6a75a-51a4-4a40-847f-9524214d2ff9.jpg)

## Structural Diagram
![new led](https://user-images.githubusercontent.com/94593380/144365319-57aea20f-ec65-4a58-8dee-66065f649d5c.jpg)

## Block Diagram
![new led (2)](https://user-images.githubusercontent.com/94593380/144367291-f8aca814-e73a-44d1-9df0-c49f7c53807c.jpg)

## Simulation
![led switch off](https://user-images.githubusercontent.com/94593380/144378910-61bc68ec-02ab-4931-b12d-ebf28b4608ec.JPG)


# Implementation
# Folder Structure
| Folder   |      Description     |
|----------|:-------------:|
| document | Doxygen documentation |
| inc | All header files |
| simulation | simulation files |
| src | Main source code for Led Blinking |

# Test Plan
# High Level Requirement
| Id    	| Description 	| Expected I/P 	| Expected O/P 	| Actual O/P 	| Type Of Test 	|
|-------	|-------------	|--------------	|--------------	|:----------:	|--------------	|
| HLR_1 	| Switch on   	| High power   	| LED On       	| LED On     	| Rquirement   	|
| HLR_2 	| Switch Off  	| No power     	| LED Off      	| LED Off    	| Requirement  	|
# Low Level Requirement
| Id    	| Description 	| Expected I/P 	| Expected O/P 	| Actual O/P 	| Type Of Test 	|
|-------	|-------------	|--------------	|--------------	|:----------:	|--------------	|
| LLR_1 	| Switch on   	| value 1      	| LED On       	| LED On     	| Rquirement   	|
| LLR_2 	| Switch Off  	| value 0      	| LED Off      	| LED Off    	| Requirement  	|

# switch is off
![led switch off](https://user-images.githubusercontent.com/94593380/144379048-62fa4b7e-5722-44ab-b5d0-c097eed97d9b.JPG)

# switch is on
![Led switch on](https://user-images.githubusercontent.com/94593380/144379099-8bac7d08-0dd9-43c7-8354-f10a931d9aa2.JPG)


