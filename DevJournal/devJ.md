# Collobaration Project 
### 2412587
### Kuranage Senith Madushan Perera

## Game Artificial Intelligence - FGCT7011

## Overview
This is a collaborative team project for the FGCT7011 Game Artificial Intelligence module. Our game is called “Project Ebonkeep”. This game is a boss fight 3D game with a medieval theme powered by game AI and was created using Unreal Engine 5.
The main objective of the game is for the player to go to a castle and defeat the AI-controlled guards, sword and bow guards there. After defeating them, the player has to search a special potion and increases his health, unlocks the fire arrow power, and faces the final large golem boss enemy.
The golem boss, sword guards and bow guards all of these are created using behavior trees and blueprints. Additionally, the game also has NPC characters called villagers. We do not use behavior trees for them, but only regular blueprints.
Our team consists of six people: three artists, two programmers and a designer. Everyone was new to Unreal Engine. So it was important to learn from each other on the project. When one didn’t know, the other helped. By being able to work well in a team environment.
My contribution to this project was to create smart AI Guards using behaviour trees. This included both sword guards and bow guards. Another contribution was to create the villagers NPC characters. Although the villager AI didn’t use behavior trees and i used blueprint and AI perception for them.
The behavior tree for the boss enemy was created by another programmer. However, I closely studied his work and helped him debug bugs when needed.
I became interested in behavior trees, AI perception systems (how the AI ​​reacts to its environment), and AI decision-making in Unreal Engine 5 through research based on YouTube tutorials, Unreal Engine documentation, and indie game developers.

## Research 
### Methodology  
 For this project, I researched several sources related to game AI. Through these researches, I learnt important principles, techniques, and practical examples of applications. I created the AI ​​system of "Project Ebonkeep" using YouTube tutorials from great game developers such as Gorka Games, Ali Elzoheiry, and Ryan Laley. And also i rearched official Unreal Engine documentation, and information available on Unreal Engine Dev community page.

Through this research, I was able to:
- Get a deep understanding of Behavior Trees
- Develop AI Perception Systems
- Understand the decision-making mechanisms in the game
- Create different types of AI agents (soldiers, archers, villagers)

My research methodology includes the following steps:
Collect and study free online resources
Obtain technical information from the Unreal Engine wiki and official documentation
After studying the resources, conduct experiments on various AI concepts
Improvement of AI systems based on the experiments

### Game Sources  
1. The Witcher 3: Wild Hunt
The mechanism used for the AI ​​minor enemies (Guards, Bandits) in The Witcher 3 was used as a guide for the swordsmen and archers in our "Project Ebonkeep". In particular, the way enemies explore, detect suspicious activity, and provide early warning of attacks were used. What makes The Witcher 3's AI system unique is its ability to respond to natural routines and the environment.Witcher 3 - The Detailed Life of NPCs (2015) At: https://www.youtube.com/watch?v=9vzzPB6PRsE (Accessed  17/05/2025).


I used the following concepts when developing the Guards AI:
- Patrol Routes
- Suspicious Activity Detection
- Switching of instruments (Normal, Investigation, Attack)

2. Assassin's Creed Series
The NPC interaction system in the Assassin's Creed series was a very special source for the development of the AI ​​in my game. The way the NPC characters in this game communicate with each other and how they interact with the player was a big inspiration for me. For example, the way the guards converse with each other, exchange information with each other, and converse with the player is a feature I would like to include in the AI ​​system of my game. I am currently working on adding this feature to the game "Project Ebonkeep".Postmortem: AI action planning on Assassin’s Creed Odyssey and Immortals Fenyx Rising (s.d.) At: https://www.gamedeveloper.com/programming/postmortem-ai-action-planning-on-assassins-creed-odyssey-and-immortals-fenyx-rising- (Accessed  17/05/2025).


The features that I am implementing from the Assassin's Creed series are:

- Dialogue and interaction system between NPC characters
- Interaction system between NPC characters and the player
- Social behavior patterns and response system
- Exchange of information between NPCs about suspicious activity

### Documentation Sources  
1. Unreal Engine Documentation - Behavior Trees Behavior Trees in Unreal Engine | Unreal Engine 5.5 Documentation | Epic Developer Community (s.d.) At: https://dev.epicgames.com/documentation/en-us/unreal-engine/behavior-trees-in-unreal-engine (Accessed  13/05/2025).

