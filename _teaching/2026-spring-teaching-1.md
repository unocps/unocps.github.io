---
title: "CSCI8530-001 Advanced Operating Systems (Spring 2026)"
collection: teaching
type: Graduate course
permalink: /teaching/2026-spring-teaching-1
venue: UNO
date: Jan. 12, 2026 - May 8, 2026
time: M 6PM - 8:40PM 
location: Peter Kiewit Institute 256
---

The course introduces the design and structure of computer operating systems and also considers advanced operating system topics and exposes students to recent developments in operating systems research. The course involves concepts, principles, functionality, trade-offs, and implementation of systems that support concurrent processing. The individual components of an operating system (Xinu) will be examined in detail at the source code level, and students will be expected to complete various assignments on real hardware (Intel Galileo board or Raspberry Pi 2B (or 3B) or BeagleBone Black. Others are NOT recommended.) or Oracle VM VirtualBox (if you cannot get this real hardware). At a minimum, you will need a board, a memory card, a USB-micro cable, and a USB-serial adapter. Some of these assignments will involve simple “follow the steps'' activities, while others will require the design of new or modified system components and application programs. Lectures will closely follow the expected readings which are indicated in the class schedule on the class web pages.

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Wednesday 12 - 2 PM via Zoom or by appointment
* Class Info: Students will attend twice a week in person (Location: Peter Kiewit Institute 256). Few day(s) may participate remotely synchronously learning if necessary. 
* [Course Schedule](#schedule)	 

## Prerequisites:    
This course assumes students have a good understanding of basic operating system principles similar to that provided by a traditional introductory undergraduate operating systems course. In particular, the major functions of an operating system should be familiar, as should the basic algorithms and techniques used to implement them. Concepts of concurrent programming, including processes, threads, and various mechanisms for interprocess communication should be familiar. It is expected that students will have familiarity with the API for a traditional UNIX/Linux operating system, including such things as input/output and process management. All the programming for the course will be done using the C programming language. Familiarity with the concepts of assembly language for some machines is expected, although it is unlikely that any assembly language code will need to be written for the programming assignments.

## Recommended Textbook
The primary textbook: Operating System Design: The Xinu Approach (second edition) by Douglas Comer, 2015, CRC Press.

### Supplemental materials
* [Raspberry Pi](https://www.raspberrypi.org/)
* [Upgrading Embedded Xinu for the Raspberry Pi 3](https://reu.cs.mu.edu/index.php/Upgrading_Embedded_Xinu_for_the_Multi-Core_Raspberry_Pi_3)
* The online book [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau
* Tanenbaum, A.S., 2009. Modern operating system. Pearson Education, Inc.
* Daniel, P. and Marco, C., 2007. Understanding the Linux kernel.
* Schimmel, C., 1994. UNIX systems for modern architectures: symmetric multiprocessing and caching for kernel programmers. Addison-Wesley.

## Grading

* Homework and Quizzes (Individual): 25%
* Programming Assignments (Teamwork, 1-3 for each group): 25%
* Discussion (Individual): 5%
* Midterm: 20%
* Final Project (Teamwork, 1-3 for each group): 25%

### Grading Type
Letter grades will be determined using the weighted average of the various items used to evaluate students. A typical grade mapping is illustrated below.

|Range 	  | Grade |
|:---------|:------|
| 100% to 97% | A+	|
| <97% to 94%  | A 	|
| <94% to 90% | A-	|
| <90% to 87%  | B+	|
| <87% to 84%  | B 	|
| <84% to 80%  | B-	|
| <80% to 77%  | C+	|
| <77% to 74%  | C 	|
| <74% to 70%  | C-	|
| <70% to 67%  | D+	|
| <67% to 64%  | D 	|
| <64% to 60%  | D-	|
| <60% to 0%   | F 	|

## Late Policy
Homeworks and Programming Assignments are subject to late penalty. Here is the point deduction policy: <span style="color:red"> **20% deduction (late by 1 day), 40% deduction (late by 2days), 80% deduction (late by 3 days), and no credit if late by more than three days.** </span>

Contact the instructor in case of a medical emergency, and written proof from your doctor is required. <span style="color:red"> **You are allowed to extend one more day after the approval.** </span>


## Academic Integrity
You may discuss the homeworks and assignments with anyone and use any reference materials but provided you do not copy any other person's work. We will follow [the University Policy on Academic Integrity](https://www.unomaha.edu/campus-policies/academic-integrity.php) regarding any cheating and plagiarism. Take the time to familiarize yourself with the contents of this page, as you are responsible for its contents.

## Accommodations
Reasonable accommodation is provided for students who are registered with Accessibility Services Center (ASC) and make their requests sufficiently in advance. For more information, contact ASC (Location: 104 H&K, Phone: 402.554.2872, Email: unoaccessibility@unomaha.edu)

---------------------------------------------------------------------------------------------------------------
# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the scheduled day.

| Week | 	 Dates     | 			  Topic   			  | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| 1  | Jan. 12  -   Jan. 18 |  [Introduction & Themes]  <br>  [Hardware and Xinu]  | Reading: ch.1 <br> [Announcement of Final Project] |
| 2  | Jan. 19  -   Jan. 25 | [Xinu on Intel Galileo User Manual] <br> [Xinu Setup Procedure] <br>  [Organization of an Operating System]  |  [Galileo System Receipt] <br> Reading: ch.2 & ch.3 <br> <a href="" style="color: blue"> Homework 1 Available</a>  |
| 3  | Jan. 26   -   Feb. 1 | [Organization of an Operating System] <br> [Hardware Architecture and Runtime Systems]   | Reading: ch.4 & ch.5  <br>  <span style="color:red"> **Project Topic Submission** <span style="color:black">  <br>  <a href="" style="color: blue">Program 1 Available</a> [stack_frame] <br> <span style="color:red"> Homework 1 Due (upload to Canvas) </span> <br>  <a href="" style="color: green">Homework 1 Solution</a>  |
| 4  | Feb. 2  -   Feb. 8 | [Hardware Architecture and Runtime Systems] | Reading: ch.5  & ch.6 <br> <a href="" style="color: blue">Homework 2 Available</a>|
| 5  | Feb. 9  -   Feb. 15 | [Process Management]   | Reading: ch.6 & ch.7 |
| 6 | Feb. 16  -   Feb. 22 | [Process Coordination and Synchronization] <br> <a href="" style="color: red">Project Progress Report</a> (at least 2 page section submission each team; Please follow the IEEE format.)	| Reading: ch.7 & ch.8 <br> <a href="" style="color: red">Project Progress Report</a> (3 mins presentation)  <br> <span style="color:red"> Homework 2 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 2 Solution</a>  |
| 7  | Feb. 23  -   Mar. 1 | [Process Coordination and Synchronization] <br> [Inter-Process Communication]   | Reading: ch.9 & ch.10 <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span> <br> <a href="" style="color: blue">Homework 3 Available</a> |
| 8  | Mar. 2 - Mar. 8 |  Spring Break  |
| 9  | Mar. 9 - Mar. 15 |  [Low-level Memory Management] <br> <span style="color:red"> **Project Progress Report** <span style="color:black"> (at least 2 page section submission each team)   | Reading: ch.10 & ch.11 & ch.12 <br> <a href="" style="color: blue">Program 2 Available</a>  <br> <span style="color:red"> Homework 3 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 3 Solution</a> |
| 10  | Mar. 16 – Mar. 22 |  [High-level Memory Management] | Reading: ch.12 & ch.13 <br> <a href="" style="color: blue">Homework 4 Available</a>  |
| 11 | Mar. 23 - Mar. 29 | [High-level Memory Management] <br> [Device Management]  |   Reading: ch.13 & ch.14 <br>  <span style="color:red"> Homework 4 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 4 Solution</a> |
| 12  | Mar. 30 - Apr. 5 | <span style="color:red"> **Midterm** </span> <br> [Device Management] |  Reading: ch.15 <br> <span style="color:red"> **Program 2 Due, 11:59pm**</span>  <br>  <a href="" style="color: blue">Homework 5 Available</a> <br> <a href="" style="color: blue">Program 3 Available</a>  |
| 13  | Apr. 6  - Apr. 12 |  [Clock and Timer Management]   | Reading: ch.14  & ch.15  |
| 14  | Apr. 13 - Apr. 19 |  [High-level Synchronous Message Passing] <br>  <span style="color:red"> **Project Progress Report** <span style="color:black"> (at least 2 page section submission each team) | Reading: ch.16 & ch.17 <br> <span style="color:red"> Homework 5 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 5 Solution</a>  |
| 15  | Apr. 20 - Apr. 26| Presentation | <span style="color:red"> **Program 3 Due, 11:59pm** </span> |
| 16 | May 1  | Final Report and Recorded Demo Due | [Report Template](https://www.ieee.org/conferences/publishing/templates.html) <br> Report and Demo Due 11:59pm <br> Submission: 1) A report, 2) Presentation slides, 3) Presentation video, and 4) Demo video. |


