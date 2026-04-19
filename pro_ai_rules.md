# rules.md — Coding Prompt Standards for GitHub Projects

Use this file to guide AI-assisted coding inside this repository. These rules help produce maintainable, secure, production-quality code.

---

## Package installing and code modification

- Ask me during the agent mode before installing the new package.
- Ask me during the agent mode before choose new modules rather sassume or imagine while agent getting confused to pick.

---

## Core Principles

- Write clean, readable, modular code.
- Prefer simplicity over cleverness.
- Optimize for maintainability first, performance second.
- Follow existing project architecture and conventions.
- Do not introduce unnecessary dependencies.
- Keep functions small and single-purpose.
- Use descriptive names for variables, functions, classes, and files.
- Avoid duplication (DRY), but not at the cost of clarity.
- Avoid emojis usage in the codebase.

---

## Before Writing Code

- Read surrounding files and understand the current pattern.
- Match the repository’s style and structure.
- Reuse existing utilities before creating new ones.
- Confirm assumptions from configs, types, schemas, or docs.
- If requirements are unclear, ask clarifying questions.

---

## Code Style

- Use consistent formatting.
- Follow linter and formatter rules.
- Prefer early returns over nested conditions.
- Avoid magic numbers and hardcoded strings.
- Use constants/enums where appropriate.
- Keep line lengths reasonable.
- Remove dead code and commented-out code.

---

## File Organization

- One clear responsibility per file.
- Group related logic together.
- Separate business logic from UI/presentation.
- Keep reusable helpers in utility modules.
- Use index/export files only when they improve clarity.

---

## Functions & Methods

- Keep functions short and focused.
- Prefer pure functions where possible.
- Explicit inputs and outputs.
- Avoid side effects unless necessary.
- Validate inputs at boundaries.
- Return predictable values.

---

## Error Handling

- Fail loudly in development, gracefully in production.
- Use meaningful error messages.
- Never swallow exceptions silently.
- Add context when rethrowing errors.
- Handle async failures properly.
