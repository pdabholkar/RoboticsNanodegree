I enrolled in the Robotics Nanodegree a month ago when Udacity frst announced their 30 day free offer. I completed 1/3 of the course when I actually wanted to complete the course in the free month. As with most wishful ideas this did not work out and after a lot of deliberation and thanks to a generous discount offered by Udacity, I continue to be enrolled in the course. The goal is to fininsh the remainder of the course in the next one month.
This website will serve as an account of my experiences.

## Day 32:
### Done today
- Read through Lesson 3 in the course "Write ROS Nodes". The material presented was easy to understand because the code is all there.
- I am stumped by the challenge in the last section that asked me to use the template class to implement the nodes in the lesson
- I have limited ability with OOP. Thankfully the knowledge forum has a question https://knowledge.udacity.com/questions/86508
- One of the solutions is a YoutTube video. Trying to follow the presenter and have watched the video a number of times to understand what is being done. I am able to grasp the idea but I am still not confident that I can attempt the question on my own
- Found another link that discusses OOP in C++ for ROS https://roboticsbackend.com/oop-with-ros-in-cpp/. Thi could be it. I have read the link and feel a bit more confident. I shoul be able to do a bit of "pattern matching" of code templates and attempt the challenge.

### What happens tomorrow
1. Follow the tutorial from roboticsbackend.com and complete the challenge
2. Move on to the Project "Go Chase It"
3. I have downloaded the eBook "A gentle introduction to ROS" https://cse.sc.edu/~jokane/agitr/ Will go through the initial few pages to check its usefulness.

## Day 33:
### Done today
- Did not attempt the challenge question.
- Progressed to Section 6 in the project that discusses enhancing the Robot URDF discussion to a wheels
- Was not able to get the rotated properly. This also causes the main chassis to flip on its belly.

### What happens tomorrow
- Will continue with the model. 

## Day 34:
### Done today
- Added the camera and LIDAR models to the URDF.
- This is a good tutorial https://wiki.ros.org/urdf/Tutorials/Building%20a%20Visual%20Robot%20Model%20with%20URDF%20from%20Scratch
The section on connecting the arm to the body with the joint was useful in understanding the concept of origins.
- **ATTN!** Because Gazebo is a physics engine, if the URDF only has the visual and the inertial models for some links and all three models for the other links. the model may topple or break
- **ATTN** The joint is necessary for the URDF to be parsed correctly. Without the joint, the link does not have a reference/origin.
- Getting the LIDAR plugin to show the Laser rays is not happening for now.

### Whatt happens tomorrow
- Will continue working on the LIDAR model and RVIZ visualization
- Complete the project
