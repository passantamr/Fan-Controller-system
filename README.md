# Fan-Controller-system
embedded project using Atmega32 
created by bassant amr
in this project we control speed of fan (motor) depenent on temperature degree
if temp < 30c   => the fan is off
else the fan is on in specific speed depend on reading of temp
if temp >= 120c  => the fan will rotate by maximuim speed
else if temp >= 90   =>  the fan will rotate by 75% from maximuim speed
else if temp >= 60   =>  the fan will rotate by 50% from maximuim speed
else if temp >= 30   =>  the fan will rotate by 25% from maximuim speed
<h3>microcontroller </h3>
in this project we will use ATmega32 which have 4 port and 8 pins for each port
<h3>Temperature sensor </h3>
we need to use LM35 temp sensor which return analog value (0-5v) connected to PA2 (PORT A - PIN_num 2) (channel 2)
<h3>10 bit ADC</h3>
we need to use 10-bit ADC (analog to digital converter) to convert analog input from LM35 into digital value (0-1023)
in atmega32 we have 8 pins (PORT A) analog and one ADC which can convert only one channel at a time
