# Smart-Home-Automation-using-Arduino
Designed a smart home automation system using Arduino Uno and simulated it on the TinkerCAD platform. The system enables remote control and automation of home appliances like lights, fans, and door locks using sensors and actuators.


HomeAutomationSystem
Sensors Used:

PIR (Passive Infrared Sensor)

![image](https://github.com/user-attachments/assets/0a5cce2f-7369-4a70-b6ed-95fc1db262f0)



LDR (Light Dependent Resistor)
image

TMP36 (Temperature Sensor)
image

Processor Used:

Arduino Uno R3
image

LCD Controller:

Breadboard
image

Functioning: if(MOTION DETECTED) {

Temperature HIGH && Light Intensity LOW: Bulb and Fan both are switched ON.
Temperature LOW && Light Intensity HIGH: Only Fan is switched ON.
Temperature LOW && Light Intensity HIGH: Only Bulb is switched ON.
Temperature LOW && Light Intensity LOW: All appliances switched OFF.
} else {

print (No MOTION DETECTED)
}

Output Screen - LCD 16x2

image

Output:

No Movement
Output

When movement is detected the Bulb and Fan is turned ON.
