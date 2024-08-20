# Flash-LFR
Flash-LFR is a line follower robot project
Stage 1
At first, we started to design our LFR chassis. We designed where we needed to put our components in the chassis. Then we make holes to attach our components with screws to the chassis. Then we attached wheel-geared motors in specific positions. Then we attached Arduino UNO REV3 in the middle of the chassis board. Then we attached Motor DRIVER L298N in the middle of the chassis and front of Arduino. We had a 12V Li-Ion battery. when we thought we would attach this battery there could be a problem because Arduino and motor driver needed 5V electric power.  So we needed a power converter to convert 12V to 5V electricity. So we attached a bug controller to solve the problem. 

Stage 2
We started making wire connections from one to another component. First, we made a connection between the Battery and the bug controller through a switch.  We ready our bug controller to give a 5V electric power supply from the battery. Then we send connections from the bug controller to Arduino and Arduino to the Motor Driver. We used jumper wires(male-female) for Arduino to motor driver connection. We made a parallel connection between two motors on the right side and did the same thing on the left side. Then we send connections from the motor driver to all wheels geared motors. We attached two Infrared sensors in front of the chassis board on the left and right and targeted to the ground. Then we send connections from Arduino to those Infrared sensors by jumper wires.



Stage 3
We made an algorithm that will show how the robot will perform on the road. According to the algorithm, we made a code for our line follower robot via the Arduino IDE application on a computer. Then we send the code from the computer to Arduino through a type B USB connector. 

Stage 4
When we ran our robot, the robot wasn't working. Then we found out that we had made a mistake when we made a wrong connection between the bug controller and Arduino. Then we fixed that problem.
