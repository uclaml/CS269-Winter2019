


## Overview

Deep learning has achieved great success in many applications such as image processing, speech recognition and Go games. However, the reason why deep learning is so powerful remains elusive. The goal of this course is to understand the successes of deep learning by studying and building the theoretical foundations of deep learning. Topics covered by this course include but are not limited to: expressive power of deep learning, optimization for deep learning, generalization performance of deep learning and robustness of deep learning. Instructor will give lectures on advanced topics of statistical learning theory. Students will present and discuss papers on the selected topics, and do a course project.

## Prerequisites
Two years of college mathematics, including calculus, linear algebra, probability and statistics, and the ability to write computer programs. CS 260 or an equivalent course.

## Logistics

<!--University of California, Los Angeles  -->

- Time: **Monday and Wednesday 4:00PM - 5:50PM**
- Location: **WG YOUNG Hall 4216**  
- Instructor: [Quanquan Gu](http://web.cs.ucla.edu/~qgu/) (Email: qgu at cs dot ucla dot edu)   
- Teaching Assistant: Xinzhu Bei (Email: xzbei at cs dot ucla dot edu)
- Office hours: 
    - The instructor's office hour is Thursday 1:30pm-2:30pm at Engineering VI 282. 
    - The TA's office hour is Monday 11:00am-1:00pm at Bolter Hall 3256S-F.
- Course Website: [https://uclaml.github.io/CS269-Winter2019](https://uclaml.github.io/CS269-Winter2019)
- Course Forum: [https://piazza.com/ucla/winter2019/cs269/home](https://piazza.com/ucla/winter2019/cs269/home)
(If you haven’t already, [sign up here](piazza.com/ucla/winter2019/cs269).)

## Recommended Textbook

There is no required textbook. The following are recommended textbooks:

1. [SSBD] Shai Shalev-Shwartz, and Shai Ben-David. Understanding machine learning: From theory to algorithms. Cambridge University Press, 2014. 
2. [MRT] Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar. Foundations of machine learning. MIT press, 2012. 
3. [GBCB] Ian Goodfellow, Yoshua Bengio, Aaron Courville, and Yoshua Bengio. Deep learning. Vol. 1. Cambridge: MIT press, 2016.
4. [ZLLS] Aston Zhang, Zack C. Lipton, Mu Li, Alex J. Smola, Dive into Deep Learning, 2018.

There are many other great statistical learning theory courses. To mention a few:

[Peter Bartlett's statistical learning theory course](https://people.eecs.berkeley.edu/~bartlett/courses/281b-sp08/)

[Sham Kakade's statistical learning theory course](http://stat.wharton.upenn.edu/~skakade/courses/stat928/)

[Maxim Raginsky's statistical learning theory course](http://maxim.ece.illinois.edu/teaching/SLT/)


## Grading Policy
 
Grades will be computed based on the following factors:

- Quiz 10%
- Lecture Note Scribing 10%
- Homework 30%
- Paper Presentation 20%
- Project 30%

## Schedule


| # | Date  | Topic  | scribed note | reading materials  | 
|----|----|----|----|----|
| | | **Part I: Statistical Learning Theory** | | |
| 1 | 1/7 | Introduction  | [lecture1](https://www.dropbox.com/s/c4bjs0uz8h0nmop/lecture1.pdf?dl=0) | Chapter 2 in MRT |
| 2 | 1/9 | Concentration Inequalities | [lecture2](https://www.dropbox.com/s/mtfravtpeznsbuk/lec02.pdf?dl=0)  | Appendix B in SSBD|
| 3 | 1/14 | Uniform Convergence | [lecture3](https://www.dropbox.com/s/fyhqr7pp1bv929m/lec03.pdf?dl=0)   | Chapter 26 in SSBD|
| 4 | 1/16 | Symmetrization and Rademacher Complexity | [lecture4](https://www.dropbox.com/s/t0xot0s20rszz7u/lec04.pdf?dl=0) | Chapter 26 in SSBD|
| 5 | 1/23 | Rademacher Complexity cont'd |[lecture5](https://www.dropbox.com/s/smqtp0r51hkj8bt/lec05.pdf?dl=0) | Chapter 26 in SSBD |
|  | 1/28 | Paper presentation | | |
|  | 1/30 | Paper presentation | | |
| 6 | 2/4 | Growth Function and VC Dimension |[lecture6](https://www.dropbox.com/s/4m7ser6jw8mhjt4/lec06.pdf?dl=0) | Chapter 3 in MRT |
| 7 | 2/6 | Sauer’s Lemma and Covering Number |[lecture7](https://www.dropbox.com/s/xgmhpuuw05i514l/lec07.pdf?dl=0) | Chapter 3 in MRT |
| 8 | 2/11 | Chaining and Dudley's Entropy Integral |[lecture8](https://www.dropbox.com/s/mzmi3o268d6uvl3/lecture8.pdf?dl=0) | |
| 9 | 2/13 | Generalization Bounds of DNNs I |[lecture9](https://www.dropbox.com/s/2yckn0zq7k5h53z/lecture9.pdf?dl=0) | |
| 10 | 2/20 | Generalization Bounds of DNNs II | [lecture10](https://www.dropbox.com/s/sdo72uhnytxwxs9/lecture10.pdf?dl=0) | |
| 11 | 2/27 | Paper presentation | | |
| 12 | 3/4 | Paper presentation | | |
| 13 | 3/6 | Paper presentation | | |
| 14 | 3/11 | Paper presentation | | |
| 15 | 3/13 | Paper presentation | | |

## Academic Integrity Policy

Students are encouraged to read the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/Individual-Student-Code) for Academic Integrity. 

## Quiz

There will be 5 in-class pop-up quiz for the purpose of reviewing the newly learned concepts. The quizzes are **closed book** and **closed notes**. No electronic aids or cheat sheets are allowed. 

## Lecture Note Scribing

Students are required to scribe one lecture note. The latex template for lecture note will be provided. The scribed lecture notes should be a zip file submitted on CCLE that compiles without errors, and it is due **4 days after the lecture**. This note will be graded. For example, if 2 students are assigned to scribe a given lecture, I expect to receive 2 separate notes. The individual notes are primarily for grading purposes (and also to make sure that each student scribes their own lecture notes), while the final version of the lecture note will be posted on the course website, after being proofread and edited by TA and/or the Instructor. 

## Homework

There will be 3 homework assignments during the semester as we cover the corresponding material. Homework consists of both mathematical derivation and algorithm analysis. **Homework is required to be written in Latex**. Latex homework template will be provided.
<!-- \noindent\textbf{Collaboration Policy:} Unless otherwise indicated, you may talk to other students about the homework problems but each student must hand in their own answers and write their own code in the programming part. You also must indicate on each homework with whom you collaborated and cite any other sources you use including
Internet sites. Students cannot use old solution sets for this class or solution manual to the textbook under any circumstances. -->

Homework assignments will be submitted through [Gradescope](https://www.gradescope.com/courses/35032). (If you didn't receive the invitation, email TA with your name, UID and account associated email address.) Login via the invite, and submit the homework assignments on time. Homework is worth full credit before the due date. It is worth zero credit after the due date.

## Paper Presentation

After each lecture, there will be a few recommended readings. Each student is required to select one paper from the list, and prepare a 25 minutes presentation for the class. One paper can only be presented by one student. Students are expected to prepare the slides by themselves, but the original authors' slides are allowed to be used with proper citation. 

Paper presentation sign up is due in the end of 3rd week of the semester. The paper presentation will start on the 5th week.

Both the instructor and other students will grade the presentation (no self-grading). You can check the detailed grading criteria on the [course syllabus](https://www.dropbox.com/s/arxjedzt8frmrkg/syllabus_CS269.pdf?dl=0).

<!-- The detailed grading criteria are as follows:
\begin{itemize}
\item Slides content was clearly visible and self-explainable (5 points)
\item Important messages of the paper were properly delivered (5 points)
\item The presentation was easy to follow 
\item Theory and proofs were  clearly explained (5 points)
%\item All students in the team well understood the paper
\item Presenter did not just read off the slides (5 points)
\item Perfect timing (5 points)
\item Able to well address audience’s questions (5 points)
\item I have learned something from this presentation and would like to read the paper in future (5 points)
\end{itemize} -->

## Project

Students are required to do a project in this class. The goal of the course project is to provide the students an opportunity to explore research directions in optimization or machine learning. Therefore, the project should be related to the course content. An expected project consists of 

- A novel and sound solution to an interesting problem
- Comprehensive literature review and discussion
- Thorough theoretical/experimental evaluation and comparisons with existing approaches

The best outcome of the project is a manuscript that is publishable in major machine learning conferences (COLT, ICML, NeurIPS, ICLR, AISTATS, UAI etc.) or journals (Journal of Machine Learning Research). **Students cannot use their own published work, or work under review by the end of winter quarter as the course project.**
Detailed instruction is available [here](https://www.dropbox.com/s/arxjedzt8frmrkg/syllabus_CS269.pdf?dl=0).

