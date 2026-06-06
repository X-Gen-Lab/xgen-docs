---
status: draft
owner: xgen-lab
language: zh-CN
source_language: zh-CN
last_reviewed: 2026-06-06
---

# 具身智能

## Purpose

沉淀视觉、边缘 AI、agent、机器人命令接口、数据采集、评估和迭代闭环知识，并让 AI 能力连接真实机器人系统。

## Learning Path

1. 摄像头、传感器数据和机器人状态接口。
2. 视觉模型、目标检测、跟踪和延迟约束。
3. 边缘推理运行时和算力预算。
4. agent 与机器人命令边界。
5. 数据采集、回放、评估指标和迭代流程。
6. 安全约束和可观测性。

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| Vision pipeline | 是机器人感知能力的入口。 | `vision-pipeline.md` |
| Edge AI runtime | 决定模型能否在真实设备上运行。 | `edge-runtime.md` |
| Agent boundary | 防止 AI 控制绕过机器人安全层。 | `agent-boundary.md` |
| Dataset loop | 支撑可评估、可迭代的实验。 | `dataset-loop.md` |
| Evaluation | 避免只看演示效果而无法比较进步。 | `evaluation.md` |

## Recommended Order

1. 先定义视觉 pipeline 和硬件约束。
2. 再定义 agent 到机器人命令的安全边界。
3. 最后建立数据集和评估闭环。

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-balancebot` | 提供真实机器人平台。 |
| `xgen-ros2-lab` | 提供机器人软件接口和仿真入口。 |

## Next Documents

- `vision-pipeline.md`
- `edge-runtime.md`
- `agent-boundary.md`
- `dataset-loop.md`
- `evaluation.md`

