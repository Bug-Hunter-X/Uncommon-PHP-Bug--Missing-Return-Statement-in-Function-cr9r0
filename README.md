# Uncommon PHP Bug: Missing Return Statement
This repository demonstrates a common yet easily overlooked bug in PHP: a missing `return` statement in a function that's expected to return a value.  This can lead to unexpected behavior and hard-to-debug issues.  The solution shows how to correctly add the missing return statement.

## Bug
The `bug.php` file contains a function `myFunction` which lacks a `return` statement. This function is implicitly returning `null` when a value is expected. 

## Solution
The `bugSolution.php` file provides a corrected version of the function, explicitly including a `return` statement.