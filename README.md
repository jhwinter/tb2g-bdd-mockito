# BDD Mockito

All source code examples in the repository are for my [Online Course - Testing Spring Beginner to Guru](https://www.udemy.com/testing-spring-boot-beginner-to-guru/?couponCode=GITHUB_REPO)

This source code repository contains JUnit 5 and Mockito BDD test examples with Maven.

## Setup
### Requirements
* Should use Java 11 or higher. Previous versions of Java are un-tested.
* Use Maven 3.5.2 or higher

## Support
For questions and help:
* Please post in course
* Or post in the Slack Community exclusive to the course.

GitHub Issues will not be addressed.



## Notes

### Behavior Driven Development

* Commonly abbreviated as BDD
* BDD was established to help people learn TDD
* BDD is largely a different way of looking at testing
* BDD focuses on behavior vs "tests"
* "Unit Tests" are referred to as specification - ie specifications of behaviors
* Test method name should be sentences - ie saveValidID

### Given When Then

* BDD tests are often written in a given-when-then context
* This approach often helps you organize your thoughts when writing the test
* **Given** - Setup of the test
* **When** - Action of the test - ie when method is called
* **Then** - Verification of expected results

### Mockito and BDD

* Mockito has added BDD support in class BDDMockito
* static method `given` allows you to configure mocks
* static method `then` allows you to verify mock interactions
