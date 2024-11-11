---
layout: single
title: "Quick Update: Pathfinding and Basic Turn System"
date: 2024-11-11
categories: [devlog, gamedev, unity]
tags: [pathfinding, turn-based, gameplay]
---

# Quick Update: Pathfinding and Basic Turn System

Hey everyone! Just a quick progress update on the development of our tile-based game. Today, I'll share some implementations of basic game mechanics that will form the foundation of our combat system.

## Pathfinding Implementation

For pathfinding, I decided to use existing solutions rather than reinventing the wheel. Unity provides several ways to handle pathfinding, and implementing it was straightforward in our tile-based system.

## Turn Management System

I've implemented a basic turn-based system with the following rules:
- Each character gets 1 action per turn
- Movement counts as an action
- After the player acts, each enemy (or future NPC) takes their turn
- Turns cycle until all characters have acted

## Movement and Enemy Interaction

Some key features implemented:
- Players can follow a path continuously across multiple turns
- Movement automatically stops if an enemy comes within range
- Currently testing with 2 dummy enemies (they only log to console for now)

![pathfinding!](/assets/images/2024-11-11/Capture.JPG)

## Next Steps

In the upcoming posts, I'll share more detailed progress with GIFs to better demonstrate these mechanics in action. Stay tuned!

---

*Note: Future posts will include GIFs demonstrating these features in action.*