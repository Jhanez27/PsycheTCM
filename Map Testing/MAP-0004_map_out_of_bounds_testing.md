## **MAP-0004:** Map Out-Of-Bounds Testing  

> **Summary:** Verify that player cannot go out of bounds within the available maps.  <br>

**Preconditions:** 

- Player has teleported to a different location using the map transitioning.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Move the player toward the edge of the map   | Verify that map boundaries prevent further movement.   | 
 |  2 |   Attempt to use dash near the edge   | Verify that the player is still restricted from leaving the map bounds.   |

**Post-conditions:**  

 - Player remains within the intended playable area of the map.
 - No collision or clipping issues are observed at map boundaries.