# Two Fer

`Two-fer` or `2-fer` is short for two for one. One for you and one for me.

```text
"One for X, one for me."
```

When X is a name or "you".

If the given name is "Alice", the result should be "One for Alice, one for me."
If no name is given, the result should be "One for you, one for me."

## Test-Driven Development

As programmers mature, they eventually want to test their code.

Here at Exercism we simulate [Test-Driven
Development](http://en.wikipedia.org/wiki/Test-driven_development) (TDD), where
you write your tests before writing any functionality. The simulation comes in
the form of a pre-written test suite, which will signal that you have solved
the problem.

It will also provide you with a safety net to explore other solutions without
breaking the functionality.

### A typical TDD workflow on Exercism:

1. Run the test file and pick one test that's failing.
2. Write some code to fix the test you picked.
3. Re-run the tests to confirm the test is now passing.
4. Repeat from step 1.
5. Submit your solution (`exercism submit /path/to/file`)

## Instructions

Submissions are encouraged to be general, within reason. Having said that, it's
also important not to over-engineer a solution.

It's important to remember that the goal is to make code as expressive and
readable as we can.

* * * *

For installation and learning resources, refer to the
[exercism help page](http://exercism.io/languages/ruby).

For running the tests provided, you will need the Minitest gem. Open a
terminal window and run the following command to install minitest:

    gem install minitest

If you would like color output, you can `require 'minitest/pride'` in
the test file, or note the alternative instruction, below, for running
the test file.

In order to run the test, you can run the test file from the exercise
directory. For example, if the test suite is called
`hello_world_test.rb`, you can run the following command:

    ruby hello_world_test.rb

To include color from the command line:

    ruby -r minitest/pride hello_world_test.rb


## Source

This is an exercise to introduce users to basic programming constructs, just after hello World. [https://en.wikipedia.org/wiki/Two-fer](https://en.wikipedia.org/wiki/Two-fer)

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.