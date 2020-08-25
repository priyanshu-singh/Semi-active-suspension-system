# Semi-active-suspension-system
Here we use servo motor inside suspension system to control the flow of suspension fluid, which then determines the stifness of the suspension sytem. 
The driver can change the stiffness of the damper according to the type of terrain using blynk mobile application.
Here we will use servo motor and Node MCU or ESP8266 as major hardware component.

Connections:
D8 pin of NodeMCU connects to Command pin of Servo Motor.
3V3 PIN of NodeMCU connects to Power PIN of Servo motor.
GND PIN of NodeMCU connects to GND of servo motor 

BLYNK App Setup on Phone:
Create a New Project in BLYNK app.
Write Project Name and Select ESP8266 or NodeMCU from dropdown.
An AUTH token will be sent to  registered email.
Tap on the screen and add a SLIDER widget on the screen.
Tap on the Widget, select Virtual PIN 3 and Start value must be 0 and End Value must be 180.

Upload the attached code to the Node MCU using Arduino IDE.
use AUTH Id from the email, your Wifi SSID and Wifi password in the code.

After uploading the code to the NodeMCU or ESP8266, device will be displayed online on the BLYNK app. 
Click Play button on top right of your app and slide over the slider to rotate Servo.
