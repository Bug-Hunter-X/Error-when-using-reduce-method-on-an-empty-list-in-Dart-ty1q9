# Error when using reduce method on an empty list in Dart

This repository contains a bug report and solution for an error encountered when using the `reduce` method on an empty list in Dart. The `reduce` method is a powerful tool for processing lists, but it can lead to errors if not handled correctly when dealing with empty lists.

## Bug Description
The `reduce` method throws a state error when used on an empty list because it requires at least one element to perform the reduction operation.  This leads to unexpected application crashes if not handled gracefully.

## Bug Solution
The solution involves adding a check to ensure the list is not empty before calling `reduce`. If the list is empty, a default value is returned, preventing the error.

## How to reproduce
1. Clone the repository.
2. Open the `bug.dart` file. 
3. Run the Dart code.  You'll observe the error.
4. Open the `bugSolution.dart` file. This version incorporates the solution and runs without errors. 