# <div align = 'center'> ECE-MAE-148-Optimization-for-Roboracing-Performance </div>
![image](https://github.com/user-attachments/assets/f92d21c1-b05b-4499-a503-8d0ad4673dce) 
### <div align = "center"> MAE 148 Final Project </div>
#### <div align = 'center'> Team 8 - Winter 2025 </div>
<div align = "center">
image of the car
</div>

# Table of Content
1. [Team Members](#team-members).
2. [Abstract](#abstract)
3. [What We Promised](#what-we-promised)
4. [Accomplishments](#accomplishments)
5. [Challenges](#challenges)
6. [Final Project Video](#final-project-video)
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
Going fast have always been an important topic. With recently technology advancement of autonomous car, we found the need to go faster... without a driver. The scope of the project is to ultilize ForzaETH repo and integrating with lidar vision in-order to adapt the car to every track without physical traning. the car will map out the track layout and will compute the best possible way to get around the track.
<hr>

# What We Promised
- Optimizing Vehicle Racing Performance using SLAM and EKF with Artemis IMU and VESC outputs.
- Creating a optimal trajectory raceline with an algorithm and following the path using Pure - Pursuit/Model and Acceleration-based Pursuit controllers. Based on ForzaETH repo.
<hr>

# Accomplishments 
- Our daily progress log can be fine [here](https://docs.google.com/document/d/1Jbvnwe5eSdBmKXfEPnErvxRPAoAEU4X7f6TuEhFGy84/edit?usp=sharing)

<hr>

# Challenges
- Initial project scope was to use V-SLAM to map out the track but V-SLAM is computationally heavy and would require Xavier NX, would take up a lot of time to build from scratch.
- Research into V-SLAM were done, there are a few alternative method to implement this with V-SLAM but that was out of the scope for the project.
- With the time available, we couldn't implemnt self mapping of the course, that could be a future improvement of the project where you can set the car on a random track then have it mapped out by itself, then car would be able to optimized the track

<hr
  
# Final Project Video
- What we achieved, a video demonstration can be found [here](https://drive.google.com/drive/folders/15zS9xfFcYgYLzARoz2ZrUlHNW0CQgAFX?usp=drive_link)

<hr>

# Software
- Lidar Node
- ForzaETH "rack_stack" in ROS environment
- Forza docker container on ROS1
- Modified node for VESC

<hr>

# Hardware:
## Standard
We followed the standard MAE/ECE 148 car setup guideline and parts list, the only exception we made is using a OAK-D Pro camera with an built-in IMU.
- The list of [parts](https://docs.google.com/file/d/1g7Q1cRvhreIL_nPo44IU39hTb_rMGENF/edit?filetype=msword)
- Car Wiring Diagram
![image](https://github.com/user-attachments/assets/518f93cc-00a1-46ad-82b5-f69ea34944a7)
- VESC set up [here](https://roboracer.ai/build)
- More detail about individual package can be found [here](https://docs.google.com/presentation/d/1jDzgPcM4uLSq9gf9zOrWzeR1uJlb5yxIsBrtGc7jHMk/edit?usp=sharing)

## Custom
### Base Plate
![image](https://github.com/user-attachments/assets/5c815773-6b8f-408f-9ff9-6ff27c4473b8)

### Camera Mount
*insert cad*
### Lidar Mount
*insert cad*
### GPS Mount
*insert cad*

<hr>

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
Aaron Kim - 
Marco Krause - 
Andrew Vo - [LinkedIn](www.linkedin.com/in/andrewvo1504)
Giovanni Torres - 

# Images and Videos
Google Drive: [Link](https://drive.google.com/drive/folders/15zS9xfFcYgYLzARoz2ZrUlHNW0CQgAFX?usp=drive_link)
