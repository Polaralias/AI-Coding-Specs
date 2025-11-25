# AI Coding Specs

This repository centralizes the Markdown Concept (`.mdc`) specification files that govern how AI agents should work on the associated codebases.

## How to use this repository
- Start with `AGENTS.md` to see how agent entrypoints map to the `.mdc` files.
- Open your agent-specific file (`codex.md`, `CLAUDE.md`, or `GEMINI.md`) to get the reading order for the standards you need.
- Consult the `.mdc` files directly for the authoritative rules.

## Specification index
The `ai-specs/specs` directory contains the standards referenced by the agent files:
- `base-standards.mdc`: universal guidance that always applies.
- `backend-standards.mdc`: Node.js/TypeScript backend conventions and architecture patterns.
- `frontend-standards.mdc`: React application standards for components, state, and testing.
- `android-standards.mdc`: Android/Kotlin development guidance.
- `ai-tools-standards.mdc`: rules for designing and implementing AI tools or automations.
- `documentation-standards.mdc`: expectations for writing and maintaining docs.

For change histories or feature-level plans, see `ai-specs/changes/`.
