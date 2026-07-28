# REPORT 1
# INTRODUCTION TO THE SOFTWARE TESTER ROLE

Student Name: Enter student name

Student ID: Enter student ID

Class: Enter class

Course: Software Testing

Lecturer: Enter lecturer name

Submission Date: Enter submission date

## 1. Introduction

Software testing is an essential activity in the software development process. A software system may contain all required functions but still have defects that affect its reliability, security, performance, or user experience.

Testing helps the development team identify problems before the product is released. It also provides information about software quality and helps reduce risks for users and organizations.

A Software Tester is responsible for evaluating a software product, finding defects, and verifying that the system meets its specified requirements.

## 2. What Is a Software Tester?

A Software Tester is a member of a software development team who evaluates the quality of software.

The tester checks whether the system works correctly according to business and technical requirements. The tester also examines how the software behaves when users provide valid, invalid, missing, or unexpected data.

The purpose of testing is not only to find defects. It also helps prevent defects, improve product quality, reduce risks, and provide a better user experience.

Software testing cannot prove that a system contains no defects. However, it can provide evidence about the quality and reliability of the system within the tested scope.

## 3. Main Responsibilities of a Software Tester

### 3.1 Requirement Analysis

The tester reviews software requirements, business rules, user stories, use cases, and interface designs.

The main objectives are:

1. Understand what the system must do.
2. Identify the target users.
3. Understand the input data and expected output.
4. Identify unclear or incomplete requirements.
5. Determine which functions need to be tested.
6. Identify possible risks and exceptional situations.

### 3.2 Test Planning

The tester prepares a Test Plan before executing the tests.

A Test Plan normally defines:

1. Testing objectives.
2. Testing scope.
3. Functions included in testing.
4. Functions excluded from testing.
5. Testing methods.
6. Test environment.
7. Required tools and test data.
8. Testing schedule.
9. Entry and exit criteria.
10. Project risks and solutions.

### 3.3 Test Case Design

A Test Case describes a specific situation that must be tested.

A standard Test Case includes:

1. Test Case ID.
2. Test Case title.
3. Test objective.
4. Preconditions.
5. Test data.
6. Test steps.
7. Expected result.
8. Actual result.
9. Test status.

The tester should design both positive and negative Test Cases.

A positive Test Case verifies the system with valid data. A negative Test Case verifies how the system handles invalid, missing, or unexpected data.

### 3.4 Test Environment and Test Data Preparation

Before executing tests, the tester prepares the required environment and data.

This may include:

1. Operating systems.
2. Web browsers.
3. Mobile devices.
4. Test accounts.
5. Valid and invalid input data.
6. Database records.
7. Network conditions.
8. The correct application version.

For medical systems, testers should use simulated data instead of real patient information unless official permission has been provided.

### 3.5 Test Execution

The tester performs each Test Case and compares the actual result with the expected result.

A Test Case can have the following statuses:

1. Pass: The actual result matches the expected result.
2. Fail: The actual result does not match the expected result.
3. Blocked: The Test Case cannot be executed because of an environmental or functional problem.
4. Not Run: The Test Case has not been executed.
5. Not Applicable: The Test Case does not apply to the current system.

### 3.6 Defect Reporting

When a defect is found, the tester creates a Bug Report.

A complete Bug Report should contain:

1. Bug ID.
2. Bug title.
3. Affected function.
4. Test environment.
5. Preconditions.
6. Steps to reproduce.
7. Test data.
8. Actual result.
9. Expected result.
10. Severity.
11. Priority.
12. Screenshot, video, or log.
13. Current status.

A good Bug Report must be clear, accurate, and reproducible. A developer should be able to reproduce the defect by following the reported steps.

### 3.7 Retesting and Regression Testing

After a developer fixes a defect, the tester performs Retesting to confirm that the specific defect has been corrected.

The tester also performs Regression Testing to ensure that the change has not negatively affected other existing functions.

### 3.8 Test Reporting

At the end of a testing period, the tester prepares a Test Summary Report.

The report normally includes:

1. Total number of Test Cases.
2. Number of passed Test Cases.
3. Number of failed Test Cases.
4. Number of blocked Test Cases.
5. Number of defects.
6. Defects classified by severity.
7. Remaining risks.
8. Final testing conclusion.

## 4. Software Testing Process

A typical software testing process includes the following stages:

1. Requirement Analysis  
The tester studies the requirements and identifies the testable functions.

2. Test Planning  
The tester defines the testing scope, approach, resources, environment, and schedule.

3. Test Case Design  
The tester prepares Test Cases and test data.

4. Test Environment Setup  
The required software, hardware, accounts, browsers, and data are prepared.

5. Test Execution  
The tester performs the Test Cases and records the results.

6. Defect Reporting  
Differences between actual and expected results are documented.

7. Retesting  
The tester verifies that reported defects have been fixed.

8. Regression Testing  
The tester checks that existing functions still work after system changes.

