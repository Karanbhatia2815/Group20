# Group20

Aim: To design and implement a motor control system using the TM4C123GH6PM microcontroller, which receives commands via a PuTTY interface and provides real-time feedback on the motor's status. The system aims to demonstrate effective communication between the user and the hardware, enabling control and monitoring of motor operations.


Description of Block Diagram Components:
1.User Interface (PuTTY):
  A terminal program that allows the user to send commands to the microcontroller.
2.TM4C123GH6PM Microcontroller:
  Central control unit that processes incoming commands and controls the motor.
  Contains modules for UART communication and motor control logic.
3.Motor Control Logic:
  Implements functions to start, stop, and change the speed of the motor based on received commands.
4.Feedback Mechanism:
  Gathers real-time information about the motor's status, such as running, stopped, or position (if applicable).
5.Motor Driver:
  Interfaces between the microcontroller and the motor, enabling the control of motor direction and speed.
6.Motor:
  The actual motor being controlled, which performs the physical work.
