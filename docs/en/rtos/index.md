---
status: draft
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# RTOS Platforms

## Purpose

Record task model, driver abstraction, concurrency, configuration, and power-management conventions for Zephyr, FreeRTOS, and robot MCU platforms.

## Learning Path

1. Tasks, threads, priorities, and scheduling model.
2. Queues, semaphores, mutexes, events, and message passing.
3. Driver abstraction and device model.
4. Configuration, build, and board porting.
5. Power management and runtime device states.
6. Testable RTOS application structure.

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| Task model | Defines real-time behavior and module boundaries. | `task-model.md` |
| IPC | Defines how tasks pass data and events. | `ipc-patterns.md` |
| Driver abstraction | Supports board reuse and platformization. | `driver-abstraction.md` |
| Zephyr platform | Main direction for the robot MCU platform. | `zephyr-platform.md` |
| Power management | Supports production firmware behavior. | `power-management.md` |

## Recommended Order

1. Define task model and IPC conventions first.
2. Organize driver abstraction and configuration structure.
3. Connect Zephyr platform work with power management.

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-zephyr-platform` | Main implementation target for RTOS documentation. |
| `xgen-balancebot` | Uses the RTOS platform for control-board responsibilities. |

## Next Documents

- `task-model.md`
- `ipc-patterns.md`
- `driver-abstraction.md`
- `zephyr-platform.md`
- `power-management.md`

