# Assignment 2 : Tiny Boy Coverage

Expand a tool for generating test coverage information for the AVR simulator using fuzzing. The tests are sequences made up of the following commands: 'U', 'D', 'R', 'L', and '_'.

Fuzzing checks possible tests that the user couldn't think of or doesn't have the time to create.

- Generate a new set of sequences to test with based on the previous experience. 
  - Use the previous sequences that produce the largest test coverage.
  - Don't use tests which are subsumed by another.
