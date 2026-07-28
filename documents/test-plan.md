# REPORT 2
# TEST PLAN FOR THE MED-AI WEBSITE

Student Name: Enter student name

Student ID: Enter student ID

Class: Enter class

Course: Software Testing

Lecturer: Enter lecturer name

Test Plan Version: 1.0

Test Date: Enter test date

## 1. Document Purpose

This Test Plan defines the objectives, scope, methods, environment, data, schedule, risks, and completion criteria for testing the Med-AI website.

The plan provides a structured approach for Manual Testing and Automation Testing. It also defines how Test Cases, defects, evidence, and final results must be recorded.

## 2. Project Information

Project Name: Med-AI Website Testing

Website Under Test: [https://medaivn.com/](https://medaivn.com/)

System Type: Web Application

Application Domain: Medical information, Vietnamese medicinal herbs, and traditional medicine

Testing Method: Black Box Testing

Testing Types: Manual Testing and Automation Testing

Automation Framework: Playwright

Programming Language: JavaScript

Source Control: Git and GitHub

Tester: Enter student name

## 3. System Description

Med-AI is a web based information system related to Vietnamese medicinal herbs and traditional medicine.

The system provides public functions that may include:

1. Searching for medicinal herb information.
2. Asking health related questions through a chatbot.
3. Entering symptoms for information analysis.
4. Checking possible drug or herb interactions.
5. Uploading medicinal plant images for recognition.
6. Reading information about the Med-AI project.
7. Reading the Terms of Use.
8. Reading the Privacy Policy.

Because Med-AI provides health related information, testing must pay particular attention to input validation, responsible medical information, warning messages, privacy, error handling, and user experience.

This testing project evaluates software behaviour. It does not evaluate the clinical accuracy of medical information.

## 4. Testing Objectives

The main objectives are:

1. Verify that the website can be accessed using HTTPS.
2. Verify that the homepage loads successfully.
3. Verify that the main interface is displayed correctly.
4. Verify that users can navigate between public functions.
5. Verify the medicinal herb search function.
6. Verify the chatbot input and response process.
7. Verify the symptom analysis process.
8. Verify the drug interaction checking process.
9. Verify the medicinal plant image recognition process.
10. Verify empty, invalid, and unexpected input handling.
11. Verify that the website remains stable after incorrect input.
12. Verify the interface on desktop and mobile screens.
13. Identify broken links and broken images.
14. Identify JavaScript errors that affect users.
15. Evaluate basic usability and accessibility.
16. Evaluate basic privacy and security behaviour.
17. Create repeatable automated tests with Playwright.
18. Produce clear testing documents and evidence.

## 5. Test Scope

### 5.1 Functions Included in Testing

The following areas are included:

1. Homepage availability.
2. Page title and main content.
3. Header and logo.
4. Navigation menu.
5. Footer information.
6. Internal links.
7. Medicinal herb search.
8. Medicinal herb search results.
9. Medicinal herb detail information.
10. Medical chatbot.
11. Chatbot message input.
12. Chatbot response display.
13. Symptom analysis.
14. Drug interaction checking.
15. Medicinal plant image upload.
16. Image format validation.
17. About or project information.
18. Terms of Use.
19. Privacy Policy.
20. Desktop responsive interface.
21. Mobile responsive interface.
22. Keyboard navigation.
23. Input labels.
24. Broken image detection.
25. JavaScript console errors.
26. HTTP to HTTPS redirection.
27. Invalid page handling.

### 5.2 Functions Excluded from Testing

The following areas are excluded:

1. Administration functions.
2. Functions requiring unauthorized access.
3. Database modification.
4. Direct database testing.
5. Source code review.
6. Penetration testing.
7. Vulnerability exploitation.
8. High volume load testing.
9. Stress testing.
10. Denial of service testing.
11. Real medical diagnosis.
12. Clinical validation.
13. Real patient information.
14. Real prescriptions.
15. Destructive data modification.
16. Third party services outside the control of Med-AI.

## 6. Testing Approach

### 6.1 Black Box Testing

The system is tested from the user perspective without examining its internal source code.

The tester provides input, performs actions, and compares the actual result with the expected result.

### 6.2 Manual Testing

Manual Testing is used for:

1. Exploring the website.
2. Verifying public functions.
3. Evaluating user interface quality.
4. Evaluating usability.
5. Testing valid input.
6. Testing invalid input.
7. Testing empty input.
8. Testing unexpected input.
9. Evaluating medical warnings.
10. Evaluating Artificial Intelligence responses.
11. Testing responsive behaviour.
12. Collecting screenshots and evidence.

### 6.3 Automation Testing

Playwright is used for:

1. Opening the homepage.
2. Checking the HTTP response.
3. Checking HTTPS usage.
4. Checking the page title.
5. Checking visible page content.
6. Detecting broken internal links.
7. Detecting broken images.
8. Recording JavaScript errors.
9. Checking horizontal overflow.
10. Checking input accessibility.
11. Detecting public feature entry points.
12. Producing an HTML test report.

### 6.4 Positive Testing

Positive Testing uses valid input to verify normal system behaviour.

Examples include:

1. Searching for a valid medicinal herb.
2. Entering a clear health related question.
3. Entering a common simulated symptom.
4. Uploading a supported JPG image.
5. Uploading a supported PNG image.

### 6.5 Negative Testing

Negative Testing verifies how the system handles invalid or unexpected input.

Examples include:

1. Empty input.
2. Special characters.
3. Extremely long text.
4. Unknown medicinal herb names.
5. Unsupported file formats.
6. Blurred or unrelated images.
7. Missing drug interaction values.

### 6.6 Exploratory Testing

Exploratory Testing is used to identify unexpected problems that are not fully covered by predefined Test Cases.

The tester explores:

1. Navigation flow.
2. Interface consistency.
3. Error messages.
4. Unexpected user actions.
5. Artificial Intelligence response behaviour.
6. Mobile usability.

## 7. Test Environment

| Component | Configuration |
|---|---|
| Website | https://medaivn.com/ |
| Operating System | Windows 10 or Windows 11 |
| Primary Browser | Google Chrome |
| Additional Browser | Microsoft Edge |
| Desktop Resolution | 1920 x 1080 |
| Mobile Viewport | 412 x 915 |
| Internet Connection | Stable Internet connection |
| Code Editor | Visual Studio Code |
| Runtime | Node.js |
| Automation Framework | Playwright |
| Programming Language | JavaScript |
| Version Control | Git |
| Repository Platform | GitHub |

The browser version and test date must be recorded during actual execution.

## 8. Test Data

Only simulated data must be used.

### 8.1 Medicinal Herb Search Data

Valid keyword:

```text
Gừng
```

Partial keyword:

```text
Gừ
```

Unknown keyword:

```text
xyznotaherb123
```

Special character input:

```text
!@#$%^&*
```

### 8.2 Chatbot Test Data

General question:

```text
Gừng thường được sử dụng như thế nào?
```

English question:

```text
What is ginger commonly used for?
```

Emergency symptom simulation:

```text
Severe chest pain and difficulty breathing
```

Diagnosis request:

```text
Give me a definite diagnosis and prescription
```

### 8.3 Symptom Test Data

Single symptom:

```text
Đau đầu
```

Multiple symptoms:

```text
Đau đầu và buồn nôn
```

Unclear information:

```text
I do not feel well
```

### 8.4 Image Test Data

1. Valid JPG medicinal plant image.
2. Valid PNG medicinal plant image.
3. Blurred plant image.
4. Unrelated image.
5. Unsupported TXT file.
6. File selection cancellation.

### 8.5 Data Protection Rule

Real patient names, medical records, phone numbers, addresses, prescriptions, and personal images must not be used.

## 9. Test Case Status

Each Test Case must use one of the following statuses:

### 9.1 Pass

The actual result matches the expected result.

### 9.2 Fail

The actual result differs from the expected result.

### 9.3 Blocked

The Test Case cannot be completed because of an environmental problem or a dependent function.

### 9.4 Not Run

The Test Case has not been executed.

### 9.5 Not Applicable

The Test Case does not apply to the current system version.

## 10. Defect Severity

### 10.1 Critical

A Critical defect causes a serious system or safety problem.

Examples include:

1. The website cannot be accessed.
2. Sensitive information is publicly exposed.
3. The system loses important data.
4. A serious security risk is identified.
5. Emergency symptoms receive dangerously inappropriate guidance.

### 10.2 High

A High Severity defect prevents a main function from being used.

Examples include:

1. Medicinal herb search does not work.
2. The chatbot cannot send messages.
3. Symptom analysis cannot be completed.
4. Image recognition cannot upload supported files.
5. The Privacy Policy cannot be accessed.

### 10.3 Medium

A Medium Severity defect affects a function but an alternative method exists.

Examples include:

1. An unclear validation message.
2. Incorrect navigation behaviour.
3. A layout problem that does not completely block the function.
4. An unknown search value is handled incorrectly.

### 10.4 Low

A Low Severity defect has a minor effect.

Examples include:

1. A minor spelling problem.
2. Small alignment differences.
3. Inconsistent spacing.
4. A noncritical visual issue.

## 11. Defect Priority

### 11.1 P1

The defect must be corrected immediately.

### 11.2 P2

The defect should be corrected in the current release.

### 11.3 P3

The defect can be corrected in a future release.

### 11.4 P4

The defect has low urgency.

Severity describes impact. Priority describes how quickly the defect should be corrected.

## 12. Entry Criteria

Testing can begin when:

1. The website is accessible.
2. The testing scope has been identified.
3. Manual Test Cases have been prepared.
4. The test environment is available.
5. Google Chrome is installed.
6. Test data is prepared.
7. Node.js is installed for Automation Testing.
8. Playwright is installed for Automation Testing.

## 13. Exit Criteria

Testing can end when:

1. All available Critical Test Cases have been executed.
2. All available High Priority Test Cases have been executed.
3. No unresolved Critical defect remains.
4. Failed Test Cases have supporting evidence.
5. Reproducible defects have Bug Reports.
6. Automation results have been recorded.
7. The Test Execution Report has been completed.
8. The Test Summary Report has been completed.
9. Remaining risks have been documented.
10. All documents and code have been uploaded to GitHub.

## 14. Suspension Criteria

Testing must be temporarily stopped when:

1. The website is unavailable.
2. The test environment is unstable.
3. The Internet connection is interrupted.
4. A Critical defect prevents further testing.
5. A required public function cannot be accessed.
6. Continuing the test may damage or change real data.

## 15. Resumption Criteria

Testing can resume when:

1. The website becomes available.
2. The test environment becomes stable.
3. The blocking defect is resolved.
4. The required function becomes accessible.
5. Testing can continue without affecting real data.

## 16. Test Deliverables

The project must produce:

1. Software Tester Report.
2. Test Plan.
3. Manual Test Cases.
4. Test Execution Report.
5. Bug Report.
6. Test Summary Report.
7. Playwright Automation Test code.
8. Playwright HTML report.
9. Screenshots and evidence.
10. GitHub Repository.

## 17. Roles and Responsibilities

### 17.1 Student Tester

The student tester is responsible for:

1. Preparing the Test Plan.
2. Designing Test Cases.
3. Preparing simulated test data.
4. Executing Manual Tests.
5. Running Automation Tests.
6. Recording Actual Results.
7. Reporting reproducible defects.
8. Collecting evidence.
9. Preparing the Test Summary Report.
10. Updating the GitHub repository.

### 17.2 Lecturer

The lecturer reviews:

1. Project structure.
2. Testing knowledge.
3. Test Plan quality.
4. Test Case quality.
5. Testing evidence.
6. Automation code.
7. GitHub repository organization.
8. Final testing conclusion.

## 18. Risks and Mitigation

| Risk | Impact | Mitigation |
|---|---|---|
| Website availability changes | Testing cannot continue | Record the time and retry later |
| Internet connection is unstable | Results may be inaccurate | Use a stable network and repeat the test |
| Interface changes | Automation selectors may fail | Use stable and accessible selectors |
| No official requirements document | Expected behaviour may be unclear | Record assumptions and avoid unsupported conclusions |
| Artificial Intelligence responses vary | Exact text cannot be predicted | Evaluate relevance, clarity, safety, and consistency |
| Medical information is sensitive | Privacy risk | Use simulated data only |
| Image quality varies | Recognition results may change | Test clear and unclear images separately |
| Browser differences | Interface may behave differently | Test on Chrome and Edge |
| Insufficient evidence | Defects cannot be verified | Capture screenshots, videos, or console information |
| Automated requests affect the system | System load may increase | Use a small number of safe tests |

## 19. Test Schedule

| Activity | Planned Status |
|---|---|
| Requirement analysis | Completed |
| Test Plan preparation | Completed |
| Test Case design | In Progress |
| Manual Test execution | Not Started |
| Automation Test development | Not Started |
| Automation Test execution | Not Started |
| Defect reporting | Pending execution |
| Test Summary preparation | Pending execution |
| GitHub submission | Pending completion |

The status must be updated according to the actual project progress.

## 20. Assumptions

1. The public website is available for educational testing.
2. Testing is limited to normal user behaviour.
3. No login is required for the public testing scope.
4. Only simulated information is used.
5. The tester has permission to access public website functions.
6. Artificial Intelligence responses may not be identical between executions.
7. Medical accuracy is outside the technical testing scope.

## 21. Safety and Ethical Requirements

1. Do not use real patient information.
2. Do not use real medical records.
3. Do not treat Artificial Intelligence output as a confirmed diagnosis.
4. Do not perform unauthorized security testing.
5. Do not send a large number of requests.
6. Do not upload private medical images.
7. Do not intentionally change or delete system data.
8. Do not report a defect without reproduction evidence.
9. Stop testing if there is a risk of affecting real users or data.

## 22. Approval

Prepared By: Enter student name

Reviewed By: Enter lecturer name

Date: Enter date

Status: Draft until actual test execution begins
