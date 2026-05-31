# Cafeteria Tactics

A turn-based tactical roguelike set in a middle school cafeteria — think XCOM, but with food fights.

Players take control of a student navigating the chaos of lunchtime, moving across the cafeteria floor, taking cover behind tables and pillars, and launching food projectiles at rival kids (bullies). Each turn allows one move and one action: **Hide** (crouch behind cover) or **Throw** (launch an apple at a target).

## Built With

- Unreal Engine 5.7
- Blueprints

## Setup

1. Clone this repository
2. Right-click `CafeteriaTactics.uproject` → **Generate Visual Studio project files**
3. Open the generated `.sln` in Visual Studio 2022 → Build (Development Editor / Win64)
4. Open `CafeteriaTactics.uproject` in Unreal Engine 5.7

## Current Features

- Sample cafeteria level with whitebox geometry (tables, pillars, food service counter, stage)
- Title screen with Start button
- Turn-based movement system with action HUD (Hide / Throw Apple / End Turn)
- Apple projectile with physics-based throw toward cursor

## Project Structure

```
Content/CafeteriaTactics/
├── Blueprints/     — Game blueprints (characters, controllers, gameplay)
├── Art/            — Meshes, materials, textures
├── Audio/          — Sound assets
└── Maps/           — Level maps
```
