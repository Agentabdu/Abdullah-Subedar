# Task 1: Robot Arm 

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



Task2

ربط نظام ROS

مع لوحة التحكم، علمًا بأن قيمة كل محرك سيتم التعبير عنها كصفحة ويب منفصلة


كتابة طريقة الربط

كتابة الأكواد باستعمال
python or C++ 

Answer: in-progress



Task3

تثبيت وتشغيل باكج الذراع على 
ROS noetic

حل مشكلة 
robot state publisher

Answer:This is a problem caused by the missing robot_state_publisher package.

simply install with this code

sudo apt-get install ros-noetic-robot-state-publisher


then update after installing the package

sudo apt-get update
