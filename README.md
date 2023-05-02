# *Library Management System Project*
#### By: Muhammad Muawiz Farooqi, Tahera Fatima, Faith Gutierrez
### Table of Contents
1. [Description](#Description "Jump to Description")
2. [Installation-and-Startup-Process](#Installation-and-Startup-Process "Jump to Installation-and-Startup-Process") 
3. [Features](#Features "Jump to Features")
  

## Description 

Welcome to our library management system project! We are excited to introduce our user-friendly GUI interface that simplifies the process of managing library resources. Our project is designed with Python's tkinter.ttk module as the front end and SQLite as the back end, providing a powerful and efficient tool for librarians and library users alike. Each section of our GUI allows users to execute SQL queries by simply giving input and pressing a button!


## Installation and Startup Process
#### Installation:
- Download the zipped repository
- Install python https://www.python.org/downloads/release/python-3113/
- Install sqlite https://www.sqlite.org/2023/sqlite-tools-win32-x86-3410200.zip
- Unzip the dowloaded repository
- Make sure files sqldiff.exe, sqlite3.exe, sqlite3_analyzer.exe, and LMS.sqlite are in the folder
To generate LMS.sqlite for the first time:
- Remove any existing LMS.sqlite file
- Enter the command line terminal and navigate to the “Code” folder.
- Open sqlite3:
```sqlite3```
- Read in the SQL file LMS.sql:
```.read LMS.sql```
#### Launching the GUI:
- Enter the command line terminal and navigate to the “Code” folder
- Run the python GUI file:
```python librarysystem.py```
- Navigate to Report.pdf for screenshots of the GUI for every task.


## Features
Our app has 7 database management features:
- **Check out a Book**
- **Get a Library Card**
- **Add a New Book to the Database**
- **Check Book Avaliability**
- **View Late Books**
- **Search for Library Card Holders**
