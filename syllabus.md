# Syllabus Fall 2022


# GEOS 505: Research Computing in the Earth and Environmental Sciences


### Instructor:

Dr. Alejandro (Lejo) Flores (he/him)

Phone: (208) 426-2903

Office Hours: TBD

Email: lejoflores@boisestate.edu


### Teaching Assistant:

Stanley Akor 

Office Hours: TBD

Email: stanleyakor@u.boisestate.edu


### Course Description:

Prepares students for data- and computing-enabled research in the Earth and environmental sciences by equipping them with knowledge and skills to use computing platforms, programming languages, and practices common in contemporary research. Topics include the linux computing environment, version control using Git, and programming with Python and R. Exercises analyze data related to climate change, geomorphology, landscape ecology, remote sensing, and hydrology.


### Required Materials: 



* **<span style="text-decoration:underline;">Access to a computer that has a linux shell.</span>** Being a scientific computing class, access to computing resources is critical. Ideally, you have access to a laptop on which you can install the required computing tools (Python, JupyterLab, and git, ideally via a package manager like conda). I acknowledge, however, that as Graduate Students your ability to procure a laptop that you can bring to class may be limited. If you need help finding access to a laptop for class, please contact me as there are a number of ways I can help. Chromebooks are potentially an option, but you will need to use a cloud computing environment like Google Colab. Beginning with Windows 10, the Windows operating system can install a Linux shell via the Windows Subsystem for Linux. 
* **<span style="text-decoration:underline;">A subscription to medium.com to get unlimited access to articles.</span>** Medium is a publishing platform where articles from thousands of authors related to scientific programming can be found. Throughout the semester, you will be assigned articles containing tutorials, examples, and case studies. As of now, the cost of a subscription is $5/month or $50/year.
* **<span style="text-decoration:underline;">A text editor with syntax highlighting</span>** will be required when we begin exploring coding outside a Jupyter Notebook environment. There are a variety of free and open source options, as well as paid options that provide additional functionality and support. I advise against using an Integrated Development Environment (IDE) like Eclipse, Spyder, PyCharm, etc. Although these can help ease onboarding if you are used to Matlab or RStudio, until you have a good working knowledge of how IDEs link your operating system and python installation they can do more harm than good. 


### Recommended Computing Setup: 

If you have experience in installing scientific computing software, or feel confident enough to try, the following software is the minimum you will need at the outset of the class. New requirements may arise throughout the semester, but you will have built some capabilities to install them. This class is committed to using only open source software and open science principles. If you are new to scientific computing, do not worry about installing these now – I will schedule a few setup sessions outside of the normal class time to help you get set up. 



