---
status: draft
owner: xgen-lab
language: en
source_language: zh-CN
last_reviewed: 2026-06-06
---

# Embedded Systems

## Purpose

Build the MCU engineering foundation for X-Gen-Lab, including board bring-up, peripheral drivers, device protocols, OTA, low power, and verifiable firmware structure.

## Learning Path

1. MCU project structure and boot flow.
2. GPIO, I2C, SPI, UART, ADC, and PWM basics.
3. Logging, assertions, error handling, and diagnostic interfaces.
4. Device communication protocols and host debugging tools.
5. Bootloader, OTA, image validation, and rollback strategy.
6. Low-power modes, wake sources, and power measurement.

## Core Topics

| Topic | Why It Matters | First Document |
| --- | --- | --- |
| Board bring-up | Gets hardware into a debuggable state. | `board-bring-up.md` |
| Peripheral drivers | Forms the base for device capability. | `peripheral-drivers.md` |
| Device protocol | Defines the boundary between device, host, and robot systems. | `device-protocol.md` |
| OTA | Supports safe updates for real devices. | `ota-baseline.md` |
| Low power | Determines usability for battery devices and long-running systems. | `low-power.md` |

## Recommended Order

1. Write board bring-up and peripheral conventions first.
2. Add communication protocol, logging, and diagnostics conventions.
3. Fill in OTA and low-power design notes.

## Related Repositories

| Repository | Relationship |
| --- | --- |
| `xgen-link` | Reuses device communication and host-side contracts. |
| `xgen-ota` | Reuses update flow and image safety assumptions. |
| `xgen-zephyr-platform` | Inherits MCU structure and driver boundaries. |

## Next Documents

- `board-bring-up.md`
- `peripheral-drivers.md`
- `device-protocol.md`
- `ota-baseline.md`
- `low-power.md`

