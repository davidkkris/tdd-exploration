## Software Testing

- **Software testing** is the process of _evaluating_ a software item to detect differences between the _expected output_ and _the actual output_.
- Testing assesses the _quality_ of the product.
- It should be done during the development process.
- Software testing is a _verification_ and _validation_ process.

## Test Driven Development

- **Test-driven development (TDD)** is an evolutionary approach to development which combines _test-first development_ and _refactoring_.
- TDD is _a set of techniques_ that any software engineer can follow which encourages _simple designs_ and test suites that _inspire confidence._
- TDD is one way to think _through your requirements_ or design before you write your functional code.
- One of TDD's primary goals is to write _clean code that works._
- To develop the habits you need to be successful with TDD (and software engineering in general) is to _write a failing test_. After that, write the code required to _make the test pass_ (more on Red, Green, Refactor section).
- Writing a failing test first might seem _counter-intuitive_, _time-consuming_ and even _tedious_. But think of it this way:
  - The **test** is the _question_ you are asking.
  - The **code** is the _answer_ for that querstion.
  - By having a **clear question**, you can always ensure that your code is working, because it will _consistently_ give you the same answers.

## Test First Development

- **Test-first development (TFD)** is where you write a test before you write enough production code to fulfill that test.

## Red, Green, Refactor

- TDD follows a 3-step process:
  1.  **Red - Write a failing test:** Understand the user requirement well enough to write a test that you expect.
  2.  **Green - Make the (failing) test pass:** Write _only_ the code/just enough code you need to make the test pass.
  3.  **Refactor - Refactor the code you wrote:** Take the time to tidy up the code you wrote to make it simpler for your future self or colleagues before you ship the code. Refactor with confidence.

## TDD Common Pitfalls/Mistakes

- Another thing to remember when writing our preliminary tests (on the first step/Red phase) are to write **minimal test**. Developers tend to test too specific and too much.
- The most common mistakes developers often make is testing _implementation details_ not _behavior_. For example:
  - In a calculator app, if you want to calculate the square root of 9, it should not matter how the module does it, as long the end result is 3.
  - In a simple mapping method for a new data structure, don't check the data structure itself because there's a possibility that the data structure itself will change and your test will fail.

# References

- https://github.com/dwyl/learn-tdd
- http://agiledata.org/essays/tdd.html
- http://tutorials.jenkov.com/java-unit-testing/test-first-development.html
- https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnx0ZXN0MTIzNHNpbTQ2NXxneDpiYTJmYWIwYTAyOGJiZmQ
- https://medium.com/javascript-scene/testing-software-what-is-tdd-459b2145405c
