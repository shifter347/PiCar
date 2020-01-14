# PiCar
The goal of this program is to enable a robot chassis controlled by a RaspberryPi computer to follow a pre-determinned path and avoid collisions with any obstacles along the way.

The chassis has 3 sets of sensors and a set of motors connected and manipulated by the program.
The first set are line sensors that allow the robot to follow the path. 
The second set are IR sensors that allow the robot to sense obstacles located in front of it.
The last set of sensors are mounted on the wheels and alllow for the robot to know how fast it's going and how far it has gone.
The program uses 2 files: initio and PiCar.
The initio file is used to set the sensors to the right pins, get the states of all sensors used and overall prepare the robot for use.
The main code is located in the PiCar file. This code enables the robot to do all of the above mentioned tasks whilist giving live feedback of everything the sensors detect.
