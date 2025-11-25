# AI Coding Specs

This repository centralizes the Markdown Concept (`.mdc`) specification files that govern how AI agents should work on the associated codebases. Each agent (Codex, Claude, Gemini) lands here to pick up the same Polaralias coding standards before working in a downstream repository.

## How to use this repository
1. **Start with the entrypoint instructions.** Read `AGENTS.md` to understand how the agent guides tie into the `.mdc` specifications.
2. **Load the canonical standards.** Open `ai-specs/specs/base-standards.mdc`; it links to every domain-specific standard you might need to combine for a task.
3. **Check your agent-specific notes.** Review `codex.md`, `CLAUDE.md`, or `GEMINI.md` for any agent nuances. These files defer to the `.mdc` standards but may call out role-specific context.
4. **Apply the standards during work.** Follow the linked `.mdc` documents while editing downstream codebases. The `.mdc` files contain the enforceable rules; the agent guides explain how to navigate them.

## Repository map
- `AGENTS.md`: Onboarding instructions for all agents and the required reading order.
- `codex.md`, `CLAUDE.md`, `GEMINI.md`: Per-agent primers that point to the required `.mdc` standards and capture any agent-only notes.
- `ai-specs/specs/`: Source of truth for the coding standards.
  - `base-standards.mdc`: Universal guidance and the navigation index for all other standards.
  - `backend-standards.mdc`: Node.js/TypeScript backend conventions and architecture patterns.
  - `frontend-standards.mdc`: React application standards for components, state, and testing.
  - `android-standards.mdc`: Android/Kotlin development guidance.
  - `ai-tools-standards.mdc`: Rules for designing and implementing AI tools or automations.
  - `documentation-standards.mdc`: Expectations for writing and maintaining documentation.
  - `api-spec.yml`: OpenAPI description referenced by the standards.
  - `development_guide.md`: Practical tips for applying the specs in active development.
  - `data-model.md`: Shared data model definitions cited by the other standards.
- `ai-specs/changes/`: Change histories and feature-level plans for the standards.

Use this repository as your single reference point before touching code elsewhere so that all changes align with the Polaralias specifications.
