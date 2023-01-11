### Level Design in Unreal 4 

##### Overview

My Level consists of three parts, the first part requires players to super jump as well as dodge bullets, the second part is to get out of the maze, and the third part is to defeat the Boss. After completing the three parts, player could enter the hut behind the Boss and step on the button to complete the level.

##### Process

At the beginning, I had no idea how to design a level. So I simply started my assignment on completing the functions of players and enemies. After I finished the Pursuer and the Mortar, I got stuck on my own enemy. So I started to design my level.

As a fan of Nintendo, especially a fan of *Super Mario Odyssey* , I borrowed its idea to the first part -- jump and dodge. I mainly use the Mortars in this part, creating bullets to hit the player.

For the second part, I borrow the idea of *Genshin Impact*, in the *Genshin Impact*, there're a lot of mazes players can explore, so I just made one.

After the above 2 parts, I gradually realized what I need for the last part -- usually there will be a Boss. So I made my own enemy a Boss, with a larger shape and the combination function of the 2 kinds.

The third part looks like the place in *Sekiro: Shadows Die Twice* where *Sekiro* met *Juzou the Drunkard*, I did not kill him from the front, instead, I went behind it and defeated it. So in my part3, I placed some obstacles and player can use it to kill the boss from behind.

---

#### Part 1: Update Your Character

##### Add a Health System

- [x] Display Health Bar
- [x] Display Game Over
  - [x] Add a Display Restart
  - [x] Restart function
  - [x] Pause Game
- [x] Create Health Pack
  - [x] Add Health
  - [x] Sound Effect



#### Part 2: Make Some Enemies

##### Enemy Behavior

- [x] Be destroyed when the players collides with their “head” 
- [x] Reduce the players health on collision with any part that is not the head
- [x] Knock the player back and remove player control for a short duration after a health reducing collision
  - [ ] add screen shake


##### The Pursuer

- [x] Have a looping patrol path that it follows
  - [x] return to its patrol path if the player gets too far away

- [x] Run at the player when they get within a moderate distance of each other, 
  - [x] look towards to the player

##### The Mortar

- [x] Destroy on head

- [x] Be an unmoving enemy placed on the ground
- [x] Randomly launch projectiles above and around it in an arc
- [x] The projectiles should cause a small explosion on collision with other objects
- [x] The explosions should knock back and reduce the players health on collision

##### Your Own Enemy

- [x] The final boss

#### Part 3: Putting It All Together

- [x] Be completable in around 5 minutes
- [x] Present some degree of challenge
- [x] Return the player to their start location when their health is reduced to zero
  - [x] or if they fall off the map
- [x] Display a level complete screen upon reaching the end of the level
- [x] Utilize both the created enemies in a way that contributes to the design
- [x] Have health pick ups scattered around the level
- [x] Have floating collectibles scattered around the level to **guide** the player and encourage them to explore
  - [x] These objects should be destroyed on collection
  - [x] number collected should be displayed some where on the UI
- [x] The design of the level should specifically take into account your enemy design
