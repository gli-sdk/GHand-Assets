# GHand Assets

[English](README.md)

本仓库包含 GHand 灵巧手的公开描述资源包。该资源包支持仿真、可视化、算法验证与机器人开发。
版本发布提供 URDF、MJCF 和 USD 机器人模型，以及对应的几何网格文件。

## 包含内容

| 系统 | 说明 | 格式 |
|---|---|---|
| `ghand5_system` | GHand 5 左/右灵巧手 | URDF、MJCF、USD |
| `ghand_lite1_system` | GHand Lite 1 左/右灵巧手 | URDF、MJCF、USD |

## 视觉目录

| 预览 | 描述文件 | 手部型号 | 配置 | 左右 |
|---|---|---|---|---|
| <img src="docs/images/ghand5_left_preview.png" alt="GHand 5 左手预览" width="180"> | URDF: ghand5_system/urdf/ghand5_left.urdf<br>MJCF: ghand5_system/mjcf/ghand5_left.mjcf<br>USD: ghand5_system/usd/ghand5_left.usd | GHand 5 | 单手 | 左 |
| <img src="docs/images/ghand5_right_preview.png" alt="GHand 5 右手预览" width="180"> | URDF: ghand5_system/urdf/ghand5_right.urdf<br>MJCF: ghand5_system/mjcf/ghand5_right.mjcf<br>USD: ghand5_system/usd/ghand5_right.usd | GHand 5 | 单手 | 右 |

## 使用模型

URDF 文件可由 ROS、RViz、Pinocchio 及其他兼容 URDF 的解析器加载。

