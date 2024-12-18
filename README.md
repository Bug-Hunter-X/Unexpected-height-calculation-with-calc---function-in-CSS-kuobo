# Unexpected height calculation with calc() function in CSS

This repository demonstrates an unexpected behavior when using the `calc()` function in CSS to combine percentage and pixel values. The intended result is not achieved, and the element's height is incorrectly calculated.

## Bug

The `bug.css` file contains the CSS code that exhibits the unexpected behavior.  The element with the class `my-element` is supposed to have a height of 50% of its parent plus 20 pixels, but instead it only takes the pixel value.  

## Solution

The `bugSolution.css` file provides a corrected CSS code snippet that resolves this issue. By ensuring the percentage calculation is placed first, the expected outcome is achieved.