# Capstone Fuzzy Farmer
## A repository for my collection game, Fuzzy Farmer

![image](https://github.com/user-attachments/assets/a5998c35-2489-4ccd-ba52-42bfdc1db5d6)

Fuzzy Farmer was designed in GAM 303: Design of Virtual Game Environments, taken in June and July of 2020. I was given a ‘client,’ a company called 'Lovey Duck' who wanted to encourage sales of their stuffed animals, or ‘fuzzys.’ I loved this opportunity to utilize my skillset to fulfill orders and help bring clients’ ideas to life. I was given their portfolio, with a rough outline of a collection type game. I had to complete a proposal and ‘pitch’ it to ‘Lovey Duck.’ 

This class focused heavily on all aspects of game development from beginning to end, such as quality assurance. I had to create and fill out a QA debugging sheet, analyzing and testing each aspect of the game. I enjoyed covering the aspects of game development from start to finish, from conception and pitch, to QA and production. This course allowed me to not only grow comfortable in Unreal Engine but in the documentation and background work of game development as well. I was taught how to move items on a movement timeline or LERP in Blueprints. 

To make the ‘fuzzies’ I merged various static meshes until they were in the approximate shape of some animals: a cat, pig, and bear. I used different movement timelines for each, so the cat moved differently than the bear or pig. I created a HUD which displayed both graphically and numerically how many of each animal was needed to win the level, and how many the player currently had. The amount needed to win varied each time the level was started. I made trigger points throughout the level that spawned a random animal. This enabled a different playthrough each time.

It was a complete level, ending with an ‘unsuccessful’ message on an ending menu if the player did not capture the right amount of animals before the timer ran out. If they did it brought up a ‘successful’ screen. Each ending screen prompted the player to play again or quit. However, it was a very rough game. The animals’ shapes left much to be desired, the level was empty except for hills and valleys and fences to keep the player from falling off the edge. To improve this I found a cute bear mesh on the marketplace, with skeletal mesh and animations included. Instead of moving static meshes, I made character actors. They walked on a nav mesh and utilized the animations included in the pack. I made them wander to random points, idle, then continue walking. I had to adjust the code in the HUD and level to be based on the new characters instead of static meshes. I also had to update the graphical elements of the code to match the new animals and created a random spawn ‘actor’ scattered throughout the level. 

The actor spawned one of the three bear types or nothing at all. So the random element of which animals would appear was still in play. I used Unreal’s procedural foliage tools and generated a forest over the level with three different kinds of trees gotten from the marketplace. The effect greatly improved the look and feel of the game. Instead of static meshes moving in a fixed, if haphazard fashion in an empty level, I now had wandering creatures in a forest. 

Fuzzy Farmer has beginning and ending screens tied to game conditions and utilizes a HUD. The animals wandering with animations required competence in creating engaging characters, moving with realistic physics and in 3D. It was built entirely in Unreal Engine 4 and was thoroughly tested for bugs and runs ‘glitch’ free. Besides Unreal Engine and its scripting Blueprints, I also used Adobe Photoshop to create the images for the HUD, utilizing skill in graphic design and 2D graphics, and the ‘cover’ picture for the game.

![image](https://github.com/user-attachments/assets/d6c9f65d-91cf-46ae-a3f8-e79e73623acc)

Below is an example of the old bear mesh, that I created with merging basic geometric shapes: 
![image](https://github.com/user-attachments/assets/78623d3c-fe9c-4730-ac5f-c76bc8f56356)

Here is the new version, created using a purchased mesh from Unreal Marketplace, the 'Funny Bear' set created by SURIYUN, it's a big improvement!

![image](https://github.com/user-attachments/assets/28df0490-325c-4f13-841e-33a3f46818ac)

Feel free to look at it all on my Behance! https://www.behance.net/gallery/129454107/Fuzzy-Farmer



