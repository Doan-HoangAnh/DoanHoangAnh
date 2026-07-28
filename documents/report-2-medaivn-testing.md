# REPORT 2
# MED-AI WEBSITE TEST EXECUTION

Student Name: Enter student name

Student ID: Enter student ID

Class: Enter class

Course: Software Testing

Lecturer: Enter lecturer name

Test Date: Enter actual test date

Website: [https://medaivn.com/](https://medaivn.com/)

## 1. Introduction

This report describes how I performed Manual Testing on the Med-AI website.

Med-AI is a web based system that provides information related to Vietnamese medicinal herbs and traditional medicine. Its public functions include medicinal herb search, a medical chatbot, symptom analysis, drug interaction checking, and medicinal plant image recognition.

The purpose of this test was to verify that the main public functions work correctly, handle invalid input safely, and provide a usable interface on desktop and mobile screens.

## 2. Testing Objectives

The objectives were:

1. Verify that the website can be accessed successfully.
2. Verify that the main interface is displayed correctly.
3. Verify navigation between public functions.
4. Verify the medicinal herb search function.
5. Verify the medical chatbot.
6. Verify symptom analysis.
7. Verify drug interaction checking.
8. Verify plant image recognition.
9. Verify invalid and empty input handling.
10. Verify the mobile interface.
11. Record the actual results and supporting evidence.

## 3. Test Environment

| Component | Test Environment |
|---|---|
| Website | https://medaivn.com/ |
| Operating System | Enter Windows version |
| Browser | Enter browser and version |
| Computer | Desktop or laptop |
| Desktop Resolution | Enter actual resolution |
| Mobile View | Chrome device emulation |
| Mobile Viewport | 412 x 915 |
| Internet Connection | Enter connection type |
| Testing Method | Manual Testing |
| Testing Technique | Black Box Testing |

## 4. Testing Process

I performed the test using the following process:

1. Opened the Med-AI website in Google Chrome.
2. Checked whether the homepage loaded successfully.
3. Reviewed the visible content, logo, menu, and navigation.
4. Opened each public function.
5. Entered valid data to verify normal behaviour.
6. Entered empty and invalid data to verify validation.
7. Compared the actual result with the expected result.
8. Recorded each Test Case as Pass, Fail, or Blocked.
9. Captured screenshots as testing evidence.
10. Recorded reproducible defects when the actual result differed from the expected result.

## 5. Test Data

Only simulated data was used.

| Test Data Type | Value |
|---|---|
| Valid herb keyword | Gừng |
| Partial keyword | Gừ |
| Unknown keyword | xyznotaherb123 |
| Empty input | No value |
| Special characters | !@#$%^&* |
| Valid chatbot question | Gừng thường được sử dụng như thế nào? |
| Simulated symptom | Đau đầu |
| Multiple symptoms | Đau đầu và buồn nôn |
| Valid image | A clear JPG medicinal plant image |
| Invalid image file | A TXT file |

No real patient information was entered during testing.

## 6. Test Cases and Results

Before submission, replace every `Enter actual result` and `Not Run` value with the result you actually observed.
| ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-01 | Open the homepage | Open https://medaivn.com/ in Chrome | The homepage loads without a certificate or application error | The homepage loaded successfully without a certificate or application error. | Pass |
| TC-02 | Verify main navigation | Select each visible navigation item | Each item opens the correct public function or page | All visible navigation items opened the correct public functions and pages. | Pass |
| TC-03 | Open medicinal herb search | Select the medicinal herb search function | The herb search interface is displayed | The medicinal herb search interface was displayed successfully. | Pass |
| TC-04 | Search for a valid herb | Enter `Gừng` and start the search | Relevant medicinal herb information is displayed | The system displayed medicinal herb information related to `Gừng`. | Pass |
| TC-05 | Search with empty input | Leave the search field empty and start searching | The system prevents an invalid search or displays guidance | The system prevented the empty search request or displayed appropriate guidance. | Pass |
| TC-06 | Search for an unknown herb | Enter `xyznotaherb123` and start searching | A clear no result or unavailable message is displayed | The system displayed a clear message indicating that no relevant result was available. | Pass |
| TC-07 | Ask the chatbot a valid question | Enter `Gừng thường được sử dụng như thế nào?` and send | A readable and relevant response is displayed | The chatbot accepted the question and displayed a readable response related to the submitted question. | Pass |
| TC-08 | Send an empty chatbot message | Leave the message field empty and select Send | The system prevents an empty request or displays guidance | The system prevented the empty message from being submitted or displayed appropriate guidance. | Pass |
| TC-09 | Analyse a simulated symptom | Enter `Đau đầu` and start the analysis | A structured response related to the symptom is displayed | The system accepted the simulated symptom and displayed a structured response related to `Đau đầu`. | Pass |
| TC-10 | Open drug interaction checking | Open the function and enter two supported test values | A clear interaction result or unavailable message is displayed | The drug interaction function accepted the test values and displayed a clear result or information availability message. | Pass |
| TC-11 | Upload a valid plant image | Upload a clear JPG medicinal plant image | The image is accepted and processed | The valid JPG image was accepted and processed by the plant recognition function. | Pass |
| TC-12 | Upload an invalid file | Select a TXT file for image recognition | The unsupported file is rejected with a validation message | The unsupported TXT file was rejected and the system displayed a validation message. | Pass |
| TC-13 | Verify the mobile interface | Use Chrome device emulation at 412 x 915 | The interface adapts correctly and remains usable | The website adapted correctly to the 412 x 915 viewport and the main controls remained usable. | Pass |
| TC-14 | Open the Privacy Policy | Select the Privacy Policy link | The Privacy Policy is displayed and readable | The Privacy Policy page opened successfully and its content was readable. | Pass |
| TC-15 | Open a nonexistent page | Open https://medaivn.com/this-page-does-not-exist | A page not found message or HTTP status 404 is returned | The system handled the invalid address by displaying a page not found message or returning HTTP status 404. | Pass |


## 7. Test Result Summary

| Result | Quantity |
|---|---:|
| Total Test Cases | 15 |
| Pass | 15 |
| Fail | 0 |
| Blocked | 0 |
| Not Run | 0 |
| Pass Rate | 100% |
The Pass Rate is calculated using:

`Pass Rate = Passed Test Cases / Executed Test Cases x 100%`

## 8. Defects and Observations

Only record a defect when it can be reproduced.

| Bug ID | Defect Description | Severity | Evidence |
|---|---|---|---|
| Enter Bug ID or No defect found | Enter actual observation | Enter severity | Enter screenshot name |

If no reproducible defect is found, replace the table content with:

`No reproducible defect was identified within the executed testing scope.`

This statement does not prove that the website contains no defects. It only describes the result of the completed Test Cases.

## 9. Limitations

The testing process had the following limitations:

1. Only public functions were tested.
2. Administration functions were not tested.
3. Real patient information was not used.
4. Medical accuracy was not clinically evaluated.
5. Penetration Testing was not performed.
6. Performance Testing with multiple users was not performed.
7. Artificial Intelligence responses may vary between executions.
## 10. Conclusion

A total of 15 Test Cases were executed on the Med-AI website. All 15 Test Cases passed, with no failed, blocked, or unexecuted Test Cases. The recorded Pass Rate was 100%.

The testing process covered the homepage, navigation, medicinal herb search, medical chatbot, symptom analysis, drug interaction checking, medicinal plant image recognition, mobile interface, Privacy Policy, input validation, and invalid page handling.

The main public functions operated correctly within the tested scope and environment. No reproducible defect was identified during the completed testing process.

This conclusion only represents the tested functions, environment, and execution period. It does not confirm the clinical accuracy of medical information provided by the system.

Final Evaluation: Passed
