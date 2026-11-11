# bic21203-lab4b-jsonandquery

## Student Information
Name: Muhammad Shameel bin Sharifuddin
Student ID: AI240030
Course: BIC21203 Web Development

Project Description

This project demonstrates how to create and use JSON data, retrieve JSON data using JavaScript fetch(), and manipulate HTML elements using jQuery.

Files Included

books.json – Contains information about two books in JSON format.
books.html – Retrieves and displays book information using JavaScript fetch().
jquery-dom.html – Demonstrates DOM manipulation and event handling using jQuery.

Setup Instructions

Question 1: Create and Structure JSON Data

1.Open Visual Studio Code.
2.Create a file named books.json.
3.Create a top-level books array containing two book objects.
4.Add the following properties to each book:
-title
-author
-publicationYear
-genres
5.Save the file and ensure the JSON syntax is valid.

Question 2: Retrieve and Display JSON Data

1.Create a file named books.html.
2.Create the basic HTML structure.
3.Use JavaScript fetch() to retrieve data from books.json.
4.Convert the response into JSON using response.json().
5.Display the first book's title and the second book's author.
6.Use forEach() to display the genres of both books.
7.Use textContent and createElement() to display the information.
8.Add error handling using try...catch.
9.Run books.html using Visual Studio Code Live Server.
10.Check the displayed information in the browser.

Question 3: Compare Native JavaScript and jQuery

1.Create a file named jquery-dom.html.
2.Add the required HTML elements: myElement, myDIV, and myButton.
3.Add the .myStyle CSS class with a coral background and 16px padding.
4.Include the jQuery 4.0.0 CDN link:
https://code.jquery.com/jquery-4.0.0.min.js
5.Use .text() to change the text to "Modified Text".
6.Use .addClass() to add the myStyle class.
7.Use .on("click") to display an alert when the button is clicked.
8.Run the file using Live Server and test all three operations.

How to Run the Project

1.Open the project folder in Visual Studio Code.
2.Install the Live Server extension if necessary.
3.Right-click books.html and select Open with Live Server.
4.Check that the JSON information is displayed correctly.
5.Open jquery-dom.html using Live Server.
6.Test the text modification, CSS styling, and button click event.

Note: Use Live Server to run books.html because the JavaScript fetch() API requires a local server to retrieve the JSON file.

Expected Results:
Successfully create and parse JSON data.
Retrieve and display information from books.json.
Successfully perform three DOM operations using jQuery.
Display the expected results in the browser.

screenshot
question 1: Picture1.png
question 2: Picture2.png
question 3: Picture3.png, Picture4.png
