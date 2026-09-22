# Prototype Instructions

Run the local server yourself and open the preview in the browser available to this environment. Do not give the user server-start instructions when you can run it.

Before making substantial visual changes, use the Product Design plugin's `get-context` skill when the visual source is unclear or no longer matches the current goal. When the user gives durable prototype-specific design feedback, preferences, or decisions, record them in `AGENTS.md`.

When implementing from a selected generated mock, treat that image as the source of truth for layout, component anatomy, density, spacing, color, typography, visible content, and hierarchy.

Build app UI in `src/`. Keep `.openai/hosting.json`, `worker/index.js`, `scripts/prepare-sites-build.mjs`, and `tests/sites-worker.test.mjs` intact so the same local prototype can be handed to Sites. Before a Sites handoff, run `npm run build` and `npm run test:sites`; the build must leave `dist/client/index.html`, `dist/server/index.js`, and `dist/.openai/hosting.json`.

## User constraints — 22 September 2026

- This is an isolated test of the selected dark forest MOST Studio design with stone arch and two website panels.
- Only push to `tvkuca1113-art/Moststudiotest`. Never write to `tvkuca1113-art/Moststudioba`, its deployment or `moststudioba.com`.
- The original visual target is the second displayed concept, `exec-2c5a373a-8d8b-46ed-9cd9-d3bcb6ab8c47.png`.
- Preserve the original website untouched until explicitly authorized.
- Bosnian spelling, working German language option. Keep test pages out of search indexing.

## Second iteration
- User rejected the first implementation as insufficiently attractive. Strengthen the complete page, project presentations and mobile composition while keeping the selected forest/lime architectural direction. Continue only in the test repository.
