---
status: draft
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# Embodied AI

## Purpose

Record knowledge for vision, edge AI, agents, robot command interfaces, data capture, evaluation, and iteration loops so AI capability can connect to real robot systems.

## Learning Path

1. Camera, sensor data, and robot state interfaces.
2. Vision models, object detection, tracking, and latency constraints.
3. Edge inference runtime and compute budgets.
4. Agent and robot command boundaries.
5. Data capture, replay, metrics, and iteration workflow.
6. Safety constraints and observability.

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| Vision pipeline | Entry point for robot perception. | `vision-pipeline.md` |
| Edge AI runtime | Determines whether models can run on real devices. | `edge-runtime.md` |
| Agent boundary | Prevents AI control from bypassing robot safety layers. | `agent-boundary.md` |
| Dataset loop | Supports measurable and repeatable experiments. | `dataset-loop.md` |
| Evaluation | Avoids relying only on demo impressions. | `evaluation.md` |

## Recommended Order

1. Define the vision pipeline and hardware constraints first.
2. Define safe boundaries from agents to robot commands.
3. Build dataset and evaluation loops.

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-balancebot` | Provides the real robot platform. |
| `xgen-ros2-lab` | Provides robot software interfaces and simulation entry points. |

## Next Documents

- `vision-pipeline.md`
- `edge-runtime.md`
- `agent-boundary.md`
- `dataset-loop.md`
- `evaluation.md`

