# cursor.md

Instructions for Cursor when working in this project.

## Project

- Name: `test_project`
- Location: Laragon web root (`e:\laragon\www\ai projects\test_project`)
- Status: new / empty workspace — establish structure and conventions before adding features

## How to work here

- Prefer small, focused changes over large rewrites
- Match existing style once files exist; do not introduce a second stack or pattern without a reason
- Do not add dependencies, config, or docs unless they are needed for the current task
- Do not commit unless the user asks

## Stack (update as the project grows)

- Runtime: not chosen yet
- Package manager: not chosen yet
- Database: not chosen yet

When adding the first real code, record the stack here and keep it accurate.

## Conventions

- Use clear, descriptive names
- Keep business logic out of UI glue when possible
- Handle errors explicitly; do not swallow exceptions
- Prefer existing files over creating new ones when a change belongs there

## Verification

- After UI or app behavior changes, verify in the browser (or the closest substitute if the app is not running)
- After backend or script changes, run the relevant command or test before considering the work done
- Report what was verified and what could not be verified

## Do not

- Commit secrets (`.env`, credentials, keys)
- Change git config or force-push
- Invent APIs, folders, or architecture that the current task does not need
