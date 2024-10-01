Title: Employee Form Project

Description: 

It is a Project that is done in both HTML and JavaScript. It is a Form where the entered details are stored in the "JsonPowerDB" Database. A peculiar feature about this project is the buttons used in the form. The Form has 9 Buttons namely 'New', 'Save', 'Edit', 'Change', 'Reset', 'First', 'Previous', 'Next', 'Last'. The 'New' and 'Edit' buttons are enabled at default, while all the other buttons are disabled. If a new record needs to be inserted, the 'New' button needs to be pushed, if an already existing data needs to be updated, the 'Edit' button needs to be pushed. The 'Save' button is enabled when 'New' button is pushed and the 'Change' button is enabled when the 'Edit' button is pushed to submit changes in both the scenarios. the buttons namely , 'First', 'Previous', 'Next', 'Last' are used to naviagte through records in the database. The 'First' button and 'Previous' button is enabled at default and when during Navigation and it works as such.

Benefits of using JsonPowerDB: Using JsonPowerDB (JPDB) in the above project offers several advantages, including its schema-free nature, which allows flexibility in storing student data without predefined structures. The built-in REST APIs simplify database interactions, making it easy to connect your frontend directly to the database with minimal code. This enables quick operations like inserting, updating, or retrieving student records in real-time with high performance.

Additionally, JPDB provides primary key support, ensuring unique identification of records, and works seamlessly with JSON, reducing the need for data transformation. Its low setup requirements, security through connection tokens, and scalability make it an ideal choice for lightweight applications, offering both speed and convenience for real-time data management.

Release History: Employee Form Management System


v1.0.0 - Initial Release
Date : 30-09-2024

Initial setup of the employee form management system.
Basic form structure using HTML and Bootstrap.
Employee details input form with fields: Employee ID, Name, Basic Salary, HRA, DA, and Deduction.
Integrated navigation buttons for first, previous, next, and last records.
"New", "Save", "Edit", "Change", and "Reset" buttons with basic functionality.
Backend connection established with JsonPowerDB using connToken.
Initial JavaScript functions to handle form data retrieval and manipulation (getFirst(), getLast(), showData(), etc.).


v1.1.0 - Navigation and Record Handling Enhancements
Date : 30-09-2024

Added JavaScript functions for handling record navigation:
getFirst(), getNext(), getPrev(), getLast() for navigating between employee records.
Local storage functionality added for tracking first and last record numbers.
Added validation to handle edge cases like no records present and only one record present.
Implemented the checkForNoOrOneRecord() function to handle navigation control.


v1.1.1 - Form Reset Functionality Improvement
Date : 30-09-2024

Enhanced resetForm() to properly reload the current record upon resetting.
Fixed a bug where form values were not properly reloaded after the reset.
Proper handling of local storage for keeping track of the current record.


v1.2.0 - Data Validation and Error Handling
Date : 30-09-2024

Added robust validation in validateData() function for all form fields:
Ensured non-empty fields for Employee ID, Name, Salary, HRA, DA, and Deduction.
Added alerts and focus management for missing fields.
Improved error handling for form submission and navigation.
Introduced error messaging for invalid employee data fetch.


v1.3.0 - Bug Fixes and Code Improvements
Date : 01-10-2024

Fixed an issue with the validateData() function where field values were being incorrectly reset.
Optimized form field fetching and validation to prevent clearing of form inputs during validation.
Improved UI feedback for navigation buttons when reaching the first or last record.
Introduced a cleaner, more organized form submission process in saveData().


v1.3.1 - Minor Bug Fix in Form Submission
Date : 01-10-2024

Fixed a minor issue in saveData() where form submission resulted in incorrect output due to an improperly focused input field.
Adjusted focus behavior for better user interaction after form submission.


v1.4.0 - UI Enhancements and Refactoring
Date : 01-10-2024

Refined the form layout for better responsiveness on smaller screens.
Simplified button disable/enable logic for improved user experience.
Added Bootstrap form styling for better UI consistency.


Completition Time : 2 days

Project Status : Completed
