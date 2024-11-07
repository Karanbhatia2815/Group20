# Group20_Project

Stepper Motor Control with Real Time Data Logging

AIM: 
This project involves controlling a stepper motor using the TM4C123 microcontroller and logging speed and position data in real-time. The data will be stored on an SD card or displayed on an interface, providing insights into the motor's performance.


DESCRIPTION of Block Diagram Components:
1.TM4C123GH6PM Microcontroller:
  Central control unit that processes incoming commands and controls the motor.
  Contains modules for UART communication and motor control logic.
2.Motor Control Logic:
  Implements functions to start, stop, and change the speed of the motor based on received commands.
3.Feedback Mechanism:
  Gathers real-time information about the motor's status, such as running, stopped, or position (if applicable).
4.Motor Driver:
  Interfaces between the microcontroller and the motor, enabling the control of motor direction and speed.
5.Stepper Motor:
  The actual motor being controlled, which performs the physical work.


























