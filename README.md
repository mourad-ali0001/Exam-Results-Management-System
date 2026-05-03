# Exam-Results-Management-System
A python application that determines student progression outcomes based on university credit results that allows users to enter pass, defer and fail credits.

## Project Overview

This project was developed as part of a Software Development I coursework project. The aim of the program is to process student credit data and categorise each student into the correct academic progression outcome.

The system classifies students into one of four outcomes:

- Progress
- Progress (module trailer)
- Do not Progress - module retriever
- Exclude

The program also keeps track of multiple student entries and displays the total number of students processed.

## Key Features

- Accepts pass, defer, and fail credit inputs from the user.
- Validates that credit values are entered as integers.
- Checks that credit values are entered in valid increments.
- Ensures the total number of credits equals 120.
- Classifies students into the correct progression category.
- Allows multiple student records to be entered in one session.
- Stores grouped progression outcomes.
- Writes final progression results to a text file.
- Generates a graphical histogram showing the number of students in each outcome category.

## Technologies Used

- Python
- graphics.py
- Tkinter-based graphics
- File handling
- Input validation
- Basic data visualisation

## How the Program Works

The user is asked to enter three credit values:

- Pass credits
- Defer credits
- Fail credits

The program checks that each input is valid and that the total equals 120 credits. Based on the credit combination, the student is assigned to one of the progression categories.

After the user finishes entering student records, the program:

1. Prints the grouped progression outcomes.
2. Saves the outcomes to `test.txt`.
3. Calculates the number of students in each category.
4. Displays a bar chart histogram in a graphics window.

## Example Outcomes

Example classifications include:

```text
Progress
Progress (module trailer)
Do not Progress - module retriever
Exclude
