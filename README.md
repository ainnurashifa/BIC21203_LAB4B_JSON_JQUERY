
# BIC21203 Lab 4B - Client-Side Scripting (JSON and jQuery)

## Student Information
- Name: Ainnur Ashifa binti Md Tohid
- Student ID: CI240036
- Course: BIC21203 Web Development
- Academic Session: 2026/2027

## Lab Description
This lab focuses on client-side scripting using JSON, modern JavaScript and jQuery. It demonstrates how to create and validate JSON data, retrieve information using the fetch() API and manipulate HTML elements using jQuery.

## Question 1 - Create and Structure JSON Data
This question involves creating a valid JSON file named books.json containing information about two books.

The data includes:
- Book title
- Author
- Publication year
- Genres

The JSON file is validated using JSONLint to ensure that the structure is correct.

File: `books.json`

## Question 2 - Retrieve and Display JSON Data
This question uses the JavaScript fetch() API to retrieve information from books.json and display the data on a webpage.

The webpage displays:
- Title of the first book.
- Author of the second book.
- Genres of both books grouped by their titles.

Error handling is also implemented to handle unsuccessful requests or invalid JSON data.

File: `books.html`

## Question 3 - Compare Native JavaScript and jQuery
This question demonstrates the use of jQuery to manipulate HTML elements and handle button click events.

The three operations are:
1. Change text from "Original Text" to "Modified Text".
2. Add the CSS class `myStyle` to the element with ID `myDIV`.
3. Display an alert message "Button clicked!" when the button is clicked.

jQuery methods used:
- `.text()`
- `.addClass()`
- `.on("click", ...)`

File: `jquery-dom.html`

## How to Run

1. Download or clone this repository.
2. Open the folder using Visual Studio Code.
3. Install the Live Server extension.
4. Open `books.html` using Live Server to test Question 2.
5. Open `jquery-dom.html` using Live Server to test Question 3.
6. For Question 1, open `books.json` in VS Code and validate it using JSONLint.

## Conclusion
This lab provides practical experience in handling JSON data, retrieving data using the fetch() API and manipulating HTML elements using jQuery.
