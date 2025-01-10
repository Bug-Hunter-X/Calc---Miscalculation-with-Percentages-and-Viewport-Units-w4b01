# CSS `calc()` Bug: Miscalculation with Percentages and Viewport Units

This repository demonstrates a bug where the CSS `calc()` function produces unexpected results when combining percentages and viewport units (like `vw` or `vh`).  The expected calculation doesn't match the rendered output.

## Bug Description

The `calc()` function is incorrectly evaluating expressions involving percentages and viewport units, leading to layout issues.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe the unexpected rendering of the element, showcasing the miscalculation by `calc()`.

## Solution

The solution involves using alternative units or restructuring the calculation to avoid the problematic combination.

See `bugSolution.css` for a corrected implementation.