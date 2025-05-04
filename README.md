# Login Page – Manual Test Cases

### Test Case 1: Verify Login Functionality

**Test ID:** TC001 

**Objective:** Verify that user can log in with valid credentials  

**Preconditions:** User has a registered account

**Priority:** High

**Platform:** Web (Google Chrome, Firefox)

**Steps:**  
- Open the login page of the application
- Enter a valid username
- Enter a valid password
- Click the "Login" button  

**Expected Result:** The user should be successfully logged in and redirected to the dashboard.

**Actual Result:** To be filled in during execution

**Status:** Pass/Fail

**Comments:** Notes on any issues encountered, screenshots, etc.

---

### Test Case 2: Invalid Password
- **Test ID:** TC_LOGIN_002  
- **Objective:** Ensure login fails with incorrect password  
- **Preconditions:** User has a registered account  
- **Steps:**  
  1. Go to login page  
  2. Enter valid email and **wrong** password  
  3. Click "Login" button  
- **Expected Result:** Error message is shown: "Invalid credentials"  
- **Status:** Pass/Fail

---

### Test Case 3: Blank Fields
- **Test ID:** TC_LOGIN_003  
- **Objective:** Check behavior when login fields are empty  
- **Steps:**  
  1. Go to login page  
  2. Leave email and password fields blank  
  3. Click "Login" button  
- **Expected Result:** Validation error message appears for both fields  
- **Status:** Pass/Fail
