# automatic-door-locking-system
working of door locking system - 
  . we will use a microprocessor/microcontroller to sense the person leaving the room.
  . The output of the Microprocessor/microcontroller will be the input for the control circuit in Servo motor.
  . The motor will close the door with precision.
  
MICROPROCESSOR - A microprocessor is a computer processor that incorporates the functions of a central processing unit (CPU) onto just a few (and often only one) integrated circuits. 
MICROCONTROLLER - A microcontroller is a small computer on a single integrated circuit chip. A microcontroller typically contains one or more processor cores, along with additional peripherals (memory, serial interface, timer, programmable I/O peripherals, etc.) on the same chip.

We have several types of micro controllers
PIC Microcontroller
ARM Microcontroller
8051 Microcontroller
AVR Microcontroller
MSP Microcontroller


Arduino Uno is a microcontroller board based on the ATmega328P (datasheet). It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz ceramic resonator (CSTCE16M0V53-R0), a USB connection, a power jack, an ICSP header and a reset button.

Here' for the door locking system we will be using PIR Sensor with ARM microcontroller.
the PIR sensor senses the infrared rays from the nearby objects and sends a signal to the microcontroller. This ARM microcontroller will give a pulse to the control circuit of the SERVO motor thos pulse will act as the input to the motor.
PIR sensors can be used with Arduino and other microcontroller boards.

""SERVO MOTOR""
This motor is used in precise position control commonly found in industrial and commercial appliances
The Servo motor setup involves:-
 .control circuit
 .Shaft amplifier
 .Encoder or a Resolver
 .Servo motor(Ac/Dc)
 
 output Shaft - this can be moved in a perticular dangle , position ,  velocity this cant be done in the regular motor 
 control circut - the main brain of the motor , the pulse signals are transferred from here to the dc part of the motor which rotates the gear.
 Encoder - this provides speed and position feedback 
 
 In this , the motor is controlled with an electric signal it may be analog or digital which deteremines the movement which represent final position of shaft.
 we will be use DC Servo motor with brushed using commutator 
 
 we will give the nessesary codes in the microcontroller and the the control circuit of the motor for the precision and the accuracy in locking 
 

  
