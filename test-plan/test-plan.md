# Test Plan Document

## Project Name
SauceDemo Manual Testing Project

## Prepared By
Prasadi Nishshanka

## Version
1.0

## Date
08 May 2026

---

# 1. Overview

This document describes the testing approach, scope, objectives, 
resources, and schedule for manual testing of the 
SauceDemo e-commerce web application.

Application URL:
https://www.saucedemo.com/

The purpose of this testing activity is to validate the core 
functionalities of the application including authentication, 
product management, cart operations, and checkout flow.

---

# 2. Scope

The scope of this project includes testing following features of 
the SauceDemo e-commerce web application.

## Inclusions

### Authentication Module
- Valid login
- Invalid login
- Empty credential validation
- Logout functionality

### Product Module
- Product listing
- Product details
- Product sorting
- Add/remove product from cart

### Cart Module
- View cart
- Remove items
- Continue shopping

### Checkout Module
- Checkout information
- Order completion
- Validation messages

---

## Test Environment

| Item | Details |
|---|---|
| Application | SauceDemo |
| URL | https://www.saucedemo.com |
| Browser | Google Chrome |
| OS | Windows 10/11 |
| Testing Type | Manual Testing |

---

## Exclusions

- Database testing
- API testing
- Performance testing
- Security testing
- Mobile application testing
- Payment gateway testing

---

# 3. Test Strategy

Testing will be conducted manually using functional testing techniques.

## Types of Testing

### Functional Testing
Verify each feature behaves according to requirements.

### UI Testing
Validate layout, labels, buttons, and navigation.

### Regression Testing
Ensure existing functionality works after changes.

### Smoke Testing
Verify critical functionalities are stable.

### Negative Testing
Validate system behavior with invalid inputs.

---

# 4. Defect Reporting Procedure

During the test execution -
- Any deviation from expected behavior by the application will be noted. If
it cannot be reported as a defect, it will be reported as an observation/
issue or posed as a question.
- Any usability issues will be reported.
- After discovery of a defect, it will be retested to verify the responsibility
of the defect. Screenshots with steps to reproduce are documented.

Note: 
- Defects will be documented in a excel.
- Test scenarios and Test cases will be documented in excel document.

---

# 5. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| QA Tester | Execute test cases |
| QA Tester | Report defects |
| QA Tester | Prepare test reports |

---

# 6. Test Schedule

| Task                         | Time Duration         |
|------------------------------|-----------------------|
| Creating Test Plan           | 5/8/2026 - 5/8/2026   |
| Test Case Creation           | 5/9/2026 - 5/10/2026  |
| Test Case Execution          | 5/10/2026 - 5/11/2026 |
| Finalizing Summary Report    | 5/12/2026 - 5/12/2026 |

---

# 7. Test Deliverables

| Deliverables          | Description                                                                                                               |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------|
| Test Plan             | Details of the scope of the project, test stratergy, test schedule, resource requirements, test deliverables and schedule |
| Functional Test Cases | Test cases created for the defined scope                                                                                  |
| Defect Reports        | Detailed description of the defects identified along with screenshots and steps to reproduce on a daily basis.            |
| Summary Reports       | Summary report with bugs by priority and functional area                                                                  |

---

# 8. Pricing

N/A

---

# 9. Entry and Exit criteria

## Entry Criteria

Testing will begin when:
- Application is accessible
- Test environment is available
- Test data is prepared

## Exit Criteria

Testing will be completed when:
- All critical test cases are executed
- High severity defects are reported
- Test summary report is prepared

---

# 10. Risks and Mitigation

| Risk | Mitigation |
|---|---|
| Test environment unavailable | Schedule alternative testing time |
| Application instability | Retest after issue resolution |
| Incomplete requirements | Clarify scenarios before execution |

--- 

# 11. Approval

| Name               | Role | Status |
|--------------------|---|---|
| Prasadi Nishshanka | QA Tester | Approved |