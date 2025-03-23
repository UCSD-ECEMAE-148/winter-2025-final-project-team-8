# <div align = 'center'> ECE MAE 148 Optimization for Roboracing Performance </div>
![image](https://github.com/user-attachments/assets/f92d21c1-b05b-4499-a503-8d0ad4673dce) 
### <div align = "center"> MAE 148 Final Project </div>
#### <div align = 'center'> Team 8 - Winter 2025 </div>
<div align = "center"> 

![image](https://github.com/user-attachments/assets/c817c29c-3b0f-4314-b9cd-84079441b218)
</div>

# Table of Content
1. [Team Members](#team-members).
2. [Abstract](#abstract)
3. [What We Promised](#what-we-promised)
4. [Accomplishments](#accomplishments)
5. [Challenges](#challenges)
6. [Project Video](#project-video)
7. [Software](#software)
8. [Hardware](#hardware)
9. [Gantt Chart](#gantt-chart)
10. [Course Deliverables](#course-deliverable)
11. [Project Reproduction](#project-reproduction)
12. [References](#references)
13. [Contacts](#contacts)
14. [Images and Video](#images-and-videos)
<hr>

# Team Members
* Aaron Kim (ECE)
* Marco Krause (ECE)
* Andrew Vo (MAE)
* Giovanni Torres (MAE)
<hr>

# Abstract
Going fast has always been an important topic. With recent technological advancements in autonomous cars, we found the need to go faster... without a driver. The scope of the project is to utilize the ForzaETH repo and integrate it with lidar vision in order to adapt the car to every track without physical training. The car will map out the track layout and compute the best possible way to get around the track.
<hr>

# What We Promised
- Optimizing Vehicle Racing Performance using Lidar SLAM and EKF with IMU and VESC outputs.
- Creating an optimal trajectory race line with an algorithm and following the path using Pure Pursuit/Model and Acceleration-based Pursuit controllers. Based on ForzaETH repo.
## System Architecture of ForzaETH stack
![image](https://github.com/user-attachments/assets/b398c61d-68ae-4752-8daa-eeb8c0e006f3)
## State Estimation Architecture of ForzaETH
![image](https://github.com/user-attachments/assets/d23ed29f-4736-4534-a119-792c1fae7f37)
## Controller Architecture of ForzaETH
![image](https://github.com/user-attachments/assets/ee664e8b-b0fe-4dce-b36c-28c380bfa1a8)

<hr>

# Accomplishments 
- Our Daily Progress Log can be found [here](https://docs.google.com/document/d/1Jbvnwe5eSdBmKXfEPnErvxRPAoAEU4X7f6TuEhFGy84/edit?usp=sharing)
- Our Final Presentation can be found [here](https://docs.google.com/presentation/d/1jDzgPcM4uLSq9gf9zOrWzeR1uJlb5yxIsBrtGc7jHMk/edit?usp=drive_link)


<hr>

# Challenges
- Initial project scope was to use V-SLAM to map out the track but V-SLAM is computationally heavy and would require Xavier NX, which would take up a lot of time to build from scratch.
- Research into V-SLAM was done, there are a few alternative methods to implement this with V-SLAM but that was out of the scope of the project.
- With the time available, we couldn't implement self-mapping of the course, that could be a future improvement of the project where you can set the car on a random track and then have it mapped out by itself, then the car would be able to optimize the track

Pivoted: 
- As a team, we decided to pivot away from V-Slam onto Lidar based Slam, here are a few reasons:
- V-Slam → requires heavy computational power and lacks support from Roboracer (Need to transfer to Jetson Xavier)
- Lidar SLAM → Lower computational requirements, better ROS 1 support
- On the Jetson Nano, it would have been required to build our own package, and is out of the scope for the class

<hr>
  
# Project Video
- What we achieved, a video demonstration can be found [here](https://drive.google.com/drive/folders/15zS9xfFcYgYLzARoz2ZrUlHNW0CQgAFX?usp=drive_link)
- In the end, we did not completely implement lidar based slam into ForzaETH:
-   But we managed to achieve
-     Successfully integrated LD06 lidar to replace the Hokuyo lidar
-     Mapped the joystick input for Logitech F710


<hr>

# Software
- Lidar Node
- ForzaETH "rack_stack" in ROS environment
- Forza docker container on ROS1
- Modified node for VESC

<hr>

# Hardware:
## Standard
We followed the standard MAE/ECE 148 car setup guideline and parts list, the only exception we made is using an OAK-D Pro camera with an built-in IMU.
- The list of [parts](https://docs.google.com/file/d/1g7Q1cRvhreIL_nPo44IU39hTb_rMGENF/edit?filetype=msword)
- Car Wiring Diagram
![image](https://github.com/user-attachments/assets/518f93cc-00a1-46ad-82b5-f69ea34944a7)
- VESC set up [here](https://roboracer.ai/build)
- More detail about individual packages can be found [here](https://docs.google.com/presentation/d/1jDzgPcM4uLSq9gf9zOrWzeR1uJlb5yxIsBrtGc7jHMk/edit?usp=sharing)

## Custom Parts
### Base Plate
![image](https://github.com/user-attachments/assets/2c00ab19-b993-463c-8061-39be3543af3c)

### Camera Mount
![image](https://github.com/user-attachments/assets/dbd4e3b4-c3f1-4f04-a926-7d310ee3d7d8)

### Lidar Mount
![image](https://github.com/user-attachments/assets/30efd033-da78-45b1-b800-fb28c57b437f)

### Electronics plate with GPS Mount
![image](https://github.com/user-attachments/assets/d3323bd6-7f4e-436c-bda8-31561a939a50)

## Complete Assembly of custom parts
![image](https://github.com/user-attachments/assets/5d800a3f-e86f-449b-98de-87af960114d2)

<hr>
## Car Assembly
![IMG_2527](https://github.com/user-attachments/assets/c5d4ca29-fa23-45b9-b096-e0ce5fa76a2b)

![IMG_2523](https://github.com/user-attachments/assets/cdf08aab-d681-4568-8fb6-68e59f9bbc3a)

![IMG_2521](https://github.com/user-attachments/assets/5aca8224-3eb9-46f9-bf52-c2bb387584ca)

# Gantt Chart
![image](https://github.com/user-attachments/assets/c405db4b-cbf1-448d-aeb3-88ed590b36e5)
<hr>

# Course Deliverable
Links to class deliverables:
- DonkeyCar Reinforcement Laps: [Link](https://www.youtube.com/shorts/jBdtot5aemE)
- OpenCV Laps: [Link](https://www.youtube.com/watch?si=heQWVJycjnkgMijZ&v=hAXUiicVj78&feature=youtu.be)
- GPS Laps: [Link](https://www.youtube.com/watch?v=ry6CfRk-CJk&ab_channel=AaronKim)
- Roboflow Model: [Link](https://www.youtube.com/watch?v=dXgY9VMILmM&ab_channel=GiovanniTorres)
- Team's Final Project Progress Report
    Week 8,9,10: [Link](https://docs.google.com/presentation/d/1jDzgPcM4uLSq9gf9zOrWzeR1uJlb5yxIsBrtGc7jHMk/edit?usp=sharing)
<hr>

# References:
ForzaETH Stack: [Link](https://github.com/ForzaETH/race_stack/blob/main/README.md) and associated repo's that ForzaETH used

ForzaETH_racestack: [Link](https://arxiv.org/html/2403.11784v2#S8)

[A Comparison of Modern General-Purpose Visual SLAM Approaches](https://arxiv.org/pdf/2107.07589)

README.md Format, reference to [winter-2024-final-project-team-7](https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-7?tab=readme-ov-file#slam-simultaneous-localization-and-mapping)
<hr>

# Contacts
Aaron Kim - [Email](aak003@ucsd.edu) or [personal email](aaaronikin@gmail.com)
Marco Krause - [Email](m1krause@ucsd.edu)
Andrew Vo - [LinkedIn](www.linkedin.com/in/andrewvo1504)
Giovanni Torres - [Email](gitorres@ucsd.edu)

# Images and Videos
Google Drive: [Link](https://drive.google.com/drive/folders/15zS9xfFcYgYLzARoz2ZrUlHNW0CQgAFX?usp=drive_link)
