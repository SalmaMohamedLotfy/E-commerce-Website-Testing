# Project: E-commerce Website Testing

## Bug Report Example

### Title: Bug in User Registration - Email Validation Fails

**Description:**  
While testing the user registration feature of an e-commerce website, I identified that the system failed to validate the email format properly during account creation. The system allowed the user to enter an invalid email (e.g., `"userexample.com"`) without triggering any error message.

### Steps to Reproduce:
1. Navigate to the registration page.
2. Enter `"userexample.com"` in the email field.
3. Enter a valid password and proceed.
4. Click on the "Register" button.

### Expected Result:  
The system should display an error message indicating an invalid email format.

### Actual Result:  
The system allowed the invalid email to be submitted without any validation.

### Severity:  
**Major**

### Environment:
- **Platform:** Web (Desktop and Mobile versions)  
- **Browser:** Google Chrome (version 95.0.4638.54), Firefox (version 93.0)  
- **Operating System:** Windows 10, macOS Monterey  
- **App Version:** v2.1.0 (latest release)  
- **Test Account:** New user account (unverified email)  

### Bug Report Link:  
[View Bug Report](https://salmamohamed2897.atlassian.net/browse/WT-1)
