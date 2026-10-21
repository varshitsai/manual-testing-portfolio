# Test Plan — Swag Labs Demo Store

## 1. Project Overview

**Application:** [Swag Labs Demo Store](https://www.saucedemo.com/)  
**Testing type:** Manual functional testing  
**Project:** Manual Testing Portfolio  
**Tester:** Varshit

## 2. Objective

The objective of this test plan is to evaluate selected core functionalities of the Swag Labs demo e-commerce application, including login, product details, shopping cart operations, and checkout validation.

The goal is to verify whether the observed application behaviour matches the expected results for the selected test scenarios.

## 3. Scope of Testing

### In Scope

- Valid login
- Invalid login credentials
- Login validation with empty fields
- Product details verification
- Adding a product to the cart
- Removing a product from the cart
- Checkout validation when required information is missing

### Out of Scope

The following areas are not covered by this test cycle:

- Payment processing and real transactions
- Security and penetration testing
- Performance and load testing
- Cross-browser compatibility testing
- Mobile device compatibility testing
- Backend API and database testing
- Comprehensive testing of all application features

## 4. Test Approach

Manual functional testing will be used to evaluate the selected scenarios.

For each test case:

1. Identify the preconditions and required test data.
2. Perform the documented steps in the application.
3. Compare the actual behaviour with the expected result.
4. Record the execution status as Pass, Fail, Blocked, or Not Run.
5. Document any unexpected behaviour and supporting evidence when available.

## 5. Test Environment

| Item | Details |
|---|---|
| Application | Swag Labs Demo Store |
| URL | https://www.saucedemo.com/ |
| Operating system | Windows |
| Browser | Google Chrome |
| Testing method | Manual |
| Execution date | 21 October 2026 |

*Note: Browser and environment details reflect the recorded test execution. Exact OS and browser versions were not recorded.*

## 6. Entry Criteria

Testing can begin when:

- The demo application is accessible.
- The required test scenarios are documented.
- Appropriate test credentials are available.
- The browser is ready for testing.

## 7. Exit Criteria

This test cycle is considered complete when:

- All planned test cases have an execution status.
- Actual results are documented.
- Failures, if any, are recorded for further investigation.
- The execution summary is updated.

Completing the planned tests does not guarantee that the application is defect-free.

## 8. Test Scenarios

| Test ID | Scenario | Expected Result |
|---|---|---|
| TC-01 | Login with valid credentials | User reaches the products page. |
| TC-02 | Login with an invalid password | Login is rejected and an appropriate error appears. |
| TC-03 | Submit login form with empty fields | Login is rejected and required-field validation appears. |
| TC-04 | View product details | Correct product information and price are displayed. |
| TC-05 | Add a product to the cart | Product appears in the cart and the cart indicator updates. |
| TC-06 | Remove a product from the cart | Product is removed and the cart updates accordingly. |
| TC-07 | Continue checkout without required details | Checkout is prevented and required-field validation appears. |

## 9. Test Deliverables

The following documentation forms part of this portfolio:

- `test-plan.md` — Testing objectives, scope, approach, and planned scenarios.
- `test-cases.md` — Test steps, expected results, actual results, and execution status.
- `bug-report-template.md` — Template for documenting defects consistently.

## 10. Risks and Limitations

- Testing covers a limited selection of functional scenarios.
- Results represent the application behaviour observed during the recorded test execution.
- The application is a demo environment and may not represent a production e-commerce system.
- No automated, security, performance, or API testing was performed as part of this cycle.
- No confirmed defects were identified in the seven executed scenarios; additional testing may reveal other issues.

## 11. Test Summary

According to the existing execution record:

- Planned test cases: 7
- Executed test cases: 7
- Passed: 7
- Failed: 0
- Blocked: 0
- Not Run: 0
- Confirmed defects identified: 0

## 12. Conclusion

The selected test scenarios were executed and the observed results matched the expected behaviour for all seven cases.

This provides evidence of basic functional testing practice, test documentation, and execution reporting. Broader coverage and additional testing techniques would be needed to assess more of the application's behaviour.
