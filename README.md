# Mansion of the Dead

A browser-playable 8-bit survival horror game inspired by classic mansion horror: pixel art, a 2.5D top-down canvas renderer, painter-sorted props, scarce supplies, undead patrols, and a CRT-styled interface.

## Play

```bash
npm run dev
```

Open `http://localhost:5173`.

## Controls

- **WASD / Arrow keys**: Move
- **Shift / Gamepad A**: Run
- **Mouse**: Aim stance direction
- **Click / Gamepad right trigger**: Fire pistol with auto-aim toward the nearest enemy
- **R / Gamepad X**: Reload the 12-round magazine from reserve ammo
- **P**: Pause
- **Enter**: Start from title/game-over screens

## Objective

Explore the seven-room mansion, collect all **3 fuses**, and reach the east exit while managing limited ammo and health. Your final escape earns an **S-C rank** based on time and condition.

## Features

- Seven tile-built rooms: main hall, corridors, dining room, library, guest room, and master suite.
- Twin-stick style movement/aiming with keyboard + mouse and Gamepad API support.
- Zombies and two tougher brutes with aggro/chase/attack AI.
- 12-round pistol magazine, manual reloads, scarce ammo pickups, green herbs, and fuse pickups.
- Typewriter prop, room-name letterbox banners, RE-style condition/ammo/fuse HUD, pause/title/death/victory screens.
- Persistent blood decals, screen shake, muzzle flash, dynamic flashlight darkness, candlelit mood colors, CRT scanlines, procedural WebAudio shots/pickups and haunted ambient drone.
