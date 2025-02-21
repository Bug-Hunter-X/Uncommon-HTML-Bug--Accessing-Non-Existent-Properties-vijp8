# Uncommon HTML Bug: Accessing Non-Existent Properties

This repository demonstrates an uncommon error in HTML that can occur when attempting to access properties of elements that do not exist. The bug is described below.  A solution is provided in `bugSolution.html`.

## Description
The script in the original `bug.html` file attempts to access a property (`nonExistentProperty`) that does not exist on the `div` element. This results in a JavaScript error.

## Solution
The solution in `bugSolution.html` addresses this by first checking if the property exists before attempting to access it. This prevents the error from occurring and ensures smoother execution.
