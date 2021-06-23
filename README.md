# Task 1: Robot Arm 

Made by: Abdullah Subedar

## Task1

تثبيت وتشغيل باكج الذراع على نظام ROS


•	كتابة الخطوات

•	تصوير النتائج

## Answer:

1.	First we install ROS in Ubuntu.

2.	After we finish installing all the necessary dependencies, we will run the simulation to show the results.

3.	We run this code in the terminal and the result would be simulation of Gazebo and RViz:

roslaunch robot_arm_pkg check_motors.launch

Gazebo:
![Robot-Arm_Gazebo](https://user-images.githubusercontent.com/86069105/123163929-fd8e6b80-d47a-11eb-9196-86118315a9c9.png)


RViz:
![Robot-Arm_RViz](https://user-images.githubusercontent.com/86069105/123163978-0b43f100-d47b-11eb-9f50-bda827e98c9d.png)



4.	Then we run this code and the result would be simulation of MoveIt in RViz:

roslaunch moveit_pkg demo.launch

MoveIt:
![Robot-Arm_MoveIt](https://user-images.githubusercontent.com/86069105/123164064-1eef5780-d47b-11eb-987d-bb33dce0eb24.png)



## Task2

ربط نظام ROS

مع لوحة التحكم، علمًا بأن قيمة كل محرك سيتم التعبير عنها كصفحة ويب منفصلة


كتابة طريقة الربط

كتابة الأكواد باستعمال
python or C++ 

## Answer: in-progress



## Task3

تثبيت وتشغيل باكج الذراع على 
ROS noetic

حل مشكلة 
robot state publisher

## Answer:This is a problem caused by the missing robot_state_publisher package.

simply install with this code

sudo apt-get install ros-noetic-robot-state-publisher

then update after installing the package

sudo apt-get update
