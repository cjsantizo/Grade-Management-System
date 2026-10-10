

# Grade Management System

## Project Overview

Grade Management System is a C++ console-based application designed to help users manage and analyze student grades through an interactive menu.

The program allows users to enter student grades, view stored grades, calculate the average, identify the highest and lowest grades, count grades within a specified range, and search for a particular grade.

## Main Goal

The goal of this project was to develop a simple grade management application while strengthening my understanding of fundamental C++ programming concepts, including:

- Arrays and data storage
- Functions and modular programming
- Loops and conditional statements
- User input and validation
- Basic data analysis and calculations

## Features

- **Enter Grades:** Store up to 100 student grades.
- **Display Grades:** View all entered grades in the order they were added.
- **Calculate Average:** Calculate the average of all stored grades.
- **Find Highest and Lowest:** Identify the maximum and minimum grades.
- **Count Grades in Range:** Determine how many grades fall within a user-specified range.
- **Search for a Grade:** Count how many times a particular grade appears.
- **Interactive Menu:** Navigate between features until choosing to exit.

## Technologies Used

- **Language:** C++
- **Application Type:** Console-based application
- **Core Concepts:** Arrays, functions, loops, conditional statements, and input validation

## How to Run the Project

### 1. Download the Project

Clone the repository using Git:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Or select **Code → Download ZIP** on GitHub and extract the downloaded folder.

### 2. Compile the Program

Make sure you have a C++ compiler installed, such as GCC (g++).

Open a terminal in the project directory and compile the source file:

```bash
g++ main.cpp -o GradeManagement
```

*Replace `main.cpp` with the actual source filename if it is different.*

### 3. Run the Program

On Windows:

```bash
.\GradeManagement.exe
```

On macOS or Linux:

```bash
./GradeManagement
```

### 4. Using the Program

After launching the application, an interactive menu will appear.

1. Select **Option 1** to enter the number of grades you want to store (maximum 100).
2. Enter each grade when prompted.
3. Select **Options 2–6** to display or analyze your stored grades.
4. Select **Option 7** to exit the application.

## Example Program Output

```text
============================================
 Grade Management System
============================================
1. Enter Grades
2. Display all grades
3. Calculate average grade
4. Find highest and lowest grades
5. Count grades in a specific range
6. Search for a specific grade
7. Exit

Enter your choice: 1

How many grades to enter (Max is 100)?: 2

Enter grade #1: 80
Enter grade #2: 75

Enter your choice: 4

The highest grade is: 80
The lowest grade is: 75
```

## What I Learned

Through this project, I gained practical experience using C++ to organize and process data. I improved my ability to work with arrays, divide a program into reusable functions, handle user input, and implement calculations based on stored values.

This project also helped me understand how to structure a menu-driven application that allows users to interact with multiple features within one program.
