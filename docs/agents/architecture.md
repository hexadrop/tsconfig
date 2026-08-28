# Architecture

## Public surface

This package publishes a single TypeScript configuration file. The public surface is `tsconfig.json`.

| Surface      | Location       | Responsibility                                                                |
|--------------|----------------|--------------------------------------------------------------------------------|
| Base TSConfig | `tsconfig.json` | Declares Node + ESM + strictest TypeScript options reused by hexadrop projects. |

## Build output

There is no build step. The published tarball exposes `tsconfig.json`, `README.md`, `LICENSE`, and `CHANGELOG.md` exactly as checked in.
