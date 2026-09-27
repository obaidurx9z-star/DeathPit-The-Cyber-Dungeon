# Top-Down Battle Arena

## Game Description

**Top-Down Battle Arena** is a 2D action/shooter game developed as a university CSE project using **C++** and the **iGraphics** library. The game features multiple levels, enemy AI, puzzles, laser obstacles, power-ups, a boss battle, an AI-controlled clone ability, and a level checkpoint/resume system.

The game is designed as a top-down battle experience where the player explores different rooms, solves puzzles, defeats enemies, and progresses through increasingly challenging levels.

## Features

- Top-down 2D gameplay.
- Multiple levels with different room layouts and objectives.
- Player movement, shooting, health system, and collision detection.
- Dynamic enemy spawning and enemy AI.
- Enemies can move, search for the player, and chase the player.
- Level 1 with dynamic enemies and puzzle-based progression.
- Exactly 7 enemies in Level 1.
- Laser obstacles that damage the player on contact.
- Puzzle switches used to unlock areas and progress through levels.
- Level 2 with a four-room layout.
- Two enemies assigned to each Level 2 room.
- Room-based enemy activation after the corresponding laser is unlocked.
- Mines that can cause Game Over.
- Temporary shield ability that protects the player from damage.
- Level 2 timer-based progression.
- Level 3 boss battle.
- Reduced boss speed and attack power for the Level 3 boss.
- AI-controlled player clones in Level 3.
- Two clones can assist the player by automatically searching for and attacking enemies.
- Clone lifetime and recharge mechanics.
- Boss-room gameplay and special Level 3 mechanics.
- Level checkpoint/resume system.
- If the player dies in a later level, the game can resume from the latest unlocked level instead of starting from Level 1.
- Level completion screens and automatic progression.
- Health and gameplay UI.
- Image-based player, enemy, laser, and puzzle-switch rendering.

## Project Details

IDE: Visual Studio 2013

Language: C / C++

Library: iGraphics

Platform: Windows PC

Genre: 2D Top-Down Action / Shooter

Project Type: University CSE Game Project

## How to Run the Project

Make sure you have the following installed:

- **Visual Studio 2013**
- **iGraphics Library**
- Required project assets/images included in this repository

### Steps

1. Clone or download this repository.
2. Open the `.sln` file in **Visual Studio 2013**.
3. Make sure the required iGraphics files and game assets are available in the project.
4. Go to **Build → Build Solution**.
5. If the build is successful, run the game using **Debug → Start Without Debugging**.

> **Note:** The project uses iGraphics and is intended to run on Windows with the appropriate iGraphics setup.

## How to Play

### **Controls**

| Action | Control |
|---|---|
| Move Up | `W` |
| Move Down | `S` |
| Move Left | `A` |
| Move Right | `D` |
| Interact / Activate Puzzle | `E` |
| Shoot | `Mouse / Existing Fire Control` |
| Activate Clone (Level 3) | `Activate Clone` button/'C' |

### **Game Rules**

- The player starts each level with a health bar and must keep their health above 0.
- Enemy contact and enemy attacks reduce the player's health.
- Touching an active laser damages the player.
- The player must defeat the required enemies and complete the required puzzle objectives to progress.
- In Level 2, the player must unlock rooms using the required switches and complete the room objectives.
- Touching a mine in Level 2 causes immediate Game Over.
- The shield provides temporary protection from damage for a limited duration.
- The Level 2 timer must be managed while completing the required objectives.
- In Level 3, the player must defeat the boss inside the boss room.
- Level 3 clones are AI-controlled and automatically search for and attack enemies.
- The player cannot directly control the clones.
- Clones remain active only for their configured lifetime and then disappear.
- The player must avoid enemies and environmental hazards while completing the level objectives.
- Completing the required objectives allows the player to continue to the next level.

## Project Contributors

1. Shishir
2. Abir
3. Majid
4. Obaidur

## Screenshots

### Main Menu
_Add screenshot/(Main_Menu.jpeg)

### Level 1
_Add screenshot/(Level1.jpg)

### Level 2
_Add screenshot/Level2.jpg

### Level 3 / Boss Battle
_Add screenshot/Level3.jpg


## YouTube Link

[CSE Game Project Demo]([YOUR_YOUTUBE_LINK_HERE](https://www.youtube.com/watch?v=GR9N4HO2GzA&t=16s))

## Project Report

[Project Report](YOUR_PROJECT_REPORT_LINK_HERE)

## Technologies Used

- C++
- iGraphics
- Visual Studio
- 2D Graphics
- Basic Game AI
- Collision Detection
- Timer-Based Game Logic
- Projectile System
- Level/Checkpoint System

## Acknowledgement

This project was developed as part of a university CSE course project to demonstrate concepts of C/C++ programming, graphics programming, game logic, artificial intelligence, collision detection, and interactive 2D game development.
