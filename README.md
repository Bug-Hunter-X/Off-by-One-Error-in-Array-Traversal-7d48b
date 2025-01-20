# Off-by-One Error in Array Traversal

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The `BuggyArraySum.java` file contains the buggy code, which attempts to sum the elements of an array but incorrectly iterates one element beyond the array bounds. This results in an `ArrayIndexOutOfBoundsException`.

The corrected version, `CorrectedArraySum.java`, shows how to avoid this error by using the `<` operator instead of `<=` in the loop condition.