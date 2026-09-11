# Login Test Cases

## 1. Objective

To verify that users can successfully log in with valid credentials
and that appropriate validation messages are displayed for invalid inputs.

## 2. Scope

The following scenarios are covered:

- Valid login
- Invalid email
- Invalid password
- Empty fields
- Invalid email format
- Password masking
- Forgot password navigation
- Login button behavior

## 3. Test Cases

| TC ID | Test Scenario | Test Steps | Expected Result | Priority |
|------|---------------|------------|-----------------|----------|
| TC_LOGIN_001 | Login with valid credentials | Enter valid email and password, then click Login | User should be successfully logged in and redirected to the dashboard | High |
| TC_LOGIN_002 | Login with invalid email | Enter an unregistered email and valid password | Appropriate error message should be displayed | High |
| TC_LOGIN_003 | Login with invalid password | Enter valid email and incorrect password | Appropriate error message should be displayed | High |
| TC_LOGIN_004 | Login with both fields empty | Leave email and password empty and click Login | Required field validation should be displayed | High |
| TC_LOGIN_005 | Login with empty email | Leave email empty and enter a valid password | Email required validation should be displayed | High |
| TC_LOGIN_006 | Login with empty password | Enter valid email and leave password empty | Password required validation should be displayed | High |
| TC_LOGIN_007 | Invalid email format | Enter an invalid email format and valid password | Email format validation should be displayed | Medium |
| TC_LOGIN_008 | Password masking | Enter a password in the password field | Password characters should be masked | Medium |
| TC_LOGIN_009 | Forgot password navigation | Click Forgot Password | User should be redirected to the password recovery page | Medium |
| TC_LOGIN_010 | Login button with invalid data | Enter invalid credentials and click Login | User should not be logged in and an appropriate error should be displayed | High |
