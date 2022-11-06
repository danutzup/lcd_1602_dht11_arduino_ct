# lcd_1602_dht11_arduino_ct  #

danzup arduino atmega2560 , ethernet shield ,  6 LM50 sensor , 1 relay , lcd 1602 , dht11
First 4 sensors are attached direct to atmega2560 , sensor 5 and 6 are attached to another
atmega16 and the readings / values are send serial to atmega2560.
Sensor LM50 from 1 to 4 are temperature monitoring my automated pellet Fornello furnace temperature (2 sensors) 
and input output of my puffer (2sensors),  
sensor 5 temperature is on my water solar pannel heater outside , 
sensor 6 temperature is on my boiler for hot watter used in kitchen and bathroom . 
the relay is for controll the electrical pump .
Atmega2560 then send mqttdata and retrieve status for the relay by subscribing to mqtt topics.
Also on a LCD 16x2 prints diferent data from sensors.
