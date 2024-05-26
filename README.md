Certainly! Here's an updated README file that includes the `views/form.ejs` file in the code overview:

---

# Mini Message Board

Mini Message Board is a simple message board application built with Express.js and EJS. It allows users to submit messages with their names and displays all submitted messages on the home page.

## Features

- Display a list of messages
- Submit a new message with an author's name and message text
- Styled with basic CSS

## Usage

### Submitting a Message

1. On the home page, fill in the "Author" and "Message" fields in the form.
2. Click the "Submit" button to add your message.
3. The new message will be displayed on the home page along with the previously submitted messages.

### Navigating

- To go back to the home page, click the "Back to Home" link.

## Code Overview

- **app.js**: Sets up the Express application, configures the view engine (EJS), serves static files, and defines routes.
- **routes/index.js**: Defines the routes for the application.
  - Handles GET requests to display the home page (`/`).
  - Handles POST requests to submit a new message (`/new`).
- **views/index.ejs**: EJS template for the home page. Displays the list of messages and includes a form for submitting new messages.
- **views/form.ejs**: EJS template for the message submission form. Includes input fields for "Author" and "Message" and a submit button.
- **public/stylesheets/style.css**: CSS file for styling the application. Defines styles for form elements and messages.

---
