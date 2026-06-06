---
status: stable
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# ADR-0001: Use Plain Markdown Multilingual Directories

## Status

Accepted

## Context

`xgen-docs` needs to become a lightweight, maintainable, and extensible knowledge base first. The main early risk is not missing site features, but scattered structure, mixed-language prose, and unclear translation paths.

## Decision

V1 uses pure Markdown without MkDocs, Docusaurus, or another site generator. Chinese and English use separate directories with isomorphic paths. Templates live in `docs/templates/`, and shared images and diagrams live in `docs/_shared/`.

## Consequences

This keeps the initial cost low, supports fast knowledge capture, and leaves room for a future site generator migration. The main maintenance cost is keeping language directories aligned and translations synchronized, which is controlled through templates and checklists.

## Alternatives

| Alternative | Why Not |
| --- | --- |
| MkDocs | Navigation, search, and publishing are not needed yet. |
| Docusaurus | Initial dependencies and structure are heavier than needed. |
| Single-file bilingual docs | Long-term maintenance and translation sync become messy. |

## Related Docs

- [../../../README.md](../../../README.md)
- [../../templates/translation-checklist.md](../../templates/translation-checklist.md)

