---
title: "CSCI8920 Fundamentals of Robotics (Spring 2023)"
collection: teaching
type: Graduate course
permalink: /teaching/2023-spring-teaching-2
venue: UNO
date: Jan 23, 2023 - May 19, 2023
time: MW 4:30PM - 5:45PM
location: Remote Learning
---

This course will cover the fundamentals of robotics and application of artificial intelligence techniques to robotics. Topics include, but not limited to, probabilistic inference, learning theory, modeling development, perception, planning, and search algorithms, localization, tracking and basic control, and  programming the robotic system. These techniques will be simulated in a programming infrastructure, the Robot Operating System (ROS), which enables efficient integration of independently developed subsystems into a single system, enabling autonomous robot operation. ROS offers an environment for developing modular control software, a communication infrastructure to connect the software components and an open source library of implemented algorithms. In the scope of this course, we shall cover the practical development of software modules in the ROS environment and integrate the techniques in artificial intelligence into a completely functional system for robot control.

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Wednesday 5:45 - 7:00 PM via Zoom or by appointment
* Class Info: MW 4:30PM - 5:45PM, Remote Learning
* [Course Schedule](#schedule)  
 

## Prerequisites:    
CSCI 3320 Data Structures AND any course equivalent to this course. CSCI 4500 Operating Systems AND any course equivalent to this course. CSCI 4450 Introduction to Artificial Intelligence AND any course equivalent to this course. Basic Python or C++ programming knowledge is recommended. You can take these courses in the same semester. However, if you have not taken these courses before or any concerns, you will need to contact the instructor of the course for approval.

## Suggested preparatory courses:
Math/STAT 4450/8456 Introduction to Machine Learning and Data Mining; Knowledge of Python and C++, and familiar with Linux operating system , and GitHub for version control.

## Recommended Textbooks
* [Robot Operating System (ROS) website](http://wiki.ros.org/)
* Joseph, L. (2018). Learning Robotics using Python: Design, simulate, program, and prototype an autonomous mobile robot using ROS, OpenCV, PCL, and Python. Packt Publishing Ltd.
This will be used as a reference, rather than as a textbook, but we will use quite a few methods from it, and it is a valuable addition to your professional library.

### Supplemental materials

* Martinez, Aaron, and Enrique Fernández. Learning ROS for robotics programming. Packt Publishing Ltd, 2013.
* Quigley, M., Gerkey, B., & Smart, W. D. (2015). Programming Robots with ROS: a practical introduction to the Robot Operating System. " O'Reilly Media, Inc.".
* Corke, P. (2017). Robotics, vision and control: fundamental algorithms in MATLAB® second, completely revised (Vol. 118). Springer.

## Get Odin account
You need to apply for an account at Odin: IS&T Core Linux Server to download our programming assignments. More details are shown below:
[https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php](https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php). Please email to UNO IST support (Email: uno-ist-support at unomaha dot edu) if you have any questions about Odin. <span style="color:red"> **Please get one asap. Don't wait until the last-minute, always finish ahead of deadlines. ** </span>

## Grading

* Programming Assignments: 50%
* Group Project: 20%
* Group Report and Presentation: 30%
* Canvas Discussion/Class Participation: ~5%

If you have questions regarding the grading of programming assignments, group project and report and presentation, you MUST email or come to see the instructor WITHIN ONE WEEK after the date your assignments have been returned to you.


### Grading Type
Letter grades will be determined using the weighted average of the various items used to evaluate students. A typical grade mapping is illustrated below.

|Points        	| Grade |
|:-----------------|:----------|
|97 – 100%| A+	|
|93 – 96%  | A             	|
|90 – 92%  | A-	|
|87 – 89%  | B+	|
|83 – 86%  | B             	|
|80 – 82%  | B-	|
|77 – 79%  | C+	|
|73 – 76%  | C 	|
|70 – 72%  | C-	|
|67 – 69%  | D+	|
|63 – 66%  | D 	|
|60 – 62%  | D-	|
|0 – 59%    | F             	|

### Late Policy
Programming Assignments and Projects are subject to late penalty. Here is the point deduction policy: <span style="color:red"> **20% deduction (late by 1 day), 40% deduction (late by 2 days), 80% deduction (late by 3 days), and no credit if late by more than three days.** </span>

Contact the instructor in case of a medical emergency, and a written proof from your doctor is required. <span style="color:red"> **You are allowed to extend one more day after the approval.** </span>

## Academic Integrity
You may discuss the homeworks and assignments with anyone and use any reference materials, but provided you do not copy any other person's work. We will follow the University Policy on Academic Integrity regarding any cheating and plagiarism. Take the time to familiarize yourself with the contents of this page, as you are responsible for its contents.

## Accommodations
Reasonable accommodations are provided for students who are registered with Accessibility Services Center (ASC) and make their requests sufficiently in advance. For more information, contact ASC (Location: 104 H&K, Phone: 402.554.2872, Email: [unoaccessibility@unomaha.edu](unoaccessibility@unomaha.edu)


---------------------------------------------------------------------------------------------------------------
# Schedule
This schedule, and the links contained in it, are subject to change during the semester. <!---Exam dates, however, are final.-->
<!--- Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the schedule day.-->

|        	|	Date   |           	Topic                  	| Assignment <!--- <br>(to be completed before class) --> |
|:--------:|:------------|:-------------------------------------|:----------------------------------------------|
|  Mon   |   Jan. 23  |  [Introduction & Themes]  |  Reading: [Building Machines That Learn and Think Like People](https://arxiv.org/abs/1604.00289), Brenden M. Lake, Tomer D. Ullman, Joshua B. Tenenbaum, Samuel J. Gershman (2016) |
|  Wed   |  Jan. 25  |  [Robot Mechanisms]  |   Reading: [Robot Mechanisms notes]	|
|  Mon   |  Jan. 30  |   [Robot Mechanisms]  |   Reading: Ch1      	|
| Wed	| Feb. 1   |  [Getting_Started_with_ROS] | [Project Announcement] <br> Reading: [Simulation and Numerical Methods notes]     |
|  Mon   |   Feb. 6   |   [Getting_Started_with_PyBullet]  |  Reading: ch2 <br> <a href="" style="color: blue">Program 1 Available</a>  	|
|  Wed   |   Feb. 8   |   [Robot Simulation]   |   Reading: ch3 <br>	<span style="color:red"> **Project Proposal (the title, project description, motivation, the references)** <span style="color:black"> (1 page submission each team) |
|  Mon   |   Feb. 13   |	[Introduction to ROS Basic Commands]     |   Reading: Ch4, [Core ROS Tutorials](http://wiki.ros.org/ROS/Tutorials): Beginner Level |
|  Wed   |   Feb. 15 |   [Introduction to ROS Build System]    | Reading: [Core ROS Tutorials](http://wiki.ros.org/ROS/Tutorials): Beginner Level   |
|  Mon   |  Feb. 20 |   [Introduction to ROS Build System]   | Reading: [Core ROS Tutorials](http://wiki.ros.org/ROS/Tutorials): Beginner Level  <br>  <span style="color:red"> **Program 1 Due, 11:59pm**</span> 	|
|  Wed   | Feb. 22  |   [Introduction to ROS Publishers and subscribers]	  | Reading: [Core ROS Tutorials](http://wiki.ros.org/ROS/Tutorials): Beginner Level <br> <a href="" style="color: blue">Program 2 Available</a>	|
|  Mon   | Feb. 27  |	[Introduction to ROS Publishers and subscribers]  | <span style="color:red"> **[Project Checkpoint 1]** <span style="color:black"> (at least 2 pages submission each team; please follow IEEE format.) <br> Reading: ch4 <br>  [Gazebo Tutorials](http://gazebosim.org/tutorials)   |
 |  Wed   | Mar. 1 |	[Sensing and Perception in Simulation]	| **[Project Checkpoint 1]** <span style="color:black"> (3 mins presentation) <br> Reading: ch4 <br>  [Gazebo Tutorials](http://gazebosim.org/tutorials) |
|  Mon   |  Mar. 6   |  [Sensing and Perception in Simulation]  |    |
|  Wed   |  Mar. 8  |  [Sensing and Perception in Simulation]  |  Reading: ch5, [Gazebo Tutorials Intermediate](http://gazebosim.org/tutorials?cat=guided_i&tut=guided_i1)	|
|  Mon   |  Mar. 13  |  	Spring Vacation (Student Holiday) - No class   |        	|
| Wed	|  Mar. 15  | 	Spring Vacation (Student Holiday) - No class   |         	|
|  Mon   |  Mar. 20  |   [Sensing and Perception in Simulation II] |  <span style="color:red"> **Program 2 Due, 11:59pm**</span>  <br> <a href="" style="color: blue">Program 3 Available</a> <br> Reading: ch5, [Gazebo Tutorials Intermediate](http://gazebosim.org/tutorials?cat=guided_i&tut=guided_i1) |
|  Wed   |  Mar. 22  |	[Sensing and Perception in Simulation II]   | <span style="color:red"> **[Project Checkpoint 2]** <span style="color:black"> (at least 2 pages submission each team) <br> Reading: [Gazebo Tutorials Intermediate](http://gazebosim.org/tutorials?cat=guided_i&tut=guided_i1), [URDF Tutorials](http://wiki.ros.org/urdf/Tutorials)   | 
|  Mon   |   Mar. 27    |  [Sensing and Perception in Simulation II]  |  Reading: [URDF Tutorials](http://wiki.ros.org/urdf/Tutorials), [Using a URDF in Gazebo](http://wiki.ros.org/urdf/Tutorials/Using%20a%20URDF%20in%20Gazebo)   |
|  Wed   |  Mar. 29     |   [Plan Planning: Representation and Fundamentals]    |  <span style="color:red"> **Program 3 Due at 11:59pm** </span> <br> Reading: ch8 | 
|  Mon   |  Apr. 3        |  [Plan Planning: Representation and Fundamentals]   |  <a href="" style="color: blue">Program 4 Available</a>  	|
| Wed	|  Apr. 5         |  	[Auto-Navigation Planner]	| Reading: Ch.8, [ROS Navigation Tutorials](http://wiki.ros.org/navigation) <br>  <a href="">Program 3 Available</a>    	|
|  Mon   |   Apr. 10 	|	[Auto-Navigation Planner]  	| <span style="color:red"> **[Project Checkpoint 3]** <span style="color:black"> (at least 2 pages submission each team) <br> Reading: Ch.7    	|
| Wed	|   Apr. 12	| 	[OpenCV + ROS]  | Reading: [OpenCV tutorials](https://docs.opencv.org/2.4/doc/tutorials/tutorials.html)           	|
| Mon	|  Apr. 17 	| 	[Learning-Based Robotics]	|  <span style="color:red"> **Program 4 Due at 11:59pm** </span> <br> Reading: [Reinforcement Learning in Robotics: A Survey](https://www.ias.informatik.tu-darmstadt.de/uploads/Publications/Kober_IJRR_2013.pdf). Jens Kober, J. Andrew Bagnell, Jan Peters (2013), [Recent Advances in Robot Learning from Demonstration](https://www.annualreviews.org/doi/full/10.1146/annurev-control-100819-063206). Harish Ravichandar, Athanasios S. Polydoros, Sonia Chernova, Aude Billard (2020)|
|  Wed   |  Apr. 19 	|	[Learning-Based Robotics] 	|  Reading: [Soft Actor-Critic Algorithms and Applications](https://arxiv.org/abs/1812.05905). Tuomas Haarnoja, Aurick Zhou, Kristian Hartikainen, George Tucker, Sehoon Ha, Jie Tan, Vikash Kumar, Henry Zhu, Abhishek Gupta, Pieter Abbeel, Sergey Levine (2018), [Continuous Control with Deep Reinforcement Learning](https://arxiv.org/abs/1509.02971). Timothy P. Lillicrap, Jonathan J. Hunt, Alexander Pritzel, Nicolas Heess, Tom Erez, Yuval Tassa, David Silver, Daan Wierstra (2015)  |
|  Mon   |  Apr. 24 	|    [Reinforcement learning]   |  Reading: [Reinforcement learning: A survey](https://www.jair.org/index.php/jair/article/view/10166). Kaelbling, Leslie Pack, Michael L. Littman, and Andrew W. Moore, Journal of artificial intelligence research 4 (1996): 237-285, [Reinforcement learning in robotics: A survey](https://journals.sagepub.com/doi/pdf/10.1177/0278364913495721?casa_token=hdd-aYNuAg4AAAAA:gaxwu9icywzk_4HMI9bLPEdD_ihrU_uu3sCQRdELuZ-OdeiZGN3vXbpNOrTrX9kYwicJ-5Qos2w), The International Journal of Robotics Research 32, no. 11 (2013): 1238-1274.   |
|  Wed   |  Apr. 26 	|   [Reinforcement learning]    | Reading: [Reinforcement learning: A survey](https://www.jair.org/index.php/jair/article/view/10166). Kaelbling, Leslie Pack, Michael L. Littman, and Andrew W. Moore, Journal of artificial intelligence research 4 (1996): 237-285, [Reinforcement learning in robotics: A survey](https://journals.sagepub.com/doi/pdf/10.1177/0278364913495721?casa_token=hdd-aYNuAg4AAAAA:gaxwu9icywzk_4HMI9bLPEdD_ihrU_uu3sCQRdELuZ-OdeiZGN3vXbpNOrTrX9kYwicJ-5Qos2w), The International Journal of Robotics Research 32, no. 11 (2013): 1238-1274	 <br>	<span style="color:red"> **[Project Checkpoint 4]** <span style="color:black"> (at least 2 pages submission each team)   |
| Mon  |  May 1 	|	Presentation  	|             	|
| Wed  |  May 3  |	Presentation   |    |
| Mon  | May 8   | Presentation   |      	       |
| Tues. | May 9  |   Report and Demo Due | [Report Template](https://www.ieee.org/conferences/publishing/templates.html) <br> Report and Demo Due 11:59pm <br> Submission: 1) A report, 2) Presentation slides, 3) Presentation video, and 4) Demo video. |


