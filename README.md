# Jaden Covington – Portfolio Page

## Overview

This project is my personal portfolio website created for my Web Interface class. The purpose of this page is to introduce myself, show my skills, and display my programming projects in one place. The site uses JavaScript to automatically load project information instead of hard-coding it in the HTML. When the page loads, it reads project data from browser storage and builds the project cards dynamically.

## How the Projects Section Works

I created an array of JavaScript objects where each object represents one project.
Each object contains:

* Project title
* Short summary
* Image/icon URL
* Link to the GitHub repository

The program converts the array into a string using `JSON.stringify()` and stores it in **sessionStorage**.
When the page loads, the script checks if the data already exists.

* If it does not exist, it stores the default project array.
* If it does exist, it retrieves the data and converts it back into objects using `JSON.parse()`.

After that, JavaScript dynamically creates the HTML elements (cards, images, text, and links) and displays them in the Projects section.

## Languages Used

* HTML
* CSS
* JavaScript

## Libraries / Frameworks

No external libraries were used.
This project was built using plain (vanilla) JavaScript.

## Storage Used

* **sessionStorage** – stores the project array data
* **localStorage** – stores the dark mode preference

## Features

* Dynamic project loading from JavaScript objects
* Dark mode toggle with saved preference
* Modal popup notice on page load
* Tooltip on the contact form button
* Contact form submission message
* DOM manipulation using JavaScript
* Automatic rendering of project cards

## How to Run

1. Open the website through GitHub Pages
   or
2. Download the files and open the HTML file in a web browser.

No installation or setup is required.

## Notes

The project section updates automatically whenever the project object array is changed in the JavaScript file. This makes the site easier to maintain because new projects can be added without editing the HTML structure.
# JavaScriptCourse
