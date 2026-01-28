# Test Cases – Checkout Functionality

| TC ID | Test Case Title | Preconditions | Test Steps | Test Data | Expected Result |
|------|----------------|---------------|------------|-----------|-----------------|
| CHK-001 | Start checkout with product in cart | User is logged in and has product in cart | 1. Open cart<br>2. Click Checkout | - | Checkout information page is displayed |
| CHK-002 | Checkout with valid user information | User is on Checkout page | 1. Enter first name<br>2. Enter last name<br>3. Enter postal code<br>4. Click Continue | John / Doe / 12345 | User proceeds to overview page |
| CHK-003 | Checkout with empty first name | User is on Checkout page | 1. Leave first name empty<br>2. Enter last name<br>3. Enter postal code<br>4. Click Continue | (empty) / Doe / 12345 | Validation error message is displayed |
| CHK-004 | Checkout with empty last name | User is on Checkout page | 1. Enter first name<br>2. Leave last name empty<br>3. Enter postal code<br>4. Click Continue | John / (empty) / 12345 | Validation error message is displayed |
| CHK-005 | Checkout with empty postal code | User is on Checkout page | 1. Enter first name<br>2. Enter last name<br>3. Leave postal code empty<br>4. Click Continue | John / Doe / (empty) | Validation error message is displayed |
