
# Test Cases — Swag Labs Demo Store

**Application:** https://www.saucedemo.com/  
**Testing type:** Manual functional testing  
**Execution status:** Not run yet

## Test Environment

- Tester: Varshit
- Device and browser: Record before testing
- Date tested: Record during execution

## Test Cases

| Test ID | Scenario | Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC-01 | Valid login | Enter valid demo credentials and tap Login | Products page opens | Not run | Not Run |
| TC-02 | Invalid password | Enter a demo username and an incorrect password | Login is rejected with an error | Not run | Not Run |
| TC-03 | Empty login fields | Leave both fields empty and tap Login | Login is prevented and validation appears | Not run | Not Run |
| TC-04 | View product details | Open a product from the products page | Correct product details appear | Not run | Not Run |
| TC-05 | Add product to cart | Add a product and open the cart | Selected product appears in the cart | Not run | Not Run |
| TC-06 | Remove product | Remove a product from the cart | Product is removed | Not run | Not Run |
| TC-07 | Checkout validation | Add a product, start checkout, leave required fields empty, and continue | Checkout does not proceed without required details | Not run | Not Run |

## Test Status Definitions

- **Pass:** Actual behaviour matches the expected result.
- **Fail:** Actual behaviour differs from the expected result.
- **Blocked:** A prerequisite or environment issue prevents testing.
- **Not Run:** The test has not been executed.

## Execution Notes

Record the actual result after performing each test. Report a bug only when unexpected behaviour is observed and can be reproduced. These scenarios are planned tests, not confirmed defects.# Test Cases — Swag Labs Demo Store

**Application:** https://www.saucedemo.com/  
**Testing type:** Manual functional testing  
**Execution date:** 21 October 2026  
**Environment:** Windows laptop, Chrome browser

## Test Cases and Execution Results

| Test ID | Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-01 | Valid login | Products page opens | Successfully logged in and reached the products page. | Pass |
| TC-02 | Invalid password | Login is rejected with an error | Login was rejected and an error message appeared stating that the username and password did not match a user. | Pass |
| TC-03 | Empty login fields | Login is prevented and validation appears | Login was rejected with the message "Username is required". | Pass |
| TC-04 | View product details | Correct product details appear | Sauce Labs Backpack details, description, price ($29.99), and Add to Cart button were displayed. | Pass |
| TC-05 | Add product to cart | Selected product appears in the cart | Backpack was added successfully, the button changed to Remove, and the cart badge displayed 1. | Pass |
| TC-06 | Remove product | Product is removed | Remove action succeeded; the cart became empty. | Pass |
| TC-07 | Checkout validation | Checkout does not proceed without required details | With checkout fields empty, checkout was blocked and the message "Error: First Name is required" appeared. | Pass |

## Test Summary

- Total test cases: 7
- Executed: 7
- Passed: 7
- Failed: 0
- Blocked: 0
- Not Run: 0
- Confirmed defects identified: 0

## Test Status Definitions

- **Pass:** Actual behaviour matched the expected result.
- **Fail:** Actual behaviour differed from the expected result.
- **Blocked:** An issue prevented test execution.
- **Not Run:** The test has not been executed.

## Execution Notes

These tests were manually executed against the Swag Labs demo store. Results were recorded based on observed behaviour during execution. No confirmed defects were identified in these seven test scenarios.

This project demonstrates introductory experience with manual functional testing, test case execution, validation checks, and documenting actual versus expected results.
