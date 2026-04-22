README.md

OpenTrack Project Manager 

  This script is a specialized Python tool designed to automate the management of open-source project metadata, contributor details, and      software issue tracking. It serves as an end-to-end data processor that collects user input and transforms it into organized reports.

Features
  Metadata Storage:Uses immutable tuples to secure core project information like versioning and leadership.
  Contributor Management: Maintains a registry of contributors, including their roles, programming languages, and commit history.
  Issue Tracker: Categorizes software bugs and features by priority (Critical, High, Medium, Low) and status.
  Set Logic: Employs Python sets to automatically identify unique tech stacks and calculate the overlap between reporters and developers.
  Automated Export: Generates a structured directory containing both a raw CSV data file and a formatted text report.

Technical Details
  Language: Python 3.x

  Author: Toshboev Utkirbek Uktam Ugli

  Key Modules: os for directory management and file I/O operations.

  Error Handling: Built-in protection against file system errors and missing reports.

How to Use
  Run the script: python week_5_completed.py.
  Input the requested contributor details (4 entries required).
  Input the issue details (5 entries required).
  View the final summary in the terminal or open the generated .txt and .csv files in the output folder.
