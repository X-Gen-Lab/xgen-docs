---
status: draft
owner: xgen-lab
language: zh-CN
source_language: zh-CN
last_reviewed: 2026-06-06
---

# 机器人

## Purpose

围绕 BalanceBot-X 建立控制、传感器融合、运动系统、安全边界、MCU-host-ROS2 集成、平台服务和整机验证知识。

## Learning Path

1. 机器人系统分层和职责边界。
2. 电机、编码器、IMU 和基础传感器。
3. 控制环、PID、安全限幅和故障处理。
4. 传感器融合、里程计和状态估计。
5. MCU、Linux host 和 ROS2 bridge 集成。
6. 整机 bring-up、测试和现场诊断。

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| System architecture | 防止机器人项目变成临时拼接。 | `system-architecture.md` |
| Motor control | 决定运动系统是否稳定。 | `motor-control.md` |
| Sensor fusion | 决定状态估计质量。 | `sensor-fusion.md` |
| Safety limits | 保护硬件和调试人员。 | `safety-limits.md` |
| Integration checklist | 保证从固件到 ROS2 的闭环可复现。 | `integration-checklist.md` |

## Recommended Order

1. 先定义系统架构和安全边界。
2. 再整理电机控制和传感器融合。
3. 最后形成整机集成 checklist。

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-balancebot` | BalanceBot-X 机器人主线落地项目。 |
| `xgen-zephyr-platform` | 提供控制板固件平台。 |
| `xgen-ros2-lab` | 提供 ROS2 集成和仿真能力。 |

## Next Documents

- `system-architecture.md`
- `motor-control.md`
- `sensor-fusion.md`
- `safety-limits.md`
- `integration-checklist.md`
