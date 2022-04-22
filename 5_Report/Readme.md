# Report
 
# Introduction 
- Whenever the door is opened, the magnet will move and become separated from the sensor. This will cause a reed switch inside the sensor to activate.

## Research
-   This application is researched from various sources (like you tube , google and research papers ) 

## Features 
- Door sensors are an essential component of your home security system: they let you know when someone is entering your home.


## Detail requirements
## High Level Requirements
| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR001 | Proper knowledge of ATmega328p with Hands on experience with SIMULIDE | Techincal | IMPLEMENTED | 
| HR002 | Proper understanding of components used like resistors , microcontroller etc | Techincal |  IMPLEMENTED  |
| HR003 | open and close door for testing sensor  | Techincal |  IMPLEMENTED  |
| HR004 | System configuration and stability analysis | Techincal |  IMPLEMENTED  |
## Low level Requirements
 
| ID | Description | HLR ID | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
| LR001 | ELECTRICAL NETWORK ANALYSIS AND FEASIBILITY REQUIREMENT | HR001 |  IMPLEMENTED  |
| LR002 | use switch as a door for implementing door sensor| HR002 |  IMPLEMENTED |
| LR003 | Simulation Requirement is must | HR002 | IMPLEMENTED |


# Block diagram

![door sensor block diagram](https://user-images.githubusercontent.com/101561224/164651000-c520b204-7a16-4db6-8b92-9f72ad5e16c7.JPG)




# Flow chart
![flow chart](https://user-images.githubusercontent.com/101561224/164651017-42bff30f-e680-4508-94aa-c69a6cb93df9.JPG)


# Test Plan
## High Level Test Plan

| Test ID| Description | Exp I/P | Exp O/P | Status |
| -------| ----------- | ------- | ------- | ------ |
| H_01 | DEVELOPMENT OF .elf file    | .C file | .elf| Implemented |
| H_02 | Cross Compilation of Files  | Converting .c file into target output | .elf or .hex using win-avr   | Implemented |
| H_03 | Search components in Simulide |  Components  | Assembling     | Implemented  |
| H_04 | Door sensor  |      Run     | led blink    | Implemented |

## Low Level Test Plan

| Test ID| Description | Exp I/P | Exp O/P | Status |
| -------| ----------- | ------- | ------- | ------ |
| L_01 | door close  | switch off | whenever required | Implemented |
| L_02 | door close| switch on | whenever required | Implemented |


# final output
## door close
![door close](https://user-images.githubusercontent.com/101561224/164676470-cf3db7ad-b788-48b4-99c1-8ee0bf4f95c4.png)

## door open
![door open](https://user-images.githubusercontent.com/101561224/164676473-3812ea56-8547-4388-8d59-bcfa193b20de.png)

