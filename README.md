# MAZE/OBSTACLE ROBO
A maze/obstacle navigation robot using infrared sensors


**PROJECT OVERVIEW**

This project uses an ESP-32 and infrared sensors on a custom-made chassis to navigate mazes or obstacles.

**HARDWARE USED**
- ESP-32
- 3 INFRARED SENSORS
- 2 TT MOTORS
- 1 L9110 MOTOR DRIVER
- 2 18650 Li RECHARGEABLE BATTERIES
- 1 LM2596 Dc to Dc Buck Converter (FOR THE BELOW BUCK CONVERTER) 
- 1 5V to 3.3 V Buck converter (FOR THE ESP32)

**SOFTWARE USED**
- ARDUINO IDE
- CHATGPT

**ARCHITECTURE**

**CIRCUIT DIAGRAM**

**PICTURES**

<img width="542" height="1204" alt="image" src="https://github.com/user-attachments/assets/37c7ad83-0907-4e1c-877d-5df524fc42a2" />
<img width="2400" height="1080" alt="image" src="https://github.com/user-attachments/assets/2d1dc84d-25ed-4103-962e-e25673bf5705" />


**WORKING PRINCIPLE**
- The ultrasonic sensors are used to determine whether an obstacle is in the vicinity. When the left and right IR sensors are active, but the front one isn't, that means that the robot should go straight. When either side IR sensors becomes inactive, that means the robot should turn in that direction. While turning, the wheels should move in opposite directions.

**CHALLENGES**
- Soldering of the wires to the PERFBOARD
- Verifying whether the soldered wires aren't touching other vital components
- Making sure that the wires themselves don't break.
- Many batteries had to be replaced due to the sagging of the current of conventional AA and 9 V batteries.

**RESULTS**

https://youtu.be/0ctTs6YcSak?si=aV5JW_eKZYqfNwxG

**CODE**

[MAZE_NAV_ROBO_CODE.txt](https://github.com/user-attachments/files/30833813/MAZE_NAV_ROBO_CODE.txt)




