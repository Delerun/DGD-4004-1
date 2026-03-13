# DGD-4004-1
GAME DESIGN DOCUMENT (GDD)

Project Name: Corridor Escape

Genre: 3D Parkour / Escape / Horror

Platform: PC

Game Engine: Unity

Graphics Type: 3D

Game Mode: Singleplayer (Offline)

1. Game Overview

Corridor Escape is a 3D parkour game where the player navigates a university corridor, overcoming obstacles while escaping from an AI that relentlessly chases them. The game is played from a first-person perspective, immersing the player in a realistic corridor environment.

The player must overcome obstacles along the corridor and reach the end without being caught by the AI. If the AI touches the player, the game ends in defeat.

2. Game Objective

The player’s goals are:

Progress through the corridor

Overcome parkour obstacles

Escape from the AI

Reach the exit at the end of the corridor

Reaching the exit results in victory.

3. Gameplay

The game takes place in a 3D environment and is played from a first-person perspective.

The player can freely move within the corridor. At the start, the player is alone, but after a short period, the AI begins to chase them.

While progressing, the player will encounter:

Obstacles to jump over

Objects to navigate around

Platforms to traverse

Quick thinking and fast reflexes are required to successfully navigate the parkour.

4. Camera System

The game uses a First-Person Camera.

The camera moves from the player’s eye level

Controlled using the mouse

This system provides a more realistic and intense experience.

5. Controls

The player uses keyboard and mouse to control the character:

W key: Move forward

S key: Move backward

A key: Move left

D key: Move right

Shift key: Sprint

Space key: Jump

Mouse: Camera control

6. Level Design

The game takes place in a single 3D corridor environment, representing a university hallway.

Corridor length: approximately 60–100 meters

Contains different parkour sections

Section 1 – Start:

The player starts in an empty corridor

Designed for the player to familiarize themselves with movement controls

Section 2 – First Obstacles:

Introduces small parkour obstacles such as:

Chairs

Small boxes

Tables

The player must jump over these objects

Section 3 – Challenging Parkour:

Obstacles become more complex:

Stacked boxes

Narrow passages

Jumping over tables

Requires quick and careful movement

Section 4 – Final Area:

The final part of the corridor

Atmosphere becomes more intense:

Flickering lights

Narrower corridors

Exit door

Reaching the door ends the game in victory

7. Artificial Intelligence (Enemy AI)

The game features an AI that chases the player.

Implemented using Unity’s NavMesh system

AI characteristics:

Speed: slightly slower than the player

Speed increase: gradually over time

Vision: constantly tracks the player

Pathfinding: uses NavMesh to reach the player’s location

Capture: touching the player ends the game

The AI creates constant tension and pressure.

8. Parkour Obstacles

Various obstacles challenge the player’s progression:

Chairs

Tables

Boxes

Narrow passages

These obstacles slow the player down and require parkour mechanics to overcome.

9. Win/Lose Conditions

Win Condition:

The player reaches the exit door at the end of the corridor

Lose Condition:

The AI touches the player, ending the game

10. Sound Design

The game uses sound effects to enhance atmosphere and tension:

Player footsteps

AI footsteps

Ambient corridor sounds

Tense music

Sound intensity increases as the AI approaches.

11. Visual Style

The visual style is 3D and semi-realistic, depicting a university corridor.

Environmental elements include:

White walls

Fluorescent lights

Classroom doors

Tables

Chairs

The atmosphere is slightly dark and tense, adding to the sense of suspense.
