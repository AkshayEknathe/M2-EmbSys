# High level Test Plan
|ID|Description of Test case|Input values|Expected Output|Actual Output|Status|	Type of test|
|----|-------|-------|---------|--------|-------|--------|
|HL_T1|When the water level is between 0 -25% |Values By Ultrasonic Sensor|Motor should turn ON|Motor Turned ON|Test Passed|Manual Testing|
|HL_T2|When the water level is between 25%-50% |Values By Ultrasonic Sensor|Motor should turn ON|Motor Turned ON|Test Passed|Manual Testing|
|HL_T3|When the water level is between 50%-75% |Values By Ultrasonic Sensor|Motor should turn ON|Motor Turned ON|Test Passed|Manual Testing|
|HL_T4|When the Tank is Full |Values By Ultrasonic Sensor|Motor should turn OFF|Motor Turned OFF|Test Passed|Manual Testing|
# Low level test plan
|ID|Description of Test case|Input values|Expected Output|Actual Output|Status|	Type of test|
|----|-------|-------|---------|--------|-------|--------|
|LL_T1|When the water level is between 0 -25% |Values By Ultrasonic Sensor|All The Leds Should Glow & Motor should be ON|All 4 LEDs are Glowing & Motor Turned ON|Test Passed|Manual Testing|
|LL_T2|When the water level is between 25%-50% |Values By Ultrasonic Sensor|Green,Yellow & Orange Leds Should Glow & Motor should be ON|Green,Yellow & Orange LEDs are Glowing & Motor Turned ON|Test Passed|Manual Testing|
|LL_T3|When the water level is between 50%-75% |Values By Ultrasonic Sensor|Green & Yellow Leds Should Glow & Motor should be ON|Green & Yellow  LEDs are Glowing & Motor Turned ON|Test Passed|Manual Testing|
|LL_T4|When the Tank is Full |Values By Ultrasonic Sensor|Only Green  Led Should Glow & Motor should be OFF|Green LED is Glowing & Motor Turned OFF|Test Passed|Manual Testing|