The official Unreal Engine documentation provides a detailed guide to Behavior Trees. Using this documentation, I learned about the use of Blackboards, Decorator and Service nodes, and Task nodes.
Important concepts I learned from the Unreal Engine documentation:

Using the Blackboard system
AI Perception Component
Behavior Tree Decorators
Behavior Tree Services
Behavior Tree Tasks

2. Ali Elzoheri’s Advanced AI Enemy tutorials
Ali Elzoheri’s YouTube tutorials discuss creating complex AI behaviors in Unreal Engine. Using these techniques, I created group AI behaviors for guards.
Important concepts I learned from Ali Elzoheri’s youtube tutorials:
I've watched a lot of his videos, and I've learned from them how he uses the behavior tree to chase the player when he sees and hears enemy sounds,Smart Enemy AI | (Part 1: Behavior Trees) | Tutorial in Unreal Engine 5 (UE5) (2023) At: https://www.youtube.com/watch?v=-t3PbGRazKg (Accessed  14/05/2025).I learned how to create a patrol route using a spline and how enemies follow that route. I also learned how to switch from combat to passive,Smart Enemy AI | (Part 2: Patrolling & States) | Tutorial in Unreal Engine 5 (UE5) (2023) At: https://www.youtube.com/watch?v=WFV5IewGks8 (Accessed  14/05/2025). I researched and learned how to use AI perception to sense and hearing and how to investigate when enemy hear a noise, how to switch to "investigate" when enemy hear a noise, and how to switch to attack when enemy can see the player.Smart Enemy AI |  (Part 3: Perception) | Tutorial in Unreal Engine 5 (UE5) (2023) At: https://www.youtube.com/watch?v=gsyZdKYAT_4 (Accessed  14/05/2025).
 In addition, I also learned about balanced attack strategies, behavior tree decorations, behavior tree tasks.I also watched Archery Enemy ai tutorial to get some bow mechanics and learn arrow physics.Also, I researched how EQS works in Enemy AI, but I didn't use it in our game because I don't think it's necessary for our game. But if it's needed in the future, I'll do it in our game too.Smart Enemy AI |  (Part 3: Perception) | Tutorial in Unreal Engine 5 (UE5) (2023) At: https://www.youtube.com/watch?v=gsyZdKYAT_4 (Accessed  14/05/2025).


3. Gorka Games YouTube Tutorials
The "Enemy AI" tutorial series created by Gorka Games was a very important resource that I used. This tutorial series discusses the process of creating a complete AI system in Unreal Engine step by step.
In addition to Gorka's AI reference component, I researched a lot of things from it. I learned from those videos about creating test nodes in the behavior tree, using variables on the blackboard, and implementing combat logic and strategic logic.

4. Ryan Lely's AI Combat Systems
Ryan Lely's set of techniques focuses on combat systems in game AI. Using this set of techniques, I developed combat actions in defensive AI.
Important concepts that I learned from Ryan Lely's guides:

Combat transitions
Dynamic attack patterns
Responding to player actions
Attack sensitive zones

## Implementation  

### Process
The process of developing collobaration game "Project Ebonkeep" took place in several steps as follows:
#### Project Initiation and Planning
 - #### Initial Inspiration and Concept
When our team first discussed creating a game for the Collabaration project, we decided to take on the challenge of creating a game with outstanding AI, even though we were all new to Unreal Engine . After discussion, we decided to create a boss battle game with a medieval theme and using Unreal Engine 5.4 because in pur university PCs are using this version.
 - #### Team Members and Task Distribution
We had six team members, and their tasks were divided as follows:
  - Three artists (3D modeling, animation, and environment design)
  - Two programmers (making AI Guards, the boss Enemey and NPC Vilagers)
  - One designer (level design and game mechanics)

My role was to develop the guard AI (swordsmen and archers) and the villagers' behaviors.
 - #### Castle Planning
We first thought about what we wanted the castle to look like. In keeping with the theme of our game, we decided to create a castle that was designed to resemble a large and ancient.
Accordingly, we initially planned what types of places and people would be in and around the castle.
 ##### Inside the castle:

- Swordsmith – to give the player the ability to craft weapons.

- Bakery – to represent the daily life of the villagers.

- Shops and Village – as an area where the general public lives.

- Guards and Villagers – as constant agents that act in AI processes.

- Training Area – to train the guards and provide combat training for the player.

- Main Boss Arena – a large area suitable for the final main battle.

