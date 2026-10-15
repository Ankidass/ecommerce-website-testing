# E-Commerce Website Manual Testing Project

## Project Overview
A portfolio case study demonstrating a structured manual QA workflow for a demo e-commerce application. The project covers authentication, product browsing, cart behavior, checkout, navigation, usability, and basic input handling.

## Test Environment
- Application: SauceDemo demo store (https://www.saucedemo.com/)
- Test type: Manual functional, negative, usability, and basic validation testing
- Browser: Record the browser/version used for any personally executed run
- Test data: Public demo credentials and non-sensitive sample checkout data only

## Scope
- Login and logout
- Product listing and product details
- Cart add/remove and quantity behavior
- Checkout validation and order confirmation
- Navigation and basic usability checks
- Safe handling of script-like input where the application supports such input

## Deliverables
- `README.md` — project overview and testing approach
- `Ecommerce_Website_Test_Cases.xlsx` — test case design
- `Ecommerce_Bug_Report_Template.xlsx` — defect documentation format
- `Test_Execution_and_Results.xlsx` — execution-log structure and illustrative examples

## Results Interpretation
The workbook contains a **sample execution dataset** for demonstrating how test results are documented. Do not describe the sample rows as a personally verified test run unless you have executed the corresponding cases and confirmed the observed behavior. Replace sample actual results with observations from your own run before using them as evidence of hands-on execution.

## Defect Handling
A defect should be reported only when the observed behavior differs from an agreed expected result and the issue can be reproduced. The defect examples in the workbook illustrate documentation format; they are not assertions that the demo application contains those defects.

## Workflow
1. Review each test case and precondition.
2. Execute the steps on the selected demo application.
3. Compare actual behavior against the expected result.
4. Record Pass, Fail, or Blocked with evidence where appropriate.
5. Log reproducible defects and retest after fixes, where applicable.
6. Summarize outcomes based on recorded results.

## Skills Demonstrated
Test case design, positive and negative testing, functional testing, test execution documentation, defect-report structure, and GitHub project organization.
