Dynamic Person Information Management App

This web application allows users to add and manage personal information dynamically, with the ability to save data to local storage and retrieve it based on Aadhaar numbers. The app has two primary tabs: Add New Person and Retrieve Information.

Features
1. Add New Person Tab
Dynamic Row Creation: Add new rows dynamically to input data for new persons.
Input Fields:
Name
Date of Birth (DOB)
Aadhaar Number (12 digits)
Mobile Number (10 digits)
Age (automatically calculated using DOB)
Validation:
Aadhaar Number must be exactly 12 digits.
Mobile Number must be exactly 10 digits.
All fields are required before saving.
Actions:
Save: Saves the row's data to local storage if validation passes.
Delete:
Removes the row if it hasn't been saved yet.
Deletes data from local storage and removes the row if it has been saved.
2. Retrieve Information Tab
Input an Aadhaar Number to search for matching data in local storage.
If a match is found:
Display all related information in a table.
If no match is found:
Display a message: "No match found."


How to Use
Navigate to the Add New Person Tab:
Click the "Add" button to create a new row.
Fill in the details in the input fields.
Click "Save" to store the data in local storage (ensure validation passes).
Use "Delete" to remove the row or delete saved data.
Navigate to the Retrieve Information Tab:
Enter an Aadhaar Number in the input field.
Click "Search" to query the data.
View the result in a table if a match is found.
If no match is found, the app will display "No match found."
