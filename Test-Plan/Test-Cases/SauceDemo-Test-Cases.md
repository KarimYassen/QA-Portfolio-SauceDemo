# SauceDemo - Test Cases

## Module: Login

| TC ID | Title | Preconditions | Steps | Test Data | Expected Result | Actual Result | Status |
|------|-------|---------------|-------|----------|-----------------|--------------|--------|
| TC-001 | Login with valid username and password | User is on login page | 1) Enter valid username 2) Enter valid password 3) Click Login | standard_user / secret_sauce | User logs in successfully and is redirected to the Products page | Logged in successfully | Pass |
| TC-002 | Login with invalid username | User is on login page | 1) Enter an invalid username 2) Enter any password 3) Click Login | kkjgharin / kasnijif | Error message is displayed and user remains on the login page | "Epic sadface: Username and password do not match any user in this service" | Pass |
| TC-003 | Login with blank username | User is on login page | 1) Leave username field blank 2) Enter password 3) Click Login | (blank) / secret_sauce | Error message is displayed and user remains on the login page | "Epic sadface: Username is required" | Pass |
| TC-004 | Login with valid username and blank password | User is on login page | 1) Enter valid username 2) Leave password field blank 3) Click Login | standard_user / (blank) | Error message is displayed and user remains on the login page | "Epic sadface: Password is required" | Pass |
