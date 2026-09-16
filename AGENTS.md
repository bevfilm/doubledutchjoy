# AGENTS.md — Double Dutch Joy

## Project Purpose

Double Dutch Joy is a small 2D arcade game about girls playing Double Dutch in 1980s Chicago.

The immediate objective is to develop a polished, replayable MVP built around the existing core loop:

jump → double jump → collect → dodge → score → fail → restart

Read `GAME_BRIEF.md` before proposing or implementing significant changes.

---

## Existing Prototype

This repository contains an existing playable prototype created in GDevelop.

Treat the existing GDevelop project as valuable source material and a reference implementation.

Before changing or replacing existing systems:

1. Inspect them.
2. Explain what they currently do.
3. Identify what is already working.
4. Determine whether modification is actually necessary.

Do not overwrite, delete, or substantially restructure the original GDevelop prototype unless explicitly instructed.

Prefer repairing, extending, or reusing working systems over rebuilding them from scratch.

---

## Development Priorities

Prioritize work in this order:

1. Core gameplay feel
2. Reliable jumping and rope interaction
3. Collecting and obstacle avoidance
4. Scoring and failure states
5. Fast restart and replayability
6. Clear player feedback
7. Basic sound and visual polish
8. Additional content

Do not prioritize large feature additions while the core gameplay loop is still unfinished or unsatisfying.

---

## MVP Scope

The MVP should remain deliberately small.

The MVP currently requires:

- One playable character
- One Double Dutch gameplay environment
- Jumping
- Double jumping
- Functional rope interaction
- Collectibles
- At least one obstacle type
- Score tracking
- Clear failure condition
- Game-over state
- Restart
- Basic sound feedback
- Clear visual feedback

Do not automatically implement ideas listed under "Future Possibilities" in `GAME_BRIEF.md`.

Those ideas are preserved for later evaluation and are not part of the current development scope.

---

## Working Style

Work in small, testable increments.

Prefer one player-visible improvement per task whenever practical.

Examples:

- improve jump timing
- add one collectible behavior
- fix one failure condition
- improve score feedback
- add restart behavior

Avoid large multi-system rewrites unless they are clearly necessary.

Before a major refactor, explain:

- why the refactor is needed
- what existing behavior could break
- what the proposed replacement improves
- whether a smaller change could accomplish the same goal

Do not refactor merely because another architecture appears cleaner.

---

## Preserve Creative Intent

Do not replace culturally specific elements with generic game conventions without explicit approval.

This includes:

- Double Dutch as the central activity
- 1980s Chicago setting
- Black girlhood
- culturally specific collectibles
- neighborhood atmosphere
- period clothing and hairstyles
- joy as the dominant emotional tone

The game should not introduce trauma, violence, poverty narratives, or social-problem framing simply because of its Black Chicago setting.

Do not invent cultural details when uncertain. Flag questions for the creator instead.

---

## Narrative and Setting

Do not make major narrative decisions without explicit direction.

Some earlier design materials contain unresolved differences about the exact Chicago neighborhood.

Do not silently reconcile contradictions in source material.

Identify the discrepancy and ask for a creative decision when it becomes relevant.

---

## Technology Decisions

Do not change engines or frameworks automatically.

If recommending migration away from GDevelop:

1. Explain why.
2. Identify what would be gained.
3. Identify what would be lost.
4. Identify which existing assets or systems can be reused.
5. Compare the cost of migration with continuing in GDevelop.

For any proposed replacement technology, prefer technologies that support:

- browser play
- simple deployment
- low maintenance
- straightforward debugging
- preservation of existing assets where possible

The smallest practical solution is preferred.

---

## Testing

After implementing changes:

1. Verify that the project still runs.
2. Test the specific behavior changed.
3. Check that existing core gameplay has not been broken.
4. Report what was changed and what was tested.
5. Identify anything that could not be verified.

When practical, create repeatable testing or debug tools that make future development easier.

Do not claim that something works unless it has actually been tested or clearly identify when testing was not possible.

---

## Source Control

Keep changes focused and easy to review.

Do not delete large amounts of project content without explicit approval.

Avoid combining unrelated changes into one task.

Preserve working history rather than replacing the entire project unnecessarily.

---

## Assets

Before replacing art, sound, sprites, or other assets:

1. Identify what already exists.
2. Determine whether the existing asset is functional.
3. Explain why replacement would improve the MVP.

Do not add copyrighted commercial music or third-party assets without clear permission or appropriate licensing.

Temporary placeholder assets are acceptable during prototyping.

---

## Feature Creep Rule

When considering a new feature, ask:

**Does this materially improve the core Double Dutch gameplay experience?**

If the answer is unclear, place the idea in the backlog rather than implementing it.

Do not turn a small arcade MVP into a large simulation, RPG, management game, multiplayer system, live-service product, or monetization platform without explicit direction.

---

## Communication

When uncertain, explain the uncertainty rather than guessing.

When multiple approaches are possible, recommend the simplest viable approach and briefly explain the tradeoffs.

Surface contradictions, missing information, technical risk, and scope expansion before acting on them.

The creator makes the final creative and product decisions.
