# Collobaration Project 

## Game Artificial Intelligence

FGCT7011
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
 For this project, I researched several sources related to game AI. Through these researches, I learnt important principles, techniques, and practical examples of applications. I created the AI ​​system of "Project Ebonkeep" using YouTube tutorials from great game developers such as Gorka Games, Ali Elzoheiry, and Ryan Laley. And also i reearched official Unreal Engine documentation, and information available on Unreal Engine Dev community page.

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
The mechanism used for the AI ​​minor enemies (Guards, Bandits) in The Witcher 3 was used as a guide for the swordsmen and archers in our "Project Ebonkeep". In particular, the way enemies explore, detect suspicious activity, and provide early warning of attacks were used. What makes The Witcher 3's AI system unique is its ability to respond to natural routines and the environment.

I used the following concepts when developing the Guards AI:
- Patrol Routes
- Suspicious Activity Detection
- Switching of instruments (Normal, Investigation, Attack)

2. Assassin's Creed Series
The NPC interaction system in the Assassin's Creed series was a very special source for the development of the AI ​​in my game. The way the NPC characters in this game communicate with each other and how they interact with the player was a big inspiration for me. For example, the way the guards converse with each other, exchange information with each other, and converse with the player is a feature I would like to include in the AI ​​system of my game. I am currently working on adding this feature to the game "Project Ebonkeep".

The features that I am implementing from the Assassin's Creed series are:

- Dialogue and interaction system between NPC characters
- Interaction system between NPC characters and the player
- Social behavior patterns and response system
- Exchange of information between NPCs about suspicious activity

### Academic Sources  
--
### Documentation Sources  
1. Unreal Engine Documentation - Behavior Trees
The official Unreal Engine documentation provides a detailed guide to Behavior Trees. Using this documentation, I learned about the use of Blackboards, Decorator and Service nodes, and Task nodes.
Important concepts I learned from the Unreal Engine documentation:

Using the Blackboard system
AI Perception Component
Behavior Tree Decorators
Behavior Tree Services
Behavior Tree Tasks

2. Gorka Games YouTube Tutorials
The "Enemy AI" tutorial series created by Gorka Games was a very important resource that I used. This tutorial series discusses the process of creating a complete AI system in Unreal Engine step by step.
Important things I learned from the Gorka Games guides:

Creating the AI ​​Perception Component
Creating Test Nodes in the Behavior Tree
Using Blackboard Variables
Implementing Combat Logic and Patrol Logic

3. Ali Elzoheiry's Advanced AI Tutorials
Ali Elzoheiry's workshops and techniques discuss creating more complex AI behaviors in Unreal Engine. Using these techniques, I created Team AI Behaviors for Soldiers and Archers.
Important concepts I learned from Ali Elzoheiry's workshops:

Coordinated Attack Strategies
Ranged Attacker AI - for archers
Melee Attacker AI - for swordsmen

4. Ryan Laley's AI Combat Systems
Ryan Laley's set of techniques focuses on combat systems in game AI. Using this set of techniques, I developed the combat actions of the Guards AI.
Important concepts I learned from Ryan Laley's guides:

Combat Transitions
Dynamic Attack Patterns
Response to player actions
Attack Sensitive Zones

## Implementation (Suggested Word Count 1,100)  

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


### New Approaches  
- Detail any innovative or new approaches you explored during the project.  
- Explain why these approaches were chosen and how they differ from standard practices.  
- Evaluate the success of these approaches, including any challenges faced and lessons learned.

### Testing
- Document the user testing conducted, specifying the type of tests used (e.g., automated testing, guided user testing, blind testing).  
- Present feedback or issues identified during testing, using graphs, tables, or visual aids to summarise results.  
- Describe how these issues were addressed. If any issues were not resolved, provide a clear justification for leaving them unaddressed.

### Technical Difficulties
- Identify any technical difficulties encountered during the implementation phase.  
- Provide details on how these issues were diagnosed and resolved.  
- If any difficulties remain unresolved, explain the impact on the project and any mitigation strategies used to minimise their effect.  
- Reflect on what you would do differently in future projects to avoid similar issues.

## Outcomes (Suggested Word Count 300) 

### Source Code/Project Files
- Provide a link to your complete source code or project files.  
- Ensure the link is publicly accessible or shared with the appropriate permissions.  
- Include a brief description of the files provided, highlighting key components or any instructions required to run the project.

### Build Link
- Share a link to a playable or executable build of your project.  
- Ensure the build is accessible across relevant platforms and is publicly accessible.  
- Include any necessary instructions for running the build, such as system requirements or installation steps.

### Video Demonstration
- Embed a video or provide a link to a recorded demonstration of your project in action.  
- The video should showcase key features, functionality, and any unique elements of your project.  
- Include a brief commentary or text overlay in the video to explain the different aspects of your project as they are shown.

## Reflection (Suggested Word Count 500) 

### Research Effectiveness  
- Assess the usefulness of the research conducted during the project.  
- Highlight which sources (games, academic, documentation) had the most significant impact on your work and explain why.  
- Identify any research gaps or areas where additional information could have improved your project outcomes.

### Positive Analysis 
- Reflect on the successful aspects of the project.  
- Highlight specific elements that worked well, such as technical solutions, creative decisions, or user feedback.  
- Provide evidence to support your analysis, such as test results, screenshots, or user comments.

### Negative Analysis  
- Identify the areas of the project that did not go as planned or could have been improved.  
- Discuss challenges you faced, whether technical, creative, or time-related, and evaluate their impact on the final product.  
- Reflect on any mistakes or missteps and what you learned from them.

### Next Time
- Outline what you would do differently if you were to undertake a similar project again.  
- Suggest improvements to your workflow, research methods, or implementation process based on your reflections.  
- Consider any new tools, techniques, or approaches you would explore in future projects to achieve better results.

## Bibliography  
- Compile a complete list of all sources referenced throughout your project. This may include articles, journals, videos, games, software, documentation, or any other materials.  
- Ensure all references are formatted according to the [university's citation method](https://mylibrary.uca.ac.uk/referencing).  
- Organise your references in alphabetical order. Alternatively, you may separate them by type (e.g., academic sources, games, videos), but consistency is key.

## Declared Assets
- Provide a detailed list of any third-party assets used in the project.  
- This includes asset packs, music, sound effects, 3D models, textures, scripts, or code from external sources.  
- Declare any use of AI tools (e.g., ChatGPT, GitHub Copilot, Meshy) or pre-existing code. Specify the purpose of these assets/tools and how they were integrated into your work.  
- Ensure you clearly distinguish between your original work and any external contributions to maintain academic integrity.

<br>
<br>
<br>
<br>

