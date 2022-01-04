# CSC 440 Grade Tracking System 

Problem Statement: EKU’s Registrar Office needs to update student course records after receiving student grades from all of the faculty at the end of each semester. Each faculty member provides the office an Excel file with letter grades (A, B, C, D, or F) of the students who took course(s) with them. The office is asking us to develop a system to manage the data for them.

Proposal: We propose a software system to allow the faculty members to add new grades of courses for each student to the database, edit a grade for a student, delete a grade for a student, and print a report card (or transcript) for a student.

System Description: The data that the system shall manage will be based upon the Excel files that are given from the faculty members to EKU’s Registrar Office. These Excel files from the faculty will be gathered by the Registrar’s office and then put into a folder. The formats of the names for the folder and excel files are shown as below:

Folder name: "Grades [Year][Semester]" EX: "Grades 2021 Spring", "Grades 2023 Fall"

File name: "[Course Prefix][Number][Year][Semester]" EX: "CSC 440 2021 Fall", "MAT 234 2027 Spring"

With this data given, the system shall be able to add new grades of courses for each student to a database. In the case of a mistake in the data in the Excel files provided by the faculty, the system shall allow the Registrar’s Office to edit the grade of a course for a student. Upon choosing to edit a grade, the system shall provide options such as changing the grade, deleting the grade, and/or adding a grade to the database. The system shall display the data that is in the database for each specific student by printing a report card (or transcript) for the student. The report card (or transcript) shall display the student’s name, ID, overall GPA, list of courses taken, and the grades for the courses taken.
