# Stepper-Motor-Interfacing-with-8051-Microcontroller

Ports and Pins:

P1 is used to control the motor phases via the ULN2003 driver inputs (IN1 to IN4).
Adjust P1 assignments (#0x01, #0x02, #0x04, #0x08) to activate the respective inputs of the ULN2003 driver to control the stepper motor coils.
Delay Function:

delay_ms macro is used to create a delay loop for controlling the speed of the stepper motor. Adjust the delay duration (10 in this example) based on the desired motor speed and characteristics.
Main Program:

The main program demonstrates moving the stepper motor forward (clockwise) and backward (counter-clockwise) by sequentially activating the motor phases and introducing delays between each phase change.
