## **MOV-0009:** Movement Stop - Map Testing  

> **Summary:** Verify that player movement is disabled when map UI is active.  <br>

**Preconditions:** 

- The player is in the post-apocalyptic world.
- There is no active UI element for Dialogue, Inventory, Quest, or Cutscene.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Press the M key in the keyboard.   | Verify that the Map UI shows on the screen.  | 
 |  2 |   Press the W key in the keyboard   | Verify that the player does not move.   | 
 |  3 |   Press the A key in the keyboard   | Verify that the player does not move.   |  
 |  4 |   Press the S key in the keyboard   | Verify that the player does not move.  |
 |  5 |   Press the D key in the keyboard   | Verify that the player does not move.  |

**Post-conditions:**  

 - The Map UI has been activated in the screen.
 - Player movement in all directions has been disabled. 
 - No collision, physics or animation errors, occured during movement.
