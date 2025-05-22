## **INV-0005:** Inventory Consume Stackable Item Testing  

> **Summary:** Verify that stackable items can be consumed successfully.  <br>

**Preconditions:** 

- Player is in the map, playing as a character of a story.
- A stackable item is available in the inventory.
- The item's action panel is active, where it includes the Consume Action.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Click on the Consume button.   | Verify that the quantity of the item is reduced by one. If te item is reduced to 0, it should be removoed from the inventory.   | 

**Post-conditions:**  

 - The item is consumed successfully.
