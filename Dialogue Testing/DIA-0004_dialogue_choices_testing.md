## **DIA-0004:** DIalogue Choices Testing  

> **Summary:** Verify that choices are displayed if choices are given, and dialogue cannot progress  if choices are available.  <br>

**Preconditions:** 

- Player is in a map, playing as a character of a story.
- Dialogue UI is active, and Dialogue interaction is ongoing.
- Choices are presented in the screen.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Press the X key in the keyboard.   | Verify that the dialogue continuation is not enabled.   | 
 |  2 |   Click on a choice button.   | Verify that the dialogue is continued.   | 

**Post-conditions:**  

 - Choice selection should disable dialogue progression if a choice hasn't been made.
