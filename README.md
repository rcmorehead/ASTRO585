ASTRO585
========

This is my repo for ASTRO 585 at Penn State Spring 2014


High-Performance Scientific Computing for Astrophysics
Astro 585, Spring 2014
Syllabus v0.41

Formal Course Name: Astro 585: Topics in Astronomy and Astrophysics, Section #001
Class Meetings: MW 11:15-12:05 in 538 Davey Lab (Note change of room!)
                            F      11:15-12:05 in 216 Osmond or 541 Davey Lab (check each week)
Instructor:  Eric Ford
Office: 428A Davey Lab 
Email: eford@psu.edu (prefered)
Phone: x3-5558
Office Hours: Thursdays 10:05-11:05am or by appointment
Website: http://www.personal.psu.edu/ebf11/teach/astro585/
Twitter: #PsuAstro585    Blog:  http://sites.psu.edu/astro585/

Scope and Spirit of the Course
High-Performance Scientific Computing for Astrophysics will combine lecture, class discussion and programming exercises to train students in the use of modern computing hardware and programming strategies for application to astronomy and astrophysics research.  Students will gain experience applying these practices during a class project (potentially in support of the student’s dissertation research).  It is intended for astronomy graduate students and is likely appropriate for graduate students in other physical sciences.  

This course can count toward the Penn State Graduate Minor in Computational Science.  It is complementary to Phys/Astro 587 Computational Physics/Astrophysics, the recent Astro 585 on Astrostatistics and Stat/IST 557 Data Mining.  The combination of these four course with the domain expertise from their Ph.D. program would provide students with an excellent introduction to “Data Science”.  

The primary goal is for students to improve their skills in scientific computing, including programming practices for achieving reproducible results and high-performance scientific computing with an eye towards scaling up to larger problems and “Big Data”.  To achieve this, students will develop a basic understanding of modern computer architectures, memory systems, programming languages and common programming patterns.  Exercises provide students with experience applying established programming practices (e.g., version control, coding standards, testing, debugging, profiling, documenting and reviewing code) and optimizing performance using multi-core processors, clusters, GPUs and (hopefully) cloud computing.  

All of these objectives may not be realized within the one-semester course, and we will adapt the scope and emphasis based on student interests and programming experience.  The version of the syllabus on the course website will be updated throughout the semester and supersede the printed version.  Students should check the website regularly for updates.



Course Topics
Overview of High Performance Computing, Scientific Computing, Data Science & Big Data; Types & Choices of Programming Languages; Floating Point Arithmetic; Best Practices for Scientific Programming; Version Control; Testing & Debugging; Benchmarking & Profiling; Documentation; Efficient Workflows & Reproducible Results; Modern Processor, Memory & Networking Architectures; Optimizing Code Performance; Parallel Programming Patterns for Modern Workstations, Clusters, Accelerators (e.g., GPUs, Intel Phi) & the Cloud (as time permits).

Textbooks & Other Readings
The two primary textbooks (available in paperback or electronic format) for this course are:
Writing Scientific Software: A Guide to Good Style (WSS)
by Suely Oliveira; Cambridge University Press; 1st edition (September 18, 2006)  ISBN-10: 0521858968 
and
Introduction to High Performance Computing for Scientists and Engineers  (IHPC4SE)
by Georg Hager & Gerhard Wellein; CRC Press; 1st edition (July 2, 2010)  ISBN-10: 143981192X 

There will also be supplementary and/or optional readings from free online sources, such as: 
Theory:
“Best Practices for Scientific Computing” (Wilson et al. 2012)
“What Every Programmer Should Know about Floating-Point Arithmetic” (Goldberg 1991) 
“What Every Programmer Should Know about Memory” (Drepper 2007)
Real Computing Made Real (Acton 2005)
Practice:
“The Julia Manual”
Julia Tutorial Source & Videos from MIT IAP 2013
Julia Overview from Cambridge Area Julia Users Network & Julia Tutorials from Forio
A Brief Tutorial for New Thrust Developers from Thrust Documentation
Easy GPU Parallelism with OpenAcc [also useful with Intel Phi] from Dr. Dobb’s Journal
Introduction to Parallel Programming [with GPUs & CUDA] at Udacity
Seminars from Penn State RCC Group

Prerequisites
The course will assume a basic familiarity with calculus, linear algebra and astronomy at the level of a typical incoming graduate student in the department of Astronomy & Astrophysics.  While examples and assignments will draw from astronomy, I do not anticipate that these would prevent students from other physical sciences from doing well in the course.  Of course, some thought may be required to figure out how concepts from the course could be applied to their own field of study.  

