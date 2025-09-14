Project Overview

This project is developed in Google Colab to demonstrate Python programming, data collection, and visualization skills. The goal is to collect student names and marks dynamically, process the data, and generate a clear visual representation of performance using Matplotlib. The visualization includes marks, grades, and the class average, making it useful for quick academic insights.

The project showcases practical problem-solving ability, use of Python data structures, and clean visualization techniques—valuable skills for data analysis and software development roles.

Problem Statement

In classrooms or training programs, analyzing student performance manually can be time-consuming and prone to error. Teachers need a simple way to:

Collect student data.

Compute class averages.

Assign grades based on marks.

Visualize performance comparisons in an easy-to-read chart.

Solution

This Python program provides an automated and visual solution. By running the notebook:

The user inputs the number of students.

Student names and marks are entered.

The program calculates the class average.

Grades are assigned to each student.

A bar chart is generated that:

Displays marks for each student.

Shows the average marks as a red dashed line.

Labels each bar with the student’s grade.

This makes performance analysis faster, more accurate, and visually intuitive.

Technical Implementation

Platform: Google Colab (no local setup required).

Language: Python 3.

Libraries Used:

Matplotlib: For data visualization.

NumPy: For efficient numeric operations.

Workflow:

Import required libraries (matplotlib, numpy).

Accept user input for number of students, names, and marks.

Store names and marks in lists.

Compute:

Class average.

Grades (A, B, C, etc.) based on marks.

Plot a bar chart:

X-axis → Student names.

Y-axis → Marks out of 100.

Bars → Individual student marks.

Dashed line → Class average.

Annotations → Student grades above each bar.
