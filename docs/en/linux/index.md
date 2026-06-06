---
status: draft
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# Embedded Linux

## Purpose

Build practical knowledge for Linux drivers, device tree, kernel modules, system services, networking, logging, tracing, and performance diagnostics.

## Learning Path

1. Character devices, platform drivers, and kernel module basics.
2. Device tree, bindings, overlays, and board description.
3. Interrupts, DMA, memory, and user-space interfaces.
4. systemd services, boot flow, and logging.
5. Networking, serial, USB, and device diagnostics.
6. Tracing, profiling, and performance analysis.

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| Character driver | Entry point for understanding the Linux device model. | `character-driver.md` |
| Device tree | Connects hardware description with driver matching. | `device-tree.md` |
| System services | Keeps devices stable on Linux hosts. | `system-services.md` |
| Diagnostics | Determines whether field issues can be located. | `diagnostics.md` |
| Performance | Helps find latency, memory, and throughput bottlenecks. | `performance.md` |

## Recommended Order

1. Organize driver and device tree foundations first.
2. Add system service, logging, and network diagnostics.
3. Fill in tracing, profiling, and performance notes.

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-linux-lab` | Hosts Linux driver and system experiments. |
| `xgen-balancebot` | Uses a Linux host to connect MCU and ROS2. |

## Next Documents

- `character-driver.md`
- `device-tree.md`
- `system-services.md`
- `diagnostics.md`
- `performance.md`

