
##Water Level Sensor

Hardware Outline Of The Water Level Sensor
Here, we are going to use a water level sensor to detect water levels. Basically, this sensor is a combination of the attached series of ten exposed copper traces. The copper traces are merged with each other in order to have one sense trace between two copper traces.
In short, there are alternate copper traces and sense traces. These traces form a bridge by water when dipped in the water. For power indication, there is an onboard power LED.


Working Of The Water Level Sensor

This sensor works on the principle of variable resistance. The sensor consists of a series of parallel exposed conductors. Together this series acts as a variable resistor, whose resistance varies according to the water level in the water tank.
As more water sensor is submerged in, the better is the conductivity and the lower is the resistance. The less the water sensor is submerged in, the poor is the conductivity and the higher is the resistance.
The output of the water level sensor is according to the resistance of the water produced. i.e. it will produce a voltage proportional with resistance.


Pin Description
S(signal pin) is an analog output that will be connected to the analog pin of the Arduino.
+VCC is powering pin of the sensor. The approved input voltage is 3.3v to 5v.
-GND is simply a ground connection.

Components Required :-

Water level sensor
Arduino Uno
Connecting Wires
LEDs
Resistors
Breadboard

