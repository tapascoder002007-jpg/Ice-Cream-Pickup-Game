# Ice Cream Delivery

A 2D Unity game where the player has to deliver ice cream to a monster hole while using speed boosts to move faster.

## Overview

In this game, the player navigates through a 2D environment and delivers ice cream to a monster hole. Along the way, the player can collect boosts that increase movement speed and help complete the delivery.

## Screenshots

<img width="2840" height="1576" alt="image" src="https://github.com/user-attachments/assets/0d3daf72-9146-4d70-8874-1e01a8837e69" />

<img width="2885" height="1594" alt="image" src="https://github.com/user-attachments/assets/4c4ca79f-f3c4-41ff-bef7-85561380ea82" />

## Features

- Ice cream delivery objective
- Monster hole as the destination
- Speed boosts that increase movement speed
- 2D platformer-style gameplay
- Interactive environment
- Boost Particle system

## Technologies & Tools

- **C#** — Game scripting and logic
- **Unity** — Game engine
- **Piskel** — Pixel-art creation

## Controls

| Action | Key |
|---|---|
| Turn Left | `A` / `←` |
| Turn Right | `D` / `→` |
| Climb Up | `W` / `↑` |
| Climb Down | `S` / `↓` |

## Project Structure

```text
Game 1/
├── Assets/
│   ├── Default/                         # Default Unity assets
│   ├── GameDev.tv - Delivery Dash Assets/ # Game assets and resources
│   ├── Prefab/                          # Reusable GameObjects
│   ├── Scenes/                          # Game scenes
│   ├── Script/                          # C# scripts and game logic
│   ├── Settings/                        # Game and project settings
│   └── TextMesh Pro/                    # TextMesh Pro assets
│
├── Packages/
│   ├── manifest.json                    # Unity package dependencies
│   └── packages-lock.json
│
├── ProjectSettings/
│   └── ProjectVersion.txt               # Unity version information
│
└── README.md

## How to Run

1. Clone the repository:

```bash
git clone <https://github.com/tapascoder002007-jpg/Ice-Cream-Pickup-Game>
```

2. Open **Unity Hub**.

3. Select **Add Project from Disk** and choose the cloned `TileVania` folder.

4. Open the project using the Unity version specified in `ProjectSettings/ProjectVersion.txt`.

5. Open the main scene from:

```text
Assets/Scenes/
```

6. Press **Play** in the Unity Editor to start the game.

## Credits

Developed by **[Tapas Dev Yadav]**.

This project was developed independently, with inspiration and learning resources from the Udemy course:

**Complete C# Unity 2D Game Development (Updated To Unity 6)**  
by GameDev.tv Team, Rick Davidson, and Ahmed Nassef.

The course was used as a learning resource and source of inspiration for developing the game.
