# ECE-MAE-148-Optimization-for-Roboracing-Performance
![image](https://github.com/user-attachments/assets/f92d21c1-b05b-4499-a503-8d0ad4673dce)
                                          Team 8
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

# Team Members
- Aaron Kim (ECE)
- Marco Krause (ECE)
- Andrew Vo (MAE)
- Giovanni Torres (MAE)

# Abstract
  Going fast have always been an important topic. With recently technology advancement of autonomous car, we found the need to go faster... without a driver
  The scope of the project is to ultilize ForzaETH repo and integrating with lidar vision in-order to adapt the car to every track without physical traning. the car will map out the track layout and will compute the best possible way to get around the track.

# What We Promised
- Optimizing Vehicle Racing Performance using SLAM and EKF with Artemis IMU and VESC outputs.
- Creating a optimal trajectory raceline with an algorithm and following the path using Pure - Pursuit/Model and Acceleration-based Pursuit controllers. Based on ForzaETH repo.

# Accomplishments 
- Lidar Integration
- SLAM Integration

# Challenges
- Initial project scope was to use V-SLAM to map out the track but V-SLAM is computationally heavy and would require Xavier NX, would take up a lot of time to build from scratch
# Final Project Video

# Software
- Lidar Node
- ForzaETH "rack_stack" in ROS environment
- Forza docker container on ROS1
- Modified node for VESC

# Hardware:
## Standard
- Traxxas Chassis
  -  steering servo
  -  sensored brushless DC motor
  -  DC-DC Converter
  -  4-cell Lipo Battery
Jetson Nano
Sparkfun Artemis IMU
Flipsky VESC 4.12
LD06 Lidar
F710 Logitech joystick controller

- Car Wiring Diagram
![image](https://github.com/user-attachments/assets/518f93cc-00a1-46ad-82b5-f69ea34944a7)

## Custom
### Base Plate
![image](https://github.com/user-attachments/assets/5c815773-6b8f-408f-9ff9-6ff27c4473b8)

### Camera Mount
*insert cad*
### Lidar Mount
*insert cad*
### GPS Mount
*insert cad*

# Gantt Chart
![image](https://github.com/user-attachments/assets/c405db4b-cbf1-448d-aeb3-88ed590b36e5)

# Course Deliverable
Links to class deliverables:
- DonkeyCar Reinforcement Laps: [Link](https://www.youtube.com/shorts/jBdtot5aemE)
- OpenCV Laps: [Link](https://www.youtube.com/watch?si=heQWVJycjnkgMijZ&v=hAXUiicVj78&feature=youtu.be)
- GPS Laps: [Link](https://www.youtube.com/watch?v=ry6CfRk-CJk&ab_channel=AaronKim)
- Roboflow Model: [Link](https://www.youtube.com/watch?v=dXgY9VMILmM&ab_channel=GiovanniTorres)
- Team's Final Project Progress Report
    Week 8,9,10: [Link](https://docs.google.com/presentation/d/1jDzgPcM4uLSq9gf9zOrWzeR1uJlb5yxIsBrtGc7jHMk/edit?usp=sharing)


# References:
ForzaETH Stack: [Link](https://github.com/ForzaETH/race_stack/blob/main/README.md) and associated repo's that ForzaETH used

@article{baumann2024forzaeth,
  title={ForzaETH Race Stack—Scaled Autonomous Head-to-Head Racing on Fully Commercial Off-the-Shelf Hardware},
  author={Baumann, Nicolas and Ghignone, Edoardo and K{\"u}hne, Jonas and Bastuck, Niklas and Becker, Jonathan and Imholz, Nadine and Kr{\"a}nzlin, Tobias and Lim, Tian Yi and L{\"o}tscher, Michael and Schwarzenbach, Luca and others},
  journal={Journal of Field Robotics},
  year={2024},
  publisher={Wiley Online Library}
}

[A Comparison of Modern General-Purpose Visual SLAM Approaches](https://arxiv.org/pdf/2107.07589)

README.md Format, reference to [winter-2024-final-project-team-7](https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-7?tab=readme-ov-file#slam-simultaneous-localization-and-mapping)

# Contacts
Aaron Kim - 
Marco Krause - 
Andrew Vo - 
Giovanni Torres - 
