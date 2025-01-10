# PHP Function with Unexpected Behavior

This repository demonstrates a subtle bug in a PHP function. The function `my_function` is intended to add two numbers, but its behavior is unexpected when the first argument is 0.  The issue arises from the use of `===` in the conditional, leading to unexpected results for specific inputs such as 0 and 0. 

The solution involves a careful review of the function's logic and the use of loose comparison in specific conditions to achieve the expected behavior.  Please review the files in this repository for a clear example of the bug and its correction.
