## 🎓 Student Grade Calculator

A Python project for Week 2 – Control Flow & Data Structures

This program allows users to enter marks for multiple students, calculates averages, assigns grades, provides feedback comments, and displays class statistics.
Great for learning loops, lists, validation, functions, and conditionals.

📌 Features
✅ Input Validation

Ensures number of students is a positive whole number

Ensures marks are between 0 and 100

Prevents empty student names

✅ Grade Calculation

Uses the student's average score to assign:

Average Range	Grade	Comment
90–100	A	Excellent! Keep up the great work!
80–89	B	Very Good! You're doing well.
70–79	C	Good. Room for improvement.
60–69	D	Needs Improvement. Please study more.
0–59	F	Failed. Please seek help from teacher.
✅ Class Statistics

Class Average

Highest & Lowest Averages

Names of top and bottom performers

✅ Summary Table

Displays results neatly:

Name                |   Avg | Grade | Comment
---------------------------------------------------------------
John                |  85.3 |   B   | Very Good! You're doing well.

🧠 Code Structure
1. calculate_grade(average)

Returns a (grade, comment) tuple based on rules.

2. get_valid_number(prompt)

Ensures user enters a valid numeric value within a specified range.

3. main()

Handles:

Student count

Name & marks input

Average calculation

Results table

Class statistics

Final output
