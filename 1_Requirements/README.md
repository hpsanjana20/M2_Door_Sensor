# Description
* Door sensor for automatic lighting control is widely being developed for energy saving and security purposes. 

# Requirements
* Visual Studio Code, AVR compiler, SimulIDE, Make Installer, Doxygen, Linux OS, Windows OS

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


# SWOT Analysis
![](https://github.com/hpsanjana20/M2_Door_Sensor/blob/main/6_Output/swot_analysis.png)

# 4W's & 1H
* **What**  : Door sensor using the microcontroller Atmega328p.
* **When**  : When there is a need to automatically on and off the light accpording to it's usage. 
* **Where** : It can be incorporated in home, restroom and business spaces.
* **Why**   : It is needed to control the energy conservation in order to save energy and reduce the utility cost.  
* **How**   : By developing an embedded system using IR sensor with Atmega328p being the microcontroller.



