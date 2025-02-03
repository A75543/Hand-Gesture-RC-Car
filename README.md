# Hand-Gesture-RC-Car
This project is a DIY hand gesture-controlled RC car using Arduino. The car is controlled via an accelerometer-based transmitter, sending signals wirelessly using an NRF24L01+ module to a receiver on the car. The receiver interprets the signals and moves the car accordingly.

Features:
- Wireless control using NRF24L01+
- Hand gestures detected using MPU6050 accelerometer
- Four-directional movement (Forward, Backward, Left, Right)
- Secret mode for special functions
- Low-cost implementation using scavenged parts
- Components Used

Hardware:
- Arduino Uno R3 (ATmega328P) - Receiver
- Arduino Nano (ATmega328P) - Transmitter
- MPU6050 Accelerometer
- NRF24L01+ 2.4GHz Wireless Modules
- L298N Motor Driver
- Robot Smart Car Chassis
- 18650 Battery and Holder
- Wires, Buttons, LEDs, and Resistors

Software:
- Arduino IDE
- C++ for programming the microcontrollers
- nRF24L01 and Wire libraries for communication
