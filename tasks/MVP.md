# MVP checklist

## Phase 1 — Feasibility (do this before implementation)
- [ ] Open this repository as a project in the connected Melty/Codex environment.
- [ ] Read the current Melty-specific project instructions and accepted release format.
- [ ] Verify that Shaolin vs Wutang Legends and Ultra Street Fighter IV are installed, with exact versions recorded.
- [ ] Identify the supported modding interfaces/loaders for each game from authoritative local documentation.
- [ ] Determine whether Melty can launch and coordinate both games simultaneously for this use case.
- [ ] Confirm that the requested cross-game combat handoff is technically possible without unsafe executable patching or redistribution of proprietary files.
- [ ] Write a feasibility report and stop for user approval if major design tradeoffs are needed.

## Phase 2 — Minimal single-player slice (only if Phase 1 passes)
- [ ] Launch the primary game through the supported Melty flow.
- [ ] Demonstrate one verified interaction with a real Ultra Street Fighter IV fighter/style using permitted runtime access or a supported mod.
- [ ] Keep the original game's own combat system responsible for its combat wherever the architecture allows.
- [ ] Test clean launch, normal exit, and rollback to unmodified games.
- [ ] Record exact test steps and observed results.

## Phase 3 — Release
- [ ] Follow the current Melty release/package instructions.
- [ ] Ensure no commercial game binaries or extracted assets are included.
- [ ] Verify the uploaded package on a clean setup.
- [ ] Only after successful in-game testing, mark the project as playable.
- [ ] Consider multiplayer only after the single-player integration is stable and tested.
