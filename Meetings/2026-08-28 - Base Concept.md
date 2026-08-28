## Base Concept

> Disclaimer: This is just a draft concept, that just holds all of our initial (Christoph and Stefan) thoughts and will not serve as full outline for the porject requirements. This will just be used for our first meeting.

Tower Defense Game .. no fixed theme, but based on nice assets from the Asset store like in the links section (something that can be used for kids as well - no blood, hard violence, etc.)

The general idea of the game is, that the player plays on the table via tangible objects (3D Printed) and can control the game with them. The second screen shows a 3D like version where the game is just executed (no interaction anymore). The user has the following different action he can perform:
What we (for sure) need/want:
* Towers (3D printed objects for the placement on our table) and enemies 
* Endless runner which will overwhelm you at some point
* Money and life for placing objects and "loosing" the game
* (Basic) enemy path where the enemies will spawn from
* A grid layout on our immersive table where items can be placed
- (Basic) Validation for the entire map (table) so that items can't be placed like everywhere and at any point/time of the game
* A Menu Screen, Game Screen
* At least a minimal version of the game loop descriped below
Optional:
* Skill tree and/or Levels (like unlocking things in the menu between runs) 
* Towers upgrades  
* End screen
* Difficulties (Easy, Hard, others.)
* Settings
* Perks
* Expanding map
* Map tiles (water tiles, earth tiles, etc.)
* Sophisticated pathing

Little more concise game loop:
1. Game starts -> Player must place a "Base" 3D object onto the table
2. Base is initialized -> Now a "Enemy path" is created (based on difficulty and depending on the pathing we decide on):
	1. Base map where there is one full road that is always the same
	2. One short path that will start to expand over time
3. Play places the first tower(s) and clicks "play" -> the 2nd screen (or VR) shows the round/run/game 
4. After n enemies defeated (one round done), depending on the optional things we decide on there are several things that can be done now:
	1. Choose a path 
	2. Place new towers
	3. Upgrade towers
	4. Replace towers
	5. Choose perk
	6. ...
5. At some point the player will be overwhelmed and lose and will return to the game menu. If we decide on a skill tree or any other form of leveling the player can upgrade 
 
Alternative: We do not use the second screen for the visualization of the game, but we show the game via MR (Quest) directly on the table. Our **preferance** is the second screen. 

>Disclaimer 2: This is our initial draft and we have many more ideas which we could integrate but we will wait for your feedback and also of our colleagues as we are not 100% sure if rather the idea is accepted and/or our colleagues will join us! We would love to do this but we will not force others to join us, but we warmly welcome them if they want to.
## Notes:
We just brainstormed this game, so there is much potential for 2-4 people to implement this entire game. Depending on the size we could do more or less of the game. 
## Links:
### Assets
- https://assetstore.unity.com/packages/2d/tiny-kingdom-tower-defense-346906
- https://assetstore.unity.com/packages/essentials/tutorial-projects/tower-defense-template-107692#content
- https://assetstore.unity.com/packages/3d/environments/fantasy/tower-defense-pack-low-poly-3d-art-143627

