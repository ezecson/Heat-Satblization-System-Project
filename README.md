# Heat-Satblization-System-Project
An AVR microcontroller was used to control the temperature of a cooking pot by stabilize the electricity flow to a heater
![alt text ](https://github.com/ezecson/Heat-Satblization-System-Project/blob/master/videos%20and%20images/protous%20schemitic%20design%20foe%20system.png)

![alt text](https://github.com/ezecson/Heat-Satblization-System-Project/blob/master/videos%20and%20images/whole%20system.jpg)

## softwares
- Proteus Schemitic Design isis professional:
    has been used to design an inital design and simulate the design
	
- KHAZAMA AVR:
    has been used to upload avr microcontroller with a code
	
- Codevision AVR Evaluation: 
    has been used to write the code of microcontroller in c language 

## Features
- Read the desired temperature that the user want from keypad.
- Display the current temperature and the keypad pressing in lcd
- Read the temperature of the cooking pot by a temperature sensor.
- Send a pwm signal to control a transistor which control the electricity flow
- AC to DC converter was used because the heater works in DC

## Tests
- ATmega 32 test 

![alt text](https://github.com/ezecson/Heat-Satblization-System-Project/blob/master/videos%20and%20images/atmega%20test%20with%20blinking%20led%20code.gif)

- Keypad and lcd test

![alt text](https://github.com/ezecson/Heat-Satblization-System-Project/blob/master/videos%20and%20images/keypad%20test.gif)

- Rectifer without capacitor
![alt text](https://github.com/ezecson/Heat-Satblization-System-Project/blob/master/videos%20and%20images/rectifier%20test%20with%20oscillscope%20without%20capacitor.jpg)

- Rectifer with capacitor
![alt text](https://github.com/ezecson/Heat-Satblization-System-Project/blob/master/videos%20and%20images/rectifier%20test%20with%20oscillscope%20with%20capacitor%201%20mF.jpg)
You can watch a [video](https://github.com/ezecson/Heat-Satblization-System-Project/blob/master/videos%20and%20images/final%20test%20of%20the%20system.mp4) for the system after integration its parts 