* `Python 3`. I highly recommend you install Python via Miniconda or Anaconda. I also highly recommend that you create a new conda environment specifically for the class.
    * Miniconda installers for Windows, Mac, and Linux devices can be found here: [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
    * Anaconda installers for Windows, Mac, and Linux devices can be found here: [https://docs.anaconda.com/anaconda/install/index.html](https://docs.anaconda.com/anaconda/install/index.html) 
* `Jupyter`. For interactive computing and programming via your web browser.
* `Numpy`. For numerical and mathematical computing.
* `Matplotlib`. For visualization and plotting results.
* `Scipy`. For some more advanced statistical analysis.
* `Pandas`. For data analysis, particularly time series analysis.
* `Geopandas`. For geospatial analysis.
* `xArray`. For analysis of multidimensional data, particularly model output and remote sensing data.


### Course Expectations


#### Course Structure

This class is divided into units, the first unit being approximately 5 weeks in duration and the second unit being approximately 10 weeks in duration. The units have different overarching goals and classes and assessments will be structured very differently. 

**<span style="text-decoration:underline;">Unit 1: Skill Building.</span>** The goal of this unit is to build and/or refine some basic competencies and proficiencies in the Python programming language, applied to analysis of Earth and environmental science data, that will be the foundation of the rest of the semester. During this unit there will be assigned readings and viewings to complete prior to class. Class will consist of narrated live coding sessions (similar to a Software Carpentry workshop) and individual and group problem-solving. You will be given and complete programming assignments in Jupyter Notebooks, commit them to a git repository, push them to a remote repository for the class on GitHub, and submit the URL of the completed assignment.  

**<span style="text-decoration:underline;">Unit 2: Class Climate Dashboard Project.</span>** The goal of this unit is to develop a minimum viable product (MVP) for a climate dashboard for Idaho. The dashboard will automatically generate a small suite of (perhaps interactive) plots that support identified stakeholder needs by: (1) automatically downloading NOAA Climate Forecast System data on a regular basis, (2) extracting a region corresponding to Idaho and the key variables required to support those visualizations, and (3) performs required data reduction and analysis to generate dashboard visualizations. To develop this dashboard we will learn and adopt practices of agile software development applied to a scientific computing application. Consistent with this approach, as a class we will:



* Conceptually design the dashboard’s workflow pipeline, 
* Identify teams to support developing the sub-elements of the dashboard, and
* Communicate across teams to manage integration. 

This 10 week unit will be subdivided into 5 “sprints” that are 2 weeks in duration each. A sprint is a period of time in the software development life cycle during which the development team identifies well-defined outcomes for the sprint, carries out activities to achieve these goals, and documents progress and problems encountered during the sprint. During each of these sprints, your team will complete and submit the following:



* **<span style="text-decoration:underline;">Sprint Planning Document:</span>** Records goals, assignments, and activities for the sprint, and
* **<span style="text-decoration:underline;">Sprint Closure Document:</span>** Records the activities carried out, spillover (things that were planned but not completed during the sprint), and identifies issues and risks to the broader project

As an individual, you will also complete a self-assessment at the end of each sprint that documents what activities you carried out, how they supported your goals for the semester, and provides evidence of your progress. These self-assessments are critical and will form the basis of your evaluation for the course. 


#### Attendance:



* Review Boise State University's attendance policy at https://www.boisestate.edu/registrar/home/registration/attendance-policy/
* Due to the nature of the class, merely completing reading materials and reviewing this GitHub repository is a poor substitute for engaged and active participation.
* Please note that absences reduce your potential for class participation, and therefore, may reduce that portion of your grade.
* Class starts on time. I make announcements, answer questions, and give reminders immediately at the beginning of class.


#### Outside of Class:



* You are expected to read all emails and announcements.
* The class reading/lecture/assignment/project schedule will be updated on this github repository. It is your responsibility to make sure you are staying up to date.
* Come prepared for class by reading assigned materials.
* If you need help, get it now! I am always willing to meet with you and go over questions or concerns. Do not wait until the end of the semester.


#### Academic Dishonesty:

Cheating or plagiarism in any form is unacceptable. All work submitted by a student must represent their own ideas, concepts, and current understanding. Academic dishonesty includes submitting substantial portions of the same academic coursework to more than one course for credit without prior permission of the instructor(s). Please be aware of your rights and responsibilities as a student by reviewing the [Boise State Student Code of Conduct](https://www.boisestate.edu/policy/student-affairs/code-of-conduct/).


#### Educational Access for All Students:

Students with additional educational and access needs are encouraged to contact the proper resource as early as possible ([Boise State Educational Access Center](https://www.boisestate.edu/eac/)). The EAC assists Boise State staff and faculty in meeting accommodations mandated by Federal and State law and University policy. They will work with you to identify and document physical and learning needs and identify appropriate accommodations for a student in their courses.


#### COVID-19 Guidelines:

As of August 2022, the COVID-19 pandemic situation remains fluid in the United States and Idaho. Masks and facial coverings are not required to be worn in class, unless you have tested positive for COVID-19 test or have been exposed to someone who has tested positive for COVID-19. Individuals may continue to mask in order to protect themselves and others. KN95 masks are available in several locations: the SUB information desk, Boise State Public Health in Campus School, residence hall information desks, and the HR offices. It is imperative that you do not attend class sick! If you need to be absent for an extended period of time due to illness, we can develop a plan to ensure your success. The student success goals of this class are centered on professional growth, which allows for flexibility and unanticipated complications.

You must enter their seat number into MyBoiseState by the end of the second week of class and need to stay with the same seat for the semester. The resulting information is critically important to contact tracing efforts. Please regularly check the University's [COVID 19 Response website for updates](https://www.boisestate.edu/coronavirus-response/). 


### Course Learning Outcomes and Supporting Activities

By the end of this course, I will be able to:



1. Setup, expand, maintain, and repair a computing environment for scientific programming,
2. Use a programming language to carry out a of tasks including data I/O, data reduction/wrangling, data analysis, visualization, and automation,
3. Demonstrate how to add, remove, and edit shared software using a version control platform,
4. Describe key properties of and create effective visualizations to convey data and communicate scientific findings,
5. Describe effective practices for identifying needs of key stakeholders of a scientific software platform,
6. Design a piece of scientific software that addresses key stakeholder needs,
7. List and describe important steps and practices of an agile scientific software development approach, and 
8. Describe my professional development as a scientific programmer during the semester and how that identity integrates with my future research and professional goals,

I will achieve these course learning outcomes by: 



1. Developing and maintaining a personal GitHub profile and repository
2. Completing and submitting programming assignments 
3. Working effectively in teams to build components of a larger piece of scientific software – a climate forecasting dashboard for Idaho
4. Deploying agile software development practices to help develop a functioning climate dashboard for Idaho
5. Creating SMART goals, monitoring and documenting progress toward achieving them, and demonstrating ability to reflect and revise them as needed, and
6. Reflecting on and describing my progress in developing an identity as a scientific programming skills and habits of mind throughout the course of the semester

<table>
  <tr>
   <td>
   </td>
   <td colspan="8" >
Learning Objectives
   </td>
  </tr>
  <tr>
   <td>Activity
   </td>
   <td>1
   </td>
   <td>2
   </td>
   <td>3
   </td>
   <td>4
   </td>
   <td>5
   </td>
   <td>6
   </td>
   <td>7
   </td>
   <td>8
   </td>
  </tr>
  <tr>
   <td>A
   </td>
   <td>X
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>B
   </td>
   <td>X
   </td>
   <td>X
   </td>
   <td>X
   </td>
   <td>X
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>C
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>X
   </td>
   <td>X
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>D
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>X
   </td>
   <td>X
   </td>
   <td>X
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>E
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>X
   </td>
   <td>X
   </td>
  </tr>
  <tr>
   <td>F
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>X
   </td>
  </tr>
</table>



### Grading and Ungrading

Assessment and evaluation approaches differ significantly between Unit 1 and Unit 2 of the course. During Unit 1 assessments and grading will be fairly conventional in that you will submit responses to programming assignments, which will be graded according to a rubric that will be provided in the class Canvas page. Below are the assessments for Unit 1:



* **<span style="text-decoration:underline;">Initial Survey:</span>** You will respond to an initial survey to get an idea of the distribution of prior experience and comfort with scientific programming, programming languages of familiarity, and some other questions related to your prior computational experience. 
* **<span style="text-decoration:underline;">GitHub Profile:</span>** As part of this class you will create and maintain a GitHub profile, which is increasingly becoming a key professional artifact for scientists and engineers that prospective employers may review. 
* **<span style="text-decoration:underline;">Jupyter Notebook Assignments:</span>** You will have approximately 4 programming assignments that will be completed in Jupyter Notebooks. Each assignment corresponds to a module that covers a key area of conceptual understanding for computational scientists in the Earth and environmental sciences. You will commit these notebooks to your GitHub repository for the course, and submit the HTML link to these notebook assignments in Canvas. 

Unit 2 will vary dramatically from traditional grading approaches in that we will adopt an “Ungraded” approach to evaluation. During this unit you will assign your grades on assessments that are worth 40% of your final grade in the class. 



* **<span style="text-decoration:underline;">Goal-setting Document:</span>** At the beginning of Unit 2, you will complete a goals document in which you will articulate 4-6 SMART (Specific, Measurable, Achievable, Relevant, and Time-bound) goals for the remainder of the class. 
* **<span style="text-decoration:underline;">Process Letters:</span>** At the end of each sprint, you will write and submit a short **_process letter_** that: (1) outlines the activities you have undertaken to achieve your goals, (2) provides evidence of those activities, (3) reflects on how well you performed those activities with respect to your expectations, (4) describes specific next steps toward achieving your goals, and (5) identifies any changes or modifications to your goals. The final process letter at the end of the semester will contain some additional reflection prompts that ask you to reflect on your process throughout the semester and set some longer-term professional development goals. You will be given a template with headings for these process letters and they should be no more than 3 pages in length (including figures and tables, you can include links to code in a GitHub repository). **You will assign your grade for the preceding ~2 week period on the process letter, but I reserve the right to revise your grade upward.**
* **<span style="text-decoration:underline;">Sprint Planning Document:</span>** Records goals, assignments, and activities for the sprint. This can be completed and submitted in class as a team the first day of each new sprint. You will be given a template with appropriate prompts.
* **<span style="text-decoration:underline;">Sprint Closure Document:</span>** Records the activities carried out, spillover (things that were planned but not completed during the sprint), and identifies issues and risks to the broader project. This can be completed and submitted as a team after the last day of each sprint. You will be given a template with appropriate prompts.

The following table contains the proportion of the final grade that each assessment comprises.


<table>
  <tr>
   <td><strong>Unit</strong>
   </td>
   <td><strong>Assessment Mechanisms</strong>
   </td>
   <td><strong>Fraction of Grade</strong>
   </td>
  </tr>
  <tr>
   <td rowspan="3" >1
   </td>
   <td>Initial survey
   </td>
   <td>3%
   </td>
  </tr>
  <tr>
   <td>Github profile
   </td>
   <td>2%
   </td>
  </tr>
  <tr>
   <td>Jupyter Notebook assignments (~4)
   </td>
   <td>30%
   </td>
  </tr>
  <tr>
   <td rowspan="4" >2
   </td>
   <td>Goal-setting document
   </td>
   <td>5%
   </td>
  </tr>
  <tr>
   <td>Process letters (5)
   </td>
   <td>40%
   </td>
  </tr>
  <tr>
   <td>Sprint planning documents* (5)
   </td>
   <td>10%
   </td>
  </tr>
  <tr>
   <td>Sprint closure documents* (4)
   </td>
   <td>10%
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Total
   </td>
   <td>100%
   </td>
  </tr>
</table>



### Late Work Policy

Submission of late assignments is understandable from time-to-time, particularly given that you are graduate students and sometimes professional development activities (e.g., fieldwork, conferences, etc.) take precedence over class work. That said, it is an essential professional skill to be able to negotiate deadlines and then follow through on negotiated delays. To promote this as a professional skill, the following procedure **must be followed** to receive credit for late work: 



1. You must notify me and the class TA via email at least 24 hours in advance of the due date and time that the assignment will be late,
2. In your notification email, you must provide a revised due date and time,
3. You must submit the assignment on or before that revised due date and time,
4. Assignments received outside of this policy will be scored as a 0.

An example of an appropriate notification email is provided below:

> Dear Lejo,
> 
> I will be at the Mountain Climate conference in Gothic, CO from September 9-13 without internet access when Jupyter Notebook number 2 is due on September 12th. If it is okay, I will submit the notebook after I arrive in Boise on September 16th by the end of the business day (5pm).
>
> Sincerely,
>
> Your name




### Approximate Timeline of Due Dates – Subject to Change


<table>
  <tr>
   <td><strong>Due Date</strong>
   </td>
   <td><strong>Individual Assignments</strong>
   </td>
   <td><strong>Team Assignments</strong>
   </td>
  </tr>
  <tr>
   <td>Aug 26
   </td>
   <td>Initial survey
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Aug 30
   </td>
   <td>GitHub profile
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Sep 06
   </td>
   <td>Jupyter Notebook 1
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Sep 13
   </td>
   <td>Jupyter Notebook 2
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Sep 20
   </td>
   <td>Jupyter Notebook 3
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Sep 27
   </td>
   <td>
   </td>
   <td>Class Dashboard Conceptual Design*
   </td>
  </tr>
  <tr>
   <td>Sep 27
   </td>
   <td>Jupyter Notebook 4
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Sep 29
   </td>
   <td>
   </td>
   <td>Requirements Definition \
Sprint 1 Planning Document*
   </td>
  </tr>
  <tr>
   <td>Oct 11
   </td>
   <td>Process Letter 1
   </td>
   <td>Sprint 1 Closure Report*
   </td>
  </tr>
  <tr>
   <td>Oct 13
   </td>
   <td>
   </td>
   <td>Sprint 2 Planning Document*
   </td>
  </tr>
  <tr>
   <td>Oct 25
   </td>
   <td>Process Letter 2
   </td>
   <td>Sprint 2 Closure Report*
   </td>
  </tr>
  <tr>
   <td>Oct 27
   </td>
   <td>
   </td>
   <td>Spring 3 Planning Document*
   </td>
  </tr>
  <tr>
   <td>Nov 08
   </td>
   <td>Process Letter 3
   </td>
   <td>Sprint 3 Closure Report*
   </td>
  </tr>
  <tr>
   <td>Nov 10
   </td>
   <td>
   </td>
   <td>Sprint 4 Planning Document*
   </td>
  </tr>
  <tr>
   <td>Nov 29
   </td>
   <td>Process Letter 4
   </td>
   <td>Sprint 4 Closure Report*
   </td>
  </tr>
  <tr>
   <td>Dec 01
   </td>
   <td>
   </td>
   <td>Sprint 5 Planning Document*
   </td>
  </tr>
  <tr>
   <td>Dec 15
   </td>
   <td>Final Process Letter and Reflection
   </td>
   <td>
   </td>
  </tr>
</table>


* You will have time to work on, complete, and submit these items in class
