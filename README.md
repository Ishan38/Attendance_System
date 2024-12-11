Student Attendance Management System
This web-based application allows teachers to manage student attendance efficiently by uploading an Excel file containing student information. It provides features to mark students as present and download the list of present students in an Excel format.

Features
Upload Excel File: Users can upload an Excel file (.xlsx or .xls) containing student data.
Mark Attendance: Attendance can be marked for each student by clicking a button that toggles between "Mark Present" and "Present."
Download Present Students: After marking students as present, the list of present students can be downloaded as an Excel file.
Technologies Used
HTML5: For the structure of the web page.
CSS3: For styling the web page and creating an intuitive interface.
JavaScript: To handle file upload, processing of Excel data, and user interaction for marking attendance.
XLSX.js: A JavaScript library for parsing and writing Excel files.
File Upload
Supported file types: .xlsx or .xls Excel files.
The file should contain student data with at least the following columns: Student ID, Name, and Semester.
How It Works
Upload an Excel File:
Click on the "Choose File" button to upload an Excel file containing student information.
Process the Excel File:
Click the "Process File" button to read and display the contents of the uploaded file in a table format.
Mark Attendance:
Each student will have a button to mark them as present. Click the button to toggle their attendance status between "Mark Present" and "Present."
Download Present Students:
Once all attendance is marked, click the "Download Present Students" button to download an Excel file containing only the students who were marked as present.
How to Use
Open the HTML file in your browser.
Upload an Excel file by clicking the "Choose File" button.
Click "Process File" to display the students in a table.
Mark students as present by clicking the "Mark Present" button.
Download the list of present students by clicking "Download Present Students."
Requirements
A modern web browser that supports JavaScript (e.g., Google Chrome, Mozilla Firefox).
The Excel file must be properly formatted to contain student data (Student ID, Name, Semester).
