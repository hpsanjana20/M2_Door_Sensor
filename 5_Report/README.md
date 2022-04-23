
# Features
* The system is developed with safety enviroment when switching ‘ON’ or ‘OFF’ the light during the room occupancy or unoccupancy.
* It also comprises manual switching in case user needs to have light during the day.
   
# Highlevel Requirements
|HLR_ID|Description|Status|
|:--:|:--:|:--:|
|HLR_1|This project ensures detection of person entering the room|Implemented|
|HLR_2|This project helps in switching on the light automatically when you enter the room|Implemented|
|HLR_3|This project ensures turning on the bulb off there is enough daylight using manual switch|Implemented|

    
# Lowlevel Requirements
|HLR_ID|LLR_ID|Description|Status|
|:--:|:--:|:--:|:--:|
|HLR_1|LLR_01|The detection is performed using manual switch|Implemented|
|HLR_2|LLR_01|The detection is performed using infrared sensor|Future|
|HLR_3|LLR_01|Power is supplied for turning on/off the bulb|Implemented|

# Architecture

* Block Diagram

![Block Diagram](https://github.com/hpsanjana20/M2_Door_Sensor/blob/main/2_Design/block_diagram.png)

* Flowchart

![Flowchart](https://github.com/hpsanjana20/M2_Door_Sensor/blob/main/2_Design/flowchart.png)

* Schematic Diagram

![Schematic Diagram](https://github.com/hpsanjana20/M2_Door_Sensor/blob/main/2_Design/schematic_diagram.png)

## Overall Working System

|Test_ID|Description|Exp O/P|Actual O/P|Type of Test|
|:--:|:--:|:--:|:--:|:--:|
|TST_1|Person neat the sensor|LED ON|LED ON|Requirements based|
|TST_2|Person not near the sensor|LED OFF|LED OFF|Requirements based|
|TST_3|Switch is on|LED ON|LED OFF|Requirements based|
|TST_4|Switch is off|LED OFF|LED OFF|Requirements based|


# SWOT Analysis
![](https://github.com/hpsanjana20/M2_Door_Sensor/blob/main/6_Output/swot_analysis.png)
