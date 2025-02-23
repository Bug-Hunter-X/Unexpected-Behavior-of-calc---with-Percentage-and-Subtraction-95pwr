# Unexpected Behavior of calc() with Percentage and Subtraction in CSS

This repository demonstrates a common, yet subtle, issue encountered when using the `calc()` function in CSS, specifically when combining percentage values with subtraction.  The problem arises when the calculated value becomes negative or very close to zero, leading to unexpected rendering behavior.  The example CSS code shows a scenario where the width of an element is calculated using `calc(50% - 10px)`, resulting in unpredictable behaviour depending on the parent container's width.

The `bug.css` file illustrates the problematic code, while `bugSolution.css` provides a solution to address this issue.

This example highlights the importance of thoroughly testing CSS calculations to ensure correct rendering across various screen sizes and parent container dimensions.