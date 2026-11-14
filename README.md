**Development of a Student-Accessible Plagiarism Detection System**

***Project Overview***
This project is a Python-based plagiarism detection system designed for university students.
It allows students to submit their assignments and check their similarity against previously submitted work.
The system identifies matching sentences and calculates a similarity percentage.
It provides a simple, interactive console-based interface.

***Main Features***

**Student Registration:** Allows new students to create accounts.
**Student Login:** Provides access through registered usernames and passwords.
**Assignment Submission:** Allows students to submit assignment titles and text.
**Similarity Checking:** Compares submitted assignments with existing submissions.
**Matching Sentence Detection:** Identifies exact sentences appearing in multiple assignments.
**Report Generation:** Creates and saves similarity reports.
**Report Viewing:** Allows students to view their previous reports.
**Assignment Search:** Helps locate assignments using a username or title.

**Softwares Used**
Python
Jupyter Notebook
JSON for data storage
Python libraries: json, os, re, hashlib, and datetime

**How to Run the Project**

Install and open Jupyter Notebook.
Download or clone this GitHub repository.
Open the project notebook in Jupyter Notebook.
Run the code cells in the correct order.
Execute the main() function to launch the portal.
Select an option from the main menu to use the system.

**How to Use the System**
Register a new student account.
Log in using your registered username and password.
Select Submit Assignment to enter an assignment title and text.
Type END on a separate line when you finish entering the assignment.
Select Check Assignment Similarity and enter your submission ID.
Review the similarity percentages and matching sentences.
Open View My Reports to access previously generated reports.
Use Search Assignments to find stored submissions.
Select Logout when finished.

**Data Storage**
Student account details are stored in users.json.
Submitted assignments are stored in submissions.json.
Generated similarity reports are stored in reports.json.
These files are automatically created inside the data folder when the program runs.

**Project Limitations**
The system compares assignments stored within its own database only.
It does not search the internet, books, journals, or external plagiarism databases.
Similarity percentages indicate textual overlap and do not automatically prove plagiarism.
The results should be reviewed by a human before making academic decisions.

**Project Type**
Academic programming project.
Python-based backend implementation.
Interactive console-based application.
