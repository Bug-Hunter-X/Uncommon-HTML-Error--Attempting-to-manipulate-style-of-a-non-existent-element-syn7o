# Uncommon HTML Bug: Non-Existent Element Style Manipulation

This repository demonstrates a subtle bug that can occur in HTML when attempting to manipulate the style of an element that does not exist.  In strict mode, this results in a runtime error. The solution showcases how to correctly handle potential null values.

## Bug
The `bug.html` file contains the faulty code. It tries to hide the div element with the id "myDiv" but fails silently if the element does not exist.

## Solution
The `bugSolution.html` file provides a corrected version. It adds a null check to prevent the error from occurring.

## How to reproduce
1. Open `bug.html` in your browser's developer console.  Observe the error in the console.
2. Open `bugSolution.html` and observe that the element is handled correctly without any errors.