# Reflection – AI Number Program Lab

##  Student Name:
Michael Felix

##  GitHub Repository Link:
https://github.com/michael7523/cmsc115_unit8_lab2.git

## Iteration 1

What the AI code does:
- The AI-generated code creates the `findResult` method and returns `0` for any array passed into it.

Tests passed/failed:
- The program compiled and ran successfully.
- Tests expecting the program to return the largest number would fail because the method always returns `0`.

What surprised you:
- I was surprised that the program could compile and run even though the method did not actually solve the intended problem.

Commit message:
- Iteration 1: AI-generated implementation

---

## Iteration 2

What changed:
- The `findResult` method was changed so that it now checks the values in the array and finds the largest integer.

What improved:
- The program now correctly returns the largest number in the sample array.
- For the array `{3, 7, 2, 9, 4}`, the program returned `9`.

What still failed and why:
- The method would still fail if the array were empty because it tries to access `values[0]`, but an empty array has no element at index 0.

Commit message:
- Iteration 2: largest value implementation

---

## Iteration 3

Final behavior:
- The final version returns the largest integer in the array.
- If the array is empty, the method returns `Integer.MIN_VALUE`.

What was fixed:
- I added a check for an empty array before the program tries to access `values[0]`.
- This prevents an error when the array has no elements.

What I learned:
- I learned that edge cases are important when writing and testing code.
- I also learned how JUnit testing and multiple iterations can help improve a program.

Commit message:
- Iteration 3: final version passing all tests---

## Final Reflection

This lab showed me how AI, testing, and Git can work together during software development. The first version of the program compiled and ran, but it did not actually solve the intended problem. The second version improved the method by finding the largest number in the array, but it still had an issue with empty arrays.

In the final version, I added a check for an empty array so the method returns `Integer.MIN_VALUE`. This fixed the remaining issue. I learned that AI-generated code still needs to be tested, and that JUnit tests are useful for finding errors and edge cases. I also learned how Git commits can be used to track different versions of a program.