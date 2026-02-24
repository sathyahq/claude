# CLAUDE.md

This file provides guidance for AI assistants working with this repository.

## Repository Overview

A personal thinking tool for creating IBIS (Issue-Based Information System) dialogue maps in the browser. Single HTML file, inline CSS/JS, zero dependencies. Open `index.html` in Chrome and it works.

## Project Structure

```
.
├── CLAUDE.md          # AI assistant guidance (this file)
├── index.html         # Complete dialogue mapping tool (single file)
```

## Development Setup

1. Clone the repository
2. Open `index.html` in a browser (no build step or dependencies needed)

## Build & Run Commands

No build tools. Open `index.html` directly in a browser. Data persists in localStorage.

## Code Conventions

- Keep files focused and single-purpose.
- Prefer explicit over implicit patterns.
- Write descriptive variable and function names.
- Add comments only where intent is non-obvious; avoid restating code.

## Testing

- Place tests adjacent to or mirroring the source file structure.
- Name test files with a `.test.*` or `.spec.*` suffix.
- Aim for meaningful coverage of business logic and edge cases.

## Git Workflow

- Use clear, descriptive commit messages.
- Keep commits focused on a single logical change.
- Branch names should be descriptive of the feature or fix.

## Important Notes for AI Assistants

- **Read before editing.** Always read a file before proposing changes.
- **Minimal changes.** Only modify what is necessary to accomplish the task.
- **Don't over-engineer.** Avoid adding abstractions, utilities, or error handling beyond what is needed.
- **Run checks.** After making changes, run the project's lint, test, and build commands to verify correctness.
- **Update this file.** When adding significant tooling, structure, or conventions to the project, update CLAUDE.md to reflect the current state.
