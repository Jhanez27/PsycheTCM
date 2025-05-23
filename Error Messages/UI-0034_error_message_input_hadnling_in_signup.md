## **UI-0034:** Error Message - Input Handling in Signup

> **Summary:** Verify that in the Signup form, username and password input fields accept valid characters. <br>

**Preconditions:** Signup form is visible.

Scenario 1

| \#  | Step                       | Expected Behavior                                                 |
| --- | -------------------------- | ----------------------------------------------------------------- |
| 1   | Enter a string to email    | Verify that the username field accepts the string without errors. |
| 2   | Enter a string to password | Verify that the password field masks the input with asterisks.    |
| 3   | Re-enter password          | Verify that the password field masks the input with asterisks.    |

**Post-conditions:**

- An error message will display for invalid email and mismatch passwords.
