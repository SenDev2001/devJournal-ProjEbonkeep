# Collobaration Project - EBONKEEP
### 2412587
### Kuranage Senith Madushan Perera

## Game Artificial Intelligence - FGCT7011

## Overview
This is a collaborative team project for the FGCT7011 Game Artificial Intelligence module. Our game is called “Ebonkeep”. This game is a boss fight 3D game with a medieval theme powered by game AI and was created using Unreal Engine 5.
The main objective of the game is for the player to go to a castle and defeat the AI-controlled guards, sword and bow guards there. After defeating them, the player has to search a special potion and increases his health, unlocks the fire arrow power, and faces the final large golden golem boss enemy.
The golem boss, sword guards and bow guards all of these are created using behavior trees and blueprints. Additionally, the game also has NPC characters called villagers. We do not use behavior trees for them, but only regular blueprints.
Our team consists of six people: three artists, two programmers and a designer. Everyone was new to Unreal Engine. So it was important to learn from each other on the project. When one didn’t know, the other helped. By being able to work well in a team environment.
My contribution to this project was to create smart AI Guards using behaviour trees. This included both sword guards and bow guards. Another contribution was to create the villagers NPC characters. Although the villager AI didn’t use behavior trees and i used blueprint and AI perception for them.
The behavior tree for the boss enemy was created by another programmer. However, I closely studied his work and helped him debug bugs when needed.
I became interested in behavior trees, AI perception systems (how the AI ​​reacts to its environment), and AI decision-making in Unreal Engine 5 through research based on YouTube tutorials, Unreal Engine documentation, and indie game developers.

## Research 
### Methodology  
 For this project, I researched several sources related to game AI. Through these researches, I learnt important principles, techniques, and practical examples of applications. I created the AI ​​system of "Ebonkeep" using YouTube tutorials from great game developers such as Gorka Games, Ali Elzoheiry, and Matt Aspland. And also i researched official Unreal Engine documentation, and information available on Unreal Engine Dev community page.

Through this research, I was able to:
- Get a deep understanding of Behavior Trees
- Develop AI Perception Systems and Behaviour tree, Ai Controller
- Understand the decision-making mechanisms in the game
- Create different types of AI agents (Sword Guards, Bow Guards and NPC Villagers)

My research methodology includes the following steps:
- Collect and study free online resources
- Obtain technical information from the Unreal Engine official documentation
- After studying the resources, conduct experiments on various AI concepts
- Improvement of AI systems based on the experiments

### Game Sources  
The Witcher 3: Wild Hunt
The mechanism used for the AI ​​minor enemies (Guards, Bandits) in The Witcher 3 was used as a guide for the swordsmen and archers in our "Project Ebonkeep". In particular, the way enemies explore, detect suspicious activity, and provide early warning of attacks were used. What makes The Witcher 3's AI system unique is its ability to respond to natural routines and the environment. (Witcher 3 - The Detailed Life of NPCs, 2015)

<iframe width="560" height="315" src="https://www.youtube.com/embed/9vzzPB6PRsE?si=spxLxoh6M9a7pli8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

   I used the following concepts when developing the Guards AI:
   - Patrol Routes
   - Suspicious Activity Detection
   - Switching of instruments (Normal, Investigation, Attack)

Assassin's Creed Series
The NPC interaction system in the Assassin's Creed series was a very special source for the development of the AI ​​in my game. The way the NPC characters in this game communicate with each other and how they interact with the player was a big inspiration for me. For example, the way the guards converse with each other, exchange information with each other, and converse with the player is a feature I would like to include in the AI ​​system of my game. I am currently working on adding this feature to the game "Ebonkeep".(Postmortem: AI action planning on Assassin’s Creed Odyssey and Immortals Fenyx Rising, s.d.)


   The features that I am implementing from the Assassin's Creed series are:

   - Dialogue and interaction system between NPC characters
   - Interaction system between NPC characters and the player
   - Social behavior patterns and response system
   - Exchange of information between NPCs about suspicious activity

### Documentation Sources  
Unreal Engine Documentation -(Behavior Trees in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community, s.d.)
The official Unreal Engine documentation provides a detailed guide to Behavior Trees. 
Using this documentation, I learned about the use of Blackboards, Decorator and Service nodes, and Task nodes.

Important concepts I learned from the Unreal Engine documentation:
- Using the Blackboard system
- AI Perception Component
- Behavior Tree Decorators
- Behavior Tree Services
- Behavior Tree Tasks

