#  Authentication Test Cases (NopCommerce Demo Site)

This file includes test scenarios related to the user registration and login functionalities on [demo.nopcommerce.com](https://demo.nopcommerce.com).

---

##  TC-001: User Registration with Valid Data

**Test Case ID:** TC-001  
**Title:** Successful user registration with valid inputs  
**Test Type:** Functional Test  
**Precondition:** The user is not registered yet  
**Test Steps:**
1. Navigate to [demo.nopcommerce.com](https://demo.nopcommerce.com)
2. Click on the “Register” button at the top right
3. Fill in the required fields: Gender, First Name, Last Name, Email, Password, Confirm Password
4. Click the “Register” button

**Expected Result:**  
- A success message “Your registration completed” should appear  
- The user should be automatically logged in  

---

##  TC-002: Successful Login with Registered User

**Test Case ID:** TC-002  
**Title:** User logs in with correct email and password  
**Test Type:** Functional Test  
**Precondition:** The user is already registered  
**Test Steps:**
1. Click on the “Log in” button at the top right
2. Enter the registered email and password  
3. Click the “Log in” button  

**Expected Result:**  
- The user should be redirected to their account  
- “My account” and “Log out” should be visible at the top  

---

##  TC-003: Login Attempt with Invalid Credentials

**Test Case ID:** TC-003  
**Title:** Unsuccessful login attempt with incorrect email or password  
**Test Type:** Negative Test  
**Precondition:** The user enters invalid or non-existent credentials  
**Test Steps:**
1. Click on the “Log in” button  
2. Enter an incorrect email or password  
3. Click the “Log in” button  

**Expected Result:**  
- An error message like “Login was unsuccessful” should be displayed  
- User should not be logged in

---

 Note: Each test case can be marked as `PASS` or `FAIL` after execution.
