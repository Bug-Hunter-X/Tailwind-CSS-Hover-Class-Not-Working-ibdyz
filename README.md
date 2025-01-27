# Tailwind CSS Hover Class Not Working

This repository demonstrates a common issue where Tailwind CSS hover classes don't seem to apply correctly. The `hover:bg-blue-700` class should change the background color on hover, but it doesn't in the provided example.

## Problem
The problem is likely due to incorrect implementation or conflict with other CSS rules.  The `bug.js` file contains the buggy code, demonstrating the problem.  The solution is provided in `bugSolution.js`.

## Solution
The solution involves carefully examining your CSS for conflicts and making sure your Tailwind configuration is correct.  Often, specificity issues or conflicting styles override Tailwind's default classes.