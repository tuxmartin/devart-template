# Hardware control

Control of desks with LED diodes will be directed through Arduino and Raspberry Pi (RPi). As operation system in RPi will be used Raspbian Linux. Control software in RPi will accept data, input by user and calculate necessary lighting up of LED diodes and rotation speed of desks. RPi is not suitable for control in real time, therefore it will send instructions via RS-232 into Arduino, which will perform the very lighting up/switching off the LED diodes and control rotation speed of the desks in real time.

User will input data using Google Drawings. Thanks to automatic saving of the draft during user’s inactivity, RPi will periodically download the newest version of the draft via Google Disk API and calculate the set up for desks and LED from the newest version.

![Example Image](../project_images/ArduinoUno_R3_Front.jpg?raw=true "Example Image")

![Example Image](../project_images/Raspberry_Pi.jpg?raw=true "Example Image")

