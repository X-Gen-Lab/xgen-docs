---
status: stable
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# Translation Checklist

Use this checklist before marking a translated document as `reviewed` or `stable`.

## Structure

- The translated file path matches the source language path.
- The translated document has exactly one H1.
- H2 and H3 sections match the source document unless an ADR allows otherwise.
- The front matter `language` field matches the directory.
- The front matter `source_language` field points to the original language.

## Content

- Technical meaning is preserved.
- Terminology follows the language glossary.
- Code blocks, commands, paths, and identifiers are not mistranslated.
- Examples still work in the target language context.

## Links And Assets

- Internal links are relative paths.
- Shared images point to `docs/_shared/`.
- Localized screenshots live in the target language directory.
- No broken links remain.

## Review

- The document status is updated only after review.
- `last_reviewed` uses `YYYY-MM-DD`.
- Any known translation gaps are listed in the document.

