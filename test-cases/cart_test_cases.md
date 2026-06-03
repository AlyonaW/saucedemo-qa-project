# Cart Test Cases — SauceDemo

## Project: SauceDemo QA Testing
## Module: Shopping Cart
## URL: https://www.saucedemo.com

---

## Test Case 1: Add item to cart

**Preconditions:**
User is logged in and on products page

**Steps:**
1. Click "Add to cart" button for any product
2. Open cart

**Expected result:**
Selected product is displayed in the cart

---

## Test Case 2: Remove item from cart

**Preconditions:**
User has item in cart

**Steps:**
1. Open cart
2. Click "Remove" button for product

**Expected result:**
Product is removed from cart

---

## Test Case 3: Cart badge counter update

**Preconditions:**
User is on products page

**Steps:**
1. Add item to cart
2. Observe cart icon badge

**Expected result:**
Cart badge shows correct number of items
