# CSS `calc()` Unexpected Behavior with Percentages

This repository demonstrates a subtle bug related to the CSS `calc()` function when using percentages in combination with other units.  The expected calculation doesn't produce the intended result.

## Bug Description
The `calc()` function is not correctly evaluating the expression involving percentages and pixels, leading to unexpected layout issues.

## Solution
The solution involves restructuring the calculation to ensure proper order of operations and unit handling within `calc()`.  This ensures accurate rendering and layout.