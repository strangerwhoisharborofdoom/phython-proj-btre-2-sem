 # University Data Engine

A Python-based mini student management system built using core data structures: Dictionaries, Tuples, Lists, and Sets. This project simulates a simple university backend system for managing student records, course enrollments, and grade tracking.

---

# Features

## Student Registry
- Stores student details using:
  - Dictionary
  - Tuple
- Each student has:
  - Student ID
  - Name
  - Major
  - Expected Graduation Year

## Course Enrollment
- Uses Sets to:
  - Prevent duplicate enrollments
  - Store unique course codes

## Grade Tracking
- Uses:
  - Lists
  - Tuples
- Maintains chronological academic history

## GPA Calculator
- Calculates average score of a student

## Common Ground Finder
- Finds common enrolled courses between two students using set intersection

## Registry Auditor
- Prints student records along with enrolled courses

---

# Technologies Used

- Python 3
- Dictionaries
- Tuples
- Lists
- Sets

---

# Project Structure

student_registry     -> Stores student identity records  
course_enrollments   -> Stores unique enrolled courses  
grade_books          -> Stores grades and academic history  

---

# Example Output

Student 1001 enrolled in AI301  
Student 1001 is already enrolled in CS101  

Common Courses Between 1001 and 1002:  
{'CS101'}  

Average Score of Student 1001:  
88.5  

---

# How to Run

## Step 1
Install Python 3

## Step 2
Save the code as:

university_data_engine.py

## Step 3
Run the program

```bash
python university_data_engine.py