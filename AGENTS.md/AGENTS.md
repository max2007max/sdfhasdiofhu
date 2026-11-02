# Repository Guidelines

## Project Structure & Module Organization

This checkout currently contains no application source, tests, or assets. Add implementation code under a clearly named directory such as `src/`, tests under `tests/`, and static resources under `assets/`. Keep related modules together and update this guide when the layout is established.

## Build, Test, and Development Commands

No build system or package metadata is present yet, so there are no repository-specific commands to run. When introducing a toolchain, document its standard setup and commands here (for example, `npm install`, `npm run build`, and `npm test`, if the project uses Node.js).

## Coding Style & Naming Conventions

Follow the formatter and lint rules adopted by the project once configured. Use descriptive names that match the language conventions, keep modules focused, and avoid adding dependencies without a clear need. Include formatting or lint commands in this section when available.

## Testing Guidelines

There is no test framework or test suite in the current checkout. Add tests alongside the chosen framework’s conventions, use descriptive test names, and document the command contributors should run before submitting changes.

## Commit & Pull Request Guidelines

No Git history is available here to establish existing commit conventions. Use short, imperative commit subjects (for example, `Add input validation`). Pull requests should describe the change, note any relevant issue, and include screenshots for user-facing visual changes.

## Security & Configuration

Keep credentials and machine-specific settings out of version control. Provide safe example configuration when needed, and document required environment variables without including secret values.

## User Preferences for Future Projects

- Communicate in Russian by default. Write project documentation in the project's established language when clear.
- Work independently on clear tasks; ask the user to resolve meaningful ambiguities before making consequential choices.
- Run checks that are relevant to the requested change. Do not run unrelated test suites or checks.
- Follow existing project conventions and suggest improvements when they would help; explain meaningful tradeoffs.
- Ask before creating Git commits.
- Match the level of explanation to the task's complexity.
- Ask before choosing a technology stack when the project does not already establish one.
- Preserve the existing interface design unless the user asks for a redesign.
- Choose dependencies freely when they provide clear value; explain notable additions.
- If you find unrelated or adjacent issues, describe them and ask before expanding the task to fix them.
- Send brief progress updates while working on longer tasks.
- No further preferences have been provided yet.
