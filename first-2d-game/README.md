# First 2D Game

A simple 2D game built with Godot Engine featuring a player character that must avoid enemies while scoring points.

## Description

This is a basic 2D game where the player controls a character that moves around the screen. The goal is to avoid enemies (mobs) that spawn randomly and move across the screen while accumulating points over time.

## How to Run

To run this game, you need to have Godot Engine installed on your system.

1. **Install Godot Engine** (version 4.5 or later)
   - Download from [https://godotengine.org/download/](https://godotengine.org/download/)

2. **Open the project**
   - Launch Godot Engine
   - Click "Import" and select the `project.godot` file in this directory
   - Click "Import & Edit"

3. **Run the game**
   - Press F5 or click the "Play" button in the Godot editor
   - Alternatively, you can run the game by pressing the "Play Scene" button (F6) while the main scene is open

## Controls

- **Arrow Keys**: Move the player character (up, down, left, right)
- **Enter**: Start a new game (when game over screen is shown)

## Game Features

- Player character with smooth movement
- Random enemy spawning from different paths
- Score system that increases over time
- Game over screen with restart functionality
- Background music and sound effects
- HUD displaying current score and game messages

## Project Structure

- `main.tscn` - Main game scene
- `main.gd` - Main game logic and mob spawning
- `player.tscn` - Player character scene
- `player.gd` - Player movement and collision handling
- `mob.tscn` - Enemy mob scene
- `mob.gd` - Mob movement and collision detection
- `hud.tscn` - User interface scene
- `hud.gd` - HUD logic and game over handling

## Assets

The game includes various sprite assets for the player and different types of enemies, along with audio files for music and sound effects.
