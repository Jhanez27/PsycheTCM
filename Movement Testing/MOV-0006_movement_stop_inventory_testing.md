## **MOV-0006:** Movement Stop - Inventory Testing  

> **Summary:** Verify that player movement is disabled when inventory UI is active.  <br>

**Preconditions:** 

- The player is in a map, playing as a character of a story.
- There is no active UI element for Dialogue, Inventory, Quest, or Cutscene.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Press the C key in the keyboard.   | Verify that a Inventory UI Element shows on the screen.  | 
 |  2 |   Press the W key in the keyboard   | Verify that the player does not move.   | 
 |  3 |   Press the A key in the keyboard   | Verify that the player does not move.   |  
 |  4 |   Press the S key in the keyboard   | Verify that the player does not move.  |
 |  5 |   Press the D key in the keyboard   | Verify that the player does not move.  |

**Post-conditions:**  

 - The Inventory UI has been activated in the screen.
 - Player movement in all directions has been disabled. 
 - No collision, physics or animation errors, occured during movement.