Based on all this information, we created these locations in Unreal Engine. We analyzed our designs in detail and tried to create a beautiful and lively castle environment.

The following pictures show our journey from the beginning of building our castle to today. 

 

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Refer%20image.png" alt="" width="800" height="350">

Figure 01

This castle picture is we refer to create our Castle 


 
<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20First%20Step.png" alt="Castle First Step" width="800" height="350">

Figure 02


<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20Parts.jpg" alt="Castle Parts" width="800" height="350">

Figure 3

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20walls.png" alt="Castle Walls" width="800" height="350">

Figure 4

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/CastleGRey.png" alt="Castle Grey" width="800" height="350">

Figure 5

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/castle%20inside.png" alt="Castle Inside" width="800" height="350">

Figure 6

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/castle%20gates.png" alt="Castle Gates" width="800" height="350">

figure 7

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20Errors.png" alt="Castle Errors" width="800" height="350">

figure 8

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Castle%20With%20rain.png" alt="Castle With Rain" width="800" height="350">

Figure 9

 This is how we Start Our Castle 

 - #### Character Creation and Design
 Boss Enemy Design
Creating the final boss, the massive Gold Golem:

Conceptual Phase - Our artists created concept drawings of a large, fearsome Gold Golem, with lion faces on both shoulders.
AI Behavior Design - A complex behavior tree for the boss was created by our other programmer, including the following special abilities:
- Fire Breath - Delivers a powerful fire attack
- Ground Smash - Delivers a powerful attack that shakes the ground
- Special Abilities: Increases impulsiveness when injured (Enrage)

Coordination - I helped my colleague build the boss AI, especially with bug fixes and performance improvements.

Guard AI Design
I designed my main role, the Guard AI, as follows:

Bow Guard Design
- Designed as a typical medieval archer
- Attacks from a distance using a crossbow
- Positioned on high walls and towers

Sword Guard Design
- Designed as a medieval knight character with a war shield and sword
- Attacks in close combat using a protective shield and a strong sword
- Deployed to guard gates and sensitive areas

Player Character
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

Villager Behavior:

Daily Activities: Villagers move between shops, gardens, and other areas during the day
When seeing the player: Stop, turn towards the player, wave, or talk
When seeing a battle: Run away in fear, hide

Player Interaction:

Display a simple dialogue system when the player talks to the villagers
Able to obtain information or missions from some villagers
### Testing


### Technical Difficulties

## Outcomes (Suggested Word Count 300) 

### Source Code/Project Files
  - #### Behavior Tree Development and Preview

<img src="https://raw.githubusercontent.com/SenDev2001/dJPICTURE-ProjEbonkeep/main/Screenshot%202025-05-09%20140318.png" alt="Castle Updated Stage" width="800">


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

This behavior tree controls the behavior of Swor guards. Basically, the guard patrols a designated path at normal speed. If a noise is heard, the guard quickly moves to the location and checks. If no one is seen, it reverts back to normal patrol. When the player is seen, the guard switches to combat mode, focuses on him, and quickly approaches and attacks the player.
I use the same setup for the bow guards, but I have removed the "Move To player" action. Since the archers are on the gates, they do not need to move to the player. All other actions work the same way, and when they see the player or hear a sound, they shoot at the player.

  - #### Guards AI controller 
   - Evenet Graph
https://blueprintue.com/blueprint/y72jyfud/ 

This Blueprint is an Event Graph for an AIC_Guard (AI Controller). This is a behavior tree attached to an AI Guard, which is configured to detect the player through the AI ​​Perception system and respond accordingly.
Here, when the Guard is possessed, the behavior tree runs. After that, a state called “Passive” is set. An updated list of actors is obtained through the Perception system through the Sight or Hearing sense. This actors list is iterated through a loop, and the Guard is asked whether the player has been seen (Sight) or heard (Hearing).
If the player has been seen through Sight, the Handle Sensed Sight function is called.
If a sound has been heard through Hearing, the stimulus is broken and the location is sent to the Handle Sensed Noise function.
Finally, this is the process of how the Guard detects the player and responds to it 

  - Set state as passive 
  https://blueprintue.com/blueprint/kg07of0i/

This Blueprint function is called "Set State as Passive". It is used to update the state of the Blackboard in the Unreal Engine AI Controller (AIC_Guard) to Passive. Here, a Set Value as Enum node assigns the Passive value of the E_AIState Enum to a Key of an Enum type in the Blackboard. This is a process to make the Guard AI's behavior silent, non-contradictory. This is part of a state machine setup that symbolizes the transitions between states of the AI ​​system.

  - Set state as Attacking 
