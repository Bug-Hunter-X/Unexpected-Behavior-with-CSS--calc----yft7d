# Unexpected Behavior with CSS `calc()`

This repository demonstrates a common issue encountered when using the `calc()` function in CSS.  The problem stems from the interaction of `calc()` with other CSS properties and layout models (particularly flexbox).

The `bug.css` file contains the problematic code. The `bugSolution.css` file shows the corrected approach.

## Bug Description:

The `calc()` function in CSS is powerful, but it requires careful attention to detail, particularly when used with units (px, %, em, etc.).  Incorrect usage can cause unexpected behavior such as layout misalignment or elements not rendering as intended. This example highlights an issue that can arise in flexbox contexts. 

## How to Reproduce:

1. Clone this repository.
2. Open `index.html` (you'll need to create a simple HTML file) in your browser.
3. Observe the layout of the element(s) styled by `bug.css`.  It will demonstrate an unexpected result caused by the improper use of `calc()`. 
4. Replace `bug.css` with `bugSolution.css` to see the corrected layout.