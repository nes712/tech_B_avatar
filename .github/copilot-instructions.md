<!-- .github/copilot-instructions.md for tech_B_avatar -->
# Copilot / AI agent instructions — tech_B_avatar

This repository is a very small static project (single `index.html`). The guidance below is tuned to help AI coding agents be immediately productive working in this repo.

Goal
- Make small, safe improvements to the single-page site. Prioritize clear, incremental changes and ask for clarification if the user requests large feature work.

Quick facts (what the agent should know)
- The project root contains a single source file: `index.html`. There is no package.json, build system, or tests.
- Changes should be minimal, reversible, and avoid adding heavy tooling unless the user asks.

What to do first
- Open and read `index.html`. Any UI or content change will be made there.
- When adding files, create them under the project root or a new directory and mention them in the PR description.

Typical tasks and examples
- Content edits: update text inside `index.html`. Example: replace the page title or add a meta description.
- Styling: add a small `<style>` block in `index.html` or create `styles.css` and link it. Keep CSS small and scoped.
- Assets: add an `assets/` directory for images or fonts and reference them with relative paths.

Project-specific patterns
- No JS frameworks or build steps are present. Prefer vanilla HTML/CSS/JS and keep changes file-local to `index.html` unless asked to scaffold a larger site.

When to ask the user
- If a change requires new tooling (npm, bundlers, linters), ask before adding.
- If the user requests a multi-file app or backend, propose a plan and confirm tech choices.

Do-not-do
- Do not add CI, package manifests, or large dependencies without explicit user approval.

Files to reference
- `index.html` — single source of truth. Use it for examples in suggestions and edits.

How to present changes
- Provide a short summary of edits, the exact file paths changed, and a concise rationale.
- For any added files, include a one-line purpose in the PR description.

If you update this guidance
- Keep it short (20–50 lines) and only document discoverable patterns.

Questions or gaps
- If the user's intent is unclear (feature request vs content edit), ask a clarifying question before making breaking changes.

---
Created by an automated agent scanning the repository structure on Oct 19, 2025.
