# Copilot instructions — blackout

> Canonical standards live in the `dev-standards` repo on SOUNDWAVE/Gitea.
> Read by Copilot chat **and** inline suggestions.

## What this repo is

A **Home Assistant theme** (not a custom component) — installable via HACS as a
theme. Theme definitions live under `themes/`.

## Repo shape

- `themes/` — the theme YAML.
- `hacs.json` — HACS metadata (theme type).

## Conventions (theme, not component)

- This is a theme: **no `manifest.json`, no `custom_components/`, no `pytest`**.
  The component pipeline in `dev-standards` does NOT apply here.
- Keep theme keys consistent across any variants.

## Never

- Don't commit secrets.
- Don't restructure this into a component — it's a theme.
