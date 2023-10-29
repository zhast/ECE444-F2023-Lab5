# ECE444-F2023-Lab5

Test-Driven Development (TDD) is where tests are written before the code is. The process of writing this kind of code is know as Red-Green-Refactor. This means first a test is written to test for failures (Red), then the code is written to pass the test (Green), and then finally the code is made cleaner (Refactor). There are many pros and cons to this method of development. 

First the benefits:
Thinking about code in this way forces programmers to think about how the end product aligns with the requriements. If not, then this can be detected early through the test cases before any code is actually written. Debugging this code through unit tests is also much simpler than littering your code with print statements that you manually check in terminal. Writing the code this way can also encourage modular code where the code coverage is very high, as parts of the program are written with the intention of being run through test cases. Often, this forces structuring the code in a organized way, making refactoring easier later on as well. 

However, there are also drawbacks associated with this kind development. Most obviously, there is a lot of initial overhead. Writing code in TDD can be slow in the beginning because of the additional time spent writing tests, which comes before any progress is made. It also takes time to initially adopt this strategy, where the programmer must learn how to write effective tests as well as learning and setting up the software used to do these tests. This can slow development in the beginning, but results in cleaner code in the end. 

In summary, TDD can improve the quality and maintainability of code. However, the overhead in writing and maintaining tests, as well as the learning curve for mastering testing are major drawbacks, especially in fast paced environments with tight deadlines. 

# My test cases
https://github.com/ECE444-2023Fall/project-1-web-application-design-group22-premium-potatoes/blob/steven_dev_test/api/tests/app_test.py#L6-L86