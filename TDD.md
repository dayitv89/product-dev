![](https://media1.tenor.com/images/9c077f58ddad4b19543a9fed0ff057db/tenor.gif?itemid=4607935)
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTNxLZUMXCKYtUfp3qZtQdB9FlmQ15Y3bbkUfB34SAaifcGH1lQ)

# Test Driven Development

One of the methods of _Agile_ is Test-Driven Development. So,

### What is TDD?

Test-driven development (TDD) is a development process that relies on the repetition of a very short development cycle requirements are turned into very specific test cases, then the product is improved to pass the new tests, only.

In a simple manner , you are developing something but it would be useless if it does not passes the tests, so you are given test cases and you start developing something that should pass the test case given to you, if it fails then you move to review the code and make changes so that it runs according to the test case. If it passes then you move towards the new test case and start developing for that particular test and this process is followed until your product passes all the test cases and the product satisfies the customer.

![An image which shows the cycle of TDD.](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRtBXUU70eMsRrmjMyD2T5aOPpDODsNGIQLyhTDmgW9Pqzdg1Z7)

#### Steps of TDD can be-

1. The first step is to quickly add a test, basically pick the test case and make something fot that case to pass or fail.
1. Next you run your tests, often the complete test suite although for sake of speed you may decide to run only a subset, to ensure that the new test does in fact fail.
1. You then update your functional code to make it pass the new tests.
1. The fourth step is to run your tests again. If they fail you need to update your functional code and retest.
1. Once the tests pass the next step is to start over.

As a software developer the pros and cons of using TDD can be-

#### Benefits

1. Makes code easier to maintain and refactor.
1. Makes collaboration easier and more efficient, team members can edit each others code with confidence because the tests will inform them if the changes are making the code behave in unexpected ways.
1. Helps prevents defects – well, at least it helps you find design or requirement issues right at the beginning. TDD provides early warning to design problems (when they are easier to fix).
1. Creates an automated regression test suite, basically for free. i.e. you don’t need to spend time afterwards writing unit tests to test the implementation code.
1. “Stupid” mistakes are caught almost immediately. It helps developers find mistakes that would waste everyone’s time if they were found in QA.

#### Drawbacks

1. Initially, it slows down development; for rapidly iterative startup environments the implementation code may not be ready for some time due to spending time writing tests first.
1. The test suite itself has to be maintained; tests may not be completely deterministic (i.e. reliant on external dependencies).
1. Although it is absolutely necessary, creating tests for failures can be tedious, but it pays off big time in the end.
1. Unless everyone on the team correctly maintains their tests, the whole system can quickly degrade.

TDD cannot be used where a customer changes their need after sometime, or if there is new functionality added after the product development has been started. It would be a waste of time if the requirement of the user changes, then the developer has to again write the tests, again refactor, So it can be very tedious. But on the other hand if you are given something whose functionality will be same forever and only some small changes would be done afterwards then TDD would be very helpful.
