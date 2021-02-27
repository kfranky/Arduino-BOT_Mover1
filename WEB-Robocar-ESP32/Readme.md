## Robo-Car - gesteuert über einen WEB-Server
Bei diesem Robo-Car wird der NANO gegen einen ESP32 ausgetauscht und über einen WEB-Server gesteuert. Die Hardware entpricht dem BOT-Mover1.

Die Anschlüsse vom ESP32 zur Dual-H-Brücke-DC-Schrittmotorantrieb L298N:

Motor 1

int motor1Pin1 = 26; 

int motor1Pin2 = 27; 

int enable1Pin = 14; 


Motor 2

int motor2Pin1 = 25; 

int motor2Pin2 = 33; 

int enable2Pin = 32;


![image](https://github.com/frankyhub/Arduino-BOT_Mover1/blob/master/WEB-Robocar-ESP32/WEB-Robocar1.png)
