# Example-Code-Architecture

This contains code for Prosthesis v1 firmware as of 01/29/2025. The flow of code is main.c performs definitions and initializations, the main loop calls the device library (prosthesis_v1.c), and the device library calls the sensor/actuator drivers. A state machine exists inside of the device library (prosthesis_v1.c).
