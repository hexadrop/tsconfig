# Development and testing

This repository publishes a single `tsconfig.json`. There are no tests, lint, or typecheck scripts.

## Commands

| Task                  | Command                                  |
|-----------------------|------------------------------------------|
| Install dependencies  | `bun install`                            |
| Changeset             | `bun changeset add`                      |
| Commitlint            | `bun run commitlint`                     |

## Before committing

Husky hooks run `bun run commitlint ${1}` on the commit message. There is no pre-push lint/test/typecheck in this repository.
