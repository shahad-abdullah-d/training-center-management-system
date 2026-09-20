# Smart Training Center Management System

A Python capstone project that implements a console-based system for managing a training center. It covers trainee registration, course enrollment, attendance tracking, assessment scores, certificate eligibility, and management reports.

The project demonstrates core Python programming concepts, object-oriented programming (OOP), data validation, file handling, and basic data analysis.

## Project Overview

The system manages trainees and technical training courses through a menu-driven console interface.

It allows a training center to register trainees, enroll them in courses, track their attendance and assessment scores, and determine whether they meet the requirements for course completion and certificate eligibility.

## Features

- Register trainees and manage training courses.
- Enroll trainees while checking course capacity.
- Record attendance and assessment scores.
- Calculate average scores and attendance percentages.
- Determine course completion status: Passed, Failed, or Incomplete.
- Check certificate eligibility based on attendance and assessment requirements.
- Generate trainee reports, course reports, and an overall management summary.
- Save and restore training center data using JSON.
- Export course reports to CSV.
- Handle invalid inputs using validation functions and custom exceptions.

## Technologies and Concepts

- Python
- Jupyter Notebook
- NumPy
- Object-Oriented Programming (OOP)
- Lists, dictionaries, sets, and tuples
- Functions, loops, and conditional statements
- Exception handling
- JSON and CSV file handling

## System Design

The project uses three main classes:

### Trainee

Stores trainee information, enrolled courses, attendance records, and assessment scores.

### Course

Stores course information, including its code, title, capacity, passing score, minimum attendance requirement, and schedule.

### TrainingCenter

Manages trainees and courses, handles enrollment and attendance, calculates performance, and generates reports.

## Certificate Eligibility

A trainee is eligible for a course certificate when:

1. The trainee is enrolled in the course.
2. At least one assessment score has been recorded.
3. The average assessment score meets the course's passing score.
4. The attendance percentage meets the minimum attendance requirement.

The system uses these conditions to determine course completion status and certificate eligibility.

## Reports and Data Persistence

The system includes:

- Individual trainee reports.
- Course reports containing assessment averages, attendance percentages, completion status, and certificate eligibility.
- An overall management summary.
- JSON saving and loading.
- CSV course report export.

## Project File

`Training_Center_Management_System.ipynb` — Python notebook containing the system implementation, sample data, demonstrations, and test cases.

## How to Run

1. Download the notebook from this repository.
2. Open it in Jupyter Notebook or Google Colab.
3. Install NumPy if it is not already available.
4. Run the notebook cells in order to initialize the classes, create the sample data, and execute the demonstrations.

To use the interactive console menu, call:

```python
run_menu(center)
```

The menu is defined in the notebook but is not started automatically.

## Project Scope

This is a Python fundamentals capstone project designed to demonstrate programming concepts through a training center management scenario.

It is a console-based educational system, not a deployed web application.

## Author

Shahad Abdullah

Python Fundamentals Capstone Project
