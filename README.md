[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Emma Austin
### Student number: 47789972 

## 1. Player Experience
### 1.1. Discovery
The player learns how to navigate the given level and the obstacles within through the gradual introduction of new challenges overtime. First, they are introduced to the jumping mechanic. While the player already knows the controls, it is important for them to discover the limits and constraints of the mechanic. This is done by having the player do some simple jumps, one showing the maximum height reachable.

![Photo of simple jumps](DocImages/1.PNG)

Next, the player encounters spikes. The player is provided with a health pickup afterwards, so that the player may discover the effects of a spike without too much repercussion. A checkpoint is placed after so that future jumps can be repeated without unnecessary repetition of mastered sections.

![Photo of simple jumps with spikes](DocImages/2.PNG)

The first encounter with an enemy is done on a reasonably empty platform, it is sectioned off from most harmful entities. This is so the player may play around and learn the gun and enemy mechanics in a simple manner.

![Photo of flat-ish terrain and single chomper](DocImages/3.PNG)

A final example of discovery is with the dynamic of push able boxes being used on pressure pads. The player can see the door open, and the box above the button, but cannot exit the door without the box. This is then problematised for a more complex box-pushing puzzle, where the box must be pushed onto acid. 

![Photo of door, pressure pad, and box all visible at once](DocImages/4.PNG)

The box floating in acid is seen near the boxes, as an example of what is required so that the player knows what is expected of them. 

![Photo of acid where box is needed to pass](DocImages/6.PNG)
![Photo of boxes near acid to demonstrate player expectations](DocImages/5.PNG)


### 1.2. Drama
The drama within the game aims to create experiential intensity for the player. This is done by having different areas focused on tasks of varying difficulties. The most intense parts of the level are towards the middle, where players are first getting used to fighting several enemies at once, and the end where the final path is littered with many dangerous encounters.
Here is the middle zone:

![Photo of large area with several chompers and spitters](DocImages/7.PNG)

This tense moment is followed by a moment of relief, the player does a small loop back to the beginning of the level. It is short and easy, but acts as a break before what is probably the hardest puzzle in the level.

![Easy Loop-back](DocImages/9.PNG)
![Hard Puzzle](DocImages/8.PNG)

After this difficult puzzle is an easy, relaxing puzzle in preparation for the final difficult stretch.

![Easy Puzzle](DocImages/10.PNG)

The final stretch adds a final dramatic climax before the level’s resolution.

![Longer and more difficult section as a final climax for the game](DocImages/11.PNG)


### 1.3. Challenge
In the drama aspect of this document I discussed the fluctuations in difficulty throughout the game used to create feelings of tension and relief. Despite these fluctuations, there is still a continual growth in the difficulty and challenges occurring which can be seen when comparing the first, second, and third section.

In section one, a significant challenge is the jump you make to get this first key. It is the first encounter with a moving platform that has danger beneath it, and the need to complete this jump creates tension.

![Early difficult jump to get key](DocImages/12.PNG)

In comparison, the third section of the game has a moving platform come out of and dip into acid, it also leads to a platform that has a chomper.

![Late difficult jump with acid-touching platform](DocImages/13.PNG)


### 1.4. Exploration
The level has been made so that the player, while having a main linear path, can explore small offshoots for bonus health, challenge, or even an easier route as seen in the area below.

![Offshoot path with enemies, health, and optional paths](DocImages/14.PNG)

The level is mostly linear, and only has a small area repeated. This space is repeated to create a moment of relief and so that the player feels they are exploring a connected space, instead of a long straight tunnel. The player is encouraged to stay on the correct path by using a destructible wall to block the ‘incorrect’ way, the player must go the long route and reach the Staff. 

![Pathing options](DocImages/15.PNG)

If the player continues the new given path, they learn how to open the previously blocked one.

![Learning section](DocImages/16.PNG)

Some screenshots may vary slightly from last minute edits (such as adding another health pack, or moving boxes to the left slightly).


## 2. Core Gameplay
### 2.4 Health Pickups / 2.6. Moving Platforms / 2.7. Passthrough Platforms
![Health Pickup, Moving Platforms, and Passthrough Platforms Storyboard](DocImages/story1.png)
I introduced the players to moving and drop-down platforms early in the level where they feel free to explore without having to worry about enemies or hazards. They are welcome to spend as much time as they like testing jump heights and the speed of platforms here. They can also identify the health pick-up sound without accidentally picking it up yet, the player loops back through here briefly, and will be able to heal properly then.

### 2.2. Checkpoints / 2.8. Spikes
![Checkpoints and Spikes Storyboard](DocImages/story2.png)
I introduce the players to spikes early within the level too, so that the player can practice interacting with and avoiding the spikes without many repercussions. If the player dies, they are right near the start, and if they succeed there is a checkpoint soon after the introductory spikes to avoid repetition. 

### 2.1. Acid 
![Acid Storyboard](DocImages/story3.png)
I introduce players to acid reasonably early as well, so they know what they need to avoid in the future areas. The jump is short and can be completed easily. The player can also drop down and observe the acid at a closer height if they want. Seeing as acid respawns the player at the previous checkpoint, a checkpoint is placed right before the first patch of acid. This means any failures will have minimal setbacks.

### 2.5. Keys
![Keys Storyboard](DocImages/story4.png)
The first key is introduced in a zone that has familiar hazards and platforms combined together for the first time. It is visible from the starting point and can be easily returned to if it is left behind accidentally. There are two ways to easily obtain the key, allowing the player to make their own decisions in regard to what they have previously learnt. 

### 2.3. Chompers / 2.10. Weapon Pickup (Gun)
![Chompers and Weapon Pickup (Gun) Storyboard](DocImages/story5.png)
The first weapon pickup, a gun, is introduced right before the first killable hazard is introduced. The weapon is only accessible after all non-moving hazards have been demonstrated first, so that the player knows it is not necessary to have a gun to avoid said hazards. This part of the level is flat, and the player is safe from the chomper and can observe its behavior before shooting it from a distance.

### 2.9. Spitters / 2.11. Weapon Pickup (Staff)
![Spitters and Weapon Pickup (Staff) Storyboard](DocImages/story6.png)
Finally, the sword pickup is introduced while the player is in a small area that is only escapable by utilizing the sword. The sword is introduced after the gun as it has more utility in this level. The first spitter can be observed and fought with the new weapon. Spitters were introduced after chompers as they are more confusing due to the moving projectile.


## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.
