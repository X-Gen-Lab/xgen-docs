---
status: draft
owner: xgen-lab
language: zh-CN
source_language: zh-CN
last_reviewed: 2026-06-06
---

# X-Gen-Lab 知识库

这里是 X-Gen-Lab 的中文知识库入口，用于沉淀嵌入式、RTOS、嵌入式 Linux、ROS2、机器人和具身智能方向的可复用工程知识。

## 阅读路径

| 方向 | 入口 | 目标 |
| --- | --- | --- |
| 嵌入式系统 | [embedded/index.md](embedded/index.md) | 建立 MCU、板级启动、外设、协议、OTA 和低功耗基础 |
| RTOS 平台 | [rtos/index.md](rtos/index.md) | 建立任务模型、驱动抽象、并发和电源管理能力 |
| 嵌入式 Linux | [linux/index.md](linux/index.md) | 建立驱动、设备树、系统服务和诊断能力 |
| ROS2 | [ros2/index.md](ros2/index.md) | 建立机器人中间件、仿真和诊断基础 |
| 机器人 | [robotics/index.md](robotics/index.md) | 连接控制、传感器融合、系统集成和 BalanceBot |
| 具身智能 | [ai/index.md](ai/index.md) | 连接视觉、边缘 AI、agent 和评估闭环 |

## 文档类型

- 概念笔记：解释一个工程概念或设计原则。
- 操作指南：记录可复用的操作流程和验证方法。
- 实验记录：记录一次 bring-up、调试、验证或探索。
- 架构决策：记录影响长期维护方式的决定。
- 术语表：统一跨语言和跨仓库的工程词汇。

## 写作规则

- 新文档从 [../templates/](../templates/) 中选择模板。
- 中文和英文分文件维护，不在同一篇正文中重复混排。
- 内部链接使用相对路径。
- 每篇 Markdown 只保留一个 H1。
- 图片和通用图表放到 [../_shared/](../_shared/)。

## 术语表

中文术语表见 [glossary.md](glossary.md)。