Ali Elzoheri’s Advanced AI Enemy tutorials.

Ali Elzoheri’s YouTube tutorials discuss creating complex AI behaviors in Unreal Engine. Using these techniques, I created group AI behaviors for guards.
Important concepts I learned from Ali Elzoheri’s youtube tutorials:
I've watched a lot of his videos, and I've learned from them how he uses the behavior tree to chase the player when he sees and hears enemy noise, (Smart Enemy AI | (Part 1: Behavior Trees) | Tutorial in Unreal Engine 5 (UE5), 2023).
I learned how to create a patrol route using a spline and how enemies follow that route. I also learned how to switch from combat to passive, (Smart Enemy AI | (Part 2: Patrolling & States) | Tutorial in Unreal Engine 5 (UE5), 2023) I researched and learned how to use AI perception to sense and hearing and how to investigate when enemy hear a noise, how to switch to "investigate" when enemy hear a noise, and how to switch to attack when enemy can see the player. (Smart Enemy AI |  (Part 3: Perception) | Tutorial in Unreal Engine 5 (UE5), 2023)

<iframe width="560" height="315" src="https://www.youtube.com/embed/-t3PbGRazKg?si=5_4OgNoSzBPAdlPY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


In addition, I also learned about balanced attack strategies, behavior tree decorations, behavior tree tasks.I also watched Archery Enemy ai tutorial to get some bow mechanics and learn arrow physics.Also, I researched how EQS works in Enemy AI, but I didn't use it in our game because I don't think it's necessary for our game. But if it's needed in the future, I'll do it in our game too. (Smart Enemy AI |  (Part 3: Perception) | Tutorial in Unreal Engine 5 (UE5), 2023).


Gorka Games YouTube Tutorials

The "Enemy AI" tutorial series created by Gorka Games was a very important resource that I used. This tutorial series discusses the process of creating a complete AI system in Unreal Engine step by step.(How to Make a Simple Behavior Tree in Unreal Engine 5 - Advanced AI, 2022).
In addition to Gorka's AI reference component, I researched a lot of things from it. I learned from those videos about creating test nodes in the behavior tree, using variables on the blackboard, and implementing combat logic and strategic logic. (Unreal Engine 5 RPG Tutorial Series - #21: AI Detection and Chasing, 2023).

<iframe width="560" height="315" src="https://www.youtube.com/embed/ljmOsZVrtok?si=QU1BSczkhrHHOZ_y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

 I also followed his Head look at video to create our game npcs look at player when player close to them. (How to Make the NPC’s Head Look At the Player in Unreal Engine 5, 2023).

 <iframe width="560" height="315" src="https://www.youtube.com/embed/8skq8t_Fffk?si=FLv3GJDvs8QY1x-w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


Matt Aspland YouTube Tutorials
I researched Matt Aspland's AI random roaming tutorial to create our game npc villager random walk and I change it to When npc see the player npc stop. (AI Random Roam | Basic Roaming - Unreal Engine 5 Tutorial, 2022).

<iframe width="560" height="315" src="https://www.youtube.com/embed/Mi7r0LqUmOE?si=ivO0B6tONcINdJJg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Implementation  

### Process
The process of developing collaboration game "Ebonkeep" took place in several steps as follows:
#### Project Initiation and Planning
 - #### Initial Inspiration and Concept
When our team first discussed creating a game for the Collaboration project, we decided to take on the challenge of creating a game with outstanding AI, even though we were all new to Unreal Engine . After discussion, we decided to create a boss battle game with a medieval theme and using Unreal Engine 5.4 because in our university PCs are using this version.
 - #### Team Members and Task Distribution
We had six team members, and their tasks were divided as follows:
  - Three artists (3D modeling, animation, and environment design)
  - Two programmers (making AI Guards, The Boss guards and NPC Villagers)
  - One designer (level design and game mechanics)

My role was to develop the behaviors of the AI Sword guards,Bow guards (Archers) and villagers. Here I got to learn big game AI concepts like Behavior Trees, AI Perception, and Blackboard setup and AI controller. Through this process, I improved my skills in creating AI behaviors.

 - #### Castle Planning
We first thought about what we wanted the castle to look like. In keeping with the theme of our game, we decided to create a castle that was designed to resemble a large and ancient.
Accordingly, we initially planned what types of places and people would be in and around the castle.
 ##### Inside the castle:

