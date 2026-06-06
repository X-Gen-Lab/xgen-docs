---
status: draft
owner: xgen-lab
language: zh-CN
source_language: zh-CN
last_reviewed: 2026-06-06
---

# ROS2

## Purpose

沉淀 ROS2 节点、topic、service、action、launch、仿真、诊断和机器人软件架构的基础知识。

## Learning Path

1. 工作空间、package 和节点结构。
2. topic、service、action 和参数。
3. launch、配置和日志。
4. URDF、RViz、Gazebo 和仿真流程。
5. rosbag、diagnostics 和调试工具。
6. MCU bridge、Linux host 和 robot interface 边界。

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| ROS2 node | 是机器人软件的基本运行单元。 | `node-basics.md` |
| Topic and service | 定义数据流和请求响应边界。 | `topic-service-action.md` |
| Launch | 支撑可重复启动和系统组合。 | `launch-workflow.md` |
| Simulation | 支撑机器人行为验证。 | `simulation.md` |
| Diagnostics | 支撑运行时观测和问题定位。 | `diagnostics.md` |

## Recommended Order

1. 先建立 node、topic、service 和 action 基础。
2. 再整理 launch、配置和仿真。
3. 最后连接 MCU bridge 和机器人接口模型。

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-ros2-lab` | 承载 ROS2 实验和架构样例。 |
| `xgen-balancebot` | 提供真实机器人接口和集成目标。 |

## Next Documents

- `node-basics.md`
- `topic-service-action.md`
- `launch-workflow.md`
- `simulation.md`
- `diagnostics.md`

