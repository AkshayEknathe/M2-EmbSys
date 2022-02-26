# Block Diagram
![FINAL BLOCK DIAGRAM](https://user-images.githubusercontent.com/98874290/155833921-381ffa6d-edca-4190-a41b-7a66b7e2fa4a.png)

# Components

## Arduino :-
* Arduino is an open-source electronics platform based on easy-to-use hardware and software.
* Arduino reads the voltage dropped across each pull down resistor for sensing the level of water in the tank.
* Arduino UNO is a low-cost, flexible, and easy-to-use programmable open-source microcontroller board that can be integrated into a variety of electronic projects. This board can be interfaced with other Arduino boards ,and can control relays, LEDs, servos, and motors as an output.
## Voltmeter :-
* A voltmeter is an instrument used for measuring electric potential difference between two points in an electric circuit.
* In this circuit we have connected voltmeter to potentiometer and Ultrasonic sensor.
## Potentiometer :-
* The mechanical system of sensor is destined to convert linearly the value of potentiometer resistance to the water level variation. The signal conditioning consists of analog and digital system especially microcontroller circuit.
## Ultrasonic Sensor (HC-SR01) :-
* To determine the distance to the water, it transmits a sound pulse that reflects from the surface of the water and measures the time it takes for the echo to return. To automatically control open and close the water gate, we use Ultrasonic sensors as input values.
## Servo Motor :-
* The function of the servo motor is to convert the control signal of the controller into the rotational angular displacement or angular velocity of the motor output shaft. Servo motor is used to drive the joints.
## LED :-
* LED is a semiconductor device used in many electronic devices, mostly used for indication purposes. It is used widely as indicator during test for checking the validity of results at different stages.
* When servo motor valve open, the Red LED will glow indicating that there is less water within the tank and when the water level continues to increases and reaches the tank, Green LED will glow.
## Main Switch:-
* A main switch detects the level of a water in a tank. Based on the water level, it will open or close an electrical circuit generally used to pump water in or out of the tank.
* Switch Supply is used to provide voltage to the Arduino, Servo motor, Sensors etc.
# Flowchart
![155781182-971e111a-5194-4b5d-8d29-571d4a0ea278](https://user-images.githubusercontent.com/98874290/155829020-56fb6a18-0aa7-4ca1-bb5b-1f5fcb246d14.png)

