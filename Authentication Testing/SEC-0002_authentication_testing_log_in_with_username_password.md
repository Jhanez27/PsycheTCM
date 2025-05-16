## **SEC-0002:** Authentication testing - Log in with Username/Password

> **Summary:** Verify user can log in with username and password. <br>

**Preconditions:**

- An account is successfully registered on Sign Up.
- The application is installed and ready to use.

Scenario 1

| \#  | Step                      | Expected Behavior                                            |
| --- | ------------------------- | ------------------------------------------------------------ |
| 1   | Open Application          | Verify that the screen displays the application's main menu. |
| 2   | Click the human icon      | Verify that a login form is visible.                         |
| 3   | Enter invalid credentials | Verify that an error message will displayed.                 |
| 4   | Enter valid credentials   | Verify that the player is redirected back to the main menu.  |

**Post-conditions:**

- Successful account authentication, proceed to main menu with no human icon on display.
