# Incorrect DOM element access in HTML
This repository demonstrates a common yet subtle error in accessing DOM elements using JavaScript within HTML. The error lies in incorrectly referencing a DOM element with an ID without using the appropriate method provided by the Document Object Model (DOM). 

## Description
The `bug.html` file showcases an attempt to directly access and modify the innerHTML property of a div element with the id 'myDiv'. This is not the correct way to do this. The correct method is to use `document.getElementById("myDiv")`.

## Solution
The corrected code is present in `bugSolution.html`, showing the proper method using `document.getElementById()`. This ensures proper access to the DOM element.

## How to run
1. Clone this repository.
2. Open `bug.html` and `bugSolution.html` in a web browser.
3. Observe the differences in execution and behavior.