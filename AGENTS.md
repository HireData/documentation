# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- **task** — the product's word for a unit of work in an automation. Write "task", not "step" or "action" (quote UI strings that say "step" unchanged).
- **HTTP Request** — the task's name, with that capitalisation. Reached via **Add → HTTP Request**.
- **Post Webhook** — the legacy task's exact label. Not "Post to Webhook" or "POST Webhook", both of which appear in source material.
- **task categories** — the nine groups tasks are added from: Add, Delay, Filter, Find, Loop, Message, Prompt, Split, Update.

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
