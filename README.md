# Webshop Manual Tester Project

## Project Overview
This project contains manual testing documentation for a demo e-commerce webshop.  
The focus is on validating core authentication features such as login and registration functionality.

The goal is to demonstrate understanding of:
- Manual test case design
- Positive and negative testing
- Bug reporting structure
- QA documentation standards

  SCREENSHOTS:

  <img width="1205" height="753" alt="Képernyőkép 2026-05-26 092152" src="https://github.com/user-attachments/assets/09652a5e-5f8e-4c75-a604-64940e4d6d77" />


---

## Test Environment
- Browser: Google Chrome (latest)
- OS: Windows 10 / Windows 11
- Testing Type: Manual Testing
- Application: Demo e-commerce webshop

---

# Test Cases

## Login Functionality

### TC-01: Successful login with valid credentials

**Preconditions:**
User has a valid registered account.

**Steps:**
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click on "Login" button

**Expected Result:**
User should be successfully logged in and redirected to the dashboard/homepage.

**Actual Result:**
User is successfully logged in and redirected to the homepage.

---

### TC-02: Login with invalid username ###

**Steps:**
1. Open login page
2. Enter invalid username
3. Enter valid password
4. Click on "Login" button

**Expected Result:**
Login should fail and an error message should be displayed:  
"Invalid username or password"

**Actual Result:**
Login is rejected and an error message is displayed.

---

### TC-03: Login with invalid password ###

**Steps:**
1. Open login page
2. Enter valid username
3. Enter invalid password
4. Click on "Login" button

**Expected Result:**
Login should fail and show error message.

**Actual Result:**
Login is rejected with error message.

---

### TC-04: Login with empty password field ###

**Steps:**
1. Open login page
2. Enter valid username
3. Leave password field empty
4. Click on "Login" button

**Expected Result:**
System should prevent login and show validation message:  
"Password is required"

**Actual Result:**
System allows request and shows generic error message.

---

# Bug Reports

The following bugs were identified during testing:

- BR-001-login-failure
- BR-002-empty-password
- BR-003-invalid-username-feedback

Bug details can be found in the `/bug-reports` folder.

---

# Testing Approach

The following testing techniques were applied:
- Positive testing (valid credentials)
- Negative testing (invalid credentials)
- Boundary / edge cases (empty fields)
- UI validation checks

---

# Severity & Priority Guidelines

**Severity levels:**
- Critical → System crash / unusable feature
- High → Major functionality broken
- Medium → Partial functionality issue
- Low → Minor UI issue

**Priority levels:**
- P1 → Immediate fix required
- P2 → High priority fix
- P3 → Normal priority
- P4 → Low priority

---

# Summary

This project demonstrates foundational QA skills including:
- Manual test case design
- Functional testing of authentication systems
- Bug identification and documentation
- Structured QA reporting suitable for Agile environments

---

# Author
Attila Tarnay
Junior Manual Tester Portfolio Project
