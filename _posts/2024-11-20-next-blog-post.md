---
layout: single
title: "Visual Progress: Trees and Corruption Mechanics"
date: 2024-11-20
categories: [devlog, gamedev, unity]
tags: [corruption-system, visuals, game-mechanics]
---

# Visual Progress: Trees and Corruption Mechanics

## Tree Implementation
Replaced the placeholder cylinders with proper tree models that reflect corruption levels:
- Base state: Full foliage
- Three corruption stages with different leaf materials
- Final corruption stage: Leafless trees

![trees!](/assets/images/2024-11-20/Capture2.JPG)

## Corruption System Implementation
Added core mechanics for the corruption system:
- Corruption/cleansing sources (currently represented as cubes)
- Turn-based corruption spread
- Proximity-based influence (closer tiles experience stronger effects)
- Visual transitions at corruption thresholds

![regenerated map](/assets/images/2024-11-20/Capture.JPG)

## Current Game Loop
1. Player action
2. Enemy turns
3. Corruption phase
   - Sources activate
   - Spread effects to nearby tiles
   - Update visuals based on corruption levels

## Technical Challenges
- Managing multiple tree variants for corruption states
- Optimizing leaf removal for higher corruption levels (postponed for later optimization)
