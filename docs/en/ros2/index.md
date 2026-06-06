---
status: draft
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# ROS2

## Purpose

Record foundations for ROS2 nodes, topics, services, actions, launch, simulation, diagnostics, and robot software architecture.

## Learning Path

1. Workspace, package, and node structure.
2. Topics, services, actions, and parameters.
3. Launch, configuration, and logging.
4. URDF, RViz, Gazebo, and simulation workflow.
5. rosbag, diagnostics, and debugging tools.
6. MCU bridge, Linux host, and robot interface boundaries.

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| ROS2 node | Basic runtime unit of robot software. | `node-basics.md` |
| Topic and service | Defines data flow and request-response boundaries. | `topic-service-action.md` |
| Launch | Supports repeatable startup and system composition. | `launch-workflow.md` |
| Simulation | Supports robot behavior validation. | `simulation.md` |
| Diagnostics | Supports runtime observation and issue diagnosis. | `diagnostics.md` |

## Recommended Order

1. Build node, topic, service, and action foundations first.
2. Organize launch, configuration, and simulation.
3. Connect MCU bridge work with the robot interface model.

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-ros2-lab` | Hosts ROS2 experiments and architecture examples. |
| `xgen-balancebot` | Provides the real robot interface and integration target. |

## Next Documents

- `node-basics.md`
- `topic-service-action.md`
- `launch-workflow.md`
- `simulation.md`
- `diagnostics.md`

