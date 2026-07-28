# Med-AI Website Testing Project

## 1. Introduction

This repository contains a complete manual and automated testing project for the Med-AI website.

Website under test: [https://medaivn.com/](https://medaivn.com/)

The project includes software testing theory, a Test Plan, Manual Test Cases, Test Execution documentation, a Bug Report, a Test Summary Report, test evidence, and Playwright Automation Tests.

## 2. Project Objectives

1. Study the role and responsibilities of a Software Tester.
2. Identify the main public functions of the Med-AI website.
3. Prepare a complete Test Plan.
4. Design Manual Test Cases for the identified functions.
5. Execute the Test Cases and record actual results.
6. Report reproducible software defects.
7. Create Automation Tests using Playwright.
8. Store and manage the testing documents and source code on GitHub.

## 3. System Under Test

Med-AI is a web based medical information system related to Vietnamese medicinal herbs and traditional medicine.

The testing scope covers the following public functions:

1. Homepage
2. Navigation
3. Medicinal herb search
4. Medical chatbot
5. Symptom analysis
6. Drug interaction checking
7. Medicinal plant image recognition
8. About information
9. Terms of use
10. Privacy policy
11. Responsive interface
12. Basic accessibility
13. Basic security
14. Error handling

## 4. Repository Structure

```text
medaivn-website-testing/
│
├── README.md
├── package.json
├── playwright.config.js
├── .gitignore
│
├── documents/
│   ├── report-1-software-tester.md
│   ├── report-2-test-plan.md
│   ├── report-3-test-execution.md
│   ├── report-4-bug-report.md
│   └── report-5-test-summary.md
│
├── test-cases/
│   └── manual-test-cases.csv
│
├── tests/
│   ├── homepage.spec.js
│   ├── navigation.spec.js
│   ├── features.spec.js
│   └── quality.spec.js
│
└── evidence/
    └── README.md
```

## 5. Project Documents

### 5.1 Report 1

[Introduction to the Software Tester Role](documents/report-1-software-tester.md)

This report explains the definition, responsibilities, testing process, testing levels, testing types, required skills, testing tools, and the role of GitHub in software testing.

### 5.2 Report 2

[Test Plan for the Med-AI Website](documents/report-2-test-plan.md)

This document defines the testing objectives, scope, approach, environment, test data, entry criteria, exit criteria, risks, and deliverables.

### 5.3 Report 3

[Test Execution Report](documents/report-3-test-execution.md)

This document records the test environment, execution rules, executed Test Cases, actual results, test evidence, and testing limitations.

### 5.4 Report 4

[Bug Report](documents/report-4-bug-report.md)

This document records reproducible defects, including reproduction steps, actual results, expected results, Severity, Priority, and supporting evidence.

### 5.5 Report 5

[Test Summary Report](documents/report-5-test-summary.md)

This report summarizes the Manual Testing results, Automation Testing results, defects, remaining risks, and final evaluation.

### 5.6 Manual Test Cases

[Manual Test Cases](test-cases/manual-test-cases.csv)

This file contains the Manual Test Cases designed for the public functions of Med-AI.

## 6. Technologies and Tools

The project uses the following technologies and tools:

1. JavaScript
2. Node.js
3. Playwright
4. Google Chrome
5. Microsoft Edge
6. Visual Studio Code
7. Git
8. GitHub

## 7. Installation

### 7.1 Prerequisites

The following software must be installed:

1. Node.js
2. Visual Studio Code
3. Git
4. Google Chrome

### 7.2 Clone the Repository

```bash
git clone https://github.com/your-username/medaivn-website-testing.git
```

Replace `your-username` with the actual GitHub username.

Open the project folder:

```bash
cd medaivn-website-testing
```

### 7.3 Install Project Dependencies

```bash
npm install
```

### 7.4 Install Playwright Browsers

```bash
npx playwright install
```

## 8. Running Automation Tests

### 8.1 Run All Tests

```bash
npm test
```

### 8.2 Run Tests with a Visible Browser

```bash
npm run test:headed
```

### 8.3 Run Tests in Playwright User Interface Mode

```bash
npm run test:ui
```

### 8.4 Open the Playwright HTML Report

```bash
npm run report
```

After execution, Playwright stores its HTML report in:

```text
playwright-report/
```

Failed Test Cases may also produce screenshots, videos, and trace files in:

```text
test-results/
```

## 9. Manual Test Execution

The Manual Test Cases are stored in:

```text
test-cases/manual-test-cases.csv
```

Each Test Case must be executed according to its defined steps.

The tester must record:

1. Actual Result
2. Test Status
3. Supporting Evidence
4. Bug ID when a reproducible defect is found

The available statuses are:

1. Pass
2. Fail
3. Blocked
4. Not Run
5. Not Applicable

A Test Case must remain `Not Run` until it has been executed.

## 10. Test Evidence

Testing evidence is stored in the `evidence` folder.

Recommended file names include:

```text
TC-001-homepage.png
TC-013-herb-search.png
TC-023-chatbot.png
TC-033-symptom-analysis.png
TC-040-drug-interaction.png
TC-047-image-recognition.png
BUG-001.png
```

Evidence should only be collected from actual test execution.

## 11. Safety and Ethical Requirements

1. Only simulated data is used.
2. Real patient information must not be entered.
3. Artificial Intelligence output must not be treated as a confirmed medical diagnosis.
4. Destructive security testing is not permitted.
5. Automated tests must not intentionally change or delete medical data.
6. High volume requests must not be sent to the website.
7. Private medical images must not be uploaded.
8. A defect must not be reported without reproduction evidence.

## 12. Test Result Policy

The project must not claim that a Test Case has passed before it is executed.

The following rules apply:

1. Use `Pass` only when the actual result matches the expected result.
2. Use `Fail` when the actual result differs from the expected result.
3. Use `Blocked` when the Test Case cannot be completed.
4. Use `Not Run` when the Test Case has not been executed.
5. Use `Not Applicable` when the Test Case does not apply to the current system.

## 13. Current Project Status

| Deliverable | Status |
|---|---|
| Software Tester Report | Completed |
| Test Plan | Completed |
| Manual Test Case Design | Completed |
| Test Execution | Not Run |
| Bug Report | Pending actual execution |
| Test Summary Report | Pending actual execution |
| Playwright Test Scripts | Completed |
| Test Evidence | Pending actual execution |

## 14. Student Information

Student Name: Enter student name

Student ID: Enter student ID

Class: Enter class

Course: Software Testing

Lecturer: Enter lecturer name

Submission Date: Enter submission date

## 15. Disclaimer

This repository is created for educational software testing purposes.

The project evaluates the technical behaviour and usability of the public Med-AI website. It does not evaluate medical accuracy and does not provide professional medical advice.
