# 🚦 Arduino Four-way Traffic lights simulation 🚥
##### by Tran Nguyen

##### 11/08/2019
##### Project definition: 
Ever stopped and waited at a red light too long that you wish you could legally run a red light? Well this
project might solve that problem! This is a four-way traffic lights simulation with built-in sensors and a
mobile app that you can send request to change that red light to green to go on with your day.
##### Pseudocode:
A user can send request to change the red light to green from their phones

IF that red light has been on for more than 3 seconds* (so people don’t just immediately send request
right after they stop)

AND there are no cars coming (this could be determined by using either photoresistors sensors to
detect car headlights or using ultrasonic sensors)

(AND that red light has more than 30 seconds* left in its cycle)

The request is going to be in a form of a command. Might setup NodeMCU server or might utilize Amazon Web Services 
The data could be stored so analysis could be done and adjustment for the duration of the traffic lights could be made.

<i> *amount might change </i> 

##### Project support needs:
- 3 ~ 4 ESP8266 NodeMCU
- 4 photoresistors sensors / ultrasonic sensors
- 4 red LEDs, 4 yellow LEDs, 4 green LEDs
- Resistors
- A lot of jumper wires
- Breadboards or 4 mini breadboards
- Cables
