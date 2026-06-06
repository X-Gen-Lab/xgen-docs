---
status: stable
owner: xgen-lab
language: zh-CN
source_language: zh-CN
last_reviewed: 2026-06-06
---

# ADR-0001: 使用纯 Markdown 多语言目录

## Status

Accepted

## Context

`xgen-docs` 需要先成为一个轻量、可维护、可扩展的知识库。当前阶段的主要风险不是缺少站点能力，而是文档结构过早发散、语言混排和后续翻译路径不清晰。

## Decision

V1 使用纯 Markdown，不引入 MkDocs、Docusaurus 或其他站点生成器。中文和英文使用独立目录，路径保持同构。模板放在 `docs/templates/`，共享图片和图表放在 `docs/_shared/`。

## Consequences

这种方式初始成本低，适合快速沉淀内容，也方便后续迁移到站点生成器。维护成本主要来自语言目录同构检查和翻译同步检查，需要通过模板和 checklist 控制。

## Alternatives

| Alternative | Why Not |
| --- | --- |
| MkDocs | 当前还不需要导航、搜索和发布流水线。 |
| Docusaurus | 初始依赖和目录约束偏重。 |
| 单文件双语 | 后续维护和翻译同步容易混乱。 |

## Related Docs

- [../../../README.md](../../../README.md)
- [../../templates/translation-checklist.md](../../templates/translation-checklist.md)

