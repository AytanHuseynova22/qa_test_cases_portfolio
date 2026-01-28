# Test Cases – Login Functionality

| TC ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|------|----------------|---------------|------------|-----------|-----------------|
| LOGIN-001 | Login with valid credentials | User is on Login page | 1. Enter valid username<br>2. Enter valid password<br>3. Click Login button | standard_user / secret_sauce | User is logged in successfully and redirected to the Products page |
| LOGIN-002 | Login with invalid username | User is on Login page | 1. Enter invalid username<br>2. Enter valid password<br>3. Click Login button | invalid_user / secret_sauce | Error message is displayed and login is not successful |
| LOGIN-003 | Login with invalid password | User is on Login page | 1. Enter valid username<br>2. Enter invalid password<br>3. Click Login button | standard_user / wrong_password | Error message is displayed and login is not successful |
| LOGIN-004 | Login with empty username | User is on Login page | 1. Leave username field empty<br>2. Enter password<br>3. Click Login button | (empty) / secret_sauce | Validation message is displayed for missing username |
| LOGIN-005 | Login with empty password | User is on Login page | 1. Enter username<br>2. Leave password field empty<br>3. Click Login button | standard_user / (empty) | Validation message is displayed for missing password |
