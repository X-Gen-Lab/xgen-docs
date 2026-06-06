---
status: stable
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# X-Gen-Lab Docs

X-Gen-Lab Docs is the multilingual knowledge base for embedded systems, RTOS platforms, embedded Linux, ROS2, robotics, and embodied AI.

## Language Entry

| Language | Entry |
| --- | --- |
| Chinese Simplified | [docs/zh-CN/index.md](docs/zh-CN/index.md) |
| English | [docs/en/index.md](docs/en/index.md) |

## Repository Role

This repository records reusable engineering knowledge, learning paths, design notes, lab notes, and architecture decisions.

`xgen-roadmap` defines long-term direction and project sequencing. `xgen-docs` keeps the reusable knowledge that supports those projects.

## Documentation Rules

- Use pure Markdown in V1. Do not add a site generator unless a later ADR accepts it.
- Keep languages in separate directories.
- Keep language directories isomorphic: if a file exists in `docs/zh-CN/`, the matching path should exist in `docs/en/`.
- Use lowercase kebab-case file names.
- Use one H1 per Markdown file.
- Use relative links for internal documentation links.
- Put shared images and diagrams in `docs/_shared/`.
- Start new documents from the templates in `docs/templates/`.

## Add A Language

1. Copy `docs/en/` to a new BCP 47 language directory, such as `docs/ja/`.
2. Update the front matter `language` field in the copied files.
3. Keep file names and relative paths aligned with existing language directories.
4. Add the new language entry to this README.

## License

MIT License. See [LICENSE](LICENSE).

