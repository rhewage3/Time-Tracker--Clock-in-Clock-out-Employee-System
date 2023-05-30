# Time-Tracker--Clock-in-Clock-out-Employee-System

This clock-in/clock-out system is built using HTML, CSS, and JavaScript with Google Sheet and Google Script integration. The system allows employees to clock in and out, saving their name or ID and the corresponding timestamps in a Google Sheet. It calculates the total worked time for each period and maintains a separate column for the total work time of each employee.

Features
Clock in and clock out functionality for employees
Saving employee name/ID and timestamps in a Google Sheet
Calculation of total worked time for each period
Error handling for specific scenarios
Checks if the selected employee is working in the specific organization
Prevents an employee from clocking in if they are already clocked in
Setup Instructions
To set up the clock-in/clock-out system, follow these steps:

Create a new Google Sheet and name it "Time Tracker".
In the Google Sheet, create two sheets named "EMPLOYEES" and "MAIN".
Copy and paste the contents of the HTML file into a new HTML file in your preferred code editor.
Save the HTML file as "TimeTracker.html".
Copy and paste the contents of the code.gs file into a new Google Script file in your Google Sheet.
Save the Google Script file as "Code.gs".
Publish the script as a web app by following these steps:
In the Google Sheet, click on "Extensions" in the menu.
Go to "Apps Script" and click on "Deploy as web app".
Set the access to "Anyone, even anonymous" and click on "Deploy".
Copy the deployed web app URL.
In the HTML file, replace the <base target="_top"> tag's href attribute with the web app URL obtained in the previous step.
Save the HTML file.
Now, you can use the clock-in/clock-out system by accessing the HTML file through the web app URL. The system will interact with the Google Sheet to track employee attendance and calculate total work hours.

Note: Make sure to grant the necessary permissions for the Google Sheet and Google Script to function properly.

Feel free to customize the HTML, CSS, and JavaScript code to match your requirements.
