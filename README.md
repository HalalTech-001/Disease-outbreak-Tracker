# Disease-outbreak-Tracker
A Python-based interactive system for tracking and analysing disease outbreaks using a simulated health dataset.

## Technologies/Focus:
Python
Data Analysis
Data Validation
Interactive Menu
Beginner Friendly

## About the Project
The Disease Outbreak Tracker is a menu-driven Python application built as part of a semester project.
It uses a simulated health dataset to allow users to:
Explore disease outbreak records
Validate data
Calculate key metrics
Classify risk levels
Search for information by country or disease
Dataset Disclaimer:
The dataset is not composed of live hospital records, official WHO statistics, or current government surveillance data. It contains fictional but realistic records created for learning and practice.


## 🎯 Objectives
The main objectives of the project are to:
✅ Validate outbreak data and identify problematic records
✅ Calculate key metrics such as total cases and deaths
✅ Classify outbreaks based on risk levels
✅ Build an interactive system for easy user exploration
✅ Demonstrate Python fundamentals through a real-life-inspired project


## ⚙️ Features
Interactive menu system
Nested while loops
Data validation and data-quality checks
Search by country and disease
Calculation of outbreak metrics
Risk classification:
Low
Medium
High
Critical
Display of high-risk outbreaks
Generation of summary reports


## 🐍 Python Concepts Used
The project applies the following Python concepts:
Variables
Strings
Integers
Floats
Arithmetic operators
Comparison operators
Logical operators
Assignment operators
User input
Conditional statements
while loops
Nested while loops
Lists
Dictionaries
Tuples
Functions
Menu-driven program design


## 📊 Simulated Dataset
The project uses fictional health records created specifically for learning and programming practice.
The data is not intended to represent:
Live hospital records
Official WHO statistics
Current government surveillance data

## 💻 Code Snippet
The image contains this main-menu section of the Python program:

# Main menu for Disease Outbreak Tracker

while True:
    print("\n==============================")
    print("     DISEASE OUTBREAK TRACKER")
    print("==============================")
    print("1. View all outbreak records")
    print("2. Add new outbreak record")
    print("3. Search by country")
    print("4. Search by disease")
    print("5. Calculate outbreak metrics")
    print("6. Validate outbreak data")
    print("7. View high-risk outbreaks")
    print("8. Generate outbreak summary")
    print("9. Exit")

    choice = input("\nEnter your choice: ")

    if choice == "9":
        print("Thank you for using Disease Outbreak Tracker.")
        break

# What this code does
The while True loop keeps the application running and continuously displays the main menu.
The user can select different operations by entering a number.
For example:
Enter your choice: 3
can take the user to the Search by Country functionality.
When the user enters:
Enter your choice: 9
the break statement terminates the loop and exits the application.