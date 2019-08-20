---
title: "CSCI4500 Operating Systems (Spring 2019)"
collection: teaching
type: Undergraduate course
permalink: /teaching/2019-fall-teaching-1
venue: UNO
date: 2019-08-26
location: 
---

An operating system is an abstraction of computer system hardware; it manages the sharing of various hardware and software resources among the users of the computer system. The parallel history of hardware and operating system development introduces many key concepts including, for example, processor modes, direct memory access (DMA), device controllers, and virtual memory. Basic approaches to kernel organization and implementation are considered. This is often the first course in which students encounter concurrency and concurrent programs. Additional topic areas include system performance evaluation (particularly relating to processor and memory management), security, virtualization, resource allocation and scheduling, and  file systems.

## Administrative Information
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
There will be four homeworks, three programming assignments, one midterm and one final.
The final course grade will be computed as follows:

* Homework and Quizzes: 15%
* Programming Assignments: 30%
* Midterm: 20%
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
Homeworks and Programming Assignments are subject to late penalty. Here is the point deduction policy: 20% deduction (late by 1 day), 40% deduction (late by 2days), 80% deduction (late by 3 days), and no credit if late by more than three days. 
<span style="color:red">some **This is Red Bold.** text</span>
Contact the instructor in case of medical emergency, and a written proof from your doctor is required.

## Academic Integrity
You may discuss the homeworks and assignments with anyone and use any reference materials, but provided you do not copy any other person's work. We will follow the University Policy on Academic Integrity regarding any cheating and plagiarism. Take the time to familiarize yourself with the contents of this page, as you are responsible for its contents.



-----------------------------------------------------------------------

# Schedule 
Readings from additional sources are linked from the schedule. All reading assignments are required and are expected to be completed before class on the schedule day.

| Date |           |               Topic                 | Assignment <br>(to be completed before class) |
|:----:|:----------|:------------------------------------|:----------------------------------------------|
| Tue  | Aug. 27   | [Introduction & Themes](https://drive.google.com/file/d/1LJZGwb4iwN0j61UWXRvGEUgvF1mr1nLa/view) |      |
| Thur | Aug. 29 | Introduction to Operating Systems & History           | Reading: ch 1.1 - 1.2 |
| Tue  | Sep. 3  | Basic Operating Systems Concepts - Part 1             | Reading: ch 1.3 - 1.4 |
| Thur | Sep. 5  | Basic Operating Systems Concepts - Part 1             | Reading: ch 1.4 - 1.5 |
| Tue  | Sep. 10 | Basic Operating Systems Concepts - Part 2             | Reading: ch 2.1 - 2.2       |
| Thur | Sep. 12 | Concurrency                                           | Reading: OSTEP [Lock](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf) (skip 28.8-28.11)|
| Tue  | Sep. 17 | Communication & Synchronization - Part 1              | Reading: OSTEP: [Common Concurrency <br> Problems, pages 1-11](pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf) (stop at "Deadlock   <br>   Avoidance via Scheduling") & OSTEP: [Monitors](pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf) |
| Thur | Sep. 19 | Communication & Synchronization - Part 1              | Reading: ch 2.3 <br> <span style="color:blue"> **Homework 1 Available** text</span>  <br>  <span style="color:green"> **Program 1 Available** text</span> |
| Tue  | Sep. 24 | Communication & Synchronization - Part 2              | Reading: ch.2.1       |
| Thur | Sep. 26 | Communication & Synchronization - Part 2              | Reading: Reading: ch.2.2 OSTEP [Lock](http://) (skip 28.8-28.11)|
| Tue  | Oct. 1  | Classic Task Communication - Part 1                   | Reading: ch.1.3 - 1.4 |
| Thur | Oct. 3  | Classic Task Communication - Part 2                   | Reading: ch.1.4 - 1.5 |
| Tue  | Oct. 8  | Classic Task Communication - Part 2                   | Reading: ch.1.3 - 1.4 |
| Thur | Oct. 10 | Deadlock                                              | Reading: ch.1.4 - 1.5 |
| Tue  | Oct. 15 | Deadlock                                              | Reading: ch.1.3 - 1.4 |
| Thur | Oct. 17 | Scheduling                                            | Reading: ch.1.4 - 1.5 |
| Tue  | Oct. 22 | Semester Break                                        | Reading: ch.1.3 - 1.4 |
| Thur | Oct. 24 | <font color="#dd0000"> Midterm </font><br />          | Reading: ch.1.3 - 1.4 |
| Tue  | Oct. 29 | Scheduling                                            | Reading: ch.1.3 - 1.4 |
| Thur | Oct. 31 | Memory Overview - Part I: Memory Partition and Relocation                | Reading: ch.1.4 - 1.5 |
| Tue  | Nov. 5  | Memory Overview - Part II: Techniques and Swapping                       | Reading: ch.1.3 - 1.4 |
| Thur | Nov. 7  | Virtual Memory - Part I: Mechanisms (Address Translation and Page Tables | Reading: ch.1.4 - 1.5 |
| Tue  | Nov. 12 | Virtual Memory - Part I: Mechanisms (Address Translation and Page Tables)| Reading: ch.1.3 - 1.4 |
| Thur | Nov. 14 | Virtual Memory - Part II: Policies (Page Replacement Algorithms)         | Reading: ch.1.4 - 1.5 |
| Tue  | Nov. 19 | Virtual Memory - Part II: Policies (Page Replacement Algorithms)         | Reading: ch.1.3 - 1.4 |
| Thur | Nov. 21 | Input/Output Hardware                                 | Reading: ch.1.4 - 1.5 |
| Tue  | Nov. 26 | Input/Output Software                                 | Reading: ch.1.3 - 1.4 |
| Thur | Nov. 28 | Thanksgiving Vacation                                 | Reading: ch.1.4 - 1.5 |
| Tue  | Dec. 3  | Conference                                            | Reading: ch.1.3 - 1.4 |
| Thur | Dec. 5  | Conference                                            | Reading: ch.1.3 - 1.4 |
| Tue  | Dec. 10 | Security                                              | Reading: ch.1.3 - 1.4 |
| Thur | Dec. 12 | Put It All Together & In class exam review            | Report Format <br> Report Due 11:59pm <br> Program 3 Due 11:59pm |
| Thur | Dec. 17 | [Final Exam](https://www.unomaha.edu/registrar/students/after-enrollment/final-exam.php#tt) TBD | 2:30pm-4:30pm |
