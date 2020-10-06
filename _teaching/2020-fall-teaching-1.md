---
title: "CSCI4500 Operating Systems (Fall 2020)"
collection: teaching
type: Undergraduate course
permalink: /teaching/2020-fall-teaching-1
venue: UNO
date: Aug 24, 2020 - Dec 18, 2020
time: TTH 3:00PM - 4:15PM or 4:30PM - 5:45PM
location: Remote Learning
---

An operating system is an abstraction of computer system hardware; it manages the sharing of various hardware and software resources among the users of the computer system. The parallel history of hardware and operating system development introduces many key concepts including, for example, processor modes, direct memory access (DMA), device controllers, and virtual memory. Basic approaches to kernel organization and implementation are considered. This is often the first course in which students encounter concurrency and concurrent programs. Additional topic areas include system performance evaluation (particularly relating to processor and memory management), security, virtualization, resource allocation and scheduling, and  file systems.

# Administrative Information
* Instructor: Pei-Chi Huang
* Email: phuang at unomaha dot edu
* Office Hour: Wednesday 9:00 - 10:00 AM via Zoom or by appointment
* Class Info: TTH 3:00PM - 4:15PM or 4:30PM - 6:00PM, Remote Learning
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
[https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php](https://www.unomaha.edu/college-of-information-science-and-technology/about/odin.php). Please email to UNO IST support (Email: uno-ist-support at unomaha dot edu) if you have any questions about Odin. <span style="color:red"> **Please get one asap. Don't wait until the last-minute, always finish ahead of deadlines. ** </span>

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

|Points       | Grade |
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
| Tue   |  Aug. 25 |   [Introduction & Themes](https://drive.google.com/file/d/1uud-mj63HNquaauuSsv_EyvlMzDgQYsL/view?usp=sharing)    |                       |
| Thur  |  Aug. 27 |   [Introduction to Operating Systems & History](https://drive.google.com/file/d/1r7WNxaYdfaUjNryxELsYN7UnlUIIXWUN/view?usp=sharing)   | Reading: ch.1.1 - 1.2 |
| Tue   |  Sep. 01  |   [Introduction to Operating Systems & History](https://drive.google.com/file/d/1r7WNxaYdfaUjNryxELsYN7UnlUIIXWUN/view?usp=sharing)   | Reading: ch.1.3 - 1.4 |
| Thur  |  Sep. 03  |   [Basic Operating Systems Concepts](https://drive.google.com/file/d/12avSu5nSzZnw0URonpE5EAiLlJhGwyRn/view?usp=sharing)    | Reading: ch.1.4 - 1.5 |
| Tue   |  Sep. 08 |    [Processes and File Systems](https://drive.google.com/file/d/1NZoLj-Ys9ZnxKTNKtfmS_ybAx8nHI5Kf/view?usp=sharing)     | Reading: ch.2.1  <br> <a href="https://drive.google.com/file/d/1cWHHJHVFfP-7OcS_atZsm5Py1i1OnVFb/view?usp=sharing" style="color: blue"> Homework 1 Available</a>  |
| Thur | Sep. 10 |   [Processes and File Systems](https://drive.google.com/file/d/1NZoLj-Ys9ZnxKTNKtfmS_ybAx8nHI5Kf/view?usp=sharing)    | Reading:  ch.2.2 <br> <a href="https://drive.google.com/file/d/1jzl-wmwoBH-btHeOYqH4C7oy2q3gIocQ/view?usp=sharing" style="color: blue">Program 1 Available</a> |
| Tue  | Sep. 15 |   [Redirection](https://drive.google.com/file/d/1sOOWfdEkat1ELzZ6mGfj1DZnSmnKgAIj/view?usp=sharing) <br> [Concurrency](https://drive.google.com/file/d/1-MXunnb4MSH-XYhFOHvMJaV6-HTVrTmL/view?usp=sharing)        | <span style="color:red"> Homework 1 Due (Upload to Canvas) </span>  <br>  <a href="https://drive.google.com/file/d/1hOTxpotR78frg5bI_hJtXeOp7tdv8T1X/view?usp=sharing" style="color: green">Homework 1 Solution</a> |
| Thur | Sep. 17 |   [Concurrency](https://drive.google.com/file/d/1-MXunnb4MSH-XYhFOHvMJaV6-HTVrTmL/view?usp=sharing)    | Reading: OSTEP: [Common Concurrency Problems, pages 1-11](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf) (stop at "Deadlock Avoidance via Scheduling") <br> <a href="https://drive.google.com/file/d/1W07P1EjDJOICB7d3R4W8w_2GKABjkEVr/view?usp=sharing" style="color: blue">Homework 2 Available</a> |
| Tue  | Sep. 22 |   [Communication & Synchronization - Part 1](https://drive.google.com/file/d/1uFz_GId5KN3mkCM3TaRl58dhSYg-9GFf/view?usp=sharing)   |   Reading: ch.2.3 <br> OSTEP [Lock](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf) (skip 28.8-28.11) |
| Thur | Sep. 24 |   [Communication & Synchronization - Part 1](https://drive.google.com/file/d/1uFz_GId5KN3mkCM3TaRl58dhSYg-9GFf/view?usp=sharing) | Reading: OSTEP: [Monitors](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-monitors.pdf) <br> <span style="color:red"> Homework 2 Due (Upload to Canvas) </span>  <br>  <a href="https://drive.google.com/file/d/1B6KuaQVXOAu6wpkhI_IybUO0IHj8b3_J/view?usp=sharing" style="color: green">Homework 2 Solution</a> |
| Tue  | Sep. 29  |  [Communication & Synchronization - Part 2](https://drive.google.com/file/d/1GO81i_ATQSG4KH08KXAYyO-UfwUw2-i5/view?usp=sharing)     | Reading: ch.2.4 <br> [The Multi-Level Feedback Queue](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-mlfq.pdf) |
| Thur | Oct. 01  | [Classic Task Communication - Part 1](https://drive.google.com/file/d/1odokSp9BMBrRWKsZhr7PKS4scs-Dy-7o/view?usp=sharing)  | Reading: ch.3.1  <br> <a href="https://drive.google.com/file/d/1LL7C7nBnkuDY0pEGYkomslRCm5qhIOTB/view?usp=sharing" style="color: blue">Homework 3 Available</a> |
| Tue  | Oct. 06  | [Classic Task Communication - Part 1](https://drive.google.com/file/d/1odokSp9BMBrRWKsZhr7PKS4scs-Dy-7o/view?usp=sharing)   | Reading: ch.3.2 |
| Thur | Oct. 08 | [Classic Task Communication - Part 2](https://drive.google.com/file/d/1CRhF9Gzu5KFIL3DKZbmVXWY7q7WCT4aL/view?usp=sharing)    | Reading: ch.3.3 <br> <span style="color:red"> **Program 1 Due, 11:59pm**</span> |
| Tue  | Oct. 13 | [Scheduling]    | <a href="" style="color: blue">Program 2 Available</a>  <br>  <span style="color:red"> Homework 3 Due (Upload to Canvas)  </span>  <br>  <a href="" style="color: green">Homework 3 Solution</a>|
| Thur | Oct. 15| [Scheduling] |  Reading: [CPU Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf) |
| Tue  | Oct. 20  | Semester Break (Student Holiday) - No classes  |  |
| Thur  | Oct. 22  | <span style="color:red"> **Midterm** </span> | <!---[Review Notes](https://drive.google.com/file/d/1ck8nXZ-yrPi86NRrlHerbdLIEtxlYkWc/view?usp=sharing) <br>  --> <span style="color:red"> **3:00pm-4:15pm or 4:30pm-6:00pm** </span> |
| Tue |  Oct. 27   |  [Deadlock]  | Reading: ch.4.1 |
| Thur  |  Oct. 29   |  [Deadlock]   | Reading: OSTEP [Address Spaces](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)|
| Tue  |  Nov. 03   |  [Memory Overview - Part I: Memory Partition and Relocation]   | Reading: ch.4.2 <br> <a href="" style="color: blue">Homework 4 Available</a>  |
| Thur |  Nov. 05 |   [Memory Overview - Part I: Memory Partition and Relocation] | Reading: ch.4.3 <br>  <span style="color:red"> **Program 2 Due, 11:59pm**</span> |
| Tue  |  Nov. 10   |  [Memory Overview - Part II: Techniques and Swapping]  | Reading: ch.4.4 <br> <a href="">Program 3 Available</a>|
| Thur |  Nov. 12  | [Memory Overview - Part II: Techniques and Swapping]    | Reading: ch.4.5  <br> <span style="color:red"> Homework 4 Due (Upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 4 Solution</a>  <br> <a href="" style="color: blue">Homework 5 Available</a> |
| Tue  | Nov. 17  |  [Virtual Memory - Part I: Mechanisms (Address Translation and Page Tables)] |  Reading: ch.5.1 |
| Thur | Nov. 19   |  [Virtual Memory - Part II: Policies (Page Replacement Algorithms)]     | Reading: ch.5.2 <br> <span style="color:red"> Homework 5 Due (Upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 5 Solution</a> <br> <a href="" style="color: blue">Homework 6 Available</a> |
| Tue  | Nov. 24 | [Input/Output Hardware]     | Reading: Distributed Systems for Fun and Profit, by Mikito Takada, [Chapter 2](http://book.mixu.net/distsys/abstractions.html)|
| Thur  | Nov. 26 | Student Holiday - No class  | Reading:  [Chapter 3](http://book.mixu.net/distsys/time.html), [The Google File System](https://ai.google/research/pubs/pub51)  |
| Tue | Dec. 01 | [Input/Output Software]   | Reading: ch.5.3   |
| Thur | Dec. 03 | [Security]  | Reading: ch.5.4 <br>  <span style="color:red"> Homework 6 Due (Upload to Canvas) </span>  <br>  <a href="" style="color: green">Homework 6 Solution</a>|
| Tue  | Dec. 8 |   [Put It All Together]   | Reading: ch.1-ch.5 and slides |
| Thur  | Dec.10 | Prep week  | Reading: ch.1-ch.5 and slides <br> <span style="color:red"> **Program 3 Due  at 11:59pm** </span>  |
| Tue or Thur | Dec.15 or Dec. 17 (TBD) | <span style="color:red"> **Final Exam (TBD)** </span> | Reading: Textbooks & all slides |
