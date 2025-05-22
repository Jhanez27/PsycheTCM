## **UI-0034:** Error Message - Input Handling in Signup

> **Summary:** Verify that in the Signup form, username and password input fields accept valid characters.  <br>

**Preconditions:** Signup form is visible. 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Enter a string to email   | Verify that the username field accepts the string without errors.   | 
 |  2 |   Enter a string to password   | Verify that The password field masks the input with asterisks.   |

**Post-conditions:**  

 - Signup button is enabled after both fields are filled.