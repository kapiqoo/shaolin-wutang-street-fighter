# Shaolin vs Wutang Legends + Ultra Street Fighter IV

## Project status
This repository currently contains a small browser-only placeholder prototype. That prototype is only a controls/interaction demo; it is **not** the requested mashup. Do not present it as the finished game or as an actual mod for either commercial game.

## Goal
Build an experimental, single-player-first Melty mashup with:
- **Primary game:** Shaolin vs Wutang Legends.
- **Companion game:** Ultra Street Fighter IV.
- **Desired concept:** cross-game duels in which both games run together and each game continues to handle its own combat. The desired end state is genuine game-to-game integration, not a standalone imitation fighting game.
- **Scope order:** first prove a safe, minimal single-player integration; only attempt multiplayer if the underlying integration is feasible and can be tested.

## Required first steps in the connected Melty/Codex environment
1. Inspect Melty's current project instructions and determine its supported mod/build workflow for both games.
2. Verify both games are installed and identify their exact versions and supported modding interfaces.
3. Determine whether both games can run together in a supported way and whether a real cross-game duel can be implemented without modifying proprietary executables or bypassing anti-cheat/security.
4. Produce a written feasibility report before making game changes. If direct simultaneous integration is unsupported, explain the blocker and propose the closest honest alternative for user approval; do not silently substitute a browser game.
5. Keep a backup/rollback path and test on a non-destructive copy or supported mod loader where possible.

## Content and safety boundaries
- Do not commit, upload, or redistribute either game's executable, extracted assets, character models, textures, music, animations, or other proprietary game files.
- Use the player's own legally installed game files at runtime only where Melty and the relevant game's terms and tools permit.
- Do not invent APIs, mod loaders, game paths, or compatibility claims. Verify each one in the actual environment.
- Do not claim that a character, stage, fighting style, or mechanic from Ultra Street Fighter IV is integrated until it is actually implemented and tested in-game.
- Do not describe the project as playable as a mashup until tested through Melty with both games.
- Preserve each game's genuine combat handling as the design target; do not replace it with a homemade web combat system and call that the requested result.

## Deliverables
- A feasibility report with verified facts, blockers, and next action.
- A minimal single-player vertical slice only after feasibility is established.
- Reproducible build/test steps, rollback instructions, and a release package that follows Melty's current requirements.
