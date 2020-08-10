# Project Outline

### Overview

The purpose of this application is to help facilitate remote learning by allowing teachers and students (and potentially also parents) to create, complete, and grade assignments or tests through a web platform.  This will be a three (potentially four) step process, each involving a distinct type of user interaction: assignment/test creation and grading (done by the teacher), assignment/test completion (done by the student), and if time allows the teacher will also be able to leave comments that the student (and potentially parents) can view.  

My original proposal in class would have had essentially the same underlying functionality, but was going to be used for translation projects rather than school assignments.  I have since decided however that this system lends itself better to this usage and that an application that helps with remote education would be in higher demand these days anyway.

### Features

1.	User login: Users will be able to create accounts of either Student or Teacher (or potentially Parent) type.  Once logged in, they will be able to view any complete or incomplete tests/assignments associated with their account or perform the actions detailed below.
2.	Test/assignment creation: Teacher-level users will be able to create tests and assignments and assign them to Student-level users. These will take the form of database tables with entries corresponding to the question and the correct answer. Initially only multiple choice will be supported, but free response questions may be added if time allows. Support for importing and exporting tests may be added too.
3.	Test/assignment taking: Student-level users will be able to take and submit tests assigned to them by Teacher-level users. Completed tests will take the form of database tables with entries corresponding to the question and the submitted answer.
4.	Test/assignment grading: Teacher-level users will be able to grade tests. Multiple-choice tests can be graded automatically at the push of a button by comparing the database table with the correct answers to the database table with the submitted answers, but if free response questions are supported they will need to be manually gradable.
5.	Test/assignment commenting (if time allows): Teachers will be able to attach comments to Students' responses when they grade them. The graded, commented tests/assignments will then be passed back for the Student (and Parents, if implemented) to review.
6.	Classrooms (if time allows): Instead of simply having Teachers select which Students a test/assignment is sent to, Teachers will be assigned Classrooms consisting of a given roster of Students. Then a test/assignment can simply be assigned to a certain Classroom and all its Students will receive it.
7.	Grade calculation (if time allows): Students' overall grades will be calculated from the grades given to their assignments/tests. Teachers can assign custom weights to assignment and test scores.

### Technologies

•	Java
•	Spring Boot
•	MySQL
•	Hibernate
•	Thymeleaf templates
•	HTML/CSS
•	JSON (if importing/exporting is implemented)

### What I'll Have to Learn

There are some aspects to this project that we didn't cover in class at all, such as creating different classes of users with different permissions and landing pages and integrating JSON files with Java. But the biggest challenge for me will be in improving my skills with the MVC pattern. This project will require fairly complex interactions between the various components relative to what we have already done in class. I will also need to improve my knowledge of SQL, as this project requires storing and manipulating a large amount of persistent data.

### Project Tracker

https://trello.com/b/tpxWdAkp/capstone-project
