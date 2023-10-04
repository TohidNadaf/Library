# Library Project-8
# Library Project Documentation

## Overview
The Library Project is a web-based application that allows users to create a virtual library of books. Users can add new books, mark books as read or unread, and remove books from their library. This project is implemented using HTML, CSS, and JavaScript.

## Project Structure
The project consists of the following components:

### HTML Structure
1. `<!DOCTYPE html>`: Declares the document type and HTML version.
2. `<html>`: The root HTML element.
3. `<head>`: Contains metadata and links to external resources such as stylesheets.
4. `<meta>`: Meta tags for character encoding, viewport settings, and compatibility.
5. `<title>`: The title of the web page displayed in the browser tab.
6. `<body>`: The main content of the web page.

### CSS Styling
They are used to style various elements of the webpage, including the library display, pop-up form, buttons, and more.

### JavaScript
The JavaScript code at the end of the document provides the interactivity and functionality of the Library Project. Here are the key functionalities:

1. **Pop-up Form**: Clicking the "+ New Book" button displays a pop-up form that allows users to enter book details such as title, author, pages, and mark the book as read or unread.

2. **Book Constructor**: Defines a JavaScript class called `Book` for creating book objects with the entered details.

3. **Adding Books**: When users submit the form, a new `Book` object is created, added to the `myLibrary` array, and saved in local storage using the `setData()` function.

4. **Rendering Books**: The `render()` function displays the user's library by creating DOM elements for each book. It includes details such as title, author, pages, and buttons to mark as read/unread or remove the book.

5. **Removing Books**: Users can click the "Remove" button to delete a book from their library. The book is removed from both the display and local storage.

6. **Toggling Read Status**: Users can click the "Read" or "Not Read" buttons to toggle the read status of a book. The status is updated in both the display and local storage.

7. **Local Storage**: The `localStorage` object is used to persist the user's library data so that it can be restored when the page is refreshed.

## How to Use
1. Open the HTML file in a web browser.
2. The Library Project webpage will load.
3. Click the "+ New Book" button to add a new book to your library.
4. Fill in the book details in the pop-up form and click "Add."
5. The book will be added to your library.
6. To mark a book as read or unread, click the respective button.
7. To remove a book, click the "Remove" button.
8. Your library data is stored locally, so it will persist even if you refresh the page.

## Project Goals
The Library Project provides a simple and interactive way to manage a personal book collection. Users can easily add, remove, and track the reading status of their books, all within a user-friendly web interface.
