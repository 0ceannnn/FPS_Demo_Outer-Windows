# Outer Space Level – Real-Time Game Systems (Playable Demo)

This project is a university game development assignment.
The source code is kept private to comply with academic integrity policies.
A playable demo is provided for gameplay and system demonstration purposes.

---

## Introduction

This level is set in an outer space environment where the player explores an open area filled with interactive rocks and a single locked treasure chest.  
The core objective is to locate a hidden key and unlock the chest to complete the level.

To enhance replayability and unpredictability, the game relies heavily on randomized systems rather than fixed outcomes.

---

## Gameplay Overview

### Core Objective
- Explore the environment
- Break rocks to search for the hidden key
- Unlock the treasure chest to complete the level

### Randomized Systems
- **Key Spawn**
  - The key can randomly appear from any breakable rock
  - Its location changes every run, ensuring no two playthroughs are identical

- **Monster Spawns**
  - Monsters may randomly emerge instead of the key
  - They do not spawn from fixed rocks; all breakable rocks are potential spawn points
  - Spawn outcomes are never predetermined

### Enemy Behavior
- Monsters remain idle upon spawning
- Once the player enters a detection radius, monsters switch to an active chase state
- Enemies pursue the player using proximity-based AI behavior

---

## Gameplay Design Philosophy

This level is designed around a **risk–reward loop**:

- Players can aggressively break rocks to find the key faster
- However, doing so increases the risk of spawning multiple monsters
- Alternatively, players may proceed cautiously to reduce danger

The combination of:
- randomized spawns
- proximity-based enemy AI
- destructible environment elements

creates tension, encourages exploration, and promotes dynamic decision-making throughout each playthrough.

---

## Systems & Features Implemented

This project extends multiple systems introduced throughout the course into a cohesive and fully playable level, including:

- Player Pawn setup
- Actor-based interaction systems
- Trigger boxes and detection volumes
- Enemy AI with idle and chase states
- Collectible and key-based progression systems
- Level completion logic
- Projectile systems
- Visual effects (VFX)
- Collision setup and response
- Materials and meshes
- Landscape and environment design

---

## Tools & Assets

- Unreal Engine (Blueprint-based implementation)
- Quixel / Fab assets for environment and props
- Custom materials and effects
- Modular actor and system design

---

## Development Approach

Throughout development, I closely followed and applied concepts from class lectures, including:

- Blueprint visual scripting
- Player Pawn configuration
- Trigger boxes and overlap events
- Macros and pure functions
- Projectile systems
- Visual effects integration
- Collision configuration
- Cohesive gameplay and level design principles

My goal was to create a polished, cohesive gameplay experience that integrates enemy interactions, collectibles, portals, custom mechanics, and environmental storytelling within a multi-level game structure.

---

## Playable Demo

The playable demo can be downloaded from the **Releases** section of this repository.

> Note: Source code can be shared privately upon request.

