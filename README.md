# Java ConcurrentModificationException Example

This repository demonstrates a common Java error: the `ConcurrentModificationException`.  The `ConcurrentModificationExceptionExample.java` file contains code that throws this exception. The `ConcurrentModificationExceptionExampleSolution.java` file provides a corrected version.

The problem arises when modifying a collection (like an ArrayList) while iterating through it using a for-each loop or an enhanced for loop.  The solution involves using an Iterator to safely remove elements while iterating.

This example showcases how to avoid this exception and write safer, more robust Java code.