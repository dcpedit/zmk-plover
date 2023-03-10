---
title: Introduction to ZMK
sidebar_label: Introduction
slug: /
---

ZMK Firmware is an open source (MIT) keyboard
firmware built on the [Zephyrâ¢ Project](https://zephyrproject.org/) Real Time Operating System (RTOS). ZMK's goal is to provide a modern, wireless, and powerful firmware free of licensing issues.

## Features

ZMK is currently missing some features found in other popular firmware. This table compares the features supported by ZMK, BlueMicro and QMK:

| Legend: | â Supported | ð§ Under Development | ð¡ Planned |
| :------ | :----------- | :------------------- | :--------- |

| **Feature**                                                                                                                        | ZMK | BlueMicro | QMK |
| ---------------------------------------------------------------------------------------------------------------------------------- | :-: | :-------: | :-: |
| Low Latency BLE Support                                                                                                            | â  |    â     |     |
| Multi-Device BLE Support                                                                                                           | â  |           |     |
| [USB Connectivity](behaviors/outputs.md)                                                                                           | â  |    â     | â  |
| User Configuration Repositories                                                                                                    | â  |           |     |
| Split Keyboard Support                                                                                                             | â  |    â     | â  |
| [Keymaps and Layers](behaviors/layers.md)                                                                                          | â  |    â     | â  |
| [Hold-Tap](behaviors/hold-tap.md) (which includes [Mod-Tap](behaviors/mod-tap.md) and [Layer-Tap](behaviors/layers.md/#layer-tap)) | â  |    â     | â  |
| [Tap-Dance](behaviors/tap-dance.md)                                                                                                | â  |  â[^3]   | â  |
| [Keyboard Codes](codes/index.mdx#keyboard)                                                                                         | â  |    â     | â  |
| [Media](codes/index.mdx#media-controls) & [Consumer](codes/index.mdx#consumer-controls) Codes                                      | â  |    â     | â  |
| [Encoders](features/encoders.md)[^1]                                                                                               | â  |    â     | â  |
| [Display Support](features/displays.md)[^2]                                                                                        | ð§  |    ð§     | â  |
| [RGB Underglow](features/underglow.md)                                                                                             | â  |    â     | â  |
| [Backlight](features/backlight.md)                                                                                                 | â  |    â     | â  |
| One Shot Keys                                                                                                                      | â  |    â     | â  |
| [Combo Keys](features/combos.md)                                                                                                   | â  |           | â  |
| [Macros](behaviors/macros.md)                                                                                                      | â  |    â     | â  |
| [Stenography](features/stenography.md)                                                                                                   | â  |           | â  |
| Mouse Keys                                                                                                                         | ð§  |    â     | â  |
| Low Active Power Usage                                                                                                             | â  |           |     |
| Low Power Sleep States                                                                                                             | â  |    â     |     |
| [Low Power Mode (VCC Shutoff)](behaviors/power.md)                                                                                 | â  |    â     |     |
| Battery Reporting                                                                                                                  | â  |    â     |     |
| Shell over BLE                                                                                                                     | ð¡  |           |     |
| Realtime Keymap Updating                                                                                                           | ð¡  |           | â  |
| AVR/8 Bit                                                                                                                          |     |           | â  |
| [Wide Range of ARM Chips Supported](https://docs.zephyrproject.org/latest/boards/index.html)                                       | â  |           |     |

[^3]: Tap-Dances are limited to single and double-tap on BlueMicro
[^2]: Encoders are not currently supported on peripheral side splits.
[^1]: OLEDs are currently proof of concept in ZMK.

## Code Of Conduct

Please note that this project is released with a
[Contributor Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/).
By participating in this project you agree to abide by its terms.
