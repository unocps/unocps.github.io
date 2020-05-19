---
title: "CSCI4500 Operating Systems (Summer 2020)"
collection: teaching
type: Undergraduate course
permalink: /teaching/2020-summer-teaching-1
venue: Remote Learning
date: May 18, 2020 - Jun 26, 2020
time: MW 5:30PM - 8:25PM
location: Zoom  
---

An operating system is an abstraction of computer system hardware; it manages the sharing of various hardware and software resources among the users of the computer system. The parallel history of hardware and operating system development introduces many key concepts including, for example, processor modes, direct memory access (DMA), device controllers, and virtual memory. Basic approaches to kernel organization and implementation are considered. This is often the first course in which students encounter concurrency and concurrent programs. Additional topic areas include system performance evaluation (particularly relating to processor and memory management), security, virtualization, resource allocation and scheduling, and  file systems.

# Course Information
* Venue: Remote Learning
* Date: May 18, 2020 - Jun 26, 2020
* Time: MW 5:30PM - 8:25PM
* Location: See the Canvas 

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Tuesday 8:30 - 9:30 PM or by appointment <!---, PKI 174A Building or by appointment * Class Info: TTH 12:00PM - 1:15PM, PKI 274 Building --> 
* [Course Schedule](#schedule)      

## Prerequisites:
CSCI 3710 (Introduction to Digital Design and Computer Organization), CSCI 3320 (Data Structures), and MATH 1950 (Calculus I). CSCI 4350 (Computer Architecture) is recommended; open only to students in the School of Engineering and declared Computer Science minors.

## Recommended Textbook
Tanenbaum and Woodhull, Operating Systems: Design and Implementation (3rd edition), Prentice-Hall (2006)

### Supplemental materials
* The online book [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau (indicated by OSTEP; this book is available for purchase at the site above if you prefer a print copy)
* Operating System Concepts 9th Edition, by Abraham Silberschatz, Peter B. Galvin, and Greg Gagne.

## Get Odin account
You need to apply for an account at Odin: IS&T Core Linux Server to finish your programs. More details are shown below:
[https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php](https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php)
<span style="color:red"> **Please get one asap. Don't wait until the last minute to meet deadlines!** </span>

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

Contact the instructor in case of medical emergency, and a written proof from your doctor is required. <span style="color:red"> **You are allowed to extend one more day after the approval.** </span>

## Academic Integrity
You may discuss the homeworks and assignments with anyone and use any reference materials, but provided you do not copy any other person's work. We will follow the University Policy on Academic Integrity regarding any cheating and plagiarism. Take the time to familiarize yourself with the contents of this page, as you are responsible for its contents.

### Accommodations 
Reasonable accommodations are provided for students who are registered with Accessibility Services Center (ASC) and make their requests sufficiently in advance. For more information, contact ASC (Location: 104 H&K, Phone: 402.554.2872, Email: [unoaccessibility@unomaha.edu](unoaccessibility@unomaha.edu)

---------------------------------------------------------------------------------------------------------------
# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the schedule day.

| Date |           |               Topic                 | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| Mon  | May 18 | [Introduction & Themes](https://drive.google.com/file/d/10KobOhtw5he9mbH6YK67y6dLe3YSPQjG/view?usp=sharing) <br> [Introduction to Operating Systems & History](https://drive.google.com/file/d/1r7WNxaYdfaUjNryxELsYN7UnlUIIXWUN/view?usp=sharing) |    Reading: ch.1.1 - 1.2  |
| Wed | May 20 |  [Basic Operating Systems Concepts](https://drive.google.com/file/d/12avSu5nSzZnw0URonpE5EAiLlJhGwyRn/view?usp=sharing)  | Reading: ch.1.3 - 1.5 <br> <a href="<!---https://drive.google.com/file/d/1Eiegb0mmqcxdHwyntymiADw3D3g-Lnt9/view?usp=sharing --> " style="color: blue"> Homework 1 Available</a> |
| Mon  | May 25 | [Processes and File Systems](https://drive.google.com/file/d/1u9PDI84dMFSbit3ie_BT4lMJYR2Z6FVt/view?usp=sharing)   | Reading: ch.2.1 <br> OSTEP [Lock](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf) (skip 28.8-28.11) <br>  <a href="<!--- https://drive.google.com/file/d/1GPoElL5mT6n0Psft_MYcep_JdArB1VRH/view?usp=sharing -->" style="color: blue">Program 1 Available</a>  |
| Wed  | May 27 | [Concurrency](https://drive.google.com/file/d/1-MXunnb4MSH-XYhFOHvMJaV6-HTVrTmL/view?usp=sharing) | Reading: OSTEP: [Common Concurrency Problems, pages 1-11](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf) (stop at "Deadlock Avoidance via Scheduling") <br>  <a href="<!---  https://drive.google.com/file/d/1H9g2GmeFIGQGd67ctUrPU_XjliLOOZqz/view?usp=sharing -->" style="color: red">Homework 1 Due & Solution</a> (Upload to the Canvas) <br> <a href="" style="color: blue">Homework 2 Available</a> |
| Mon  | Jane 1 | [Communication & Synchronization - Part 1](https://drive.google.com/file/d/1BshCOkYzbp9_88RSRpcXxilrtPbQdOS_/view?usp=sharing) | Reading: ch.2.2-2.3 <br> OSTEP: [Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf)  |
| Wed | Jane 3  | [Communication & Synchronization - Part 2](https://drive.google.com/file/d/1GO81i_ATQSG4KH08KXAYyO-UfwUw2-i5/view?usp=sharing)  |  [The Multi-Level Feedback Queue](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf) <br>  <a href="<!--- https://drive.google.com/file/d/1pteLzBxzOHuSf6U2FTYhmu8b4nVViz_6/view?usp=sharing --> " style="color: red">Homework 2 Due & Solution</a> (Upload to Canvas) <br> <a href="<!--- https://drive.google.com/file/d/1c1-gj8jP0hZIz95KmMZ_eYmx0bJD-rAK/view?usp=sharing --> " style="color: blue">Homework 3 Available</a> <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span> |
| Mon  | Jane 8  |  [Classic Task Communication - Part 1](https://drive.google.com/file/d/1odokSp9BMBrRWKsZhr7PKS4scs-Dy-7o/view?usp=sharing)    <br> [Classic Task Communication - Part 2](https://drive.google.com/file/d/1CRhF9Gzu5KFIL3DKZbmVXWY7q7WCT4aL/view?usp=sharing)  | Reading: ch.3.2-3.3 |
| Wed | Jane 10 | [Scheduling](https://drive.google.com/file/d/1E4b5cSOFFzbhgI46qYTMIDLLxmHL7BNf/view?usp=sharing) |  Reading: [CPU Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf) <br> <a href="<!--- https://drive.google.com/file/d/17YTauXpvNMATYC5C5vDJt8mXd1X_7PDH/view?usp=sharing -->" style="color: blue">Program 2 Available</a>  <br>  <a href="" style="color: green">Homework 3 Due & Solution</a> (Upload to Canvas) |
| Mon | Jane 15 | [Deadlock](https://drive.google.com/file/d/12QKDruQugUNwVdaFbNBq894_EsdOg_Ra/view?usp=sharing)   |  Reading: ch.4.1- 4-2 & OSTEP [Address Spaces](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf) 
<br> <a href=" <!--- https://drive.google.com/file/d/1b0Haq-nhmyPYoXJv_29vCZnQ0ZA84yN8/view?usp=sharing --> " style="color: blue">Homework 4 Available</a>  |