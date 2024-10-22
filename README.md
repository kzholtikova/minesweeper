# Weather Minesweeper
-	The game engine randomly generates a specified number of bombs and hides them.
-	If the player clicks on the cell with a bomb - he loses. If there is no bomb, the number of the neighbor bombs is displayed. If the number of the neighbor bombs is 0, then all such cells with 0 bombs nearby are opened.
-	The player can mark a cell with a flag meaning there’s a bomb without revealing it.
-	The player wins if all the cells were opened, except the cells with the bomb.
-	There’s classic and weather mode. The latter includes snow hiding the revealed numbers when the player’s stroke takes much time, occasional fog temporarily obscuring tiles, and occasional earthquakes shuffling the part of the grid.

## System Design
![Use Case Diagram](https://github.com/user-attachments/assets/c260fb32-24d2-44c1-9aee-3f7a7b34ff04)
![Activity Diagram](https://github.com/user-attachments/assets/68b5b130-a476-45e9-959a-91542b0e16d2)
![Left-Click Sequence Diagram](https://github.com/user-attachments/assets/0ddc8147-d01b-4a46-a15c-73608c640ff7)
![Right-Click Sequence Diagram](https://github.com/user-attachments/assets/e96c9637-0803-422c-8b93-2df9610aa9ea)
![Class Diagram](https://github.com/user-attachments/assets/67e04ea0-09f3-48a3-b9f6-2d0554ec572c)
![Cell State Diagram](https://github.com/user-attachments/assets/d2509a50-a9ac-47fa-9ec5-2bdbe4439143)
