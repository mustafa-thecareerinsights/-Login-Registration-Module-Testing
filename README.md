# Login & Registration Testing Project

## Project Overview

This project focuses on testing the **Login** and **Registration** modules of a web application. The objective of this assignment was to design and execute test cases to verify the functionality, validation rules, and reliability of the user authentication system.

The testing process included analyzing the application behavior, writing structured test cases, executing them manually, and documenting the results.

---

## Application Under Test

The test cases were executed on the following website:

**Demo Web Shop (Tricentis)**

https://demowebshop.tricentis.com/

This website provides a sample e-commerce platform that allows testing of user authentication features such as registration and login.

---

## Modules Tested

- User Registration Module
- User Login Module

---

## Test Case Coverage

The test cases were designed to cover multiple types of scenarios including:

- Positive scenarios (valid user actions)
- Negative scenarios (invalid inputs or incorrect credentials)
- Validation checks (required fields and input format validation)
- Boundary value test cases

---

## Test Execution Summary

| Module | Total Test Cases | Passed | Failed |
|----------|----------|----------|----------|
| Registration | 15 | 14 | 1 |
| Login | 15 | 15 | 0 |
| Total | 30 | 29 | 1 |

---

## Defects Identified

One defect was identified during testing.

### Issue

The system allows numeric characters in the **First Name** and **Last Name** fields during registration. These fields are generally expected to contain alphabetic characters only.

This issue has been documented in the Bug Report.

---

## Observation

During testing, it was also observed that even when the **Remember Me** checkbox was not selected, the user session remained active after refreshing or reopening the browser.

Ideally, the user should be required to log in again when this option is not selected.

---

## Documents Included in This Repository

- Test Case Document – Detailed test cases for Login and Registration modules
- Test Execution Document – Detailed execution results of test cases
- Bug Report Document – Information about the defect identified during testing
- Test Summary Report – Summary of test execution and results

---

## Tools Used

- Manual Testing
- Microsoft Word (Test Documentation)
- GitHub (Project Submission)

---

## Conclusion

The Login and Registration modules were tested using multiple functional scenarios. Most test cases passed successfully, confirming that the core functionality works as expected.

One minor validation issue was identified and documented for further review.
