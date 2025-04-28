# Smart-Home-Automation-using-Arduino
Designed a smart home automation system using Arduino Uno and simulated it on the TinkerCAD platform. The system enables remote control and automation of home appliances like lights, fans, and door locks using sensors and actuators.


HomeAutomationSystem
Sensors Used:

PIR (Passive Infrared Sensor)

![image](https://github.com/user-attachments/assets/0a5cce2f-7369-4a70-b6ed-95fc1db262f0)



LDR (Light Dependent Resistor)

![image](https://github.com/user-attachments/assets/0c186a7f-17e9-4d72-b229-db97abc339f4)


TMP36 (Temperature Sensor)

![image](https://github.com/user-attachments/assets/65ec34b8-71bc-4c47-b408-906a9f2589b0)


Processor Used:
Arduino Uno R3
![image](https://github.com/user-attachments/assets/a2d92c49-0969-40fb-8e64-4be9a6cd0627)


LCD Controller:

Breadboard
![image](https://github.com/user-attachments/assets/6f52253d-566f-4f2b-824e-233440d468e9)


Functioning: if(MOTION DETECTED) {

Temperature HIGH && Light Intensity LOW: Bulb and Fan both are switched ON.
Temperature LOW && Light Intensity HIGH: Only Fan is switched ON.
Temperature LOW && Light Intensity HIGH: Only Bulb is switched ON.
Temperature LOW && Light Intensity LOW: All appliances switched OFF.
} else {

print (No MOTION DETECTED)
}

Output Screen - LCD 16x2



![image](https://github.com/user-attachments/assets/ce20b09f-8cab-4703-80b5-bfc0881ae5c9)


Output:

No Movement
Output
![image](https://github.com/user-attachments/assets/89712f19-25b6-4633-a6ae-f73d0d8523cb)


When movement is detected the Bulb and Fan is turned ON.

![image](https://github.com/user-attachments/assets/f86bcaee-4cd1-4c31-844c-8c9659201c92)

