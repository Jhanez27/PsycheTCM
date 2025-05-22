## **SAVE-0003:** Default Save Progress Testing  

> **Summary:** Verify that game progress is saved successfully before player exits the game.  <br>

**Preconditions:** 

- Player is in the game world. 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Click the Exit button in the game.   | Verify that the game exits successfully.   | 
 |  2 |   Reopen Rekindle and Load Game    | Verify that game progress has been successfully saved.   | 

**Post-conditions:**  

 - Game data should be persistent after application exits.