https://blueprintue.com/blueprint/7fnwaspi/

This Blueprint process is called "Set State as Attacking". This is what sets a Guard AI in an Unreal Engine AI Controller to enter an active attacking state. First, the "Set Value as Object" node assigns the target object launched as "Attack Player" to the Object key specified as "Attack Target Key Name" in the Blackboard. This helps the Guard AI decide who to attack.
Next, a "Set Value as Enum" node assigns the value **Attacking** from the "E_AIState" enum to the Enum key specified as "State Key Name" in the Blackboard. This updates the Guard AI's internal state to "Attacking".
This process updates the necessary Blackboard Variables to trigger **a powerful and aggressive attacking behavior** in the Guard AI. This strengthens the functionality of the AI ​​Behavior Tree and helps the AI ​​behave in a way that is authentic and realistic.


 - Set state as Investigate 
 https://blueprintue.com/blueprint/qe5khhb8/





https://blueprintue.com/blueprint/k8uh0mvp/ set movement speed

https://blueprintue.com/blueprint/r5ar0qlb/ sword guard attack

https://blueprintue.com/blueprint/g4a0etc3/ damage and death

https://blueprintue.com/blueprint/-5h48wdt/ sword guard health bar widget 

https://blueprintue.com/blueprint/7zk9a1-4/ patrol route increment

https://blueprintue.com/blueprint/ps7tlgw8/ get spline point as world position



https://blueprintue.com/blueprint/80zg2b8y/ BP Villager

https://blueprintue.com/blueprint/y_-77ewl/ Bow Guard attack




### Build Links

#### GitHub Link -https://github.com/SenDev2001/ProjectEbonkeep
#### Game Link - 


### Video Demonstration -


## Reflection 

### Research Effectiveness  
The research I did for this project was extremely valuable and useful. In particular, I learned new things about Behavior Trees and AI Perception methods in Unreal Engine. The guidance of instructors like Gorka Games and Ali Elzoheri on YouTube helped me gain a deeper understanding. Through this research, I understood how AI Agents work in different ways.
This research had a very positive impact on my project. In particular, I was able to create AI systems for swords guards, archers(Bow guards), and NPC villagers. However, if I had more time, I would have liked to do more research on EQS (Environment Query System) and NPC relationship systems.

### Positive Analysis 
There are a number of successful aspects of this project that I can be very happy about:

- Archer and Swordsman AI Systems: 

Although I originally planned to create only swordsmen, I was eventually able to include archers as well. I successfully implemented the crossbow function for the bow attack mechanic. I created this process to shoot the crossbow arrow towards the player's location. Although this was a very complex process, it was successfully completed.

- AI Perception System:

 I developed an AI Perception system so that the troops could react accordingly when they saw the player and heard sounds. In particular, I created this system so that when the troops heard a sound, they could check the location and investigate the sound. This was one of my favorite processes.

- NPC Villagers: 

Although it was my first time working on a project using Unreal Engine, I was able to create simple NPC villagers. I created how they go about their daily lives by visiting different places in the village.
Creating Behavior Trees: Through this project, I gained a deep understanding of creating Behavior Trees. In particular, I learned about the use of Task, Sequence, Selector, Decorator, and Service nodes.

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

- Git LFS:

 There were issues using Git LFS (Large File Storage) to handle large files. We had to pay to fix this.
Wrong Version Conflicts: When some members pushed changes with the wrong Unreal Engine version, the project completely crashed. We had to revert to the previous version to fix this.
Team Member Dropouts: Due to these technical issues, some team members dropped out of the project, thinking we couldn't finish it. This affected the morale of the rest of the team.

### Next Time
For the next time, I would change the following things:

-  NPC Communication System: 

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


## Declared Assets
- Provide a detailed list of any third-party assets used in the project.  
- This includes asset packs, music, sound effects, 3D models, textures, scripts, or code from external sources.  
- Declare any use of AI tools (e.g., ChatGPT, GitHub Copilot, Meshy) or pre-existing code. Specify the purpose of these assets/tools and how they were integrated into your work.  
- Ensure you clearly distinguish between your original work and any external contributions to maintain academic integrity.

<br>
<br>
<br>
<br>

