---
status: draft
owner: xgen-lab
language: zh-CN
source_language: zh-CN
last_reviewed: 2026-06-06
---

# 嵌入式 Linux

## Purpose

建立 Linux 驱动、设备树、内核模块、系统服务、网络、日志、追踪和性能诊断的实践知识。

## Learning Path

1. 字符设备、platform driver 和内核模块基础。
2. 设备树、binding、overlay 和板级描述。
3. 中断、DMA、内存和用户态接口。
4. systemd 服务、启动流程和日志。
5. 网络、串口、USB 和设备诊断。
6. tracing、profiling 和性能分析。

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| Character driver | 是理解 Linux 设备模型的入口。 | `character-driver.md` |
| Device tree | 连接硬件描述和驱动匹配。 | `device-tree.md` |
| System services | 支撑设备在 Linux 主机上稳定运行。 | `system-services.md` |
| Diagnostics | 决定现场问题能否被定位。 | `diagnostics.md` |
| Performance | 帮助识别延迟、内存和吞吐瓶颈。 | `performance.md` |

## Recommended Order

1. 先整理驱动和设备树基础。
2. 再整理系统服务、日志和网络诊断。
3. 最后补 tracing、profiling 和性能笔记。

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-linux-lab` | 承载 Linux 驱动和系统实验。 |
| `xgen-balancebot` | 使用 Linux 主机连接 MCU 和 ROS2。 |

## Next Documents

- `character-driver.md`
- `device-tree.md`
- `system-services.md`
- `diagnostics.md`
- `performance.md`