- Swordsmith –This character does not craft weapons for the player. Instead, he acts as a single point of contact for power-up arrows. The player can obtain special power-up arrows from him, such as Fire Arrows, which can be used to deal extra damage in boss battles or against special guards. These weapons are essential to the game's progression and victory.

- Bakery – This location, which represents village life, can be used by the player for health regeneration. At the bakery, the player can buy food such as wet bread, cakes, and dry foods. Using these foods, the player can regain their health, playing a role similar to a Health Potion in gameplay.

- Shops and Village – This area brings the life of the people to life. Various shops, residences, and the daily lives of the villagers are shown here, and the player can purchase some fashionable or gameplay-based items. The Villager AI is constantly active here and their behavior can change based on the player's actions.

- Guards and Villagers – These characters are the basis for AI processes. The guards patrol and respond to actions such as the player breaking down walls or attacking villagers. The Villager AI represents normal life and keeps the gameplay environment alive.

- Training Area – This is a training area for the guards, where the player can practice their weaponry, climbing, and combat skills. This is an important area for player progression in the gameplay.

- Main Boss Arena – This is a large area designed for the final and most challenging battle in the game. Here, the player must face a deadly threat using power-ups such as Fire Arrows. The environment, the action, and the heat of battle are at their highest level.

We created all of these locations as a detailed project in Unreal Engine. Throughout the design process, we meticulously planned the gameplay-related factors, the environment, the AI, and the environment. In this way, the Castle environment we created became a lively, magnificent, and stylish environment.

The photos below help show our journey from the beginning of the creation of this Castle to today.. 
 
<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Refer%20image.png" alt="" width="800" height="350">

Figure 01 - This castle picture is we refer to create our Castle.


 
<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20First%20Step.png" alt="Castle First Step" width="800" height="350">

Figure 02 - This shows the initial gray model of our castle during its early development.


<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20Parts.jpg" alt="Castle Parts" width="800" height="350">

Figure 3 - This is a picture of our game's first scene, showing the player character and castle walls in true scale

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20walls.png" alt="Castle Walls" width="800" height="350">

Figure 4 - This picture shows the design phase of our game, Walls.

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/CastleGRey.png" alt="Castle Grey" width="800" height="350">

Figure 5 - This picture shows the complete gray model of our castle.

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/castle%20inside.png" alt="Castle Inside" width="800" height="350">

Figure 6 - This picture shows the process of creating the inside of our castle."

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/castle%20gates.png" alt="Castle Gates" width="800" height="350">

figure 7- This picture shows our castle after we added textures and materials.

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20Errors.png" alt="Castle Errors" width="800" height="350">

figure 8- This picture shows a texture modeling error.

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20With%20rain.png" alt="Castle With Rain" width="800" height="350">

Figure 9- This picture shows the castle after we finished building it, added the guards and NPCs, and began planning where everything else will go.

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Screenshot%202025-05-22%20230540.png" alt="Updated Scene" width="800" height="350">

Figure 10 - This is a picture of our completed final castle. This is how we finished our castle.

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Screenshot%202025-05-22%20230615.png" alt="Updated Scene" width="800" height="350">

Figure 11 - This is a picture of our completed final castle front view.

 - #### Character Creation and Design
 #### Boss Enemy Design
Creating the final boss, the massive Gold Golem:

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Boss%20enemy%20sketch.jpg" alt="Boss Enemy Sketch" height="450"> 

Figure 12 -This picture shows a sketch of the boss enemy

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Screenshot%202025-05-22%20192938.png" alt="New Scene" height="450">

Figure 13- This is our game's final boss enemy.

Conceptual Phase - Our artists created concept drawings of a large, fearsome Gold Golem, with lion faces on both shoulders.
AI Behavior Design - A complex behavior tree for the boss was created by our other programmer, including the following special abilities:
- Fire Breath - Delivers a powerful fire attack
- Ground Smash - Delivers a powerful attack that shakes the ground
- Special Abilities: Increases impulsiveness when injured (Enrage)

Coordination - I helped my colleague build the boss AI, especially with bug fixes and performance improvements.

#### Guard AI Design
I designed my main role, the Guard AI, as follows:
I used characters from Mixamo and Sketchfab as assets in the design process.

Bow Guard Design

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Screenshot%202025-05-21%20230735.png" alt="Castle Scene" height="450">