Entering Astronomy graduate students span a wide range in terms of level of experience with programming.  The intent is for all students to improve their programming skills.  Therefore, students entering with significant computing skills should aim to achieve more than students entering with minimal experience.  Astronomy graduate students who are not already familiar with using the Unix/Linux/OS X command line interface and/or with no programming experience are encouraged to take the course, but should be prepared to put in some extra effort early in the semester.  If you let me know about your background, I can suggest some resources to help you get started and/or schedule a time to meet with you to answer questions.  

Assessed Work
The assessed work for this course consists of homework assignments (50%) and a class project (50%).  There are no exams.  The class project will have several components and will be described in more detail below.  Early in the semester, homework assignments will be assigned once a week.  Later in the semester, homework assignments will become less frequent, since you will be working on your class project.  Assignment due dates will be announced at the time they are assigned.  Assignments are due at least an hour prior to class on the day they are due (typically Wednesdays).  If the University is closed on the day of a scheduled test (due to bad weather or any other reason), the assignment will be due one hour before the next class session.  Students should start assignments well before the due date, so they can resolve any technical difficulties well in advance of the deadline.  Since assignments will typically be discussed in class on the day they are due, credit will be given based on what is turned in prior to class.  In cases where turning in assignments on time is not practical due to illness, family emergency, or other university-approved excuse, assignments should still be completed and turned in, but those assignments will not be included when computing the course grade in an effort to be fair to all students.  If portions of the class project totalling more than 10% of course grade can not be completed before the course end date due to illness, family emergency, etc., then the student can elect to receive a “deferred grade” (DF) and to submit the remaining portions of the project no later than eight weeks after the course end date.  Students electing this option should be familiar with the PSU DF policies (http://handbook.psu.edu/content/deferred-grade).

In order to protect student privacy, all students need to choose a “code name”.  This code name needs to be used on all student course work.  Students should avoid including their name, ID number, email or other identifying information in the files they submit, file names, url names, username for the git repository or in the files in their code repositories.  Obviously, you'll need to inform the instructor of your code name, so you can receive credit for your assignments. 

Class Projects
The class project (worth a total of 50% of final grade) includes the following key elements:
a written proposal outlining your project (5%), 
implementing a solution to your problem that passes your tests and uses programming practices from class in time for the peer code review (10%), 
performing a helpful code review on a peer's project (5%), 
optimizing performance for a multi-core shared-memory system (i.e., modern workstation; 10%), 
optimizing performance using either a distributed memory system (e.g., RCC cluster), a many-core accelerator (e.g., GPU or Intel Phi), or on the cloud (e.g., Amazon Elastic Compute Cloud, MultyVac?) (10%), and 
a presentation to the class describing your project, documenting the performance of different versions of your code as a function of problem size and lessons learned (10%).  

Project Proposals
The instructor will suggest multiple ideas that could become the basis for a class project.  You may choose one of these or you may develop an independent proposal more closely related to your research interests.  If you choose to develop an independent proposal, then you should discuss it with the instructor far enough in advance of the deadline, that you can refine or change your plans prior to the proposal due date (Friday, February 21).  In either case, the written proposal should include the project goal, a description of the inputs, a description of the outputs, a plan for how you will test your code, a discussion of the relevant range of problem sizes, what computer architectures, programming languages, libraries and parallel programming patterns you will use, as well as an explanation of your choices.  More information about the expectations for class projects will be provided. 

Homework Assignments
Most assignments will not have a unique solution, and comparing the accuracy and/or performance of different solutions will likely prove educational.  Therefore, rather than providing “the solution”, we will typically discuss selected student solutions during class to help illustrate the advantages and disadvantages of different approaches.  

The homework assignments are designed to be educational.  The experience of working on the assignment is more valuable than having “the solution”.  As this is a three credit class, it is expected that students will devote an average of 5 hours per week to the course outside of class.  If we estimate an average of ~1 hour/week for reading, then that leaves ~4 hours per week to work on homework assignments or your class project outside of class.  If a student completes a homework assignment with less than ~3 hours of effort, then I would encourage them to go beyond the minimum to complete the assignment and try to come up with an even more efficient solution to the problem.  Conversely, if you have done the readings, participated in class and devoted 4 hours of focused effort outside of class to a homework assignment, then you should stop coding!  At that point, write up a description of what you've done, what's working, what problems you've encountered and what you think you would try next.  Don't let one homework assignment take an unreasonable amount of your time.  I will adjust the length and difficulty of the homework assignments based on what students turn in.  Since some students will have more programming experience than others, I will try to make each homework assignment a little more than the average student can do in 4 hours, so that all students are challenged.  If for some reason you choose to work longer on a homework assignment, then please indicate how far along you were after 4 hours of focused effort, so that I have an accurate idea of how much students are accomplishing in a reasonable amount of time.

Readings & Class Participation
Students are expected to read assignments before class on the days indicated, so they will be prepared to participate in class discussions and/or make progress writing code for the assignment.  All students, and particularly any who are reluctant to ask questions in class, are strongly encouraged to submit questions about the readings prior to class.  In-class discussions and coding sessions will be an important part of the course, so students should attend regularly.  If you know you need to miss class due to research travel, then let the instructor know in advance and make plans to get a classmate's notes for those sessions.  

My intention is for the homework portion of the class grade to be based solely on written assignments and code.  However, if I feel that some students could benefit from having a greater incentive to engage in class more actively, then up to 20% of the homework score (i.e., 10% of the course grade) may be based on class participation, as measured by contributing to in-class discussion and/or submitting questions in advance of class.  

Etiquette
Students are expected to be civil and considerate in class.  In particular, we want to create an environment where everyone feels comfortable asking questions and sharing imperfect code.  Students should refrain from any actions that distract their classmates,  instructor or the class.  For example, cell phones should be silenced and put away during class.  Apps and windows unrelated to the class should be closed throughout class.  

The Eberly College of Science has a Code of Mutual Respect and Cooperation.  This code embodies the values that we hope our faculty, staff, and students possess and will endorse to make The Eberly College of Science a place where every individual feels respected and valued, as well as challenged and rewarded.

All students are responsible for knowing and following all the rules and regulations for this course as set forth in the syllabus (including the details on the class web site) and what is announced in class.  In case of any ambiguity, ask the instructor to clarify.  

Ethics and Honorable Behavior
All Penn State, Eberly College of Science, and Astronomy Department policies regarding ethics and honorable behavior apply to this course. These can be found at:
http://www.psu.edu/ufs/policies/47-00.html#49-20
http://www.science.psu.edu/academic/Integrity/Policy.html
http://www.astro.psu.edu/deptinfo/Astropolicy.html

Unless otherwise instructed, you are expected to present your own work for homework assignments and the class project.  Students will be strongly encouraged to consult with each other as part of completing assignments.  A good rule of thumb is that you want to ask for help in planning what to do or figuring out what could be causing a problem, but when it comes time to implement those ideas, you should do it yourself.  When you work with a classmate to develop a plan, you should each implement it individually.  

Another good rule of thumb is that you should not copy and paste text or code for a homework assignment.  Any time you do (e.g., if you were to modify code from the Julia base or a package developed by a third party), you should clearly indicate in both the code and whatever you turn in for the assignment which parts are you own and which were borrowed.  That doesn't mean that you'll get credit for other people's work, but it will mean you've been upfront about what was your contribution.  If you're ever unsure whether something is ok, you should ask and include an explanation of the contributions of others in your code and whatever you turn in.

You will be encouraged to use “pair coding”.  When pair coding, you can choose to either: 1) have each student be the “driver” for their own assignment (probably best for class projects and some short questions on homework) or 2) swap between “driver” and “navigator” roles frequently within each question (or sub-question).  Any time you pair code, you should always indicate who you paired with for each task.  You may _not_ have one student be the driver for question 1, then swap and have another student be the driver for question 2, as that makes it likely that the “navigator” will not understand the solution as well as the “driver”.  

