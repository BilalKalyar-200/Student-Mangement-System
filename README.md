About Project:
Student Management System (SMS)


Overview
•	A Command-Line Interface (CLI) application built using Bash scripting.
•	Designed for a single teacher to manage up to 20 students.
•	Stores student data in a text file for persistence.

Primary Users
1.	Teacher
o	Manages all student operations (add, edit, delete, grade).
2.	Student
o	Can log in to view grades and CGPA.

Core Features
Feature	Description		
Teacher Account	Secure login to access and manage student records.		
Add Students	Add student details (Roll No, Name, Total Marks, etc.) – up to 20 students.		
View Details	Search and display individual student records.		
Update Information	Modify student data such as marks or personal info.		
Delete Student	Remove student record based on Roll Number.		
Calculate Grades	Automatic grade generation based on FAST’s grading policy.		
Calculate CGPA	Compute CGPA from grades and marks.		
Generate Report	View full list in ascending/descending order, or filter by pass/fail.		
Save & Load Data	Data is stored in a text file and loaded on program start.		

Student Functionalities
•	Login securely to access records.
•	View Grades assigned by the teacher.
•	View CGPA calculated by the system.

Grading & Performance
•	FAST Grading Criteria used for grade calculation.
•	Students categorized into:
o	Passed Students – CGPA above threshold.
o	Failed Students – CGPA below threshold.
•	Sorting available by CGPA (ascending/descending).

