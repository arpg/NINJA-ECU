# NINJA-ECU
ECU board in order to control sensors and actuators of ARPG's self driving vehicle
## How board versions work?
each ECU pcb has a version format of **v.**_X_**.**_Y_ in which
* X represents the major change in functionality of the board
* Y represents minor changes like fixing errors in PCB or adding simple functions like an LED

## How to add a new board with major change?
* branch from current master (this should only add some readme files and folders)
* create your project in the folders created from previous step
* when you are ready to push your changes,create a new branch and name it as 'v.major_number' (ex. **v.3** )
* after you are done with your design add a minor tag of 1 to your last commit (ex. add tag **v.3.1**)

## How to add minor changes for last major board?
* apply andd commit your changes when you were done add a minor tag for your commit (ex. add tag **v.3.2**)

## What should every last minor commit include?
* updated pcbproject, schematic and layout files
* updated gerber files
* updated nc-drill files
* updated assembly files
* updated BOM
* updated pdf showing all schematic and layout files
