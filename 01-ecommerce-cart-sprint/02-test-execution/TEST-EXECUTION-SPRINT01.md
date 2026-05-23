# Sprint 01 - Test Execution Report (E-commerce Cart Testing)


## Objective
Execute manual test cases for the e-commerce cart functionality and validate system behavior.


## Scope
- Add product to cart
- Update product quantity
- Remove product from cart
- Invalid quantity validation
- Cart behavior and UX validation


## Test Summary

| Total Test Cases | Passed | Failed | Not Executed |
|------------------|--------|--------|--------------|
| 5                | 4      | 1      | 0            |


## Test Cases Executed

- TC001 - Add product to cart → Passed  
- TC002 - Add same product multiple times → Passed  
- TC003 - Invalid quantity validation → Failed (BUG001)  
- TC004 - Remove product from cart → Passed  
- TC005 - Update quantity in cart → Passed  


## Defects Found

- BUG001 - Invalid Product Quantity is Accepted in Cart


## Improvements Suggested

- IMP001 - Improve hover UX on product selection  
- IMP002 - Add quantity selector on product page  


## Conclusion

The cart functionality is mostly stable, with one critical issue identified in quantity validation.
Overall system behavior is consistent, but requires improvement in input validation.


## Evidence

All execution evidence is stored in:

📁 /04-evidence/

- TC001/
- TC002/
- TC003/
- TC004/
- TC005/
- BUGS/BUG001/
- IMPROVEMENTS/
