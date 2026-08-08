# Test Cases

## Application
Demoblaze E-commerce Web Application

## Test Case Format

| Test Case ID | Scenario ID | Test Case | Priority | Type | Preconditions | Test Data | Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|---|---|---|

| TC-REG-001 | TS-REG-001 | Verify user can register with valid credentials | High | Functional | Registration page is accessible and username is not already registered | Unique username, valid password | 1. Open Sign Up. <br>2. Enter valid username. <br>3. Enter valid password. <br>4. Submit registration. | User should be successfully registered and appropriate confirmation should be displayed. | Not Executed | Not Executed |
| TC-REG-002 | TS-REG-002 | Verify registration behavior with an existing username | High | Negative | An account already exists with the test username | Existing username, valid password | 1. Open Sign Up. <br>2. Enter existing username. <br>3. Enter valid password. <br>4. Submit registration. | Application should prevent duplicate registration and display appropriate feedback. | Not Executed | Not Executed |
| TC-REG-003 | TS-REG-003 | Verify registration behavior with blank username | High | Negative | Sign Up form is accessible | Username: blank, valid password | 1. Open Sign Up. <br>2. Leave username blank. <br>3. Enter valid password. <br>4. Submit registration. | Application should validate the missing username and prevent invalid registration. | Not Executed | Not Executed |
| TC-REG-004 | TS-REG-004 | Verify registration behavior with blank password | High | Negative | Sign Up form is accessible | Valid username, password: blank | 1. Open Sign Up. <br>2. Enter valid username. <br>3. Leave password blank. <br>4. Submit registration. | Application should validate the missing password and prevent invalid registration. | Not Executed | Not Executed |
| TC-REG-005 | TS-REG-005 | Verify registration behavior when both fields are blank | Medium | Negative | Sign Up form is accessible | Username: blank, Password: blank | 1. Open Sign Up. <br>2. Leave username blank. <br>3. Leave password blank. <br>4. Submit registration. | Application should prevent submission and provide appropriate validation/feedback. | Not Executed | Not Executed |