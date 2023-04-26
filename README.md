# Smart Home Security and monitoring System

> **Abstract** : This will be consisting of various sensors like motion detector , Smoke detection which upon triggered will sound an alarm on owners phone.

### Project Members
1. RANE RIYAL RAJEEV  [ Team Leader ] 
2. KUNDE PRATIK NITIN 
3. SINGH MAYANK SANJAY 
4. MISHRA SHAILESH MAHESHDUTT 

### Project Guides
1. PROF. ANUPAM CHOUDHARY  [ Primary Guide ] 

### Deployment Steps
Please follow the below steps to run this project.

1. Gather the components: You will need an Arduino Uno board, an IR flame sensor module, an LCD display, a Wi-Fi module, jumper wires, a breadboard, a power supply, and an alarm or buzzer.

2. Connect the IR flame sensor module to the Arduino Uno board using jumper wires. Connect the VCC and GND pins of the module to the 5V and GND pins of the Arduino, respectively. Connect the DO (digital output) pin of the module to any digital pin of the Arduino board.

3. Connect the LCD display to the Arduino Uno board using jumper wires. Connect the VCC and GND pins of the display to the 5V and GND pins of the Arduino, respectively. Connect the SDA and SCL pins of the display to the A4 and A5 pins of the Arduino board, respectively.

4. Connect the Wi-Fi module to the Arduino Uno board using jumper wires. Connect the VCC and GND pins of the module to the 3.3V and GND pins of the Arduino, respectively. Connect the TX and RX pins of the module to the TX and RX pins of the Arduino board, respectively.

5. Connect the alarm or buzzer to any digital pin of the Arduino board.

6. Open the Arduino IDE software and upload the code for the flame detection system. The code will read the sensor data from the IR flame sensor module and display the status on the LCD display. If a flame is detected, the alarm or buzzer will be triggered, and a notification will be sent to the user's smartphone via the Wi-Fi module.

7. Test the flame detection system by lighting a match or a candle near the IR flame sensor module. If the system is working correctly, the LCD display should show the status, and the alarm or buzzer should sound.

8. Mount the flame detection system in the desired location, ensuring that the sensor module has a clear view of the area to be monitored.

9. Connect the power supply to the Arduino Uno board and turn on the system. The flame detection system is now deployed and ready to monitor for flames.


### Subject Details
- Class : TE (COMP) Div A - 2022-2023
- Subject : Mini Project Lab: 2B (mP2B)
- Project Type : Mini Project

### Platform, Libraries and Frameworks used
1. [Arduino UNO](https://docs.arduino.cc/hardware/uno-rev3)


### References
--    Kim, M., Kim, H., & Lee, D. (2018). An IoT-based fire detection system using multiple environmental sensors. Sensors, 18(6), 1859.
--    Choudhury, P., Sarker, I., Rana, S., & Chakraborty, C. (2018). A wireless sensor network-based fire detection system using adaptive threshold. Journal of               Intelligent & Fuzzy Systems, 35(1), 77-86.






