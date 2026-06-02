# Login Test Cases - SauceDemo

## Project: SauceDemo QA Testing
## Module: Login functionality
## URL: https://www.saucedemo.com

---

## Test Case 1: Valid login

**Preconditions:**
User is on login page

**Test data:**
- Username: standard_user
- Password: secret_sauce

**Steps:**
1. Enter valid username
2. Enter valid password
3. Click “Login” button

**Expected result:**
User is successfully logged in and redirected to the products page

---

## Test Case 2: Invalid password

**Preconditions:**
User is on login page

**Test data:**
- Username: standard_user
- Password: wrong_password

**Steps:**
1. Enter valid username
2. Enter invalid password
3. Click “Login” button

**Expected result:**
Error message is displayed: “Username and password do not match”

---

## Test Case 3: Empty fields login

**Preconditions:**
User is on login page

**Test data:**
- Username: empty
- Password: empty

**Steps:**
1. Leave username field empty
2. Leave password field empty
3. Click “Login” button

**Expected result:**
Validation error message is displayed indicating required fields
