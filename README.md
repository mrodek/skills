# skills

![Visibility](https://img.shields.io/badge/visibility-public-brightgreen)

A collection of Claude skills.

## How to quickly check if this repo is public

This repository is **public**. You can verify this at any time by:

1. **GitHub badge** — the green `visibility: public` badge above reflects the repo's visibility status.
2. **GitHub UI** — the repository header on [github.com/mrodek/skills](https://github.com/mrodek/skills) shows a `Public` label next to the repo name.
3. **GitHub API** — run the following command:
   ```bash
   curl -s https://api.github.com/repos/mrodek/skills | grep '"private"'
   # "private": false  →  the repo is public
   ```
4. **GitHub CLI** — if you have `gh` installed:
   ```bash
   gh repo view mrodek/skills --json visibility -q '.visibility'
   # PUBLIC
   ```

## Contents

| Skill | Description |
|-------|-------------|
| [idea-catalyst](./idea-catalyst/) | Finds cross-disciplinary inspiration for research problems using the Idea-Catalyst framework |
