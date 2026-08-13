# Project Context — testering-1234

The Project Context entry-point every Worker reads before writing code. It records
what this repository actually is today; keep it truthful and update it as the repo grows.

## What this project is

`testering-1234` is a newly-initialized repository managed with Fredrin. At present it
contains only a `README.md` (holding the project name) — no application source, tests,
or build tooling have been added yet. This file is the first Project Context artifact.

## Stack

None established yet. There are no language manifests in the repo (`package.json`,
`Cargo.toml`, `go.mod`, `pyproject.toml`, etc.), so no language, framework, or package
manager is committed at this time. Update this section once a stack is chosen.

## Layout

- `README.md` — the only tracked file; currently just the project name.
- `.fredrin/` — Fredrin tooling and worker context (`FREDRIN.md`, the `fredrin` CLI,
  hooks). Git-ignored operational files, not part of the application.
- `.claude/` — Claude Code local settings. Not part of the application.

## Commands

None defined yet. There is no manifest declaring build, test, lint, or dev scripts,
so none are listed here — add the real commands once a manifest exists rather than
guessing them.
