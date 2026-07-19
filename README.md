# Smart-device-management-system
UMaT MINI PROJEC. EL162 (OBJECT ORIENTED PROGRAMMING)


PROJECT OVERVIEW
The UMaT Smart Device Management System is an Object Oriented Programming (OOP) project developed using Python. The system is designed to manage different smart devices by allowing users to monitor and control their operations through a simple menu-driven interface. The project demonstrate important OOP concepts including classes and objects, construtors, inheritance, encapsulation, getters and setters, methods and the use of "super()"

## PROJECT DESCRIPTION
The system consist of a parent class called "SmartDevice" which contains common fatures shared by all devices such as name, device ID and power status. Three child classes inherit from the SmartDevice class:

TemperatureSensor: Reads and displays temperature values.
SmartLight: controls brihtness level and allows brightness to be increased or decreased
SecurityCamera: Controls recording functions and allows recording to start and stop.
The child classes use inheritance and suprer() to initialize attributesfrom the parent class. Sensitive attributes such as device ID and power status are protected using encapsulation and property methods

##FEATURES The system allows users to:

Display device iformation
Turn device ON
Turn device OFF
Read temperature from the temperature sensor
Adjust smart light brightness
Start and stop security camera recording
Exit the program
the program uses loops and conditional statements to provide a menu-driven user interface

OOP concepts Demonstrated
classes and Objects
constructors(init)
Methods
Inheritance
Encapsulation
Getters and setters using '@property'
use of 'super()'
Conditional statements
Loops
User inputs and Outputs
DEVICE IMPLEMENTED
The project creates the following Smart devices:

UMaT Environment's Temperature sensor
All lights on UMaT Main Campus
All UMaT Buildings CCTV Cameras
HOW TO RUN THE PROGRAM
REQUIREMENTS
Python 3 installed on your computer.

STEPS
Clone or download this reprository.
Open the project folder
Run the python file.
The instruction displayed on the menu.
#=====UMaT SMART DEVICE MANAGEMENT SYSTEM======

Display device information
Turn Device ON
Turn Device OFF
Read Temperature
Adjust brightness
Start/Stop Recording
Exit
AUTHOR: NTEBE BLESS GMASAUYAAN (FOE.41.006.121.25) EL1B EL162 OBJECT ORIENTED PROGRAMMING MINI PROJECT GIVEN BY: DR. MATTHEW COBBINAH
