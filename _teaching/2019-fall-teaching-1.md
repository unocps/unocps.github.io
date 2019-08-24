---
title: "CSCI4500 Operating Systems (Fall 2019)"
collection: teaching
type: Undergraduate course
permalink: /teaching/2019-fall-teaching-1
venue: UNO
date: 2019-08-26
location: 
---

An operating system is an abstraction of computer system hardware; it manages the sharing of various hardware and software resources among the users of the computer system. The parallel history of hardware and operating system development introduces many key concepts including, for example, processor modes, direct memory access (DMA), device controllers, and virtual memory. Basic approaches to kernel organization and implementation are considered. This is often the first course in which students encounter concurrency and concurrent programs. Additional topic areas include system performance evaluation (particularly relating to processor and memory management), security, virtualization, resource allocation and scheduling, and  file systems.

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Wednesday 3:00 - 4:00 PM, PKI 174A Building or by appointment
* Class Info: TTH 3:00PM - 4:15PM, Peter Kiewit Institute 155
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

---------------------------------------------------------------------------------------------------------------

# Schedule
This schedule, and the links contained in it, are subject to change during the semester. Exam dates, however, are final.
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the schedule day.

| Date |           |               Topic                 | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| Tue  | Aug. 27 | [Introduction & Themes](https://drive.google.com/)  |                       |
| Thur | Aug. 29 | Introduction to Operating Systems & History           | Reading: ch.1.1 - 1.2 |
| Tue  | Sep. 3  | Basic Operating Systems Concepts - Part 1             | Reading: ch.1.3 - 1.4 |
| Thur | Sep. 5  | Basic Operating Systems Concepts - Part 1             | Reading: ch.1.4 - 1.5 |
| Tue  | Sep. 10 | Basic Operating Systems Concepts - Part 2             | Reading: ch.2.1  <br> <span style="color:blue"> **Homework 1 Available** </span> |
| Thur | Sep. 12 | Concurrency                                           | Reading: OSTEP [Lock](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf) (skip 28.8-28.11) <br>  <span style="color:blue"> **Program 1 Available** </span> |
| Tue  | Sep. 17 | Communication & Synchronization - Part 1              | Reading: OSTEP: [Common Concurrency Problems, pages 1-11](pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf) (stop at "Deadlock Avoidance via Scheduling") <br>  <span style="color:red"> **Homework 1 Due, in Class** </span>  <br>  <span style="color:green"> **Homework 1 Solution** </span> |
| Thur | Sep. 19 | Communication & Synchronization - Part 1              | Reading: OSTEP: [Monitors](pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf) <br> <span style="color:blue"> **Homework 2 Available** </span> |
| Tue  | Sep. 24 | Communication & Synchronization - Part 2              | Reading: ch.2.2 |
| Thur | Sep. 26 | Communication & Synchronization - Part 2              | Reading: ch.2.3 <br> <span style="color:red"> **Homework 2 Due, in Class** </span>  <br>  <span style="color:green"> **Homework 2 Solution**</span> |
| Tue  | Oct. 1  | Classic Task Communication - Part 1                   | Reading: ch.2.4, [The Multi-Level Feedback Queue](pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf) |
| Thur | Oct. 3  | Classic Task Communication - Part 2                   | Reading: ch.3.1 <br> <span style="color:blue"> **Homework 3 Available** </span> |
| Tue  | Oct. 8  | Classic Task Communication - Part 2                   | Reading: ch.3.2 |
| Thur | Oct. 10 | Deadlock                                              | Reading: ch.3.3 <br> <span style="color:red"> **Homework 3 Due, in Class** </span>  <br>  <span style="color:green"> **Homework 3 Solution**</span> |
| Tue  | Oct. 15 | Scheduling                                            | Reading: [CPU Scheduling](pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf) <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span> <br>  <span style="color:blue"> **Program 2 Available** </span> |
| Thur | Oct. 17 | <span style="color:red"> **Midterm** </span> |   <span style="color:red"> **3:00pm-4:15pm** </span>   |
| Tue  | Oct. 22 | Semester Break | <span style="color:blue"> **Homework 4 Available** </span> |
| Thur | Oct. 24 | Semester Break | Reading: ch.3.4 |
| Tue  | Oct. 29 | Memory Overview - Part I: Memory Partition and Relocation               | Reading: ch.4.1 <br> <span style="color:red"> **Homework 4 Due, in Class** </span>  <br>  <span style="color:green"> **Homework 4 Solution**</span> |
| Thur | Oct. 31 | Memory Overview - Part I: Memory Partition and Relocation               | Reading: OSTEP [Address Spaces](pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)|
| Tue  | Nov. 5  | Memory Overview - Part II: Techniques and Swapping                       | Reading: ch.4.2 |
| Thur | Nov. 7  | Virtual Memory - Part I: Mechanisms (Address Translation and Page Tables | Reading: ch.4.3 |
| Tue  | Nov. 12 | Virtual Memory - Part I: Mechanisms (Address Translation and Page Tables)| Reading: ch.4.4 <br> <span style="color:blue"> **Homework 5 Available** </span> <br> <span style="color:red"> **Program 2 Due, 11:59pm**</span>|
| Thur | Nov. 14 | Virtual Memory - Part II: Policies (Page Replacement Algorithms)         | Reading: ch.4.5 <br>  <span style="color:blue"> **Program 3 Available** </span> |
| Tue  | Nov. 19 | Virtual Memory - Part II: Policies (Page Replacement Algorithms)         | Reading: ch.4.6 <br> <span style="color:red"> **Homework 5 Due, in Class** </span>  <br>  <span style="color:green"> **Homework 5 Solution**</span>  |
| Thur | Nov. 21 | Input/Output Hardware                                 | Reading: ch.5.1 |
| Tue  | Nov. 26 | Input/Output Software                                 | Reading: ch.5.2 |
| Thur | Nov. 28 | Thanksgiving Vacation                                 | <span style="color:blue"> **Homework 6 Available** </span> |
| Tue  | Dec. 3  | Conference                                            | Reading: Distributed Systems for Fun and Profit, by Mikito Takada, [Chapter 2](book.mixu.net/distsys/abstractions.html), [Chapter 3](book.mixu.net/distsys/time.html), [The Google File System](https://ai.google/research/pubs/pub51) |
| Thur | Dec. 5  | Conference                                            | Reading: ch.5.3 <br> <span style="color:red"> **Homework 6 Due** </span>  <br>  <span style="color:green"> **Homework 6 Solution**</span> |
| Tue  | Dec. 10 | Security                                              | Reading: ch.5.4 |
| Thur | Dec. 12 | Put It All Together & In class exam review            | <span style="color:red"> **Program 3 Due, 11:59pm** </span> |
| Thur | Dec. 17 | [Final Exam](https://www.unomaha.edu/registrar/students/after-enrollment/final-exam.php#tt) (TBD) | <span style="color:red"> **2:30pm-4:30pm** </span> |
