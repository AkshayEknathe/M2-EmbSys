# Smart Water Level Controller Using Arduino
## Introduction : -
* Automation of smart system is the essence of today's world. the “Smart Water Level Controller Using Arduino ”, can be an appropriate example for the smart system. In the recent times due to to the huge scarcity of water resources frequent droughts have been occurring, due to which the various initiatives have been undertaken, out of which one is the system that will serve to save the water that is being wasted in the households, agriculture's and in different industries . some of the hazardous incidents such as the boiler bursts due to the lowering of the water level also can be avoided, which is also controlled by using this smart system.
* Smart water level controller senses the level of water in a tank and drives the water pump. Water level controllers switch the motor ON whenever the water level drops below a certain level and shuts the motor OFF when the water rises well above a fixed level. This circuit which will detect the water level and will Glow the Unique led colours to show the water level in the Tank
## High Level Requirements
|ID|Description|
|----|------|
|HLR01|Ultrasonic Sensor should sense the level of water|
|HLR02|LED should glow|
|HLR03|Turn off the motor when water tank is Full|
|HLR04|Turn on the motor when water tank is empty|
## Low Level Requirements
|ID|Description|
|----|------|
|LLR01|All the LEDs should glow  when Water Level iS between 0-25%|
|LLR02|Green,Yellow & Orange  LEDs should glow  when Water Level iS between 25%-50%|
|LLR03|Green & Yellow LEDs should glow  when Water Level iS between 50%-75%|
|LLR04|Green LED should glow  when Water Level is between 75%-100%|
# SWOT

