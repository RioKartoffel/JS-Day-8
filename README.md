# JS-Day-8
Form Wave Animation

This code consists of 3 components: HTML, CSS and JavaScript.

HTML

- The HTML code defines the structure and content of a web page.
- The **`<!doctype html>`** declares that this document is an HTML5 document.
- The **`<html>`** tag is the root element of the HTML document.
- The **`<head>`** tag contains information about the document, such as the title, meta-data, and link to the CSS file.
- The **`<body>`** tag contains the main content of the web page, which in this case is a login form.
- The form consists of two text inputs for email and password, a submit button, and a text link for registering a new account.

CSS

- The CSS code is used to style the HTML elements.
- The CSS file is linked to the HTML file using the **`<link>`** tag in the **`<head>`** section.
- The stylesheet uses CSS selectors to target specific HTML elements and apply styles to them.
- The styles applied include font family, background color, text color, padding, border radius, and positioning.
- The styles also define the behavior of the form when the input fields are in focus or have valid input.

JavaScript

- The JavaScript code adds interactivity to the web page.
- The JavaScript file is linked to the HTML file using the **`<script>`** tag in the **`<body>`** section.
- The code selects all the labels with the class **`form-control label`** using the **`querySelectorAll()`** method.
- Then, using the **`forEach()`** method, the JavaScript code modifies the inner HTML of each label.
- The inner HTML of each label is transformed into an array of **`<span>`** elements, where each **`<span>`** element represents a letter in the label.
- The delay for each **`<span>`** element is set using the **`transition-delay`** property, where each letter is delayed by an increment of 50 milliseconds.

This code creates a simple login form with a wave animation effect on the form labels when the input fields are in focus or have valid input.
