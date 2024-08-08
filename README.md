Here i will show u how to install RoS-1 on ubuntu 20.04

Step1: you need to download VirtualBox

Step 2: now you need to download ubuntu 20.04

you can used this link to download it : https://releases.ubuntu.com/20.04/

![image](https://github.com/user-attachments/assets/6bed5ac8-ed47-4411-b423-dab061b56a42)

![image](https://github.com/user-attachments/assets/d763502f-0b6d-4a7f-a56f-8f26d13d5d48)

![image](https://github.com/user-attachments/assets/2fe5b896-5d4d-4949-8656-fdb1e4467bf6)

![image](https://github.com/user-attachments/assets/f44ad3fa-4104-4b85-8168-b48fbe3b66db)

Step 3: after you download the ubuntu 20.04 you need to open the Terminal on the ubuntu and start to write this lines:

1- sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

2-sudo apt install curl
![image](https://github.com/user-attachments/assets/8e5da2b2-3b7d-49ca-95ad-43472ef6055c)

3-curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -

4-sudo apt update

5-sudo apt install ros-noetic-desktop-full
![image](https://github.com/user-attachments/assets/ae74e943-3b41-45e7-b638-7135b1ccd415)

6-echo "source /opt/ros/noetic/setup.bash"

7- to make sure that the Ros1 is working: write: roscore
