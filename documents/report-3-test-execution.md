# REPORT 3
# TEST EXECUTION REPORT FOR THE MED-AI WEBSITE

Student Name: Enter student name

Student ID: Enter student ID

Class: Enter class

Course: Software Testing

Lecturer: Enter lecturer name

Website Under Test: [https://medaivn.com/](https://medaivn.com/)

Report Version: 1.0

Execution Status: Not Started

## 1. Purpose

This report documents the execution of Manual Test Cases and Playwright Automation Tests for the Med-AI website.

The report records:

1. Test environment.
2. Test execution procedure.
3. Test Case results.
4. Supporting evidence.
5. Identified defects.
6. Testing limitations.
7. Final execution status.

The results must only be updated after the corresponding Test Cases have been executed.

## 2. Test Scope

The execution scope includes:

1. Homepage.
2. Navigation.
3. Footer and internal links.
4. Medicinal herb search.
5. Medical chatbot.
6. Symptom analysis.
7. Drug interaction checking.
8. Medicinal plant image recognition.
9. Information pages.
10. Responsive interface.
11. Basic accessibility.
12. Basic security.
13. Error handling.
14. Playwright Automation Tests.

## 3. Test Basis

Testing is based on the following project documents:

1. Report 1: Introduction to the Software Tester Role.
2. Report 2: Test Plan for the Med-AI Website.
3. Manual Test Cases stored in `test-cases/manual-test-cases.csv`.
4. Public behaviour of the Med-AI website.
5. Common web usability, accessibility, and security expectations.

## 4. Test Environment

The actual environment must be completed before test execution.

| Component | Actual Environment |
|---|---|
| Website | https://medaivn.com/ |
| Operating System | Enter operating system |
| Computer | Enter computer information |
| Primary Browser | Enter browser and version |
| Additional Browser | Enter browser and version |
| Desktop Resolution | Enter screen resolution |
| Mobile Viewport | 412 x 915 |
| Internet Connection | Enter connection type |
| Node.js Version | Enter after installation |
| Playwright Version | Enter after installation |
| Execution Start Date | Not Started |
| Execution End Date | Not Started |

## 5. Test Data

Only simulated data is used.

The main test data includes:

1. Valid medicinal herb keyword: `Gừng`.
2. Partial keyword: `Gừ`.
3. Unknown keyword: `xyznotaherb123`.
4. Special characters: `!@#$%^&*`.
5. Empty values.
6. Long text containing more than 256 characters.
7. Simulated symptom: `Đau đầu`.
8. Simulated multiple symptoms: `Đau đầu và buồn nôn`.
9. Valid JPG test image.
10. Valid PNG test image.
11. Blurred plant image.
12. Unrelated image.
13. Unsupported TXT file.

Real patient information must not be used.

## 6. Test Execution Procedure

Each Manual Test Case must be executed using the following process:

1. Open `test-cases/manual-test-cases.csv`.
2. Select the next Test Case with the `Not Run` status.
3. Confirm that all Preconditions are satisfied.
4. Prepare the required Test Data.
5. Perform each Test Step in the defined order.
6. Compare the Actual Result with the Expected Result.
7. Record the Actual Result.
8. Update the Test Status.
9. Capture evidence when required.
10. Create a Bug Report if a reproducible defect is found.
11. Continue with the next Test Case.

## 7. Test Status Definitions

### 7.1 Pass

Use `Pass` when the Actual Result matches the Expected Result.

### 7.2 Fail

Use `Fail` when the Actual Result differs from the Expected Result.

A failed Test Case must include:

1. A clear Actual Result.
2. Screenshot or video evidence.
3. A Bug ID when the defect is reproducible.

### 7.3 Blocked

Use `Blocked` when the Test Case cannot be completed because of:

1. Website unavailability.
2. Network problems.
3. A dependent function failure.
4. Missing test data.
5. Missing environmental requirements.

### 7.4 Not Run

Use `Not Run` when the Test Case has not been executed.

### 7.5 Not Applicable

Use `Not Applicable` when the Test Case does not apply to the current website version.

A reason must be recorded for every Not Applicable result.

## 8. Initial Test Execution Summary

The following table represents the status before actual execution.

| Result | Quantity |
|---|---:|
| Total Test Cases | 68 |
| Pass | 0 |
| Fail | 0 |
| Blocked | 0 |
| Not Run | 68 |
| Not Applicable | 0 |
| Executed Test Cases | 0 |
| Pass Rate | Not Available |

This table must be updated after actual execution.

## 9. Initial Results by Module

| Module | Total | Pass | Fail | Blocked | Not Run | Not Applicable |
|---|---:|---:|---:|---:|---:|---:|
| Smoke Testing | 2 | 0 | 0 | 0 | 2 | 0 |
| Homepage | 4 | 0 | 0 | 0 | 4 | 0 |
| Navigation | 4 | 0 | 0 | 0 | 4 | 0 |
| Footer | 1 | 0 | 0 | 0 | 1 | 0 |
| Links | 1 | 0 | 0 | 0 | 1 | 0 |
| Herb Search | 11 | 0 | 0 | 0 | 11 | 0 |
| Chatbot | 10 | 0 | 0 | 0 | 10 | 0 |
| Symptom Analysis | 7 | 0 | 0 | 0 | 7 | 0 |
| Drug Interaction | 8 | 0 | 0 | 0 | 8 | 0 |
| Image Recognition | 7 | 0 | 0 | 0 | 7 | 0 |
| Information Pages | 3 | 0 | 0 | 0 | 3 | 0 |
| Responsive | 3 | 0 | 0 | 0 | 3 | 0 |
| Accessibility | 2 | 0 | 0 | 0 | 2 | 0 |
| Quality | 2 | 0 | 0 | 0 | 2 | 0 |
| Security | 2 | 0 | 0 | 0 | 2 | 0 |
| Error Handling | 1 | 0 | 0 | 0 | 1 | 0 |
| Total | 68 | 0 | 0 | 0 | 68 | 0 |

This table must be updated after actual execution.

## 10. Pass Rate Calculation

The Pass Rate must be calculated using:

`Pass Rate = Passed Test Cases / Executed Test Cases x 100%`

Executed Test Cases include:

1. Pass.
2. Fail.
3. Blocked.

Not Run and Not Applicable Test Cases are not included in the Pass Rate calculation.

Because no Test Case has been executed, the current Pass Rate is:

```text
Not Available
```

## 11. Manual Test Execution Record

The detailed execution results are stored in:

```text
test-cases/manual-test-cases.csv
```

The following fields must be updated:

1. Actual Result.
2. Status.

Recommended additional information may be included in the Actual Result:

1. Execution date.
2. Browser.
3. Evidence file name.
4. Bug ID.
5. Additional observation.

## 12. Test Evidence

Evidence must be stored in the `evidence` folder.

Recommended file names include:

```text
TC-001-homepage.png
TC-014-valid-herb-search.png
TC-018-empty-herb-search.png
TC-025-chatbot-question.png
TC-033-emergency-response.png
TC-035-symptom-analysis.png
TC-042-drug-interaction.png
TC-050-valid-jpg-upload.png
TC-052-invalid-file-upload.png
TC-060-mobile-interface.png
TC-068-page-not-found.png
BUG-001.png
```

Evidence should clearly show:

1. The tested function.
2. The entered Test Data.
3. The Actual Result.
4. The relevant error message.
5. The browser address when necessary.

## 13. Defect Recording

A Bug Report must be created when:

1. A Test Case fails.
2. The problem can be reproduced.
3. The Actual Result differs from the Expected Result.
4. Sufficient evidence is available.

Each Bug Report must include:

1. Bug ID.
2. Bug title.
3. Affected module.
4. Environment.
5. Preconditions.
6. Steps to reproduce.
7. Test Data.
8. Actual Result.
9. Expected Result.
10. Severity.
11. Priority.
12. Reproducibility.
13. Evidence.

Do not create an invented Bug Report.

## 14. Automation Test Execution

Automation Testing will be performed after the Playwright project is installed.

Required commands:

```bash
npm install
npx playwright install
npm test
```

The HTML report can be opened using:

```bash
npm run report
```

The Automation Test results must be recorded below after execution.

| Automation Result | Quantity |
|---|---:|
| Total Automated Tests | Not Run |
| Passed | Not Run |
| Failed | Not Run |
| Skipped | Not Run |
| Execution Duration | Not Available |

## 15. Testing Limitations

The following limitations apply:

1. Artificial Intelligence responses may change between executions.
2. Exact Artificial Intelligence response text cannot always be predicted.
3. Medical accuracy is not evaluated as a clinical diagnosis.
4. Administration functions are excluded.
5. Penetration testing is excluded.
6. High volume load testing is excluded.
7. Real patient information is not used.
8. Third party service behaviour may be outside the control of Med-AI.
9. Testing results only represent the tested environment and execution period.

## 16. Current Defect Status

No defect conclusion is available because testing has not started.

| Severity | Open | Fixed | Retest | Closed |
|---|---:|---:|---:|---:|
| Critical | 0 | 0 | 0 | 0 |
| High | 0 | 0 | 0 | 0 |
| Medium | 0 | 0 | 0 | 0 |
| Low | 0 | 0 | 0 | 0 |

This table must only be updated after reproducible defects are identified.

## 17. Current Execution Conclusion

The current execution status is:

```text
Not Started
```

All 68 Manual Test Cases currently have the `Not Run` status.

No conclusion about the quality or release readiness of Med-AI can be made before actual test execution.

After testing is completed, this section must be replaced with a conclusion based on:

1. Executed Test Cases.
2. Pass Rate.
3. Failed Test Cases.
4. Defect Severity.
5. Automation Test results.
6. Remaining risks.

## 18. Tester Confirmation

Tester: Enter student name

Execution Status: Not Started

Execution Start Date: Not Started

Execution End Date: Not Started

Signature: Not Applicable for the initial version
