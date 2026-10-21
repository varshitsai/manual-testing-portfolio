
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

Record the actual result after performing each test. Report a bug only when unexpected behaviour is observed and can be reproduced. These scenarios are planned tests, not confirmed defects.
