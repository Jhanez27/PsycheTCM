## **SEC-0001:** Authentication testing - Sign Up with Username/Password

> **Summary:** Verify user can sign up with username and password. <br>

**Preconditions:**

- No player account currently created.
- Application is installed and ready to launch.

Scenario 1

| \#  | Step                      | Expected Behavior                                            |
| --- | ------------------------- | ------------------------------------------------------------ |
| 1   | Open Application          | Verify that the screen displays the application's main menu. |
| 2   | Click the human icon      | Verify that the login form is visible.                       |
| 3   | Click Sign Up             | Verify that the sign up form is visible.                     |
| 4   | Enter not match passwords | Verify that an error message will display in wrong inputs.   |
| 5   | Enter valid inputs        | Verify that a message to verify account is displayed.        |

**Post-conditions:**

- New Player account will be created in the database.
- A confirmation email is sent to the player's registered email address.
