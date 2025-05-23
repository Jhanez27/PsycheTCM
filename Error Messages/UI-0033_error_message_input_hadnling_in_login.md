## **UI-0033:** Error Message - Input Handling in Login

> **Summary:** Verify that in the Login form, username and password input fields accept valid characters. <br>

**Preconditions:** Login form is visible.

Scenario 1

| \#  | Step                       | Expected Behavior                                                 |
| --- | -------------------------- | ----------------------------------------------------------------- |
| 1   | Enter a string to email    | Verify that the username field accepts the string without errors. |
| 2   | Enter a string to password | Verify that The password field masks the input with asterisks.    |

**Post-conditions:**

- An error message will display if the credentials are invalid.
