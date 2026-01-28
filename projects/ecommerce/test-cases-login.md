# Test Cases – Login

| TC ID | Title | Preconditions | Steps | Test Data | Expected Result |
|------|-------|---------------|-------|----------|----------------|
| LOGIN-001 | Login with valid credentials | User is on Login page | 1. Enter valid username<br>2. Enter valid password<br>3. Click Login | standard_user / secret_sauce | User is successfully logged in and redirected to Products page |
| LOGIN-002 | Login with invalid username | User is on Login page | 1. Enter invalid username<br>2. Enter valid password<br>3. Click Login | wrong_user / secret_sauce | Error message is displayed, login fails |
| LOGIN-003 | Login with invalid password | User is on Login page | 1. Enter valid username<br>2. Enter invalid password<br>3. Click Login | standard_user / wrong_pass | Error message is displayed, login fails |
| LOGIN-004 | Login with empty username | User is on Login page | 1. Leave username empty<br>2. Enter password<br>3. Click Login | (empty) / secret_sauce | Validation error message is displayed |
| LOGIN-005 | Login with empty password | User is on Login page | 1. Enter username<br>2. Leave password empty<br>3. Click Login | standard_user / (empty) | Validation error message is displayed |
