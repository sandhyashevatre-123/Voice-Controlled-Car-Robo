# Voice-Controlled-Car-Robo
To build a voice-controlled car using an Arduino Uno, you will need a few components:

Arduino Uno: This is the microcontroller board that will serve as the brain of your voice-controlled car.

Motor Driver: You'll need a motor driver module to control the motors of your car. L293D is a commonly used motor driver.

DC Motors: These are the motors that will drive your car's wheels. The number of motors depends on the type of car you want to build.

Bluetooth Module: You'll need a Bluetooth module (e.g., HC-05 or HC-06) to establish a connection between your Arduino and a mobile device for voice commands.

Power Supply: Choose a suitable power supply (such as a battery pack) to power your Arduino and motors.

Chassis and Wheels: Select a chassis that suits your project and attach wheels to it.

Once you have the necessary components, you can follow these general steps to create a voice-controlled car using Arduino Uno:

Connect the motor driver module to your Arduino Uno. Connect the motor terminals to the motor driver outputs.

Connect the Bluetooth module to the Arduino Uno. Typically, you'll need to connect the TX (transmit) and RX (receive) pins of 
the Bluetooth module to the RX and TX pins of the Arduino, respectively. Make sure to cross-connect the TX and RX pins.

Power your Arduino Uno and motor driver with the appropriate power supply.

Write the Arduino code. You'll need to program the Arduino to receive voice commands via Bluetooth and control the motors accordingly. 

You can use the Arduino IDE and libraries such as "SoftwareSerial" for Bluetooth communication.

Pair your mobile device with the Bluetooth module.

Install a Bluetooth terminal app on your mobile device and establish a connection with the Bluetooth module.

Test the voice control functionality.

Send voice commands from your mobile device to the Arduino via the Bluetooth terminal app and observe how the motors respond.
