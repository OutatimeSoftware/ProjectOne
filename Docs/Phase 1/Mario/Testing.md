# Testing

> Nov 3, 2020
> Passing test input to Scanner, unit testing, JUnit, Test-Driven development

Manually testing the program is often laborious. It's possible to automate the passing of input by, for example, passing the string to be read into a Scanner object.

String input = "one\n" + "two\n"  +
                "three\n" + "four\n" +
                "five\n" + "one\n"  +
                "six\n";

Scanner reader = new Scanner(input);

**Unit testing**
Refers to the testing of individual components in the source code, such as classes and their provided methods. The writing of tests reveals whether each class and method observes or deviates from the guideline of each method and class having a single, clear responsibility. The more responsibility the method has, the more complex the test. If a large application is written in a single method, writing tests for it becomes very challenging, if not impossible. Similarly, if the application is broken into clear classes and methods, then writing tests is straightforward.

<p align="center">
  <img src="https://github.com/OutatimeSoftware/ProjectOne/blob/main/Img/testDrivenDevelopment.png">
</p>

**Test-Driven development**

Test-driven software development consists of five steps that are repeated until the functionality of the program is complete.

1-Write a test. The programmer decides which program functionality to test and writes a test for it.

2-Run the tests and check if the tests pass. When a new test is written, the tests are run. If the test passes, the test is most likely erroneous and should be corrected - the test should only test functionality that hasn't yet been implemented.

3-Write the functionality that meets the test's requirements. The programmer implements functionality that only meets the test requirements. Note: this doesn't do things that the test does not require - functionality is only added in small increments.

4-Perform the tests. If the tests fail, there is likely to be an error in the functionality written. Correct the functionality - or, if there is no error in the functionality, fix the latest test that was performed.

5-Repair the internal structure of the program. As the size of the program increases, its internal structure is adjusted as needed. Methods that are too long are broken down into multiple parts and classes representing concepts are isolated. The tests are not modified, but are instead used to verify the correctness of the changes made to the program's internal structure - if a change in the program structure changes the functionality of the program, the tests will produce a warning and the programmer can remedy the situation.