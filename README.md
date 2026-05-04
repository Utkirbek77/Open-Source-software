OpenTrack Project Manager

Week 5 Python Assignment
Student: Toshboev Utkirbek

Project Overview

This script is a specialized Python tool designed to automate the management of open-source project metadata, contributor details, and software issue tracking. It serves as an end-to-end data processor that collects user input and transforms it into organized reports.

Features

- Metadata Storage: Uses immutable tuples to secure core project information like versioning and leadership.
- Contributor Management: Maintains a registry of contributors, including their roles, programming languages, and commit history.
- Issue Tracker: Categorizes software bugs and features by priority (Critical, High, Medium, Low) and status.
- Set Logic: Employs Python sets to automatically identify unique tech stacks and calculate the overlap between reporters and developers.
- Automated Export: Generates a structured directory containing both a raw CSV data file and a formatted text report.

Main Variables and Their Purpose

- project (Tuple) → Stores core project information (name, version, year, language, lead). Tuple is used because it is immutable.
- contributors (List of Dictionaries) → Stores detailed information of all contributors.
- issues (List of Dictionaries) → Holds all issues with id, title, priority, reporter, and status.
- reporters & tech_stack (Set) → Used to handle unique values and perform set operations.
- priority_count (Dictionary) → Counts issues by priority level.
- status_groups (Dictionary) → Groups issues based on their current status.
- reporter_count (Dictionary) → Used to find the top reporter.
- urgent (List) → Stores titles of Critical and High priority issues.
- folder_name, report_path, csv_path (String) → Manage folder creation and file paths.

Custom Functions

- There are no custom functions (def) in this project.
- The entire program runs in procedural style (line by line execution).

Built-in Functions and Methods Used

- print(), input(), int(), len(), sorted(), range()
- open() with with statement for file operations
- os.makedirs() and os.listdir() for directory handling
- List & Dictionary methods (.append(), .update(), .get(), .pop())
- Set methods (.add(), .union(), .intersection(), .difference(), .discard())

Technical Details

- Language: Python 3.x
- Key Modules: os (for directory and file operations)
- Error Handling: Includes protection against file system errors

How to Run the Project

1. Download or clone this repository.
2. Open terminal / command prompt in the project folder.
3. Run the following command:

   python week_5_completed.py
