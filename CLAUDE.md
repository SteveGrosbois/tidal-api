# tidal-cli Development Guidelines

Auto-generated from all feature plans. Last updated: 2026-03-15

## Active Technologies
- Markdown (YAML frontmatter) — no code to compile + Claude Code skills system, `tidal-cli` CLI (Python 3.10+ / Typer) (002-cli-skills)
- N/A — skills are static files (002-cli-skills)

- Python 3.10+ + `tidalapi` (API Tidal), `typer` (framework CLI) (001-tidal-cli-wrapper)

## Project Structure

```text
tidal_cli.py      # CLI principal (point d'entrée unique)
skills/           # Skills Claude Code (fichiers Markdown)
specs/            # Spécifications de fonctionnalités
pyproject.toml
requirements.txt
```

## Commands

```bash
pytest            # Lancer les tests
ruff check .      # Vérifier le style
```

## Code Style

Python 3.10+: Follow standard conventions

## Recent Changes
- 002-cli-skills: Added Markdown (YAML frontmatter) — no code to compile + Claude Code skills system, `tidal-cli` CLI (Python 3.10+ / Typer)

- 001-tidal-cli-wrapper: Added Python 3.10+ + `tidalapi` (API Tidal), `typer` (framework CLI)

<!-- MANUAL ADDITIONS START -->
<!-- MANUAL ADDITIONS END -->