Even if you complete assignments individually, you are encouraged to compare your implementation's code, accuracy and performance to that of your classmates.  When you do that, submit both the version of your code before you did those comparisons and a final version that reflects changes you learned from doing those comparisons.  In the write up, summarize what changes you made, how much of a difference they made and what you learned from the experience.  

Computer Requirements
Students will need access to a computer with the Julia programming language tools.  The easiest way to install Julia on your personal computer is as part of JuliaStudio which is freely available from http://forio.com/julia/downloads/.  

ITS has installed this and other computing tools in the computer lab at 216 Osmond.  My hope is that we can meet in 216 Osmond during most of our regular Friday class sessions for integrating coding into class and to help each other on assignments and class projects.  If the Osmond computer lab does not serve our needs well, then we will revert to meeting in 541 Davey Lab.  Hopefully, enough students can bring laptops that we could still have coding sessions during class, but we'll reevaluate if/when we reach that point.  Regardless of the usefulness of the 216 Osmond lab, students will need access to a computer with Julia outside of class hours for completing the homework assignments and (in most cases) their class project.  While some assignments will require that you run your code on a high-end workstation (or multiple workstations), students should plan to develop code and test your work on your own laptop/workstation.  

For some assignments, students will need access to additional computing resources that are part of the Penn State Astronomy department network and/or the Research Computing and CyberInfrastructure Group (RCC).  If you do not already have an account on either system, then you should let the instructor know by the “Regular Add Deadline” (January 23).  
Optional assignments or possible directions for your class project are likely to use additional programming languages and libraries, such as C/C++, OpenMP, MPI, OpenAcc, Thrust, CUDA, BLAS and FFTW.  Be sure to at least read through assignments far enough in advance that you have time to identify a machine you're able to use that already has the tools you need installed and/or to install them yourself.  

