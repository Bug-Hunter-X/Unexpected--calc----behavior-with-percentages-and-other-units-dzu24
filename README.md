# Unexpected `calc()` Behavior with Percentages and Other Units in CSS

This repository demonstrates a common issue encountered when using the `calc()` function in CSS with a mix of percentages and other units.  The calculated value may differ from the expected result, leading to unexpected layout problems.

## Bug Description

When using `calc()` with percentages and other units, the order of operations and unit handling can lead to incorrect calculations.  This issue is particularly apparent when combining percentages with fixed units (like pixels).

## Bug Reproduction

The `bug.css` file contains CSS code that demonstrates this issue. The intended layout may not match the actual layout due to incorrect `calc()` evaluation.

## Solution

The `bugSolution.css` file provides a corrected version. The solution might involve adjusting the order of operations within the `calc()` expression or using alternative methods to achieve the desired layout.