# BIO 594-004: Using genomic techniques to examine the evolution of populations  

## Instructor: Dr. Jon Puritz, Biological Sciences
#### Office: CBLS 183
#### Office hours: Wed, Thu 10:00 am to 11:00 am
Feel free to come by during this time without an appointment, otherwise schedule a time with me via email
#### Email: jpuritz@uri.edu  Phone: 401-874-902
*I will do my best to respond promptly during business hours (M-F: 9-5)*

## Meeting Time and Location for Spring 2018
#### Wednesdays 1:00 pm to 3:50 pm
#### Woodward 312

## Course Description
The advent of next-generation sequencing (NGS) has rapidly transcended population genetics to population genomics. Sequencer outputs have expanded from kilobases to gigabases while becoming over 30,000 times less expensive. This allows population levels studies to use thousands of genetic markers across the entire genome, and to survey both neutral and adaptive loci. In this class, we will cover a variety of techniques including: restriction-site associated sequencing (RADseq), RNA sequencing and transcriptomics, exome capture, low-coverage whole genome sequencing, pooled sequencing, and methods designed to examine patterns of methylation across genomes.

Techniques will be focused on non-model organisms without reference genomes. Lectures will be focused on experimental design, technical limitations, and analytical objectives. Computer-based “laboratory sessions” will immediately follow the lecture and cover bioinformatics, especially initial data assessment and manipulation, and population genomic analyses using real and simulated data sets. Students are encouraged to bring their own data sets to the class, and the final curriculum will be tailored to class interests.

## Course Goals and Student Learning Outcomes
After completing this course, students should be able to:
* Effectively work in a command-line Linux environment
* Visualize and manipulate multiple next-generation sequencing data formats
* Use and apply the tools and analyses covered in class
* Knowledgeably filter data sets for statistical and bioinformatic artifacts
* Determine loci potentially under selection and estimate population genetic parameters with both neutral and putatively adaptive loci
* Produce a completely open and repeatable documentation of a complete population genomic analysis

## Readings
Readings will be selected from web based tutorials, package vignettes, software documentation, and the primary literature.  Readings will be assigned on a week by week basis.  

## Required Equipment
Students must bring their own laptop (Mac, Windows, or Linux) with the capability of SSHing into a linux server and a working installation of RStudio.  Please contact the instructor if you do not have a laptop available to use and/or requiring one is not a financial possibility

## Schedule
Updated 2/21/2018 and still subject to change

