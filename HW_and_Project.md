---
layout: page
title: Homework & Project 
description: Course Homework and Project.
---

<!-- ## Table of contents -->
{: .no_toc .text-delta }

1. TOC
{:toc}
{:.no_toc}
---


# Homework

<br>

**Assignment 1**
- <span style="color: #e94c4c; font-weight: normal;">Due Sep. 30</span>    <span style="float: right;"> 📄 [Download](https://rpai-lab.github.io/EE211-25Fall/assets/hw/Assignment_1.pdf) </span>
<br>

**Assignment 2**
- <span style="color: #e94c4c; font-weight: normal;">Due Nov. 11</span>    <span style="float: right;"> 📄 [Download](https://rpai-lab.github.io/EE211-25Fall/assets/hw/Assignment_2.pdf) </span>
<br>

---

# Final Project



**Project Description & Grading**

The project requires autonomous completion of navigation obstacle avoidance, pick & place, and visual detection tasks
Each group has three attempts in the final, which is to be conducted in the final week of the course.

<img src="https://rpai-lab.github.io/EE211-25Fall/assets/images/proj_description_pic1.png" alt="map illustration" style="zoom:25%;" />


### Pick & Place <span style="float: right;">45 points</span>
> Pick the targer object, then place it onto the target area

- Pick target object from a fixed position, then place.  		<span style="float: right; color: #7253ed;">35 points</span>
- Pick target object from a random position in an area, then place.  		<span style="float: right; color: #7253ed;">+ 5 points</span>
- Pick target object without `aruco` for object localization  				<span style="float: right; color: #7253ed;">+5 points</span>
<br>

### Navigation <span style="float: right;">40 points</span>
> Navigate autonomously across the given map

- Navigate on a map with fixed obstacles 				<span style="float: right; color: #7253ed;">30 points</span>
- Navigate on a map with random placed obstacles  				<span style="float: right; color: #7253ed;">+ 5 points</span>
- Implement your own planner for navigation  					<span style="float: right; color: #7253ed;">+ 5 points</span>


### Detection <span style="float: right;">15 points</span>
> Stop when the red light is detected, continue when the green light is detected, stop when the stop sign is detected

- Able to detect traffic lights and stop signs via camera    				<span style="float: right; color: #7253ed;">10 points</span>
- Able to detect traffic lights and stop signs during navigation  				<span style="float: right; color: #7253ed;">+ 5 points</span>


<!-- 1. Move from the starting point to the "stop" marker. Stop in place when the camera captures this sign, move on after the sign was removed (15 points). -->
<!--  -->
<!-- 2. Navigate to the Pick area and pick up the target cube (35 points). -->
<!--  -->
<!-- 3. Navigate to the traffic light place. Stop in place when the red light turnes on, move on once the green light turned on (15 points). -->
<!--  -->
<!-- 4. Navigate to the Place area and place the target cube here (15 points). -->
<!--  -->
<!-- 5. Navigate to the Park area, stays for 5 seconds (10 points). -->
<!--  -->
<!-- 6. Navigate back to the starting point (10 points). -->
<!--  -->
<!--  -->
<!-- ## Resources -->
<!--  -->
<!-- - [Manual for the robot we use](https://rpai-lab.github.io/EE211-25Fall/assets/project/robot_doc_for_25Fall_project) -->
<!-- [> - [Manual for the robot we use](http://127.0.0.1:4000/EE211-25Fall/assets/project/robot_doc_for_25Fall_project) <] -->
<!-- - [Remote connection to robot](https://rpai-lab.github.io/EE211-25Fall/assets/project/remote_connection) -->
<!-- - [A script that may help configuring developing environment on your robot](https://github.com/RPAI-Lab/EE211-25Fall/blob/25Fall/assets/project/configure_dev_env.sh) -->

<br>

---

<br>

