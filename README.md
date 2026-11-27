# MyShopify: Test Case Documentation (Sauce Demo Store)

![Test Cases](https://img.shields.io/badge/Test%20Cases-26-blue) ![Test Steps](https://img.shields.io/badge/Test%20Steps-158-lightgrey) ![Passed](https://img.shields.io/badge/Passed-21-brightgreen)

Manual functional testing of the **Sauce Demo** Shopify storefront. The test cases cover browsing, search, account sign-up/login, cart, checkout/payment, wish list, referral, and keyboard accessibility.

##  Project Details

| | |
|---|---|
| **Project** | MyShopify (PR001) |
| **Application under test** | https://sauce-demo.myshopify.com/ |
| **Tester / Author** | Unichi Rosemary |
| **Test date** | 27 November 2026 |
| **Environment** | Google Chrome 158.0.8127.89 (desktop) |
| **Document version** | v0.1 |
| **Testing type** | Manual functional, negative, edge-case, and keyboard accessibility testing |

> This is a demo storefront. Only test data was used and no real payment details were entered.

##  Objective
Verify that the core shopping flows of the Sauce Demo store work as intended: browsing, search, account sign-up/login, cart, checkout/payment, wish list, referral, and keyboard accessibility.

## 📊 Execution Summary

| Test cases | Count |
|---|---|
| Total executed | 26 |
| ✅ Passed | 21 |
| ❌ Failed | 4 |
| ⚠️ Known issue | 1 |
| 🔁 Re-test required | 0 |
| 🚫 Blocked | 0 |

| Test steps | Count |
|---|---|
| Total | 158 |
| Passed | 152 |
| Failed | 5 |
| Known issue | 1 |

**Test case pass rate:** 21 / 26 (about 81%) | **Step pass rate:** 152 / 158 (about 96%)

### Coverage by category and priority

| Category | Cases | | Priority | Cases |
|---|---|---|---|---|
| Happy Path | 13 | | High | 19 |
| Negative | 8 | | Medium | 5 |
| Edge | 5 | | Low | 2 |

### Coverage by module

| Module | Test cases |
|---|---|
| Home | 1 (MS-001) |
| Catalog | 2 (MS-002, MS-019) |
| Search | 3 (MS-003, MS-011, MS-015) |
| Account (sign-up / login) | 6 (MS-004, MS-005, MS-012, MS-013, MS-016, MS-017) |
| Cart | 7 (MS-006 to MS-009, MS-018, MS-024, MS-025) |
| Checkout | 4 (MS-010, MS-014, MS-020, MS-021) |
| Wish list | 1 (MS-022) |
| Refer a friend | 1 (MS-023) |
| Accessibility (keyboard) | 1 (MS-026) |

##  What Was Tested
- **Happy path:** homepage load, catalog browsing, valid search, registration, login, add/remove/multiple items in cart, quantity update, checkout with a registered and a guest user, wish list and referral links
- **Negative:** no-match search, invalid email, empty email, wrong password, empty password, empty-cart checkout, missing delivery address, placeholder address
- **Edge:** numeric search, sold-out item, order quantity limit, cart persistence after logout and login, keyboard-only navigation

##  Test Case Format
Each test case includes: Test Case ID, Module, Title, Category, Priority, Preconditions, Test Data, Step-by-step actions, Expected Result, Actual Result, Status, and Comments.

**Status legend:** `PASSED` | `FAILED` | `KNOWN ISSUE` | `RE-TEST` | `NOT RUN` | `BLOCKED`

##  Repository Contents
```
├── MyShopify_main_test_case_documentation.xlsx   # Test cases + execution summary
└── README.md
```

##  Tools
`Microsoft Excel` `Google Chrome`

##  Contact
**Unichi Rosemary** | Certified Software Tester
 Owerri, Nigeria | ✉️ unichirosemary@gmail.com | 🔗 [LinkedIn](your-linkedin-url)
[MyShopify main test case documentation.xlsx](https://github.com/user-attachments/files/35532470/MyShopify.main.test.case.documentation.xlsx)
[MyShopify_Improved_Test_Plan.docx](https://github.com/user-attachments/files/35532445/MyShopify_Improved_Test_Plan.docx)
