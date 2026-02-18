# AGENTS.md

## Project Overview

This is a **GitHub profile README repository** (`vvelikodny/vvelikodny`).
It renders as the public profile page at https://github.com/vvelikodny.

There is no application source code, build system, or test suite.
The repository contains only static assets: a Markdown file and SVG icons.

## Repository Structure

```
.
├── AGENTS.md              # This file
├── README.md              # GitHub profile page (the main content)
├── icons/
│   ├── linkedin.svg       # LinkedIn social icon
│   ├── shield.svg         # Shield icon
│   ├── telegram.svg       # Telegram social icon
│   └── x.svg              # X (Twitter) social icon
└── .claude/
    └── settings.local.json  # Claude Code permissions
```

## Build / Lint / Test Commands

None. This repository has no build system, package manager, linter, formatter,
CI/CD pipeline, or test framework. Changes are verified visually on GitHub
after pushing.

## Editing Guidelines

### README.md

- The file is rendered by GitHub as the user's profile page.
- Keep it concise — profile READMEs should be scannable.
- Use GitHub-flavored Markdown.
- Inline HTML (`<img>` tags) is acceptable for custom icon sizing.
- Technology badges use [Shields.io](https://shields.io/) with `style=flat`.
  Follow the existing pattern:
  ```
  ![Label](https://img.shields.io/badge/Label-HexColor?style=flat&logo=logoname&logoColor=white)
  ```
- Social links use SVG icons from the `icons/` directory at `width="22px"`.
- Use `&nbsp;` for spacing between inline icon links.
- End the file with a trailing newline.

### SVG Icons (`icons/`)

- Keep SVGs minimal and compact (single-line body preferred).
- Use a `viewBox="0 0 24 24"` viewport (standard 24x24 icon grid).
- Include the `xmlns="http://www.w3.org/2000/svg"` attribute.
- Use inline `fill` attributes for color.
- End each file with a trailing newline.

### General

- All files should end with a trailing newline.
- Do not add application code to this repository — it is for the profile page only.
- Do not commit secrets, tokens, or credentials.

## Git Workflow

- Work directly on the `main` branch (single-contributor profile repo).
- Write clear, concise commit messages focused on what changed.
- Do not mention AI assistants in commit messages.
