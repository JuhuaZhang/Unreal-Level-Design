### Level Design in Unreal 4 


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
