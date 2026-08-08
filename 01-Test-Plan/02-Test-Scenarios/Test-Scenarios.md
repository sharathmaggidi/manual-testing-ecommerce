# Test Scenarios

## Application
Demoblaze E-commerce Web Application

## Testing Approach

The scenarios below were derived from exploratory review of the application and cover functional, negative, boundary, integration and state-based testing.

---

## 1. User Registration

| ID | Test Scenario | Type | Priority |
|---|---|---|---|
| TS-REG-001 | Verify a new user can register with valid credentials | Positive | High |
| TS-REG-002 | Verify registration behavior when the username already exists | Negative | High |
| TS-REG-003 | Verify registration behavior when username is blank | Negative | High |
| TS-REG-004 | Verify registration behavior when password is blank | Negative | High |
| TS-REG-005 | Verify registration behavior when both fields are blank | Negative | Medium |
| TS-REG-006 | Verify registration with special characters in input fields | Negative | Medium |
| TS-REG-007 | Verify registration with boundary-length input values | Boundary | Medium |
| TS-REG-008 | Verify the user receives appropriate feedback after registration | Functional | High |

---

## 2. User Login

| ID | Test Scenario | Type | Priority |
|---|---|---|---|
| TS-LOGIN-001 | Verify a registered user can log in with valid credentials | Positive | Critical |
| TS-LOGIN-002 | Verify login behavior with an invalid username | Negative | High |
| TS-LOGIN-003 | Verify login behavior with an invalid password | Negative | High |
| TS-LOGIN-004 | Verify login behavior with both username and password invalid | Negative | High |
| TS-LOGIN-005 | Verify login behavior when username is blank | Negative | High |
| TS-LOGIN-006 | Verify login behavior when password is blank | Negative | High |
| TS-LOGIN-007 | Verify login using case variations in credentials | Boundary | Medium |
| TS-LOGIN-008 | Verify appropriate feedback is displayed for unsuccessful login | Functional | High |
| TS-LOGIN-009 | Verify logged-in user state is reflected correctly in the application | State | High |

---

## 3. Product Categories & Navigation

| ID | Test Scenario | Type | Priority |
|---|---|---|---|
| TS-PROD-001 | Verify products are displayed on the home page | Functional | High |
| TS-PROD-002 | Verify Phones category displays relevant products | Functional | High |
| TS-PROD-003 | Verify Laptops category displays relevant products | Functional | High |
| TS-PROD-004 | Verify Monitors category displays relevant products | Functional | High |
| TS-PROD-005 | Verify category navigation works correctly | Functional | High |
| TS-PROD-006 | Verify product cards display expected information | UI | Medium |
| TS-PROD-007 | Verify user can navigate from a product listing to product details | Functional | High |
| TS-PROD-008 | Verify navigation between product categories does not display stale product data | Integration | Medium |

---

## 4. Product Details

| ID | Test Scenario | Type | Priority |
|---|---|---|---|
| TS-DETAIL-001 | Verify product details page opens for a selected product | Functional | High |
| TS-DETAIL-002 | Verify product name is displayed correctly | Functional | High |
| TS-DETAIL-003 | Verify product price is displayed correctly | Functional | High |
| TS-DETAIL-004 | Verify product description is displayed correctly | Functional | Medium |
| TS-DETAIL-005 | Verify product image is displayed correctly | UI | Medium |
| TS-DETAIL-006 | Verify Add to Cart functionality is available for a product | Functional | Critical |

---

## 5. Shopping Cart

| ID | Test Scenario | Type | Priority |
|---|---|---|---|
| TS-CART-001 | Verify a product can be added to the cart | Positive | Critical |
| TS-CART-002 | Verify the selected product appears in the cart | Functional | Critical |
| TS-CART-003 | Verify product name in cart matches the selected product | Integration | High |
| TS-CART-004 | Verify product price in cart matches the selected product price | Integration | High |
| TS-CART-005 | Verify cart total is calculated correctly | Functional | Critical |
| TS-CART-006 | Verify multiple products can be added to the cart | Functional | High |
| TS-CART-007 | Verify cart total is recalculated when multiple products are present | Functional | Critical |
| TS-CART-008 | Verify a product can be removed from the cart | Functional | High |
| TS-CART-009 | Verify cart total is updated after removing a product | Functional | Critical |
| TS-CART-010 | Verify cart behavior when no products have been added | Negative | Medium |
| TS-CART-011 | Verify cart contents persist correctly during normal navigation | State | Medium |

---

## 6. Order Placement

| ID | Test Scenario | Type | Priority |
|---|---|---|---|
| TS-ORDER-001 | Verify Place Order form can be opened from the cart | Functional | Critical |
| TS-ORDER-002 | Verify an order can be placed using valid customer information | Positive | Critical |
| TS-ORDER-003 | Verify order placement behavior when mandatory information is missing | Negative | Critical |
| TS-ORDER-004 | Verify order placement behavior with invalid input data | Negative | High |
| TS-ORDER-005 | Verify order confirmation is displayed after successful order placement | Functional | Critical |
| TS-ORDER-006 | Verify order information in the confirmation is consistent with the submitted order | Integration | High |
| TS-ORDER-007 | Verify cart/application state after successful order placement | State | High |
| TS-ORDER-008 | Verify order placement behavior when the cart contains multiple products | Integration | High |

---

## 7. User Session & Logout

| ID | Test Scenario | Type | Priority |
|---|---|---|---|
| TS-SESSION-001 | Verify logged-in user can log out | Positive | High |
| TS-SESSION-002 | Verify user interface changes appropriately after logout | State | High |
| TS-SESSION-003 | Verify application behavior after refreshing the page following logout | State | Medium |
| TS-SESSION-004 | Verify application behavior when navigating after logout | State | Medium |
| TS-SESSION-005 | Verify login state is maintained appropriately during normal navigation | State | High |

---

## 8. Exploratory & Usability Testing

| ID | Test Scenario | Type | Priority |
|---|---|---|---|
| TS-EXP-001 | Explore navigation using browser refresh and back/forward controls | Exploratory | Medium |
| TS-EXP-002 | Explore application behavior with rapid repeated clicks | Exploratory | Medium |
| TS-EXP-003 | Verify important user actions provide understandable feedback | Usability | Medium |
| TS-EXP-004 | Verify application remains usable after invalid user actions | Exploratory | Medium |
| TS-EXP-005 | Explore inconsistent UI behavior across major application flows | Exploratory | Medium |

---

## Scenario Coverage Summary

| Area | Approx. Scenarios |
|---|---:|
| Registration | 8 |
| Login | 9 |
| Product & Navigation | 8 |
| Product Details | 6 |
| Shopping Cart | 11 |
| Order Placement | 8 |
| Session & Logout | 5 |
| Exploratory & Usability | 5 |
| **Total** | **60** |

---

## Testing Techniques Applied

- Positive Testing
- Negative Testing
- Boundary Value Analysis
- Equivalence Partitioning
- Functional Testing
- Integration Testing
- State-based Testing
- UI Testing
- Exploratory Testing
- Usability Testing
