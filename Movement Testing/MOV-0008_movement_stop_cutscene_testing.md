## **MOV-0008:** Movement Stop - Cutscene Testing  

> **Summary:** Verify that player movement is disabled when story cutscene is active.  <br>

**Preconditions:** 

- The player is in a map, playing as a character of a story.
- A cutscene is active and playing.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Press the W key in the keyboard   | Verify that the player does not move.   | 
 |  2 |   Press the A key in the keyboard   | Verify that the player does not move.   |  
 |  3 |   Press the S key in the keyboard   | Verify that the player does not move.  |
 |  4 |   Press the D key in the keyboard   | Verify that the player does not move.  |

**Post-conditions:**  

 - Player movement in all directions has been disabled. 
 - No collision, physics or animation errors, occured during movement.
