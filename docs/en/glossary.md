---
status: draft
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# Glossary

## Terms

| Term | Translation | Meaning | Preferred Usage | Avoid |
| --- | --- | --- | --- | --- |
| firmware | firmware | Software running on an MCU or embedded device. | Use for device-side software. | Do not use for normal PC applications. |
| bring-up | board bring-up | Work that makes new hardware bootable, flashable, and debuggable. | Use for new board validation. | Do not reduce it to boot only. |
| driver | driver | Code that controls a hardware peripheral or operating-system device. | Distinguish MCU drivers from Linux drivers. | Do not use for every module. |
| protocol | protocol | Rules for data exchange between devices, hosts, or services. | Use for frames, commands, and payload rules. | Do not mix with API casually. |
| OTA | OTA update | Updating firmware or software images over a communication link. | Keep the OTA abbreviation. | Do not omit validation and rollback semantics. |
| RTOS | RTOS | Operating system for deterministic scheduling and embedded task management. | Keep the RTOS abbreviation. | Do not equate it with general Linux. |
| task | task | Execution unit in an RTOS. | Use for FreeRTOS-like contexts. | Prefer thread in Zephyr-specific text. |
| IPC | IPC | Mechanism for passing data or events between execution units. | Can apply to tasks, threads, or processes. | Do not limit it only to processes. |
| device tree | device tree | Linux data structure for describing hardware. | Keep the English term and explain it. | Do not discuss it without bindings. |
| kernel module | kernel module | Loadable functional module for the Linux kernel. | Use for drivers and kernel extensions. | Do not mix with user-space services. |
| ROS2 node | ROS2 node | Basic runtime unit in a ROS2 system. | Include ROS2 on first use. | Do not drop ROS2 when ambiguous. |
| topic | topic | Publish-subscribe data channel in ROS2. | Use for data streams. | Do not use for request-response semantics. |
| service | service | Request-response interface in ROS2. | Use for synchronous request-response. | Do not use for continuous data streams. |
| action | action | Long-running ROS2 interface with feedback and cancellation. | Use for navigation-like tasks. | Do not mix with service. |
| simulation | simulation | Software environment that models a robot, sensors, or world. | Use with Gazebo and RViz workflows. | Do not equate it with unit testing. |
| control loop | control loop | Periodic loop that reads state, computes control, and outputs commands. | Use for motor and robot control. | Do not use for generic business loops. |
| sensor fusion | sensor fusion | Combining multiple sensors to estimate a more reliable state. | Use for IMU, encoder, and odometry combinations. | Do not equate it with simple data concatenation. |
| edge AI | edge AI | AI inference running on local devices or edge compute platforms. | Use for Jetson, NPU, and device-side inference. | Do not use for cloud AI. |
| agent | agent | Software entity that can plan or act using goals, tools, and context. | Use for AI control and tool-use boundaries. | Do not use for ordinary scripts. |
| embodied AI | embodied AI | AI connected to physical systems, perception, and action loops. | Use for robotics and real-world interaction. | Do not equate it with chatbots. |

