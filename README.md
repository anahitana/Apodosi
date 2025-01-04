# Apódosi
This game will be soon available for everyone to try it out! :)


Project Videos:

* Project Demo: [YouTube URL](https://youtu.be/feYIX6_9uKc)
* Project Trailer: [YouTube URL](https://youtu.be/ekdjXX7HOCM)
* Project Presentation: [YouTube URL](https://youtu.be/RErM8TKpjVo)

Project Group Members:

* Farhan Rahman Khan
* Erfan Mohammed Abu Jafar
* Anahita Nik aien 
* Tridib Paul Turjo

## Game Mechanics
- [x] Collisions
  - [x] Rectangular bounding box collisions between some entities
  - [x] Some collision between player and level geometry (walls, tiles, etc)
- [x] Movement
    - [x] Teleport
    - [x] Double Jump
- [x] Bullets / Weapons
  - [x] Our Game's Weapons are:
    - [x] Basic Lightning Ball Shoot
    - [x] Slash Attack Causing Bleeding
    - [x] Stun Attack Causing Enemies to be stunned and they cant attack or move
    - [x] Power Attack (Basically a high damage lightning close range like a shotgun)
    - [x] Lightning Grenade
  - [x] Weapons are swappable during gameplay via hotkey or ui element
- [x] NPCs
  - [x] At least 3 unique non-player characters in the game that act as enemies or allies
  - [x] contain basic AI such as path-finding / shooting / patrolling / battling with the player
  - [x] Each NPC has a unique weapon or method for interacting with the player
- [x] Hit Points / Damage
  - [x] Player / enemies in the game hit points (life) and take damage / die
  - [x] Invincibility frames is implemented for all entities that take damage (Only for player, a gameplay functionality)
  - [x] Enemy HP levels is displayed to the user in some way
- [x] Objects / Inventory
    - [x] Health Potion
    - [x] Mana Potion
    - [x] Strength Potion
- [x] Ray Casting for Visibility
- [x] Gravity / Acceleration
- [x] Camera / World View
    - [x] Standard Camera as a bounding box camera
    - [x] Mini-map of local area that shows player position and enemies
    - [x] Fitting Boss and Player Camera on Boss Level
- [x] Audio
- [x] Assets
- [x] Options
  - [x] Music Volume
  - [x] Sound Effects
  - [x] Game Difficulty - Normal, Easy (deal 1.75x dmg, have 3x hp), Hard (deal 0.75x dmg, have .5x hp)
  - [x] Rebind main gameplay scene keys – for example moving left / right, jump, shoot, etc
- [x] Game Progression
  - [x] Overworld map lock or unlock game progression based on levels completed
- [x] Status Effects
    - [x] Health Regen
    - [x] Mana Regen
    - [x] Strengthening
    - [x] Stunned
    - [x] Bleeding
- [x] User Interface / HUD
    - [x] Player health
    - [x] Abilities and Energy(Mana)
    - [x] Game Progression
    - [x] Status Effects / Timers
    - [x] Inventory/Items/Potions
- [x] Shaders
- [x] Parallax
- [x] Ray Casting for Simple Lighting Effect
- [x] Pathfinding/Steering
- [x] Extras
- [ ] 
Level Editor Functionality:
- [x] Menu that allows you to select an existing level to edit
- [x] Ability to select and place any Texture / Animation defined in the Assets file into the level
- [x] Any parameters of specific entities must be editable via the level editor. For example, this can include:
  - [x] Whether NPCs block vision, movement, or neither
  - [x] The hit points / damage of NPCs in the level
  - [x] The patrol points of moving tiles or NPCs
