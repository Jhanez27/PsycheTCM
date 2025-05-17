## **MOV-0014:** Movement Resume - Map Testing  

> **Summary:** Verify that player movement is enabled when map UI is inactive.  <br>

**Preconditions:** 

- The player is in the post-apocalyptic world.
- The Map UI is currently active.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Press the M key in the keyboard.   | Verify that the Map UI disappears from the screen.  | 
 |  2 |   Press the W key in the keyboard   | Verify that the player moves upwards.   | 
 |  3 |   Press the A key in the keyboard   | Verify that the player moves leftwards.   |  
 |  4 |   Press the S key in the keyboard   | Verify that the player moves downwards.  |
 |  5 |   Press the D key in the keyboard   | Verify that the player moves rightwards.  |

**Post-conditions:**  

 - The Map UI has been deactivated in the screen.
 - Player movement in all directions has been enabled. 
 - No collision, physics or animation errors, occured during movement.
