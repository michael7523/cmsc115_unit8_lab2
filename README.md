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
-

What was fixed:
-

What you learned:
-

Commit message:
-

---

## Final Reflection

- How did AI responses change across prompts?
- How did testing affect your changes?
- What did version control help you understand?