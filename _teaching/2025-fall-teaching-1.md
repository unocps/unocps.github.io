---
title: "CSCI4500 Operating Systems (Fall 2025)"
collection: teaching
type: Undergraduate course
permalink: /teaching/2025-fall-teaching-1
venue: UNO
date: Aug 25, 2025 - Dec 19, 2025
time: Anytime
location: Totally Online
---
An operating system is an abstraction of computer system hardware; it manages the sharing of various hardware and software resources among the users of the computer system. The parallel history of hardware and operating system development introduces many key concepts including, for example, processor modes, direct memory access (DMA), device controllers, and virtual memory. Basic approaches to kernel organization and implementation are considered. This is often the first course in which students encounter concurrency and concurrent programs. Additional topic areas include system performance evaluation (particularly relating to processor and memory management), security, virtualization, resource allocation and scheduling, and file systems.

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Wed 8AM - 9AM or 4:15pm - 5:15pm via Zoom by appointment
* CSCI4500-850: Students will learn from the recorded videos. (Location: Totally Online)

* [Course Schedule](#schedule)    

## Prerequisites:    
CSCI 3710 (Introduction to Digital Design and Computer Organization), CSCI 3320 (Data Structures), and MATH 1950 (Calculus I). CSCI 4350 (Computer Architecture) is recommended; open only to students in the School of Engineering and declared Computer Science minors.

## Recommended Textbook
Silberschatz, Abraham, Peter B. Galvin, and Greg Gagne. Operating System Concepts, 10e Abridged Print Companion. John Wiley & Sons, 2018.

### Supplemental materials
* The online book [Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/) by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau (indicated by OSTEP; this book is available for purchase at the site above if you prefer a print copy)
* Tanenbaum and Woodhull, Operating Systems: Design and Implementation (3rd edition), Prentice-Hall (2006)

## Get Odin account
You need to apply for an account at Odin: IS&T Core Linux Server to finish your programs. More details are shown below:
[https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php](https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php). Please email to UNO IST support (Email: uno-ist-support at unomaha dot edu) if you have any questions about Odin. <span style="color:red"> **Please get one asap. Don't wait until the last-minute, always finish ahead of deadlines. ** </span>

## Grading
If you have questions regarding the grading of homework, programming assignments, midterms and final, you MUST come to see the instructor WITHIN ONE WEEK after the date your homework, programming assignments, or exams have been returned to you.

### Grading Type
 Letter grades will be determined using the weighted average of the various items used to evaluate students. A typical grade mapping is illustrated below.

|Points   	| Grade |
|:---------|:------|
| 100% to 97% | A+	|
| <97% to 93%  | A 	|
| <93% to 90% | A-	|
| <90% to 87%  | B+	|
| <87% to 83%  | B 	|
| <83% to 80%  | B-	|
| <80% to 77%  | C+	|
| <77% to 73%  | C 	|
| <73% to 70%  | C-	|
| <70% to 67%  | D+	|
| <67% to 63%  | D 	|
| <63% to 60%  | D-	|
| <60% to 0%   | F 	|


## Late Policy
Homeworks and Programming Assignments are subject to late penalty. Here is the point deduction policy: <span style="color:red"> **20% deduction (late by 1 day), 40% deduction (late by 2 days), 80% deduction (late by 3 days), and no credit if late by more than three days.** </span>

Contact the instructor in case of a medical emergency, and a written proof from your doctor is required. <span style="color:red"> **You are allowed to extend one more day after the approval.** </span>

## Academic Integrity
You may discuss the homeworks and assignments with anyone and use any reference materials, but provided you do not copy any other person's work. We will follow [the University Policy](https://www.unomaha.edu/student-life/student-conduct-and-community-standards/policies/academic-integrity.php) on Academic Integrity regarding any cheating and plagiarism. Take the time to familiarize yourself with the contents of this page, as you are responsible for its contents.

### Accommodations
Reasonable accommodations are provided for students who are registered with Accessibility Services Center (ASC) and make their requests sufficiently in advance. For more information, contact ASC (Location: 104 H&K, Phone: 402.554.2872, Email: [unoaccessibility@unomaha.edu](unoaccessibility@unomaha.edu)


---------------------------------------------------------------------------------------------------------------
# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the scheduled day.


| Week |    	|           	Topic             	| Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| 1  |  Aug. 26  -   Aug.31  |   [Themes] &  [Introduction to Operating Systems & History]   	|                   	|
| 2  |  Sep. 1  -   Sep. 7   |   Labor Day <br> [Introduction to Operating Systems & History]         	| Reading: ch.1 |
| 3  |  Sep. 8   -   Sep. 14	|   [Operating Systems Structure]       	| Reading: ch.2  <br> <a href="" style="color:blue"> Homework 1 Available</a> |
| 4  |  Sep. 15  -   Sep. 21  |   [Operating Systems Structure] <br> [Processes]   	| Reading: ch.3 <br> <span style="color:red"> Homework 1 Due (Upload to Canvas) </span>   <br> <a href="" style="color:blue">Program 1 Available</a>  |
| 5  |  Sep. 22  -   Sep. 28  |	[Processes]   	|	Reading: ch.4 <br> OSTEP: [Common Concurrency Problems, pages 1-11](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf) (stop at "Deadlock Avoidance via Scheduling") |
| 6  |  Sep. 29  -   Oct. 5 |   [Threads & Concurrency]  <br> [CPU Scheduling]      	|	Reading:  ch.5 <br> <a href="" style="color: blue">Homework 2 Available</a>  <br>  [CPU Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf)  <br> [The Multilevel Feedback Queue](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf)   |
| 7  |  Oct. 6  -   Oct. 12  | [CPU Scheduling]   	|	Reading: ch.6	<br> <span style="color:red"> Homework 2 Due (Upload to Canvas) </span> <br> <a href="" style="color: blue">Homework 3 Available</a>   <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span>   <br>  <a href="" style="color: blue">Program 2 Available</a>   <br> OSTEP [Lock](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf)  (skip 28.8-28.11)  |
| 8  |  Oct. 13 - Oct. 19	|  [Process Synchronization]	| Reading: ch.7  <br>  <span style="color:red"> Homework 3 Due (Upload to Canvas)  </span> 	<br> OSTEP: [Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf)   |
| 9  |  Oct. 20 - Oct. 26  	|   Semester Break <br> <span style="color:red"> **Midterm** </span> |   Reading: <!---[Review Notes](https://drive.google.com/file/d/1ck8nXZ-yrPi86NRrlHerbdLIEtxlYkWc/view?usp=sharing) <br>  --> <span style="color:red"> Anytime, 90 mins </span>    	|
| 10  |  Oct. 27 - Oct. Nov. 2	|   [Synchronization Example]   | Reading: Ch.8 <br>	<a href="" style="color: blue">Homework 4 Available</a>  |
| 11  |   Nov. 3 - Nov. 9  	|  [Deadlocks] <br> [Main Memory]	|  Reading: ch.9   <br>  OSTEP [Address Spaces](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)   <br> 	<span style="color:red"> **Program 2 Due, 11:59pm**</span>   <br> <a href="" style="color:blue"> Program 3 Available</a>  	|
| 12  |   Nov. 10 - Nov. 16 	| [Main Memory]	<br> [Virtual Memory] 	| Reading: ch.10  <br> <span style="color:red"> Homework 4 Due (Upload to Canvas) </span>	<br> <a href="" style="color: blue">Homework 5 Available</a>  |
| 13  |   Nov. 17  - Nov. 23   | [Virtual Memory] | Reading: ch.11  <br>  Distributed Systems for Fun and Profit, by Mikito Takada, [Chapter 2](http://book.mixu.net/distsys/abstractions.html)  	|
| 14 |   Nov. 24 - Nov. 30   |  [Mass Storage Structure] <br>  Thanksgiving Vacation | Reading: ch.12  <br> <a href="" style="color: blue">Homework 6 Available</a>   <br> [The Google File System](https://ai.google/research/pubs/pub51)   <br> <span style="color:red"> Homework 5 Due (Upload to Canvas) </span> |
| 15  |  Dec. 1 - Dec. 7  |   [I/O Systems] <br> [Put It All Together]     	|   Reading: Ch.12  <br> [Chapter 3](http://book.mixu.net/distsys/time.html)  <br>  <span style="color:red"> Homework 6 Due (Upload to Canvas) <br>	<span style="color:red"> **Program 3 Due  at 11:59pm** </span> 	|
| 16 | Dec. 8 - Dec. 12  |  Prep Week - Study Days   | Reading: textbook, supplemental materials, and all slides |
| 17  | Dec 15  |   <span style="color:red"> [**Final Exam** ](https://www.unomaha.edu/registrar/students/after-enrollment/final-exam.php#tts2) </span> | Reading: textbook, supplemental materials, and all slides <br> <span style="color:red"> Anytime, 120 mins </span> |
