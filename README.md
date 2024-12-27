# Subtle `calc()` Syntax Error in CSS

This repository demonstrates a subtle but impactful error that can occur when using the `calc()` function in CSS.  The issue is a missing space around the minus operator within the calculation, leading to unexpected layout behaviors. While not a typical syntax error flagged by many compilers, this omission can cause considerable debugging headaches.

## The Problem

The original CSS code (in `bug.css`) incorrectly omits spaces around the minus operator within the `calc()` function.  This prevents the browser from correctly parsing the calculation, leading to the element not being rendered as expected.

## The Solution

The corrected CSS code (in `bugSolution.css`) shows the proper use of the `calc()` function. The key fix is adding spaces around the minus operator to allow for correct calculation.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your browser. Note the layout of the element.
3. Open `bugSolution.html` in your browser. Note the corrected layout of the element.

This showcases the importance of precise syntax when using CSS's `calc()` function, highlighting that even small omissions can have significant consequences.