# 74HC595-soft-joystick-mobile-app-control-obstacle-avoidance
This repository contains the code for an arduino robot car featuring mobile app control, driving mood and obstacle avoidance mood. 

I've shared the arduino sketch of a arduino robot car. This car features mobile app control (created with MIT app inventor), driving mood and obstacle avoidance mood. 
I've included a 74HC595 in the circuit as well as written essentials for it in the code. This is because I'm currently working to attach a robotic arm on this vehicle, 
which will require 6-7 pins for driving servo motor. Thus freeing up arduino pins by using 74HC595 shift register seemed to be a feasible option. 

Though the analog pins are assigned for line following sensor array. The mechanism for line follower has not been implemented yet. 
I wish to do the job after I learn PID control algorithm. 

But for with the published stable versioni of the code you can driving the car in joystick driving mood, and run it in obstacle
avoidance mood using the mobile app included in the Controller essentials file. 