9. Test Closure  
The tester summarizes the results, remaining risks, and final conclusion.

## 5. Main Levels of Software Testing

### 5.1 Unit Testing

Unit Testing checks individual functions, methods, classes, or modules. It is usually performed by developers.

### 5.2 Integration Testing

Integration Testing checks whether different modules, services, databases, or Application Programming Interfaces work correctly together.

### 5.3 System Testing

System Testing evaluates the complete application as an integrated system.

### 5.4 Acceptance Testing

Acceptance Testing verifies whether the system meets business needs and is ready for delivery to the customer or end user.

## 6. Common Types of Software Testing

### 6.1 Functional Testing

Functional Testing verifies that each function operates according to the specified requirements.

Examples include login, searching, submitting forms, and displaying information.

### 6.2 User Interface Testing

User Interface Testing checks visual components such as text, colours, images, buttons, forms, menus, and page layouts.

### 6.3 Usability Testing

Usability Testing evaluates whether the application is easy to understand and use.

### 6.4 Compatibility Testing

Compatibility Testing checks the application on different browsers, operating systems, screen sizes, and devices.

### 6.5 Performance Testing

Performance Testing evaluates response time, stability, resource usage, and system behaviour under different workloads.

### 6.6 Security Testing

Security Testing evaluates authentication, authorization, data protection, session management, and other security risks.

Advanced security testing should only be performed with clear authorization and an approved testing scope.

### 6.7 Smoke Testing

Smoke Testing checks the most important functions to determine whether a software version is stable enough for detailed testing.

### 6.8 Regression Testing

Regression Testing checks existing functions after software changes to ensure that they still operate correctly.

## 7. Manual Testing and Automation Testing

| Criterion | Manual Testing | Automation Testing |
|---|---|---|
| Execution | Performed directly by a tester | Performed by test scripts |
| Programming knowledge | Usually not required | Required |
| Initial preparation | Simple | Requires framework and code |
| Repeated execution | Time consuming | Fast and consistent |
| Exploratory testing | Highly suitable | Limited |
| Regression testing | Less efficient | Highly suitable |
| Human observation | Strong | Limited |
| Maintenance | Test documents must be updated | Test scripts must be updated |

Manual Testing and Automation Testing support each other. Automation is useful for repeated and stable processes, while Manual Testing is important for exploratory testing, usability evaluation, and unexpected user behaviour.

## 8. Severity and Priority

Severity represents how seriously a defect affects the system.

1. Critical: The system is unavailable, data is lost, or a serious security risk exists.
2. High: A main function does not work and there is no acceptable alternative.
3. Medium: A function works incorrectly but an alternative solution exists.
4. Low: A minor interface, content, or usability problem exists.

Priority represents how quickly a defect should be fixed.

1. P1: The defect must be fixed immediately.
2. P2: The defect should be fixed in the current release.
3. P3: The defect can be fixed in a future release.
4. P4: The defect has low urgency.

Severity and Priority are related but not identical. A spelling error may have low Severity but high Priority if it appears on the homepage and affects the professional image of the product.

## 9. Skills Required for a Software Tester

A Software Tester should have the following skills:

1. Logical and analytical thinking.
2. Attention to detail.
3. Understanding of software development processes.
4. Ability to design Test Cases.
5. Ability to write clear Bug Reports.
6. Communication and teamwork skills.
7. Basic knowledge of databases and Application Programming Interfaces.
8. Basic knowledge of Git and GitHub.
9. Programming skills for Automation Testing.
10. Awareness of information security and data privacy.

## 10. Tools Used by Software Testers

Common testing tools include:

1. Jira for task and defect management.
2. Postman for Application Programming Interface testing.
3. Playwright for automated web testing.
4. Selenium for automated browser testing.
5. Cypress for automated front end testing.
6. JMeter for performance testing.
7. Chrome DevTools for inspecting elements, requests, and console errors.
8. Git for version control.
9. GitHub for storing code, documents, and project history.
10. Visual Studio Code for writing and running test scripts.

## 11. The Role of GitHub in Software Testing

GitHub is useful for both developers and testers.

A tester can use GitHub to:

1. Store automation test code.
2. Store Test Plans, Test Cases, and testing reports.
3. Track changes to testing documents.
4. Share test scripts with team members.
5. Review previous versions.
6. Manage reported issues.
7. Connect automated tests to a Continuous Integration process.
8. Provide the repository link as evidence of completed work.

## 12. Conclusion

A Software Tester plays an important role in the software development process. The tester reviews requirements, prepares Test Plans, designs Test Cases, executes tests, reports defects, verifies bug fixes, and evaluates product quality.

Modern software testing combines Manual Testing and Automation Testing. Manual Testing provides human observation and exploratory evaluation, while Automation Testing increases the speed and consistency of repeated tests.

The tester does not only search for defects. The tester also helps prevent problems, reduce project risks, improve the user experience, and provide reliable information before the software is released.
