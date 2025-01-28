# Inconsistent Indentation and Unclosed Nested List in HTML

This repository demonstrates a common, yet often overlooked, error in HTML: improper nesting and closing of unordered lists (<ul>).  Inconsistent indentation can make this type of error harder to spot, leading to unexpected visual results in the rendered HTML.

The `bug.html` file contains the erroneous code. The `bugSolution.html` file provides the corrected version.

## Bug

The primary issue is the missing closing `</ul>` tag for the inner unordered list and poor indentation, making the structure unclear and prone to rendering issues.