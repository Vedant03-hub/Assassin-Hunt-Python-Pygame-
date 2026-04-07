# Assassin Hunt (Python / Pygame)

A small top-down stealth hunting/assassin game implemented in Python using Pygame. No external assets required.

## Requirements
- Python 3.8+
- pygame (install with `pip install pygame`)

## Run
Save `game.py` and run:
```
python game.py
```

## Controls
- Move: WASD or Arrow keys
- Aim: Mouse
- Fire (pistol / melee): Left mouse button
- Switch weapon: 1 = Pistol, 2 = Knife
- Crouch (reduces enemy detection): Hold Left/Right Shift
- Reload pistol: R
- Start / Restart: Enter
- Quit: Close window / Esc (window close)

## Gameplay
- Patrol enemies with vision cones. If they see you they will chase.
- Use cover (the gray rectangles) and crouch to reduce detection range.
- Pistol: ranged weapon with limited ammo and reload.
- Knife: instant melee takedown at close range (cooldown).
- Score increases for enemy kills.

## Tweak / Extend
- Adjust constants at top of `game.py` to change difficulty, spawn, and mechanics.
- Add sound, levels, enemy projectiles, or more weapons (silenced pistol, bow, throwing knives).
