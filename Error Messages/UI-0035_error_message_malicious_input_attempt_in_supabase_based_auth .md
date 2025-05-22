## **UI-0035:** Error Message - Malicious Input Attempt in Supabase-Based Auth  

> **Summary:** Verify that the authentication input fields properly malicious, but still validate UI behavior.  <br>

**Preconditions:** _None_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Enter in email: 'admin@example.com' OR '1'='1'    | Verify that 'admin@example.com' OR '1'='1' is in the email input field.   | 
 |  2 |   Enter in password: '12345' OR 'x'='x'   | Verify that '12345' OR 'x'='x' is in the password input field.   | 
 |  3 |   Press the Login button.   | Supabase client SDK safely treats the input as plain strings and no SQL executed   |  

**Post-conditions:**  

 - The login attempt fails. 
 - No raw error messages such as Supabase API stack trace appear in the UI.   
 - Input fields remain responsive and editable.