Figure 14 - This picture shows our game's bow guard.

- Designed as a typical medieval archer
- Attacks from a distance using a crossbow
- Positioned on high walls and towers


Sword Guard Design

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Screenshot%202025-05-21%20230720.png" alt="Updated Scene" height="350">

Figure 15 - This picture shows our game's Sword guard.

- Designed as a medieval knight character with a war shield and sword
- Attacks in close combat using a protective shield and a strong sword
- Deployed inside castle areas, they follow a patrol route every time they patrol


#### NPC Villagers
<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Screenshot%202025-05-21%20230706.png" alt="Updated Scene" height="450">

Figure 16 - This picture shoes our game's NPC Villager. 

- Deployed inside castle, AI random roaming.


#### Player Character Design
- Designed as a hero character with a large shield and crossbow
- A hero wearing a heavy armor with a balance of strength and protection
- Fire arrows special ability available (after finding a special nutrient liquid)


### New Approaches  
### Sword Guards and Bow Guards AI Behaviors:
When player is seen: Activate Combat State, move towards player.
When sound is heard: Activate Investigating State, move towards sound.This AI Perception system allows Guards to respond naturally to the player, for example:

   - Run towards to Player and Attack as soon as they see it
   - When sound is heard, investigate the direction of sound
   - If there is no doubt after investigation, return to Passive State


### Villager NPC System
Apart from Guard AI, I also created Villager NPC characters, they have behavior trees instead of Using Common Blueprints:

Villager Blueprint Setup:

Created a Character Blueprint
Change locations periodically during Event Tick
Respond to AI Perception

Villager Behaviour:

Daily Activities: Villagers move between shops, gardens, and other areas during the day
When seeing the player: Stop, turn towards the player, wave, or talk
When seeing a battle: Run away in fear, hide

Player Interaction:

Display a simple dialogue system when the player talks to the villagers
Able to obtain information or missions from some villagers

### Technical Difficulties

- Wrong Unreal Version:

We made this game in Unreal Engine 5.4 because that's the version available on the university computers. However, one of our team members used Unreal Engine 5.5.4 and pushed their changes. Now we're in the final days before submission and don't have time to fix it.
"When you open the project, it opens in 5.5.4."

- Git LFS:

There were issues using Git LFS (Large File Storage) to handle large files. We had to pay to fix this.
Wrong Version Conflicts: When some members pushed changes with the wrong Unreal Engine version, the project completely crashed. We had to revert to the previous version to fix this.
Team Member Dropouts: Due to these technical issues, some team members dropped out of the project, thinking we couldn't finish it. This affected the morale of the rest of the team.

## Outcomes

### Build Link


### GitHub Link
https://github.com/SenDev2001/ProjectEbonkeep

### Source Code/Project Files
  - #### Behavior Tree Development and Preview

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Screenshot%202025-05-21%20191048.png" alt="Castle Scene Update" width="750" height="350">

Figure 17 - This diagram illustrates the behaviour tree of my sword and bow guards.


 -  Main Behavior Tree Structure:
  
  I set up a Selector Node to select the three main AI states:
  -  Combat State
  - Investigating State
  - Passive State

#### Combat State:

In the Sequence Node:

 - BTT_SetMovementSpeed: Set Sprint Speed
 - BTT_FocusPlayer: Focus on the player
 - Move to Player: "MoveToPlayer" for Swordsmen
 - BTT_Attack: Activate Attack
 - Wait (2 seconds): Time between attacks

#### Investigating State:

In Sequence Node:

- BTT_SetMovementSpeed: Set Walking Speed
- BTT_ClearFocus: Clear Focus
- Move to Suspicious Location
- Wait (5 seconds): Inspect Area
- BTT_SetStateAsPassive: Set AI's State to Passive

#### Passive State:

In Sequence Node:

- BTT_SetMovementSpeed: Set Normal Walking Speed
- BTT_MovePatrolRoute: Move along Patrol Route
- Wait (Random 2-5 seconds): Pause 

This behavior tree controls the behavior of Sword guards. Basically, the guard patrols a designated path at normal speed. If a noise is heard, the guard quickly moves to the location and checks. If no one is seen, it reverts back to normal patrol. When the player is seen, the guard switches to combat mode, focuses on him, and quickly approaches and attacks the player.
I use the same setup for the bow guards, but I have removed the "Move To player" action and "BIsBlocking". Since the archers are on the gates, they do not need to move to the player they can not block with crossbow. All other actions work the same way, and when they see the player or hear a noise, they shoot at the player.

  - #### Guards AI controller 
   - Event Graph
