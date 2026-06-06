---
status: draft
owner: xgen-lab
language: zh-CN
source_language: zh-CN
last_reviewed: 2026-06-06
---

# RTOS 平台

## Purpose

沉淀 Zephyr、FreeRTOS 和机器人 MCU 平台需要的任务模型、驱动抽象、并发通信、配置管理和电源管理约定。

## Learning Path

1. 任务、线程、优先级和调度模型。
2. 队列、信号量、互斥锁、事件和消息传递。
3. 驱动抽象和设备模型。
4. 配置、构建和板级移植。
5. 电源管理和运行时设备状态。
6. 可测试的 RTOS 应用结构。

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| Task model | 决定实时行为和模块边界。 | `task-model.md` |
| IPC | 决定任务之间如何传递数据和事件。 | `ipc-patterns.md` |
| Driver abstraction | 支撑跨板复用和平台化。 | `driver-abstraction.md` |
| Zephyr platform | 是机器人 MCU 平台的主要方向。 | `zephyr-platform.md` |
| Power management | 支撑产品级固件行为。 | `power-management.md` |

## Recommended Order

1. 先定义任务模型和 IPC 约定。
2. 再整理驱动抽象和配置结构。
3. 最后连接 Zephyr 平台和电源管理。

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-zephyr-platform` | RTOS 文档的主要落地目标。 |
| `xgen-balancebot` | 使用 RTOS 平台承担控制板职责。 |

## Next Documents

- `task-model.md`
- `ipc-patterns.md`
- `driver-abstraction.md`
- `zephyr-platform.md`
- `power-management.md`

