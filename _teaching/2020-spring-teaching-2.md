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

---------------------------------------------------------------------------------------------------------------

# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the schedule day.
| Date |           |               Topic                 | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| Tue  | Jan. 14 | [Introduction & Themes](https://drive.google.com/file/d/1Uga4Y1GsR2j5D2aiDyDRLvJJv7Tz1o68/view?usp=sharing) |  |
| Thur | Jan. 16 | [Hardware and Xinu](https://drive.google.com/file/d/1uqzWAwhv9ciOSE69hA-rmrwNm9CulMyH/view?usp=sharing)| Reading: ch.1 |
| Tue  | Jan. 21  | [Xinu on Intel Galileo User Manual, Xinu Setup Procedure] | Reading: ch.2 |
| Thur | Jan. 23  | [Organization of an Operating System]  | Reading: ch.3 |
| Tue  | Jan. 28  | [Organization of an Operating System]  | Reading: Ch.4  <br> <a href=" " style="color: blue"> Homework 1 Available</a>  |
| Thur | Jan. 30  | [Hardware Architecture and Runtime Systems]    | Reading: ch.5 <br>  <a href="" style="color: blue">Program 1 Available</a> |



| Tue  | Feb. 4 | [Concurrency]<!---(https://drive.google.com/file/d/1-MXunnb4MSH-XYhFOHvMJaV6-HTVrTmL/view?usp=sharing) -->               | Reading: OSTEP: [Common Concurrency Problems, pages 1-11](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf) (stop at "Deadlock Avoidance via Scheduling") <br> <span style="color:red"> Homework 1 Due, in Class </span>  <br>  <a href=" " style="color: green">Homework 1 Solution</a> |
| Thur | Feb. 6 | [Communication & Synchronization - Part 1]<!---(https://drive.google.com/file/d/1MAIAuhTYBHN4KF0lIAO7bb-LIZnYQHQk/view?usp=sharing) -->    | Reading: OSTEP: [Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf) <br> <a href=" " style="color: blue">Homework 2 Available</a> |
| Tue  | Feb. 11 | [Communication & Synchronization - Part 1]<!---(https://drive.google.com/file/d/1MAIAuhTYBHN4KF0lIAO7bb-LIZnYQHQk/view?usp=sharing) -->    | Reading: ch.2.2 |
| Thur | Feb. 13 | [Communication & Synchronization - Part 2]<!---(https://drive.google.com/file/d/1GO81i_ATQSG4KH08KXAYyO-UfwUw2-i5/view?usp=sharing) -->     | Reading: ch.2.3 <br> <span style="color:red"> Homework 2 Due, in Class </span>  <br>  <a href="" style="color: green">Homework 2 Solution</a> |
| Tue  | Feb. 18  | [Communication & Synchronization - Part 2]<!---(https://drive.google.com/file/d/1GO81i_ATQSG4KH08KXAYyO-UfwUw2-i5/view?usp=sharing) -->     | Reading: ch.2.4, [The Multi-Level Feedback Queue](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf) |
| Thur | Feb. 20  | [Classic Task Communication - Part 1]<!---(https://drive.google.com/file/d/1odokSp9BMBrRWKsZhr7PKS4scs-Dy-7o/view?usp=sharing)     -->     | Reading: ch.3.1 |
| Tue  | Feb. 25  |  [Classic Task Communication - Part 2]<!---(https://drive.google.com/file/d/1CRhF9Gzu5KFIL3DKZbmVXWY7q7WCT4aL/view?usp=sharing)  -->                   | Reading: ch.3.2 <br> <a href="  " style="color: blue">Homework 3 Available</a> |
| Thur | Feb. 27 | [Scheduling]<!---(https://drive.google.com/file/d/1E4b5cSOFFzbhgI46qYTMIDLLxmHL7BNf/view?usp=sharing)  -->      | Reading: ch.3.3 <br> |
| Tue  | March 3 | [Scheduling]<!---(https://drive.google.com/file/d/1E4b5cSOFFzbhgI46qYTMIDLLxmHL7BNf/view?usp=sharing)  -->  | <span style="color:red"> **Program 1 Due, 11:59pm**</span> <br> <span style="color:red"> Homework 3 Due, in Class </span>  <br>  <a href=" " style="color: green">Homework 3 Solution</a> |
| Thur | March 5 | [Deadlock]<!---(https://drive.google.com/file/d/12QKDruQugUNwVdaFbNBq894_EsdOg_Ra/view?usp=sharing) -->       |  Reading: [CPU Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf) <br> <a href=" " style="color: blue">Program 2 Available</a> |
| Tue  | March 10 | <span style="color:red"> **Midterm** </span> | [Review Notes]<!---(https://drive.google.com/file/d/1ck8nXZ-yrPi86NRrlHerbdLIEtxlYkWc/view?usp=sharing) --> <br> <span style="color:red"> **12:00pm-1:15pm** </span> |
| Thur | March 12 |  [Memory Overview - Part I: Memory Partition and Relocation]<!---(https://drive.google.com/file/d/1TP6_lLILPJiaBFYuoP6FCaAlAWx8xVaz/view?usp=sharing) -->  | Reading: ch.4.1 |
| Tue  | March 17 | [Memory Overview - Part I: Memory Partition and Relocation]<!---(https://drive.google.com/file/d/1TP6_lLILPJiaBFYuoP6FCaAlAWx8xVaz/view?usp=sharing) -->  |  <a href="" style="color: blue">Homework 4 Available</a> |
| Thur | March 19 |  [Memory Overview - Part II: Techniques and Swapping]<!---(https://drive.google.com/file/d/1iN4dw1UbQtUxUcpnQZJ1mBZvmN9RukIv/view?usp=sharing) -->     | Reading: OSTEP [Address Spaces](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)|
| Tue  | March 24  | Spring Vacation  | Reading: ch.4.2 |
| Thur | March 26  | Spring Vacation | Reading: ch.4.3  <br> <span style="color:red"> Homework 4 Due, in Class </span>  <br>  <a href=" " style="color: green">Homework 4 Solution</a>  |
| Tue  | March 31 | [Memory Overview - Part II: Techniques and Swapping]<!---(https://drive.google.com/file/d/1iN4dw1UbQtUxUcpnQZJ1mBZvmN9RukIv/view?usp=sharing) -->  | Reading: ch.4.4 |
| Thur | Apr. 2 | [Virtual Memory - Part I: Mechanisms (Address Translation and Page Tables)]<!---(https://drive.google.com/file/d/1ak8YjWM22XT16cCNCvHTjkSxyAJzI5Ul/view?usp=sharing) -->  | Reading: ch.4.5 <br>  <a href=" ">Program 3 Available</a> <br> <a href=" " style="color: blue">Homework 5 Available</a>   <br> <span style="color:red"> **Program 2 Due, 11:59pm**</span>|
| Tue  | Apr. 7 | [Virtual Memory - Part II: Policies (Page Replacement Algorithms)]<!---(https://drive.google.com/file/d/1SKbeNV2T-AgfnwqsdZzJeuJOEk2Oznd4/view?usp=sharing)   -->      | Reading: ch.4.6 |
| Thur | Apr. 9 | [Virtual Memory - Part II: Policies (Page Replacement Algorithms)]<!---(https://drive.google.com/file/d/1SKbeNV2T-AgfnwqsdZzJeuJOEk2Oznd4/view?usp=sharing)   -->      | Reading: ch.5.1 |
| Tue  | Apr. 14 | [Input/Output Hardware]<!---(https://drive.google.com/file/d/1PagIcxeeZvnkJbK_qoQlBsyCYVe7qQAA/view?usp=sharing) -->     | Reading: ch.5.2 <br> <span style="color:red"> Homework 5 Due, in Class </span>  <br>  <a href=" " style="color: green">Homework 5 Solution</a>|
| Thur | Apr. 16 | [Input/Output Software]<!---(https://drive.google.com/file/d/1SbURC3lB5TYRmvmtEiJKdm9Dfufatljx/view?usp=sharing) -->                                | <a href=" " style="color: blue">Homework 6 Available</a> |
| Tue  | Apr. 21 | [Input/Output Software]<!---(https://drive.google.com/file/d/1SbURC3lB5TYRmvmtEiJKdm9Dfufatljx/view?usp=sharing) -->        | Reading: Distributed Systems for Fun and Profit, by Mikito Takada, [Chapter 2](http://book.mixu.net/distsys/abstractions.html), [Chapter 3](http://book.mixu.net/distsys/time.html), [The Google File System](https://ai.google/research/pubs/pub51) |
| Thur | Apr. 23 | Project presentations       | Reading: ch.5.3 <br>  <span style="color:red"> Homework 6 Due, in Class </span>  <br>  <a href=" " style="color: green">Homework 6 Solution</a>|
| Tue  | Apr. 28 | Project presentations <!---(https://drive.google.com/file/d/1Q2QlnlXHMPSGcowcq8UHWmEA6LmJbr9q/view?usp=sharing) & In class exam review   -->                              | Reading: ch.5.4 |
| Thur | Apr. 30 | Project presentations| <span style="color:red"> **Program 3 Due, 11:59pm** </span> |
| Thur | May 5 | Oral Presentation| Group |

