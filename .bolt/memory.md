# Project memory

## Product intent & audience

- Project is Composer, the dependency manager for PHP projects.
- Target users are PHP developers managing project dependencies via CLI.
- Current version in development: 2.11.

## Brand personality & voice

- Technical, developer-oriented; communication is direct and factual.

## Visual design & UX direction

- No web UI, database, or visual interface — this is a CLI tool.
- Entry point lives in `bin/`; core code under `Composer/` source folder.
- No design system, components, or responsive considerations apply.

## Decisions, constraints & rationale

- Language/toolchain: PHP.
- Architecture: command-line application, not a web app.
- No `.bolt/prompt` authoritative instructions present.

## Open questions & assumptions

- User intent unclear — they may have expected a web app rather than a CLI tool.
- Awaiting clarification on whether they want to build something new or work within Composer itself.