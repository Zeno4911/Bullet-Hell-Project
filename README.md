This is a small bullet hell game I made using Godot and GDScript.
The game has an enemy that shoots "bullets" and a player that has to dodge the bullets.
I made an algorithm for different patterns of bullets that the enemy can shoot.
There's a global file that stores the values that you can change for the patterns (rotation speed, time between bullets etc.).
When the bullets exit the screen they are destroyed so it doesn't cause performance issues since the enemy never stops shooting bullets.
There is a damage detection system. When the player gets hit by a bullet the game prints in the console a number. It doesn't do anything
but it's there for future updates when I add health.