https://blueprintue.com/blueprint/y72jyfud/ 

<iframe src="https://blueprintue.com/render/y72jyfud/" style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>


This Blueprint is an Event Graph for an AIC_Guard (AI Controller). This is a behavior tree attached to an AI Guard, which is configured to detect the player through the AI ​​Perception system and respond accordingly.
Here, when the Guard is possessed, the behavior tree runs. After that, a state called “Passive” is set. An updated list of actors is obtained through the Perception system through the Sight or Hearing sense. This actors list is iterated through a loop, and the Guard is asked whether the player has been seen (Sight) or heard (Hearing).
If the player has been seen through Sight, the Handle Sensed Sight function is called.
If a sound has been heard through Hearing, the stimulus is broken and the location is sent to the Handle Sensed Noise function.
Finally, this is the process of how the Guard detects the player and responds to it. 

  - Set state as passive 
 <iframe src="https://blueprintue.com/render/kg07of0i/" style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

This Blueprint function is called "Set State as Passive". It is used to update the state of the Blackboard in the Unreal Engine AI Controller (AIC_Guard) to Passive. Here, a Set Value as Enum node assigns the Passive value of the E_AIState Enum to a Key of an Enum type in the Blackboard. This is a process to make the Guard AI's behavior silent, non-contradictory. This is part of a state machine setup that symbolizes the transitions between states of the AI ​​system.

  - Set state as Attacking 
<iframe src="https://blueprintue.com/render/7fnwaspi/"  style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

This Blueprint process is called "Set State as Attacking". This is what sets a Guard AI in an Unreal Engine AI Controller to enter an active attacking state. First, the "Set Value as Object" node assigns the target object launched as "Attack Player" to the Object key specified as "Attack Target Key Name" in the Blackboard. This helps the Guard AI decide who to attack.
Next, a "Set Value as Enum" node assigns the value **Attacking** from the "E_AIState" enum to the Enum key specified as "State Key Name" in the Blackboard. This updates the Guard AI's internal state to "Attacking".
This process updates the necessary Blackboard Variables to trigger **a powerful and aggressive attacking behavior** in the Guard AI. This strengthens the functionality of the AI ​​Behavior Tree and helps the AI ​​behave in a way that is authentic and realistic.


- Set state as Investigate 
<iframe src="https://blueprintue.com/render/qe5khhb8/" style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

This Blueprint process helps an Unreal Engine Guard AI enter an "Investigating" state. This is used to allow an AI to enter a suspicious location. First, the Set Value as Enum node assigns the "Investigating" value of the E_AIState enum to the Blackboard key State Key Name. This updates the AI's current state to "Investigating".
Next, the Set Value as Vector node assigns the location from the "Location" pin to the Blackboard's Point of Interest Key Name Vector Key. This helps the AI ​​identify the location to search.
Accordingly, this Blueprint process updates the Blackboard Variables necessary to allow the AI ​​to enter a suspicious location and set the AI ​​state to "Investigating" at that time. This helps make the AI ​​Guard more realistic and immersive.

- Sword guard attack
<iframe src="https://blueprintue.com/render/pw8_s2p7/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

When a Guard makes an attack, it checks to see if there is a player character nearby using a sphere trace. If a player is found, damage is applied to it. The attack is called from the Behavior Tree.


- Sword guard attack and block
<iframe src="https://blueprintue.com/render/522qaqte/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

If the player shoots an arrow at the guard while it is blocking, the guard's health will not decrease. However, after a short delay, blocking is disabled. When the player shoots again, the guard will not block, so its health will decrease.

- Bow Guard attack
<iframe src="https://blueprintue.com/render/y_-77ewl/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

This Bow Guard attack process is executed through the BTT_AttackBow task node, which is connected to the behavior tree. Before the Bow Guard attacks the Player, the Find Look at Rotation node turns the Guard's face to the player's location. Accordingly, the arrow will correctly go in the direction of the player.
In the FireArrow process, the player is identified by a Line Trace and an arrow is spawned. The Bow Guard is specified as the Owner of that arrow. If the hit actor is a player character, a sound is played .
This process is executed by the bowGuard's AI controller and the Blackboard system, and is configured as a long-range attack system. After the AI ​​sees the player, the BTT_AttackBow node is executed and the arrow is used to attack the player.
This makes the Bow Guard an AI system that can intelligently attack a player from a distance.

