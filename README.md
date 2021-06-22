# Abdullah-Subedar
Task 1: Robot Arm 

Task1

تثبيت وتشغيل باكج الذراع على نظام ROS


•	كتابة الخطوات

•	تصوير النتائج

Answer:

1.	First we install ROS in Ubuntu.

2.	After we finish installing all the necessary dependencies, we will run the simulation to show the results.

3.	We run this code in the terminal and the result would be simulation of Gazebo and RViz:

roslaunch robot_arm_pkg check_motors.launch


4.	Then we run this code and the result would be simulation of MoveIt in RViz:

roslaunch moveit_pkg demo.launch


Task3

تثبيت وتشغيل باكج الذراع على ROS noetic

حل مشكلة robot state publisher

![image](https://user-images.githubusercontent.com/86069105/122990921-221c1200-d3ad-11eb-9fdc-4e8247abe934.png)

Answer:This is a problem caused by the missing robot_state_publisher package.
