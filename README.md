# Off-by-One Error in Java Array Loop

This repository demonstrates a common off-by-one error in Java when iterating over an array using a `for` loop.  The error occurs because the loop condition `i <= arr.length` attempts to access an index beyond the valid range of the array.

The `Bug.java` file contains the erroneous code.  The `BugSolution.java` file provides a corrected version.

This example highlights the importance of careful loop condition checking to prevent common array access errors.