- damage and death
<iframe src="https://blueprintue.com/render/g4a0etc3/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

- sword guard health bar widget 
<iframe src="https://blueprintue.com/render/-5h48wdt/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

- patrol route increment 
<iframe src="https://blueprintue.com/render/7zk9a1-4/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

- get spline point as world position
<iframe src="https://blueprintue.com/render/ps7tlgw8/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

- BP Villager
<iframe src="https://blueprintue.com/render/80zg2b8y/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe> 

- set movement speed 
 <iframe src="https://blueprintue.com/render/k8uh0mvp/"style="width: 100%; height:560" scrolling="no" allowfullscreen></iframe>

### Video Demonstration -


-  Sword Guards and NPCs

<iframe width="560" height="315" src="https://www.youtube.com/embed/B3lbsZjUn3I?si=ae7gDx1FnKxX4aHt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


- Bow guards


<iframe width="560" height="315" src="https://www.youtube.com/embed/CvXdapR6qXc?si=4roxnlW5ZZGTfjt_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- Game Play 

<iframe width="560" height="315" src="https://www.youtube.com/embed/nxOjKMeuWVo?si=bKLT7Dd8eeF8Lll1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Reflection 

### Research Effectiveness  
The research I did for this project was extremely valuable and useful. In particular, I learned new things about Behavior Trees and AI Perception methods in Unreal Engine. The guidance of instructors like Gorka Games and Ali Elzoheri on YouTube helped me gain a deeper understanding. Through this research, I understood how AI Agents work in different ways.
This research had a very positive impact on my project. In particular, I was able to create AI systems for swords guards, archers(Bow guards), and NPC villagers. However, if I had more time, I would have liked to do more research on EQS (Environment Query System) and NPC relationship systems.

### Positive Analysis 
There are a number of successful aspects of this project that I can be very happy about:

- Learning Unreal and AI game development

Although it was my first time working on a project using Unreal Engine, I was able to create simple NPC villagers. I created how they go about their daily lives by visiting different places in the village.
Creating Behavior Trees: Through this project, I gained a deep understanding of creating Behavior Trees. In particular, I learned about the use of Task, Sequence, Selector, Decorator, and Service nodes.

- Bow Guards and Sword Guards AI Systems: 

Although I originally planned to create only sword guards, I was eventually able to include bow guards as well. However I successfully implemented the crossbow function for the bow attack mechanics to bow guards. I created this process to shoot the crossbow arrow towards the player's location. Although this was a very complex process, it was successfully completed.

- AI Perception System:

 I developed an AI Perception system so that the troops could react accordingly when they saw the player and heard sounds. In particular, I created this system so that when the troops heard a sound, they could check the location and investigate the sound. This was one of my favorite processes.

- NPC Villagers: 
Although this wasn't my main work, I started creating NPC villagers to make our game look more natural. I was able to create simple NPCs. I made them randomly move around the entire castle village and stop when they saw the player.

- Team Collaboration:

 Despite all the challenges, it was a great achievement to be able to work together with the rest of the team and successfully complete the project. Especially, even though Unreal Engine was new to all of us, in the end we created a successful game.

### Negative Analysis  
This project also had some shortcomings and challenges:

- Time Limit:

 Since this was my first Unreal Engine project, it was a challenge to do this project while still learning it. Due to time constraints, I was unable to implement my plan to give the player the ability to change weapons (such as swords, bows, etc.).

- NPC Communication:

 My original plan was to create a system that would allow NPC villagers to communicate with each other and with the player. However, this was not feasible due to time and experience constraints.
Technical Challenges: Learning about Unreal Engine’s Behavior Trees and AI Perception methods was challenging. Sometimes it took me a long time to fix bugs.
GitHub and Team Collaboration Issues: Since we were all new to a collaborative project, we ran into a number of serious GitHub issues:


### Next Time
For the next time, I would change the following things:

- NPC Communication System: 

Next time, I would like to create a full conversation system where NPC villagers can communicate with each other and with the player.
Improved Weapon System: Give the player the ability to change different weapons and use different types of attack methods.


- More Complex Behavior Trees:

 I would like to create more complex AI systems using EQS (Environment Query System). This will help the troops make more intelligent decisions.
