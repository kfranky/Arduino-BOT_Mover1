## RoboCar - gesteuert über einen WEB-Server
Bei diesem Robo-Car wird der NANO gegen einen ESP32 ausgetauscht und mit einen WEB-Server gesteuert. Die Hardware entpricht dem BOT-Mover1. Die IP-Adresse wird im seriellen Monitor angezeigt.

Die Anschlüsse vom ESP32 zur Dual-H-Brücke-DC-Schrittmotorantrieb L298N:

Motor 1

int motor1Pin1 = 26; 

int motor1Pin2 = 27; 

int enable1Pin = 14; 


Motor 2

int motor2Pin1 = 25; 

int motor2Pin2 = 33; 

int enable2Pin = 32;


### WEB-Server:

![image](https://github.com/frankyhub/Arduino-BOT_Mover1/blob/master/WEB-Robocar-ESP32/WEB-Robocar1.png)




## Stückliste:

- 1 Arduino ESP32
- 4 Getriebemotoren mit Räder
- 1 Dual-H-Brücke-DC-Schrittmotorantrieb L298N
- 2 ABS Platten Kunststoff 29x21cm 4mm dick
- 2 18650 Akkus mit Akkucase
- Kleinmaterial, Schrauben, Muttern, Klemmen, Draht
- Platinenhalter
- Optional: Solarpanel für die Akku-Ladung



## Links:

- Download Inkscape (*.svg): [Link](https://inkscape.org/de/release/inkscape-1.0.1) 

- Downlaod Arduino (*.ino): [Link](https://www.arduino.cc/en/Main/Software)

- Arbeitsschritte Arduino BOT-Mover: [Link](https://github.com/frankyhub/Arduino-BOT_Mover1/blob/master/Arbeitsschritte%20Arduino%20Bot.pdf)

- Deck- und Bodenplatte (SVG-File): [Link](https://github.com/frankyhub/Arduino-BOT_Mover1)

- Platinenhalter: [Link](https://github.com/frankyhub/openscad-Beispiele/tree/master/008%20Platinenhalter)

- Arduino Programm: [Link](https://github.com/frankyhub/Arduino-BOT_Mover1/blob/master/WEB-Robocar-ESP32/WEB-Robocar-ESP32.ino)
