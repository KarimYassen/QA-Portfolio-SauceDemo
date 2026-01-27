# SauceDemo - Test Cases

## Module: Login

| TC ID | Title | Preconditions | Steps | Test Data | Expected Result | Actual Result | Status |
|------|-------|---------------|-------|----------|-----------------|--------------|--------|
| TC-001 | Login with valid credentials | User is on login page | 1) Enter username 2) Enter password 3) Click Login | standard_user / secret_sauce | User logs in successfully and home page is displayed |  |  |
| TC-002 | Login with invalid password | User is on login page | 1) Enter username 2) Enter wrong password 3) Click Login | standard_user / wrong_pass | Error message appears and user stays on login page |  |  |
