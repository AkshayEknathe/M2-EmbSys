# Digital Tachometer
## Block Diagram

![tacometer block diagram](https://user-images.githubusercontent.com/98874290/154829891-219b88f4-3ebd-4bc8-9193-ff388bb3a2ba.png)
## Introduction
* A digital tachometer is a digital device that measures and indicates the speed of a rotating object. A rotating object may be a bike tire, a car tire or a ceiling fan, or any other motor, and so on. A digital tachometer circuit comprises LCD or LED readout and a memory for storage. Digital tachometers are more common these days and they provide numerical readings instead of dials and needles.
* A digital tachometer is an optical encoder that determines the angular velocity of a rotating shaft or motor. Digital tachometers are used in different applications such as automobiles, airplanes, and medical and instrumentation applications.
## Components
# Optical Sensor:- 
* An optical sensor consists of an optical diskplaced near the motor which generate pulses proportional to therotating shaft. A slotted disk and IR emitter are used to generate these pulses.
#  Magnetic sensing: 
* In this type of sensing, there is a possibility to use either Hall Effect sensors or magnetic sensors. Hall Effect principle generates the pulses proportional to the speed of the shaft and magnetic sensors are used to generate pulses by making use of variable reluctance.
# Signal Conditioning: 
* The output signals from the sensors are noisy, and therefore, are filtered, amplified and digitized so that the microcontroller recognizes these signals for further action. 
# Microcontroller:
 * A microcontroller is used to analyze and process the readings from the sensors and it sends the signal to memory.
# Memory Unit  :- 
* Memory stores the data/Reading from the microcontroller to display it on the output screen.
# Display Unit  :-
* Display is used to show the result/output stored in memory .