![SWOT](https://user-images.githubusercontent.com/98874290/157167000-0058b0ac-7342-43f8-a892-952d3dd361d3.png)

## Strength
* Very easy to use.
* Quick installtion.
* Less maintaince.
* Highly reliable and Economically competitive.
* Enhanced Security of Urban Water supply and Water use efficiency.
## Weakness
* Lack of graphical user interface.
* If the Ardunio gets reset the system will not work.
* System is very sensitive we have to handle it with care.
* The automatic water level controller shows poor durability.
## Opportunity
* Since now a days water usage is increasing so much it is very important to save the water so this kind of systems are required.
* Maximize Water supply Benefits and provide balanced allocation of water resources.
## Threats
* Fault in the circuit will cause problem in water supply.
* More advance technology is there to overcome this issue.
# 4W'S & 1H
## WHY
* A water level controller helps save money by limiting the waste of water and electricity.
## WHO
* Everyone can use this device as for their commercial aur domestic use.
## WHEN
* Whenerver the tank level gets low/high it starts and stops according to the requirements.
## WHAT
* Results into less manual work which saves human time and energy.
## HOW
* By setting these devices as per the requiement so as to save the loss of water and and save the motor from dry run and manual work load.
## Applications
* It can be widely used for the household purposes to avoid the wastage of water through the water tanks.
* It can be widely used in chemical industries to manage the liquid filled in the big tanks.
* It can be used in nuclear power plants as the water controlling systems is essential.
* It can be also used in the thermal power plants .
* It also finds a wide applications in the oil refineries industries.
* It can be used in dairy farms.
* It can be also used in water purification plant.



# Block Diagram
![blockDiagram](https://user-images.githubusercontent.com/98874290/157085630-ef93102e-df00-4e71-9220-ce289b208393.png)

# Components

## Arduino :-
* Arduino is an open-source electronics platform based on easy-to-use hardware and software.
* Arduino reads the voltage dropped across each pull down resistor for sensing the level of water in the tank.
* Arduino UNO is a low-cost, flexible, and easy-to-use programmable open-source microcontroller board that can be integrated into a variety of electronic projects. This board can be interfaced with other Arduino boards ,and can control relays, LEDs, servos, and motors as an output.
## Ultrasonic Sensor (HC-SR01) :-
* To determine the distance to the water, it transmits a sound pulse that reflects from the surface of the water and measures the time it takes for the echo to return. To automatically control open and close the water gate, we use Ultrasonic sensors as input values.
## Servo Motor/Water pump(Actuator) :-
* Pump is a mechanical device which converts the mechanical energy into the pressure energy. It creates the partial vacuum in the suction side and sucks the liquid which is delivered with high pressure at a required height.
## LED :-
* LED is a semiconductor device used in many electronic devices, mostly used for indication purposes. It is used widely as indicator during test for checking the validity of results at different stages.
## Power Supply:-
*  It suppy power to all the components in the system.This is one of the most important part of the System.
## Potentiometer :-
* The mechanical system of sensor is destined to convert linearly the value of potentiometer resistance to the water level variation. The signal conditioning consists of analog and digital system especially microcontroller circuit.

# Flowchart
![155781182-971e111a-5194-4b5d-8d29-571d4a0ea278](https://user-images.githubusercontent.com/98874290/155829020-56fb6a18-0aa7-4ca1-bb5b-1f5fcb246d14.png)






# High level Test Plan
|ID|Description of Test case|Input values|Expected Output|Actual Output|Status|	Type of test|
|----|-------|-------|---------|--------|-------|--------|
|T1|When the water level is between 0 -25% |Values By Ultrasonic Sensor|Motor should turn ON|Motor Turned ON|Test Passed|Manual Testing|
|T2|When the water level is between 25%-50% |Values By Ultrasonic Sensor|Motor should turn ON|Motor Turned ON|Test Passed|Manual Testing|
|T3|When the water level is between 50%-75% |Values By Ultrasonic Sensor|Motor should turn ON|Motor Turned ON|Test Passed|Manual Testing|
|T4|When the water level is between 75%-99% |Values By Ultrasonic Sensor|Motor should turn ON|Motor Turned ON|Test Passed|Manual Testing|
|T5|When the Tank is Full |Values By Ultrasonic Sensor|Motor should turn OFF|Motor Turned OFF|Test Passed|Manual Testing|
# Low level test plan
|ID|Description of Test case|Input values|Expected Output|Actual Output|Status|	Type of test|
|----|-------|-------|---------|--------|-------|--------|
|T1|When the water level is between 0 -25% |Values By Ultrasonic Sensor|All The Leds Should Glow & Motor should be ON|All 4 LEDs are Glowing & Motor Turned ON|Test Passed|Manual Testing|
|T2|When the water level is between 25%-50% |Values By Ultrasonic Sensor|Green,Yellow & Orange Leds Should Glow & Motor should be ON|Green,Yellow & Orange LEDs are Glowing & Motor Turned ON|Test Passed|Manual Testing|
|T3|When the water level is between 50%-75% |Values By Ultrasonic Sensor|Green & Yellow Leds Should Glow & Motor should be ON|Green & Yellow  LEDs are Glowing & Motor Turned ON|Test Passed|Manual Testing|
|T4|When the Tank is Full |Values By Ultrasonic Sensor|Only Green  Led Should Glow & Motor should be OFF|Green LED is Glowing & Motor Turned OFF|Test Passed|Manual Testing|








## When tank is 0-25% Filled
![Tank is 25% filled](https://user-images.githubusercontent.com/98874290/157168515-0fa2a946-cc97-41d6-921d-3d67718830b5.png)
## When tank is 25%-50% Filled
![Tank is 50% Filled](https://user-images.githubusercontent.com/98874290/157168537-ab8909d5-f95b-443b-ae2c-035a1021d846.png)
## When tank is 50-75% Filled
![Tank is 75% filled](https://user-images.githubusercontent.com/98874290/157168541-d50509f9-1191-40a9-8a08-0dd00a2d6d14.png)
## When tank is Full
![Tank Is Full](https://user-images.githubusercontent.com/98874290/157168558-551ef979-a05a-43ce-bc3e-9ce3c8097546.png)

