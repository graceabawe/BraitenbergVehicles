Implementation of the classic Braitenberg vehicles, a simple, autonomous robot. Braitenberg vehicles respond to the light in their environment with different
behaviors. There are 4 main behaviors (aka personalities), being Love, Fear, Aggression, and Coward. Each vehicle can exhibit all behaviors and are switched
through a button input. The basic principle is that though the vehicle itself is simple, complex behaviors can be derived by following very basic principles. 
For Braitenberg vehicles, the wiring between the sensors and the motors, as well as how the robot is told to react to light is what dictates behavior. For example, 
the “Love” robot wires the right light sensor to its right motor and the same for the left side. When it senses light, the stronger the light source, the more 
intense the input will be for the sensor to detect, which will make the motor react more intensely. Thus, if there is light on the robot’s right side, it will
subsequently turn right because it's right motor will turn at a faster velocity than its left until it is facing the light head on, and will attempt to drive through the light.
For additional functionality, each behavior state has its own  OLED display and buzzers that play music. 
