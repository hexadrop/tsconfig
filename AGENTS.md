# @hexadrop/tsconfig agent guide

Single-file published TypeScript configuration reused by hexadrop projects.

- **Package manager:** Bun (`bun`)
- **Build:** no build — published `tsconfig.json` as-is
- **Test / Lint / Typecheck:** not applicable (no source code beyond the JSON)

## Task guides

- [Architecture](docs/agents/architecture.md) — public surface and publish contents.
- [Conventions](docs/agents/conventions.md) — package management conventions.
- [Development and testing](docs/agents/development.md) — install, changesets, commitlint.
- [Release process](docs/agents/release-process.md) — changesets, beta snapshots, stable releases, and hotfixes.
- [Pull requests](docs/agents/pull-requests.md) — approved-issue, labeling, checklist, and merge requirements.
- [Branches and commits](docs/agents/branches-and-commits.md) — GitFlow branches, naming, conventions, and hooks.
