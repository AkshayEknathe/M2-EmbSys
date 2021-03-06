# Temperature Controlled Automatic Air Conditioning System
## Block Diagram
![AC](https://user-images.githubusercontent.com/98874290/154834601-2ebe34ab-6871-4ea3-8c00-378879353c37.png)
## Components
# Microcontroller :-
 * The converted binary data from the A/D converter is applied to microcontroller.The microcontroller reads binary data from A/D converter,convert it to suitable form and performs different operations based on the value of temperature read from A/D converter.
# Temperature sensor :- 
* The temperature sensor gives the analog output voltage based on the temperature of the room.
# A/D converter :-
* This analog voltage is fed to the A/D converter.The A/D converter then converts the analog input voltage from the temperature sensor into equivalent binary bits.
# LCD display :
* The LCD is used to display the data given by microcontroller.
# Optocoupler:-
* Microcontroller can turn on dc fan through the optocoupler if required.
# Heater:-
* If the temperature falls very down heater is used.
# HighLevel Requirements
|ID|Description|
|----|---------|
|HLR01|To sense the temperature|
|HLR02|Power Supply|
|HLR03|regulation of fan speed|
# LowLevel Requirements
|ID|Description|
|-----|------|
|LLR01|Provide air according to temperature|
|LLR02|Display the temperature on screen|
|LLR03|It should be able to maintain room temperature|
|LLR04|Should Take input from user|