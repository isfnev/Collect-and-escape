# Collect and Escape

## Project Info
- Unity 6000.0.38f1
- Platform Target: Windows (.exe)

## Architecture Notes
- `GameManager`: Tracks timer, collectables, and door state.
- `DoorController`: Handles door open movement + sound.
- `PlayerController`: Handles movement physics.
- `SceneFlowManager`: Controls scene transitions.
- `MenuManager`: Handles Main Menu & Settings (volume + graphics).
- UI: PauseMenu, Results screen with best time save.

## Known Issues / TODOs
- Some UI scaling might look different on ultra-wide screens.
- Collect sound may cut off if item destroyed too fast (fixed with delay).

## Controls
- Move: WASD / Arrow Keys
- Pause: Escape
- Collect: Walk into item
- Finish: Reach end trigger

## Test Instructions
1. Launch `CollectAndEscape.exe`.
2. Main Menu → Play.
3. Collect all pickups → Door opens.
4. Reach exit → Results screen.
