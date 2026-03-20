# 3D LAN Multiplayer Starter

This repo is a standalone copy of the `networking/robot_war` demo from `template-20-mini-games`.

It is intended to preserve the original demo's look and behavior, with one deliberate change: the project launches directly into `res://networking/robot_war/robot_war.tscn` instead of the source repo's scene selector.

## Included

- Original `robot_war` launcher scene and arena assets
- Original two-window `Spawn Game Windows` flow
- Shared networking lobby and multiplayer settings scripts
- Shared `gdbot` player model stack
- Original project theme, input map, fullscreen handler, and subwindow settings
- Import sidecars (`.import` files) carried over from the source project

## Run

1. Open the folder in Summer Engine.
2. Run the project.
3. Click `Spawn Game Windows`.
4. In one window press `Host`.
5. In the other window press `Join`.

## Controls

- `WASD` or arrow keys to move
- `Alt` plus left or right to strafe
- Left or right without `Alt` to turn
