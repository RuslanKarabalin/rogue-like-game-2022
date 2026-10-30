# rogue-like-game-2022

A roguelike game I created as part of
the 7bits Coding Garden in the summer of 2022

| Symbol | Description   | Sprite                                                      |
|--------|---------------|-------------------------------------------------------------|
| @      | Player        | <img src="assets/sprites/player.png" alt="player">          |
| E      | Enemy         | <img src="assets/sprites/enemy.png" alt="enemy">            |
| %      | Food          | <img src="assets/sprites/food.png" alt="food">              |
| #      | Wall          | <img src="assets/sprites/wall.png" alt="wall">              |
| &      | Cat-Wife      | <img src="assets/sprites/cat.png" alt="cat">                |
| -      | Key           | <img src="assets/sprites/key.png" alt="key">                |
| \>     | Next Door     | <img src="assets/sprites/next_door.png" alt="next_door">    |
| \<     | Previous Door | <img src="assets/sprites/prev_door.png" alt="previous_door">|

---

The player has:

- health points (HP)
- damage points (DP)
- current number of steps (Steps)
- the maximum number of steps for all levels (Max Steps)
- rating points (Social Credits)

At each level there is a door that will take you to the next level,
to remove the obstacle in front of the door, pick up the "Key".
Some levels have a door that will take you back to the previous level

To win you need to go through all 4 levels

You can lose if your health becomes 0,
or if your current steps exceed the maximum number of steps

- Use arrow keys to move
- Eat Food to restore HP
- Kill Enemy and earn Social Credits
- Enter to Next Door and go to the next level(there are 4 levels in total)

---
> Special Features:
>
> 1. Cheat System (try press WASD on level 0 and in settings)
> 2. Enemy can eat food
> 3. Wife feed you and restore your HP
