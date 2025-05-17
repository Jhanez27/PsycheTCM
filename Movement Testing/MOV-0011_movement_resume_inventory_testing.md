## **MOV-0011:** Movement Resume - Inventory Testing  

> **Summary:** Verify that player movement is enabled when inventory UI is inactive.  <br>

**Preconditions:** 

- The player is in a map, playing as a character of a story.
- The Inventory UI is active.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Press the C key in the keyboard.   | Verify that the Inventory UI disappears from the screen.  | 
 |  2 |   Press the W key in the keyboard   | Verify that the player moves upwards.   | 
 |  3 |   Press the A key in the keyboard   | Verify that the player moves leftwards.   |  
 |  4 |   Press the S key in the keyboard   | Verify that the player moves downwards.  |
 |  5 |   Press the D key in the keyboard   | Verify that the player moves rightwards.  |

**Post-conditions:**  

 - The Inventory UI has been deactivated in the screen.
 - Player movement in all directions has been enabled. 
 - No collision, physics or animation errors, occured during movement.
