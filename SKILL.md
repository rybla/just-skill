---
name: just-skill
description: Guide for using the Just command runner.
---

"Just" is a simple command runner.
Just is used through the shell command `just`.
This project uses Just for all common development commands.
All the Just commands for this project are defined in the `Justfile` at the project root.

## Common Usage

- List all commands: `just --list`
- Run a command: `just <command>`
- Read the `Justfile` at the root of the project to see the definitions of all commands

## Guidelines

- _All_ important development commands have already been included in the `Justfile`. You should _always_ prioritize using commands defined in the `Justfile` via `just <command>`.
