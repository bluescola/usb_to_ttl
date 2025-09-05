# USB 转 TTL 串口模块

## 项目概述
本项目是一个基于 Altium Designer 设计的 USB 转 TTL 串口模块的 PCB 工程。该模块用于实现 USB 与 TTL 电平的串口通信，适用于嵌入式开发、调试和通信场景。

## 文件结构
- `usb_to_ttl.PcbDoc`: PCB 设计文件
- `usb_to_ttl.SchDoc`: 原理图设计文件
- `usb_to_ttl.PrjPcb`: 项目文件
- `Project Outputs for usb_to_ttl/`: 项目输出文件目录
- `Project Logs for usb_to_ttl/`: 项目日志目录

## 功能特性
- 支持 USB 2.0 标准
- 提供 TTL 电平的串口通信接口
- 适用于常见的嵌入式开发板（如 Arduino、ESP8266、STM32 等）

## 使用说明
1. 使用 Altium Designer 打开 `usb_to_ttl.PrjPcb` 文件。
2. 查看原理图 (`usb_to_ttl.SchDoc`) 和 PCB 布局 (`usb_to_ttl.PcbDoc`)。
3. 生成 Gerber 文件或其他生产文件（位于 `Project Outputs for usb_to_ttl/` 目录）。

## 注意事项
- 确保使用兼容的 USB 转 TTL 芯片（如 CH340、CP2102 等）。
- 检查 PCB 布局是否符合电气安全规范。

## 维护与更新
如需修改设计，请更新原理图和 PCB 文件，并重新生成生产文件。