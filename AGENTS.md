# Documentation project instructions

## Agent guidance

- Treat `AGENTS.md` as the canonical agent contract; keep `CLAUDE.md` as a relative symlink.
- Keep repository-owned skills in `.agents/skills/`; add relative compatibility links only for clients that need them.
- When manifests or configuration expose a fact, omit it from agent guidance unless it prevents a known mistake.
- When an observed failure, missing decision, or direct correction warrants guidance, add or replace the narrowest applicable rule.
- When a skill change alters behavior, add or update a realistic behavioral eval.

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