Advance Planning and Training: Next time, I would like to gain more understanding of Unreal Engine before starting the project. This will allow me to work more efficiently.

- Better Team Collaboration:

 In the next project, I will try to establish a proper Git methodology from the beginning of the project:

Conduct a training session on Git and Git LFS for all team members.
Adopt the correct Unreal Engine version and common settings among all members.
Establish clear rules for adding, modifying, and removing files.
Maintain better communication between team members.

Through this project, I learned a lot about Behavior Trees, AI Perception, and Blueprint Programming in Unreal Engine. Not only that, I also gained valuable experience in the challenges that can arise when working on a collaborative project and how to overcome them. This was a valuable experience for my future projects.

## Bibliography  

- Witcher 3 - The Detailed Life of NPCs (2015) At: https://www.youtube.com/watch?v=9vzzPB6PRsE (Accessed 16/02/2025).

-  Postmortem: AI action planning on Assassin’s Creed Odyssey and Immortals Fenyx Rising (s.d.) At: https://www.gamedeveloper.com/programming/postmortem-ai-action-planning-on-assassins-creed-odyssey-and-immortals-fenyx-rising- (Accessed  16/02/2025).

- Behavior Trees in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/behavior-trees-in-unreal-engine (Accessed  13/05/2025).

- Smart Enemy AI | (Part 1: Behavior Trees) | Tutorial in Unreal Engine 5 (UE5) (2023) At: https://www.youtube.com/watch?v=-t3PbGRazKg (Accessed  16/02/2025).

- Smart Enemy AI | (Part 2: Patrolling & States) | Tutorial in Unreal Engine 5 (UE5) (2023) At: https://www.youtube.com/watch?v=WFV5IewGks8 (Accessed  17/02/2025).

- Smart Enemy AI |  (Part 3: Perception) | Tutorial in Unreal Engine 5 (UE5) (2023) At: https://www.youtube.com/watch?v=gsyZdKYAT_4 (Accessed  20/01/2025).

- Smart Enemy AI |  (Part 4:  EQS) | Tutorial in Unreal Engine 5 (UE5) (2023) At: https://www.youtube.com/watch?v=Oy_LojjRiWo (Accessed  14/05/2025).

- How to Make a Simple Behavior Tree in Unreal Engine 5 - Advanced AI (2022) At: https://www.youtube.com/watch?v=QJuaB2V79mU (Accessed  15/02/2025).

- Unreal Engine 5 RPG Tutorial Series - #21: AI Detection and Chasing (2023) At: https://www.youtube.com/watch?v=ljmOsZVrtok (Accessed  22/02/2025).

- How to Make the NPC’s Head Look At the Player in Unreal Engine 5 (2023) At: https://www.youtube.com/watch?v=8skq8t_Fffk (Accessed  04/03/2025).

- AI Random Roam | Basic Roaming - Unreal Engine 5 Tutorial (2022) At: https://www.youtube.com/watch?v=Mi7r0LqUmOE (Accessed  04/03/2025).


## Declared Assets

- Sword Guard - https://www.mixamo.com/#/?page=1&type=Character
- Bow Guard -  Medieval Guard - Download Free 3D model by Taylor (@r.taylor) (2016) At: https://sketchfab.com/models/ca548172f0984660bc4213b9404284fa/embed?autostart=1 (Accessed  20/03/2025).
- NPC Villager- Medieval Civilian 3 - Download Free 3D model by Leonardo Carvalho (@livrosparacriancas) (2020) At: https://sketchfab.com/models/d99ca22f06134e8dab28fdfa75d87f31/embed?autostart=1 (Accessed  20/03/2025).
- Meteor hit noise: https://freesound.org/people/SuperSouper/sounds/684987/ (Accessed: 26 Feb 2025)
- Impact circle: https://clipground.com/images/magic-circle-clipart-12.png (Accessed: 22 Feb 2025)
- Crossbow shot sfx: https://freesound.org/people/Lunevix/sounds/246015/ (Accessed: 25 Feb 2025)
- Crossbow model by wolkoed: https://sketchfab.com/3d-models/crossbow-29266724221344da8c37367f90959b81#download (Accessed: 12 Feb 2025)
- Rocks and meteors (Rock Pack Vol 01 by Vampawn): https://www.fab.com/listings/f66023d1-7951-4c62-8ad5-121b4b0df349 (Accessed: 3 March 2025)