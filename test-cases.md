# Test Cases — Swag Labs Demo Store

**Application:** https://www.saucedemo.com/  
**Testing type:** Manual functional testing  
**Execution date:** 21 October 2026  
**Environment:** Windows laptop, Chrome browser

## Test Cases and Execution Results

| Test ID | Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-01 | Valid login | Products page opens | Logged in successfully and reached the products page. | Pass |
| TC-02 | Invalid password | Login is rejected with an error | Login was rejected and a username/password mismatch error appeared. | Pass |
| TC-03 | Empty login fields | Login is prevented and validation appears | Login was rejected with "Username is required". | Pass |
| TC-04 | View product details | Correct product details appear | Sauce Labs Backpack details, description, price ($29.99), and Add to Cart button were displayed. | Pass |
| TC-05 | Add product to cart | Selected product appears in the cart | Backpack was added; the button changed to Remove and the cart badge displayed 1. | Pass |
| TC-06 | Remove product | Product is removed | The Remove action succeeded and the cart became empty. | Pass |
| TC-07 | Checkout validation | Checkout does not proceed without required details | Checkout was blocked with "Error: First Name is required". | Pass |

## Test Summary

- Total test cases: 7
- Executed: 7
- Passed: 7
- Failed: 0
- Blocked: 0
- Not Run: 0
- Confirmed defects identified: 0

## Execution Notes

These seven scenarios were manually executed against the Swag Labs demo store. Results reflect observed behaviour during execution. No confirmed defects were identified in these scenarios.

## Test Status Definitions

- **Pass:** Observed behaviour matched the expected result.
- **Fail:** Observed behaviour differed from the expected result.
- **Blocked:** An issue prevented test execution.
- **Not Run:** The test has not been executed.
