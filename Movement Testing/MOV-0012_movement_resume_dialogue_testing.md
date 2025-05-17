## **MOV-0012:** Movement Resume - Dialogue Testing  

> **Summary:** Verify that player movement is enabled when dialogue UI is inactive.  <br>

**Preconditions:** 

- The player is in a map, playing as a character of a story.
- The Dialogue interaction has recently finished.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Press the W key in the keyboard   | Verify that the player moves upwards.   | 
 |  2 |   Press the A key in the keyboard   | Verify that the player moves leftwards.   |  
 |  3 |   Press the S key in the keyboard   | Verify that the player moves downwards.  |
 |  4 |   Press the D key in the keyboard   | Verify that the player moves rightwards.  |

**Post-conditions:**  

 - Player movement in all directions has been enabled. 
 - No collision, physics or animation errors, occured during movement.
