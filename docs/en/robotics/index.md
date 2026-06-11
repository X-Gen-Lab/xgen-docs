---
status: draft
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# Robotics

## Purpose

Build BalanceBot-X-centered knowledge for control, sensor fusion, motion systems, safety boundaries, MCU-host-ROS2 integration, platform services, and whole-system validation.

## Learning Path

1. Robot system layers and responsibility boundaries.
2. Motors, encoders, IMUs, and basic sensors.
3. Control loops, PID, safety limits, and fault handling.
4. Sensor fusion, odometry, and state estimation.
5. MCU, Linux host, and ROS2 bridge integration.
6. Whole-system bring-up, testing, and field diagnostics.

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| System architecture | Prevents the robot project from becoming ad hoc integration. | `system-architecture.md` |
| Motor control | Determines whether the motion system is stable. | `motor-control.md` |
| Sensor fusion | Determines state-estimation quality. | `sensor-fusion.md` |
| Safety limits | Protects hardware and people during debugging. | `safety-limits.md` |
| Integration checklist | Keeps the firmware-to-ROS2 loop reproducible. | `integration-checklist.md` |

## Recommended Order

1. Define system architecture and safety boundaries first.
2. Organize motor control and sensor fusion.
3. Build the whole-system integration checklist.

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-balancebot` | Main BalanceBot-X robotics implementation project. |
| `xgen-zephyr-platform` | Provides the control-board firmware platform. |
| `xgen-ros2-lab` | Provides ROS2 integration and simulation capability. |

## Next Documents

- `system-architecture.md`
- `motor-control.md`
- `sensor-fusion.md`
- `safety-limits.md`
- `integration-checklist.md`
