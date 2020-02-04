---
title: "CSCI8530 Advanced Operating Systems (Spring 2020)"
collection: teaching
type: Graduate course
permalink: /teaching/2020-spring-teaching-2
venue: UNO
date: Jan 13, 2020 - May 08, 2020
time: TTH 3:00PM - 4:15PM
location: Peter Kiewit Institute 274
---

The course introduces the design and structure of computer operating systems, and also considers advanced operating system topics and exposes students to recent developments in operating systems research. The course involves the concepts, principles, functionality, trade-offs, and implementation of systems that support concurrent processing. The individual components of an operating system (Xinu) will be examined in detail at the source code level, and students will be expected to complete various assignments on real hardware (Raspberry Pi 2B or 3B or Beagle Bone Black or Intel Galileo board. Others are NOT recommended.). At a minimum, you will need a board, a memory card, a USB-micro cable, and a USB-serial adapter. Some of these assignments will involve simple “follow the steps” activities, while others will require the design of new or modified system components and application programs. Lectures will closely follow the expected readings which are indicated in the class schedule on the class web pages. 

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Wednesday 2:30 - 3:30 PM, PKI 174A Building or by appointment
* Class Info: TTH 3:00PM - 4:15PM, PKI 274 Building
* [Course Schedule](#schedule)      

## Prequisites:	
This course assumes students have a good understanding of basic operating system principles similar to that provided by a traditional introductory undergraduate operating systems course. In particular, the major functions of an operating system should be familiar, as should the basic algorithms and techniques used to implement them. Concepts of concurrent programming, including processes, threads, and various mechanisms for interprocess communication should be familiar. It is expected that students will have familiarity with the API for a traditional UNIX/Linux operating system, including such things as input/output and process management. All of the programming for the course will be done using the C programming language. Familiarity with the concepts of assembly language for some machine is expected, although it is unlikely that any assembly language code will need to be written for the programming assignments.

## Recommended Textbook
The primary textbook: Operating System Design: The Xinu Approach (second edition) by Douglas Comer, 2015, CRC Press.

### Supplemental materials
* [Raspberry Pi](https://www.raspberrypi.org/)
* [Upgrading Embedded Xinu for the Raspberry Pi 3](http://reu.mscs.mu.edu/index.php/Upgrading_Embedded_Xinu_for_the_Multi-Core_Raspberry_Pi_3)
* The online book [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau
* Tanenbaum, A.S., 2009. Modern operating system. Pearson Education, Inc.
* Daniel, P. and Marco, C., 2007. Understanding the Linux kernel.
* Schimmel, C., 1994. UNIX systems for modern architectures: symmetric multiprocessing and caching for kernel programmers. Addison-Wesley.

## Grading

* Homework and Quizzes (Individual): 16%
* Programming Assignments (Teamwork, only 1 or 2 for each group): 27%
* Midterm: 22%
* Final (Teamwork, only 1 or 2 for each group): 35%


### Grading Type
 Letter grades will be determined using the weighted average of the various items used to evaluate students. A typical grade mapping is illustrated below.

|Points	   | Grade |
|:---------|:------|
|97 – 100% | A+    |
|93 – 96%  | A     |
|90 – 92%  | A-    |
|87 – 89%  | B+    |
|83 – 86%  | B     |
|80 – 82%  | B-    |
|77 – 79%  | C+    |
|73 – 76%  | C     |
|70 – 72%  | C-    |
|67 – 69%  | D+    |
|63 – 66%  | D     |
|60 – 62%  | D-    |
|0 – 59%   | F     |

## Late Policy
Homeworks and Programming Assignments are subject to late penalty. Here is the point deduction policy: <span style="color:red"> **20% deduction (late by 1 day), 40% deduction (late by 2days), 80% deduction (late by 3 days), and no credit if late by more than three days.** </span>

Contact the instructor in case of medical emergency, and a written proof from your doctor is required.

## Academic Integrity
You may discuss the homeworks and assignments with anyone and use any reference materials, but provided you do not copy any other person's work. We will follow the University Policy on Academic Integrity regarding any cheating and plagiarism. Take the time to familiarize yourself with the contents of this page, as you are responsible for its contents.

## Accommodations 
Reasonable accommodations are provided for students who are registered with Accessibility Services Center (ASC) and make their requests sufficiently in advance. For more information, contact ASC (Location: 104 H&K, Phone: 402.554.2872, Email: unoaccessibility@unomaha.edu)

---------------------------------------------------------------------------------------------------------------

# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the schedule day.

| Date |           |               Topic                 | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| Tue  | Jan. 14  | [Introduction & Themes](https://drive.google.com/file/d/1WcWtcpMVgTr0JCag4ExpLgFth8c_lZ6h/view?usp=sharing)|    |
| Thur | Jan. 16  | [Hardware and Xinu](https://drive.google.com/file/d/1KKELMFod6h72_rUdvs3H76QudORE7Q2V/view?usp=sharing)| Reading: ch.1 <br> [Announcement of Final Project](https://drive.google.com/file/d/1rgnYin7oGLA4n1fcQMXgR_N3tNGbPRUt/view?usp=sharing) |
| Tue  | Jan. 21  | [Xinu on Intel Galileo User Manual](https://drive.google.com/file/d/1gJlI3AoWDbBgFb5ZqsugrscmOU2Xcs7Y/view?usp=sharing) <br> [Xinu Setup Procedure](https://drive.google.com/file/d/1FQyCMn6bjh_5jko49ydTCSn_vjc-Lzqc/view?usp=sharing) | [Galileo System Receipt](https://drive.google.com/file/d/1jCtAfXEXYv17TyEpndDRWBzli0x7BoaC/view?usp=sharing) <br> Reading: ch.2  |
| Thur | Jan. 23  | [Organization of an Operating System](https://drive.google.com/file/d/1-oU5uTOMux7nOjIEFJCHyW0VHvxQXBL8/view?usp=sharing)  | Reading: ch.3 <br> <span style="color:red"> Submit Project Topics </span>  |
| Tue  | Jan. 28  | [Organization of an Operating System](https://drive.google.com/file/d/1-oU5uTOMux7nOjIEFJCHyW0VHvxQXBL8/view?usp=sharing)  | Reading: Ch.4  <br> <a href="https://drive.google.com/file/d/1Q7sWMA_OzFTwaKk9BeVQA6wGfXoCeD11/view?usp=sharing" style="color: blue"> Homework 1 Available</a>  |
| Thur | Jan. 30  | [Hardware Architecture and Runtime Systems](https://drive.google.com/file/d/1Q-Qcmd4bmKcNumAQgq2uDEL1tGf0Q8gm/view?usp=sharing) | Reading: ch.5 <br>  <a href="https://drive.google.com/file/d/1XTrXZQ0O-A5JPR9DlLA7k5_mzc8eTDb5/view?usp=sharing" style="color: blue">Program 1 Available</a> |
| Tue  | Feb. 4 | [Hardware Architecture and Runtime Systems](https://drive.google.com/file/d/1Q-Qcmd4bmKcNumAQgq2uDEL1tGf0Q8gm/view?usp=sharing) | Reading: ch.5 <br> <span style="color:red"> Homework 1 Due (upload to Canvas) </span>  <br>  <a href=" " style="color: green">Homework 1 Solution</a> |
| Thur | Feb. 6  | [Process Management](https://drive.google.com/file/d/1UgOuyvdqVbmrA_fFr8Ig9CgMbqN-cWlj/view?usp=sharing)   | Reading: ch.6 <br> <a href="https://drive.google.com/file/d/1sZ-qv1nHBWatOj0R1pv0vS98zmT2Os5r/view?usp=sharing" style="color: blue">Homework 2 Available</a> |
| Tue  | Feb. 11 | [Process Management](https://drive.google.com/file/d/1UgOuyvdqVbmrA_fFr8Ig9CgMbqN-cWlj/view?usp=sharing)   | Reading: ch.6 |
| Thur | Feb. 13 | [Process Coordination and Synchronization]  <br> <span style="color:red"> Project Progress Report </span>    | Reading: ch.7 |
| Tue  | Feb. 18  | [Process Coordination and Synchronization]    | Reading: ch.7 <br> <span style="color:red"> Homework 2 Due (upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 2 Solution</a> |
| Thur | Feb. 20  | [Inter-Process Communication]     | Reading: ch.8 |
| Tue  | Feb. 25  | [[Inter-Process Communication]    | Reading: ch.9  <br> <a href="  " style="color: blue">Homework 3 Available</a> |
| Thur | Feb. 27 | [Low-level Memory Management]      | Reading: ch.9,10 <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span> |
| Tue  | March 3 | [Low-level Memory Management]      | Reading: ch.10 <br> <a href=" " style="color: blue">Program 2 Available</a>  <br> <span style="color:red"> Homework 3 Due </span>  <br>  <a href=" " style="color: green">Homework 3 Solution</a> |
| Thur | March 5 | [High-level Memory Management]    |  Reading: ch.10, 11|
| Tue  | March 10 | <span style="color:red"> **Midterm** </span> | <span style="color:red"> **3:00pm-4:15pm** </span> |
| Thur | March 12 | [High-level Memory Management] <br> <span style="color:red"> Project Progress Report </span>  | Reading: ch.12, 13 |
| Tue  | March 17 | [Device Management]      |  Reading: ch.14, 15 <br> <a href="" style="color: blue">Homework 4 Available</a> |
| Thur | March 19 | [Clock and Timer Management]   | Reading: ch.16, 17|
| Tue  | March 24  | Spring Vacation  |    |
| Thur | March 26  | Spring Vacation | <span style="color:red"> Homework 4 Due </span>  <br>  <a href=" " style="color: green">Homework 4 Solution</a>  |
| Tue  | March 31  |  [High-level Synchronous Message Passing]  | Reading: ch.18 |
| Thur | Apr. 2 | [High-level Synchronous Message Passing] <br> <span style="color:red"> Project Progress Report </span> | Reading: ch.19 <br>  <a href=" ">Program 3 Available</a> <br> <a href=" " style="color: blue">Homework 5 Available</a>   <br> <span style="color:red"> **Program 2 Due, 11:59pm**</span>|
| Tue  | Apr. 7 | [Network and Protocol Implementation]      | Reading: ch.20 |
| Thur | Apr. 9 | [Network and Protocol Implementation]      | Reading: ch.20 |
| Tue  | Apr. 14 | [File Systems]     | <span style="color:red"> Homework 5 Due, in Class </span>  <br>  <a href=" " style="color: green">Homework 5 Solution</a>|
| Thur | Apr. 16 | Project presentations     |  Presentation List <br> Team 1, Team 2, Team 3 |
| Tue  | Apr. 21 | Project presentations     |  Presentation List <br> Team 4, Team 5, Team 6 |
| Thur | Apr. 23 | Project presentations     |  Presentation List <br> Team 7, Team 8, Team 9 |
| Tue  | Apr. 28 | Prep week                 |                                                |
| Thur | Apr. 30 | Prep week                 | <span style="color:red"> **Program 3 Due, 11:59pm** </span> |
| Sunday | May 3  | Report and Demo Due | [Report Template] <br> Report and Demo Due 11:59pm |

