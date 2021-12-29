## Software Testing

- **Software testing** is the process of evaluating a software item to detect differences between the expected output and the actual output.
- Testing assesses the quality of the product.
- It should be done during the development process.
- Software testing is a verification and validation process.

## Test Driven Development

- **Test-driven development (TDD)** is an evolutionary approach to development which combines _test-first development_ and _refactoring_.
- It's one way to think _through your requirements_ or design before you write your functional code.
- One of TDD's primary goals is to write _clean code that works._
- To develop the habits you need to be successful with TDD (and software engineering in general) is to **write a failing test**. After that, write the code required to **make the test pass** (more on Red, Green, Refactor section).
- Writing a failing test first might seem _counter-intuitive_, _time-consuming_ and even _tedious_. But think of it this way:
  - The **test** is the question you are asking.
  - The **code** is the answer for that querstion.
  - By having a **clear question**, you can always ensure that your code is working, because it _consistently_ gives you the same answers.

## Test First Development

- **Test-first development (TFD)** is where you write a test before you write enough production code to fulfill that test.
- TFD is a slightly broader, less specific than TDD.

## Red, Green, Refactor

- TDD follows a 3-step process:
  1.  **Red - Write a failing test:** Understand the user requirement well enough to write a test that you expect.
  2.  **Green - Make the (failing) test pass:** Write only the code you need to make the previously failing test pass, while ensuring the existing test still pass.
  3.  **Refactor - Refactor the code you wrote:** Take the time to tidy up the code you wrote to make it simpler for your future self or colleagues before you ship the code.

# References

- https://github.com/dwyl/learn-tdd
- http://agiledata.org/essays/tdd.html
- http://tutorials.jenkov.com/java-unit-testing/test-first-development.html
