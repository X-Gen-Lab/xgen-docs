---
status: draft
owner: xgen-lab
language: zh-CN
source_language: zh-CN
last_reviewed: 2026-06-06
---

# 嵌入式系统

## Purpose

建立 X-Gen-Lab 的 MCU 工程基础，包括板级启动、外设驱动、设备协议、OTA、低功耗和可验证的固件结构。

## Learning Path

1. MCU 工程结构与启动流程。
2. GPIO、I2C、SPI、UART、ADC、PWM 外设基础。
3. 日志、断言、错误处理和诊断接口。
4. 设备通信协议和 host 调试工具。
5. Bootloader、OTA、镜像校验和回滚策略。
6. 低功耗模式、唤醒源和功耗测量。

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| Board bring-up | 决定硬件能否进入可调试状态。 | `board-bring-up.md` |
| Peripheral drivers | 是所有设备能力的基础。 | `peripheral-drivers.md` |
| Device protocol | 定义设备、主机和机器人系统之间的边界。 | `device-protocol.md` |
| OTA | 支撑真实设备的安全升级。 | `ota-baseline.md` |
| Low power | 决定电池设备和长期运行系统的可用性。 | `low-power.md` |

## Recommended Order

1. 先写 board bring-up 和外设约定。
2. 再写通信协议、日志和诊断约定。
3. 最后补 OTA 和低功耗设计笔记。

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-link` | 复用设备通信协议和 host 侧契约。 |
| `xgen-ota` | 复用升级流程和镜像安全假设。 |
| `xgen-zephyr-platform` | 继承 MCU 工程结构和驱动边界。 |

## Next Documents

- `board-bring-up.md`
- `peripheral-drivers.md`
- `device-protocol.md`
- `ota-baseline.md`
- `low-power.md`

