# Swag Labs (SauceDemo) – Manual Testing Project

## Project Overview

This project demonstrates manual testing of the Swag Labs e-commerce web application. The objective was to verify application functionality, identify defects, and document test execution results.

**Application URL:** https://www.saucedemo.com/

## Testing Types

- Functional Testing
- UI Testing
- Negative Testing
- Boundary Testing
- Navigation Testing
- Basic Accessibility Testing

## Modules Tested

- Login and Logout
- Product Listing and Sorting
- Shopping Cart
- Checkout Process
- Order Completion
- Navigation and Session Handling
- Accessibility and Usability

## Test Execution Summary

| Metric | Result |
|---|---|
| Total Test Cases | 40 |
| Test Cases Executed | 40 |
| Passed | 38 |
| Failed | 2 |
| Pass Rate | 95% |
| Fail Rate | 5% |
| Reported Defects | 2 |

## Defects Reported

### SD-BUG-001 – Checkout Allowed With Empty Cart

**Description:** The application allowed checkout to proceed with an empty shopping cart and displayed an order confirmation.

**Severity:** Medium

### SD-BUG-002 – Missing Visible Focus Indicator

**Description:** The Login button could be activated using the keyboard, but no clear focus highlight was observed.

**Severity:** Low

## Project Deliverables

The Excel workbook contains:

1. **Test Cases** – Test steps, expected results, actual results, and execution status.
2. **Bug Reports** – Defect descriptions, reproduction steps, severity, priority, and evidence.
3. **Requirement Traceability Matrix (RTM)** – Requirements mapped to test cases.
4. **Project Summary** – Testing scope, environment, and execution results.

Original screenshots supporting the reported defects are stored in the `Bug_Evidence` folder.

## Tools Used

- Microsoft Excel
- Google Chrome
- GitHub

## Test Environment

**Operating System:** Windows

**Browser:** Google Chrome

**Application:** Swag Labs (SauceDemo)

## Conclusion

Completed the execution of 40 manual test cases, with 38 passed and 2 failed.

Documented two observed issues and prepared supporting evidence.

This project demonstrates practical skills in manual software testing, test case execution, defect reporting, requirement traceability, and test documentation.