Special Accommodations
Penn State welcomes students with disabilities into the University's educational programs. If you have a disability-related need for reasonable academic adjustments in this course, contact the Office for Disability Services (ODS) located in room 116 Boucke Building at 814-863-1807. For further information regarding ODS, please visit their World Wide Web site at www.equity.psu.edu/ods. Instructors should be notified as early in the semester as possible regarding the need for reasonable academic adjustments.




Tentative Class & Reading Schedule (read prior to class on day indicated)
Week 1: Course Overview, Programming Languages, Floating Point Arithmetic
Friday, Jan 17: Read Writing Scientific Software (WSS) Ch 2 (22pgs) 
Week 2: Priorities for Scientific Computing
Wed, Jan 22: Read WSS Ch 3. Priorities (6pg) & Ch 4 Famous Disasters (4pg)
Fri, Jan 24: HW #1 (Floating Point Arithmetic, Functions) Due
Week 3: Programming Best Practices 
Mon, Jan 27: Read Best Practices for Scientiﬁc Computing (11pg)
Wed, Jan 29: Read WSS Ch 7 (ok to skip 7.11) Software Design (29pg)
Fri, Jan 31: Read WSS Ch 17.2 Revision control Systems (2pg) & github tutorial (including “Fork a Repo”)
Fri, Jan 31: HW #2 (Assertions, Benchmarking, Plotting) Due
Week 4: Computer Architectures
Mon, Feb 3: Read WSS Ch 6 Computer Organization (12pg)
Wed, Feb 5: Read IHPC4SE Ch 1 Modern Processors (32pg)  [Guest discussion leader: David Hogg]  
Fri, Feb 7: HW #3 (Version control, Testing, Documentation, Disk I/O) Due
Week 5: Serial Optimization
Mon, Feb 10: Read IHPC4SE Ch 2 Serial Optimization (26pg)
Wed, Feb 12: Read: WSS Ch 17.3 Profiling (2pg) 
Fri, Feb 14: HW #4 (Performance Comparisons 1/2 : Profiling, Loops vs Vectorized vs Map) Due
Week 6:  Memory Systems
Mon, Feb 17: Read IHPC4SE Ch 3 (excl. 3.1.2, 3.6) Data Access Optimization (24pg)
Wed, Feb 19: Read: WSS Ch 14 Memory Allocation & Garbage Collection (13pg)
Fri, Feb 21:  Class Project Proposals Due (Do lab using pair coding)
Week 7:  Parallel Computing Concepts
Mon, Feb 24: Read IHPC4SE Ch 4 Parallel Computers (20pg)
Wed, Feb 26: Read IHPC4SE Ch 5 Basics of Parallelization (22pg)
Fri, Feb 28: HW #5 (Performance Comparisons 2/2:  Memory Access) Due
Week 8:  Shared-Memory Parallel Programming
Mon, March 3:  Read IHPC4SE Ch 6 Shared-memory Parallel Programming w/ OpenMP (22 pg)
Wed, March 5: Read IHPC4SE Ch 7.2 Efficient OpenMP Programming: Performance Pitfalls (15 pg)
Fri, March 7: HW #6 (Parallel Programming for Multi-Core, Shared-Memory System) Due
Week 9:  Spring Break
Week 10:  Distributed Memory Parallel Programming
Mon, March 17: Read IHPC4SE Ch 9 (excl. 9.2.5) Distributed Memory Parallel programming w/ MPI (29 pg)
Wed, March 19: Read IHPC4SE Ch 10 Efficient MPI Programming (29 pg) [Optional]
Wed, March 19: First Set of Project Code due (solves problem, passes test, serial, unoptimized)
Fri, March 21: Read IHPC4SE Ch 11.-11.1.2 Hybrid Parallelization w/ MPI and OpenMP (14 pg) [Optional]
Week 11: Accelerators, GPU Computing
Mon, March 24: Read Introduction to CUDA; README for Julia's CUDA package
Wed, March 26: Read Thrust Quick Start Guide
Fri, March 28: HW #7 (Parallel Programming for Distributed-Memory System) Due
Week 12:  GPU Computing, continued
Mon, March 31: Read TBD (TODO)
Wed, April 2:  Second Set of Project Code due (passes tests, optimized for multi-core shared-memory system)
Week 13:  Code Reviews, Workflows & Reproducible Results
Mon, April 7: Read WSS Ch 17.0-17.1 Make (4pg); BPSC Sec. 2; TBD? (TODO)
Wed, April 9: Third Set of Project Code due (passes tests, optimized for 2nd architecture, ready for code review)
Week 14:  Cloud Computing
Mon, April 14: Read TBD (TODO)
Wed, April 16: Peer Code Review due
Weeks 15: Student Presentations
Weeks 16: Student Presentations, continued
Mon, May 5:   All Class Projects Final Code & Supporting Documentation Due
