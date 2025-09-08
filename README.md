# In-Lab Assignment 1

## Problem
You are asked to help a small student office at GIU manage basic student records. Each student has:
- ID  
- Name  
- GPA  

The office wants a simple program that demonstrates **structs, pointers, references, and functions**.

## Requirements
1. Define a struct `Student` with the fields: `id`, `name`, and `gpa`.
2. Write a function `void inputStudent(Student* s)` that takes a pointer to a student and allows the user to enter the student’s information.
3. Write a function `void updateGPA(Student& s, float newGPA)` that uses a reference to update a student’s GPA.
4. Write a function `void printStudent(Student s)` that prints a student’s details.
5. In `main()`:
   - Create an array of 3 students.
   - Use `inputStudent` to read their details.
   - Update the GPA of the second student using `updateGPA`.
   - Print all students using `printStudent`.

## Rules
1. Duration of the in-lab assignment is strictly 30 minutes.  
2. Use of AI tools or external help is strictly prohibited.  
3. Each student must work individually.  
4. Late submissions will not be accepted.  

## Submission
Push your code to this repository. The autograder will run automatically.
