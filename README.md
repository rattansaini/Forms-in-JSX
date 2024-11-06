# Forms-in-JSX
Forms in JSX
This project is a simple React app demonstrating form handling and displaying input data in a table. The app allows users to submit a student's name and marks, which are displayed in a table below the form. This example helps illustrate the use of React refs, form submission, and rendering data in JSX.

Features
Form to capture student names and marks.
Displays submitted entries in a table format.
Clears input fields upon submission.

Getting Started
Prerequisites
To run this project, you need:

A web browser that supports JavaScript.
An internet connection to load the React and Babel CDN libraries.
Running the App
Download or clone this repository to your local machine.
Open the index.html file in your browser to start the app.

Code Overview
index.html
The main HTML file includes:

React and ReactDOM: Imported via CDN links for rendering the React components.
Babel: Included to allow inline JSX within <script type="text/babel">.

App Components:
Form: A form component containing two input fields (Name and Marks) and a submit button. Input values are managed using React refs.
Result: A table that displays each student's name and marks. New entries appear at the top of the table.
App: The main component that combines both Form and Result components.

Key Functions
addStudent: This function handles the form submission. It retrieves the values from the input fields, validates them, and adds the entry to the students array. After adding, it clears the input fields and re-renders the component to update the table.

Example Usage
Enter a student's name in the "Name" input field.
Enter the student's marks in the "Marks" input field.
Click the "Submit" button. The entry will appear in the table below the form, and the input fields will be cleared.

Technologies Used
React: JavaScript library for building user interfaces.
Babel: JavaScript compiler to support inline JSX syntax in this setup.

Potential Improvements
Add validation to ensure that only numerical values are entered for marks.
Allow editing and deleting of entries.
Save entries to localStorage to persist data on page reloads.

License
This project is open-source and available under the MIT License.
