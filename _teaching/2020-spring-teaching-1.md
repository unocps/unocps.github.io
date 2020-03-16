---
title: "CSCI4500 Operating Systems (Spring 2020)"
collection: teaching
type: Undergraduate course
permalink: /teaching/2020-spring-teaching-1
venue: UNO
date: Jan 13, 2020 - May 08, 2020
time: TTH 12:00PM - 1:15PM
location: Peter Kiewit Institute 274

---

An operating system is an abstraction of computer system hardware; it manages the sharing of various hardware and software resources among the users of the computer system. The parallel history of hardware and operating system development introduces many key concepts including, for example, processor modes, direct memory access (DMA), device controllers, and virtual memory. Basic approaches to kernel organization and implementation are considered. This is often the first course in which students encounter concurrency and concurrent programs. Additional topic areas include system performance evaluation (particularly relating to processor and memory management), security, virtualization, resource allocation and scheduling, and  file systems.

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Wednesday 2:30 - 3:30 PM, PKI 174A Building or by appointment
* Class Info: TTH 12:00PM - 1:15PM, PKI 274 Building
* [Course Schedule](#schedule)      

## Prequisites:	
CSCI 3710 (Introduction to Digital Design and Computer Organization), CSCI 3320 (Data Structures), and MATH 1950 (Calculus I). CSCI 4350 (Computer Architecture) is recommended; open only to students in the School of Engineering and declared Computer Science minors.

## Recommended Textbook
Tanenbaum and Woodhull, Operating Systems: Design and Implementation (3rd edition), Prentice-Hall (2006)

### Supplemental materials
* The online book [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau (indicated by OSTEP; this book is available for purchase at the site above if you prefer a print copy)
* Operating System Concepts 9th Edition, by Abraham Silberschatz, Peter B. Galvin, and Greg Gagne.

## Grading
There will be six homeworks, three programming assignments, one midterm and one final.
The final course grade will be computed as follows:

* Homework and Quizzes: 16%
* Programming Assignments: 30%
* Midterm: 22%
* Final 32%

If you have questions regarding the grading of homework, programming assignments, midterms and final, you MUST come to see the instructor WITHIN ONE WEEK after the date your homework, programming assignments, or exams have been returned to you.

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

### Accommodations 
Reasonable accommodations are provided for students who are registered with Accessibility Services Center (ASC) and make their requests sufficiently in advance. For more information, contact ASC (Location: 104 H&K, Phone: 402.554.2872, Email: unoaccessibility@unomaha.edu)

---------------------------------------------------------------------------------------------------------------

# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the schedule day.

| Date |           |               Topic                 | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| Tue  | Jan. 14 | [Introduction & Themes](https://drive.google.com/file/d/1z4MxQtp75F2xu7-tTIWmQGHe4_VGt4sZ/view?usp=sharing)|                       | 
| Thur | Jan. 16 | [Introduction to Operating Systems & History](https://drive.google.com/file/d/1r7WNxaYdfaUjNryxELsYN7UnlUIIXWUN/view?usp=sharing)| Reading: ch.1.1 - 1.2 |
| Tue  | Jan. 21  | [Basic Operating Systems Concepts](https://drive.google.com/file/d/12avSu5nSzZnw0URonpE5EAiLlJhGwyRn/view?usp=sharing)| Reading: ch.1.3 - 1.4 |
| Thur | Jan. 23  | [Basic Operating Systems Concepts](https://drive.google.com/file/d/12avSu5nSzZnw0URonpE5EAiLlJhGwyRn/view?usp=sharing)   | Reading: ch.1.4 - 1.5 |
| Tue  | Jan. 28 | [Processes and File Systems](https://drive.google.com/file/d/1u9PDI84dMFSbit3ie_BT4lMJYR2Z6FVt/view?usp=sharing)   | Reading: ch.2.1  <br> <a href="https://drive.google.com/file/d/1Eiegb0mmqcxdHwyntymiADw3D3g-Lnt9/view?usp=sharing" style="color: blue"> Homework 1 Available</a>  |
| Thur | Jan. 30 | [Processes and File Systems](https://drive.google.com/file/d/1u9PDI84dMFSbit3ie_BT4lMJYR2Z6FVt/view?usp=sharing)   | Reading: OSTEP [Lock](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf) (skip 28.8-28.11) <br>  <a href="https://drive.google.com/file/d/1GPoElL5mT6n0Psft_MYcep_JdArB1VRH/view?usp=sharing" style="color: blue">Program 1 Available</a> |
| Tue  | Feb. 4 | [Concurrency](https://drive.google.com/file/d/1-MXunnb4MSH-XYhFOHvMJaV6-HTVrTmL/view?usp=sharing) | Reading: OSTEP: [Common Concurrency Problems, pages 1-11](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf) (stop at "Deadlock Avoidance via Scheduling") <br> <span style="color:red"> Homework 1 Due (Upload to Canvas) </span>  <br>  <a href="https://drive.google.com/file/d/1H9g2GmeFIGQGd67ctUrPU_XjliLOOZqz/view?usp=sharing" style="color: green">Homework 1 Solution</a> |
| Thur | Feb. 6 | [Communication & Synchronization - Part 1](https://drive.google.com/file/d/1MAIAuhTYBHN4KF0lIAO7bb-LIZnYQHQk/view?usp=sharing)    | Reading: OSTEP: [Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf) <br> <a href="https://drive.google.com/file/d/1C4SyhA4b86yVHlPePnqInes6KZYhmkwG/view?usp=sharing" style="color: blue">Homework 2 Available</a> |
| Tue  | Feb. 11 | [Communication & Synchronization - Part 1](https://drive.google.com/file/d/1MAIAuhTYBHN4KF0lIAO7bb-LIZnYQHQk/view?usp=sharing) | Reading: ch.2.2 |
| Thur | Feb. 13 | [Communication & Synchronization - Part 2](https://drive.google.com/file/d/1GO81i_ATQSG4KH08KXAYyO-UfwUw2-i5/view?usp=sharing) | Reading: ch.2.3 <br> <span style="color:red"> Homework 2 Due (Upload to Canvas) </span>  <br>  <a href="https://drive.google.com/file/d/1pteLzBxzOHuSf6U2FTYhmu8b4nVViz_6/view?usp=sharing" style="color: green">Homework 2 Solution</a> |
| Tue  | Feb. 18  | [Communication & Synchronization - Part 2](https://drive.google.com/file/d/1GO81i_ATQSG4KH08KXAYyO-UfwUw2-i5/view?usp=sharing) <br> [fork example](https://drive.google.com/file/d/1yIM3CdJNSCeWgZkRn4w0cc_oAwERchzH/view?usp=sharing) | Reading: ch.2.4, [The Multi-Level Feedback Queue](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf) |
| Thur | Feb. 20  | [Classic Task Communication - Part 1](https://drive.google.com/file/d/1odokSp9BMBrRWKsZhr7PKS4scs-Dy-7o/view?usp=sharing)  | Reading: ch.3.1  <br> <a href="https://drive.google.com/file/d/1c1-gj8jP0hZIz95KmMZ_eYmx0bJD-rAK/view?usp=sharing" style="color: blue">Homework 3 Available</a> |
| Tue  | Feb. 25  |  [Classic Task Communication - Part 1](https://drive.google.com/file/d/1odokSp9BMBrRWKsZhr7PKS4scs-Dy-7o/view?usp=sharing)    | Reading: ch.3.2 |
| Thur | Feb. 27 | [Classic Task Communication - Part 2](https://drive.google.com/file/d/1CRhF9Gzu5KFIL3DKZbmVXWY7q7WCT4aL/view?usp=sharing)    | Reading: ch.3.3 <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span> |
| Tue  | March 3 | [Scheduling](https://drive.google.com/file/d/1E4b5cSOFFzbhgI46qYTMIDLLxmHL7BNf/view?usp=sharing) | <a href="https://drive.google.com/file/d/17YTauXpvNMATYC5C5vDJt8mXd1X_7PDH/view?usp=sharing" style="color: blue">Program 2 Available</a>  <br>  <span style="color:red"> Homework 3 Due (Upload to Canvas)  </span>  <br>  <a href="https://drive.google.com/file/d/1URgyA0466LWEzfvKAtGcWoq3-SZbuMU8/view?usp=sharing" style="color: green">Homework 3 Solution</a>|
| Thur | March 5 | [Scheduling](https://drive.google.com/file/d/1E4b5cSOFFzbhgI46qYTMIDLLxmHL7BNf/view?usp=sharing) |  Reading: [CPU Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf) |
| Tue  | March 10 | <span style="color:red"> **Midterm** </span> | <!---[Review Notes](https://drive.google.com/file/d/1ck8nXZ-yrPi86NRrlHerbdLIEtxlYkWc/view?usp=sharing) <br>  --> <span style="color:red"> **12:00pm-1:15pm** </span> |
| Thur | March 12 |  [Deadlock](https://drive.google.com/file/d/12QKDruQugUNwVdaFbNBq894_EsdOg_Ra/view?usp=sharing)  | Reading: ch.4.1 |
| Tue  | March 17 | Spring Vacation  |   |
| Thur | March 19 | Spring Vacation  | Reading: OSTEP [Address Spaces](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)|
| Tue  | March 24  | Spring Vacation  | Reading: ch.4.2 |
| Thur | March 26  | Spring Vacation  | Reading: ch.4.3  <br> <a href="" style="color: blue">Homework 4 Available</a> |
| Tue  | March 31 |  [Memory Overview - Part I: Memory Partition and Relocation]<!---(https://drive.google.com/file/d/1TP6_lLILPJiaBFYuoP6FCaAlAWx8xVaz/view?usp=sharing) --> | Reading: ch.4.4  <br> <span style="color:red"> **Program 2 Due, 11:59pm**</span> |
| Thur | Apr. 2 | [Memory Overview - Part II: Techniques and Swapping]<!---(https://drive.google.com/file/d/1iN4dw1UbQtUxUcpnQZJ1mBZvmN9RukIv/view?usp=sharing) -->| Reading: ch.4.5 <br>  <a href=" ">Program 3 Available</a> 
<br> <span style="color:red"> Homework 4 Due (Upload to Canvas) </span> |
| Tue  | Apr. 7 |  [Virtual Memory - Part I: Mechanisms (Address Translation and Page Tables)]<!---(https://drive.google.com/file/d/1ak8YjWM22XT16cCNCvHTjkSxyAJzI5Ul/view?usp=sharing) -->     | Reading: ch.4.6 |
| Thur | Apr. 9 | [Virtual Memory - Part II: Policies (Page Replacement Algorithms)]<!---(https://drive.google.com/file/d/1SKbeNV2T-AgfnwqsdZzJeuJOEk2Oznd4/view?usp=sharing)   -->      | Reading: ch.5.1 |
| Tue  | Apr. 14 | [Input/Output Hardware]<!---(https://drive.google.com/file/d/1PagIcxeeZvnkJbK_qoQlBsyCYVe7qQAA/view?usp=sharing) -->     | Reading: ch.5.2 <br> <span style="color:red"> Homework 5 Due (Upload to Canvas) </span>  <br>  <a href=" " style="color: green">Homework 5 Solution</a>|
| Thur | Apr. 16 | [Input/Output Software]<!---(https://drive.google.com/file/d/1SbURC3lB5TYRmvmtEiJKdm9Dfufatljx/view?usp=sharing) -->                                | <a href=" " style="color: blue">Homework 6 Available</a> |
| Tue  | Apr. 21 | [Input/Output Software]<!---(https://drive.google.com/file/d/1SbURC3lB5TYRmvmtEiJKdm9Dfufatljx/view?usp=sharing) -->        | Reading: Distributed Systems for Fun and Profit, by Mikito Takada, [Chapter 2](http://book.mixu.net/distsys/abstractions.html), [Chapter 3](http://book.mixu.net/distsys/time.html), [The Google File System](https://ai.google/research/pubs/pub51) |
| Thur | Apr. 23 | [Security] <!---(https://drive.google.com/file/d/1Hs6S5NGaCTqa9GnO_Q7x3YUymVfGSCd3/view?usp=sharing) -->                          | Reading: ch.5.3 <br>  <span style="color:red"> Homework 6 Due (Upload to Canvas) </span>  <br>  <a href=" " style="color: green">Homework 6 Solution</a>|
| Tue  | Apr. 28 | [Put It All Together]<!---(https://drive.google.com/file/d/1Q2QlnlXHMPSGcowcq8UHWmEA6LmJbr9q/view?usp=sharing) & In class exam review   -->                              | Reading: ch.5.4 |
| Thur | Apr. 30 | Prep week | <span style="color:red"> **Program 3 Due, 11:59pm** </span> |
| Tue | May 5 | [Final Exam](https://www.unomaha.edu/registrar/students/after-enrollment/final-exam.php#tt2) | <span style="color:red"> **12:00pm-2:00pm** </span> |