| Date | Topic | Reading Assignment|
|-----|------|----|
|1/24/18| Course Intro and Computer Setup and Testing| None|
|1/31/18| Unix Command Line| https://www.codecademy.com/learn/learn-the-command-line; https://devhints.io/bash
|2/7/18 | NGS Data Structures- Visualization and Manipulation|[Web Links](/Readings/Week%03%0(2:7:2018)/Readings.md)|
|2/14/18| RADseq: *De novo* assembly and read mapping|[Davey et al. 2010](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%204%20(2:14:2018)/Davey%20et%20al.%20-%202010%20-%20RADSeq%20next-generation%20population%20genetics.pdf), [2013](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%204%20(2:14:2018)/Davey%20et%20al._2013_Special%20features%20of%20RAD%20Sequencing%20data%20implications%20for%20genotyping.pdf); [Flanagan et al. 2017](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%204%20(2:14:2018)/Flanagan_et_al-2017-Molecular_Ecology_Resources.pdf); [Puritz et al. 2014](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%204%20(2:14:2018)/Puritz%20et%20al._2014_Demystifying%20the%20RAD%20fad.pdf)|
|2/21/18| RADseq: SNP Calling and Filtering|[Hodel et al. 2017](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%205%20(2:21:2018)/Hodel%202017.pdf); [O'Leary et al. Submitted](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%205%20(2:21:2018)/O'leary%20et%20al.%20Submitted.pdf); [Shafer et al. 2016](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%205%20(2:21:2018)/Shafer_et_al-2016-Methods_in_Ecology_and_Evolution.pdf)|
|2/28/18| Detecting Loci Under Selection||
|       |  Intro to Population Genomics|[Allendorf *et al.* 2010](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%202%20(1:31:2018)/Allendorf%2C%20Hohenlohe%2C%20Luikart_2010_Genomics%20and%20the%20future%20of%20conservation%20genetics.pdf); [Jones & Good 2015](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%202%20(1:31:2018)/Jones%2C%20Good_2015_Targeted%20capture%20in%20evolutionary%20and%20ecological%20genomics(2).pdf); [Matz 2017](https://github.com/jpuritz/BIO_594_2018/blob/master/Readings/Week%202%20(1:31:2018)/Matz_2017_Fantastic%20Beasts%20and%20How%20To%20Sequence%20Them%20Ecological%20Genomics%20for%20Obscure%20Model%20Organisms.pdf)|
|3/7/18| Analyzing Population Structure||
|3/14/18| SPRING BREAK!!! No class|No Readings|
|3/21/18| Exome Capture ||
|3/28/18| RNAseq ||
|4/4/18| Pool-seq and Low Coverage Whole Genome Sequencing
|4/11/18| Epigenetics and Methylation| Project Plans Due!
|4/18/18| Final Projects | No Readings|
|4/25/18| Final Projects | No Readings|

## Grading

### Class Participation (50%)
This class will be most effective when students come prepared for class (finished with assigned readings) and are ready to think critically about the day's topic.  You're highly encouraged to ask questions and share your opinions with the class
* Attendance (10 points)
  * You will receive one point per class attended with a maximum of 10 points out of the 13 class meetings.
  * Virtual attendance is allowed!
* Exercises (40 points)
  * Each class will have a "laboratory" section where each student will work through exercises at their own pace.  Each exercise must be completed and documented on Github by the next class to receive credit (four points per week).  

### Final Projects (50%)
The culmination of this course will be the completion of a final Population Genomics Project.  Each student must analyze a NGS data set from raw sequencing files to a completed population level analysis.  Students are encouraged to use their own data sets, but students can also use an actual data set of Dr. Puritz or a simulated data set.  Projects can be completed on a different computing system or may use software and packages not discussed in the course, but all analyses and results must be documented and repeatable.  

* Project Plan and Approval (10 points)
  * A detailed outline of the proposed data set and analyses must be submitted and approved by Dr. Puritz by 4/11/18
* Analysis (20 points)
  * All bioinformatic are properly completed
  * Appropriate population genomic analyses are utilized and properly completed
* Documentation (20 points)
  * All work must be fully documented and repeatable on the class Github account
  * This includes markdown style documentation and executable scripts for each analysis component


## Accommodations

Any student with a documented disability is welcome to contact me as early in the semester as possible so that we may arrange reasonable accommodations. As part of this process, please be in touch with Disability Services for Students Office at 330 Memorial Union, 401-874-2098 (http://www.uri.edu/disabilittddss/) or the Academic Skills Center, 239 Shepard Building, Alan Shawn Feinstein Providence Campus, 401-277-5221 
(http://web.uri.edu/ceps/academic-skills-center/). 

"Section 504 of the Rehabilitation act of 1973 and the Americans with Disabilities Act of 1990 require the University of Rhode Island to provide academic adjustments or the accommodations for students with documented disabilities. The student with a disability shall be responsible for self-identification to the Disability Services for Students in the Office of Student Life, providing appropriate documentation of disability, requesting accommodation in a timely manner, and follow-through regarding accommodations requested."  It is the student's responsibility to make arrangements for any special needs and the instructor's responsibility to accommodate them with the assistance of the Office of Disability Services for Students. More resources are available here: http://web.uri.edu/disability/

## Course Assistance
This is a challenging course. Success requires that you keep pace with the work, understand course concepts, and study effectively. The Academic Enhancement Center helps URI students succeed through three services: Academic Coaching, Tutoring, and The Writing Center. To learn more about any of these services, please visit web.uri.edu/aec or call 401-874- 2367 to speak with reception staff In Providence, the Academic Skills Center (ASC) is at 239 Shepard Building, (401) 277-5221. Hours are posted each semester at http://web.uri.edu/ceps/academic-skills-center/

## Conduct and Behavior
Students are expected to treat faculty and fellow classmates with dignity and respect.  Students are responsible for being familiar with and adhering to the published "Student Code of Conduct" which can be accessed in the University Student Handbook (http://web.uri.edu/studentconduct/student-handbook/).  If you must come in late, please do not disrupt the class.  Please turn off all cell phones, e-watches, or any electronic devices.

## Academic Honesty
Students are expected to be honest in all academic work. A student’s name on any written work, quiz or exam shall be regarded as assurance that the work is the result of the student’s own independent thought and study. Work should be stated in the student’s own words, properly attributed to its source.   Students have an obligation to know how to quote, paraphrase, summarize, cite and reference the work of others with integrity. The following are examples of academic dishonesty.

* Using material, directly or paraphrasing, from published sources (print or electronic) without appropriate citation

* Claiming disproportionate credit for work not done independently

* Unauthorized possession or access to exams

* Unauthorized communication during exams

* Unauthorized use of another’s work or preparing work for another student

* Taking an exam for another student

* Altering or attempting to alter grades

* The use of notes or electronic devices to gain an unauthorized advantage during exams

* Fabricating or falsifying facts, data or references

* Facilitating or aiding another’s academic dishonesty

* Submitting the same paper for more than one course without prior approval from the instructors.
