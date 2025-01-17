# Testing

Testing is a crucial part of software development. It is also a topic that brings a lot of debate and discussion.
At the beginning, junior developers hate testing. It may seem as boring and a waste of time.
As soon as they face real life incident in production, they start to understand the importance of testing.

When the pain of writing tests is less than the pain of dealing with production incidents, unhappy or angry customers and stakeholders, they start to love testing.

## Manual Testing

Manual testing is the process of testing manually some or all of the features of a software.
It can be testing a function or a whole application.

Conceptually speaking there is nothing wrong with manual testing. As long as you have a good test plan, and you are disciple enough to run the test rigorously everytime you make a change.
In reality, you will quickly discover that this is time-consuming and error-prone. But if the costumer is really to pay for manual testing, it is not necessarily wrong. A small program that does not change often, may not need automated testing.

As soon as your program grows and changes often, you will quickly discover that manual testing is not sustainable.

The biggest issue is that you have to test every functionality every time you publish a new release. This can become a nightmare if you need to fix a bug quickly as you can create new bugs.
These new bugs are called regression bugs. They are bugs that were not present in the previous version of the software. If you face a major incident and your bug fix create a new major incident because you did not re-test everything. You will quickly understand the importance of automated testing.

## Unit Testing

A unit test is the smallest test you can write. It tests a function or part of a function. You write a function that tests another function to see if the last one works.

Such a test should be executed fast because you way execute it very often as you develop your software.

## Integration Testing

## End-to-End Testing

## Performance Testing

## Security Testing

## Accessibility Testing

## Usability Testing

## A/B Testing