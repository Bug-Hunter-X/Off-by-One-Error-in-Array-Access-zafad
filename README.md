# Off-by-One Error in Array Access

This Java code demonstrates a common off-by-one error when iterating through an array.  The loop condition `i <= arr.length` is incorrect and causes an `ArrayIndexOutOfBoundsException`.  The solution shows how to correct the loop condition to avoid this error.

## Bug
The `bug.java` file contains the buggy code.  This code attempts to access an element outside the valid bounds of the array. 

## Solution
The `BugSolution.java` file shows the corrected code. The loop condition is changed to `i < arr.length` to prevent the out-of-bounds access.