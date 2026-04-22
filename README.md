# check-my-dev-in-web

Standalone home for the OpenCode `check-my-dev-in-web` skill.

## What this repository contains
- `SKILL.md` — canonical skill definition
- `scripts/` — smoke-check and verification helpers

## Current use
- Cheap web validation first
- Build, HTTP smoke, and asset checks
- webhint and Lighthouse gating
- Browser escalation only when needed

## Install
```bash
mkdir -p ~/.config/opencode/skills
rm -rf ~/.config/opencode/skills/check-my-dev-in-web
git clone https://github.com/SIN-Skills/check-my-dev-in-web ~/.config/opencode/skills/check-my-dev-in-web
```

## Goal
Verify the app cheaply before opening a full browser session.
