# Preliminary technical feasibility — Makoto crossover

Status: **Not yet verified in-game; do not publish as playable.**

## Target
- Primary game: Shaolin vs Wutang Legends
- Fighter source: Ultra Street Fighter IV
- First fighter: Makoto
- Desired style: faithful karate, forward dash, close-range strikes, and recognizable special attacks
- Initial scope: single-player experiment; multiplayer later

## Evidence found
- Public SteamDB records identify Shaolin vs Wutang Legends as a Windows Unity Engine game (Steam app 3917840): https://steamdb.info/app/3917840/info/
- Its listed Windows depot contains a large Unity data archive and managed assemblies including Assembly-CSharp.dll: https://steamdb.info/depot/3917841/
- Ultra Street Fighter IV has a separate established PC modding ecosystem, including character-resource and moveset tools: https://aemods.pbworks.com/w/page/41161851/Ultra%20Street%20Fighter%204%20Modding%20Wiki
- USFIV's modding tools operate on USFIV's own character/resource formats. That is not evidence that its model, animation, or combat data can be loaded directly into Shaolin vs Wutang Legends.

## Current conclusion
A Unity-based mod may be technically investigable, but no supported mod API, loader compatibility, or way to register a new character in Shaolin vs Wutang Legends has been confirmed. The requested cross-game combat handoff is also unproven. Owning both games alone does not establish compatibility.

## Required local verification
1. Inspect the installed Shaolin vs Wutang Legends directory and exact build.
2. Determine whether its character assets, animation controllers, and combat definitions can be extended through a supported loader or data format.
3. Check whether the Melty integration can launch/coordinate the actual installed games and what package schema it accepts.
4. Inspect USFIV's installed Makoto resources locally; do not redistribute game files.
5. Build a minimal local-only proof of concept and test it in the real primary game.

## Guardrails
- Do not use the browser prototype as the requested deliverable.
- Do not describe the mod as playable until verified in-game.
- Do not upload game executables or extracted commercial assets.
- If the engine does not permit a faithful import, stop and explain the exact blocker before changing the design.
