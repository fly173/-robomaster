# RoboMaster 学习资源整合 🤖

> 我将把我在长空御风学到的一切开源，同时整合优质的 RoboMaster 学习资料，包括机械、电控、视觉等方向。

欢迎 Star ⭐ 和 PR！如果你也有好的资源，欢迎提交 Issue 或 Pull Request。

---

## 📚 目录

- [官方资源](#官方资源)
- [机械设计](#机械设计)
- [电控学习](#电控学习)
- [视觉学习](#视觉学习)
- [优秀开源战队](#优秀开源战队)
- [如何贡献](#如何贡献)

---

## 官方资源

| 资源 | 链接 |
|------|------|
| RoboMaster 官网 | https://www.robomaster.com |
| RoboMaster 规则手册 | https://www.robomaster.com/zh-CN/resource/pages/1016 |
| RoboMaster 开发者平台 | https://robomaster-dev.readthedocs.io |
| DJI RoboMaster GitHub | https://github.com/RoboMasterDev |
| RoboMaster 开发板资料（C型/A型） | https://github.com/RoboMasterDev/RoboMaster-Development-Board-C-Examples |
| RoboMaster 电机驱动文档 | https://www.robomaster.com/zh-CN/products/components/general/M3508 |
| RoboMaster 裁判系统协议 | https://www.robomaster.com/zh-CN/resource/pages/1016 |

---

## 机械设计

### 学习资料

| 资源 | 说明 |
|------|------|
| [SolidWorks 官方教程](https://www.solidworks.com/sw/resources/solidworks-tutorials.htm) | 主流机械建模软件教程 |
| [Autodesk Fusion 360 教程](https://www.autodesk.com/products/fusion-360/learn-training-tutorials) | 适合入门的 3D 建模工具 |
| [GrabCAD 机械模型库](https://grabcad.com/library) | 大量开源机械模型，可搜索 RoboMaster |
| [麦克纳姆轮原理介绍](https://zhuanlan.zhihu.com/p/75227243) | 全向底盘机械设计关键知识 |
| [碳纤维加工工艺介绍](https://zhuanlan.zhihu.com/p/397019032) | RM 机器人常用材料工艺 |

### 优秀机械开源设计

| 来源 | 机器人类型 | 链接 |
|------|----------|------|
| DJI RoboMaster 官方 | 步兵/英雄/哨兵 | https://www.robomaster.com/zh-CN/resource/pages/1016 |
| 哈尔滨工程大学创梦之翼战队 | 多种机器人 STEP 文件 | https://github.com/creamsensation |
| 上海交通大学 SJTU 战队 | 步兵/英雄底盘 | https://github.com/SJTU-RoboMaster-Team |
| 华中科技大学 HUST 战队 | 发射机构/云台 | https://github.com/HUSTLY2024-LEARNER |
| GrabCAD RoboMaster 合集 | 多种机器人 | https://grabcad.com/library/tag/robomaster |

### 机械设计要点

- **底盘设计**：全向轮底盘（麦克纳姆轮）/ 舵轮底盘 / 差速底盘
- **云台设计**：两轴云台（Pitch + Yaw）/ 平衡重心设计
- **发射机构**：摩擦轮转速匹配 / 拨弹盘设计 / 弹道一致性
- **装甲模块**：装甲板固定方式 / 防撞设计

---

## 电控学习

### 入门基础

| 资源 | 说明 |
|------|------|
| [STM32 入门教程（野火）](https://doc.embedfire.com/mcu/stm32/f103/hal_generalzh/latest/index.html) | 国内最全 STM32 HAL 库教程 |
| [STM32CubeMX 使用指南](https://wiki.stmicroelectronics.cn/stm32mcu/wiki/STM32StepByStep:STM32CubeMX_configuration) | 官方代码生成工具 |
| [FreeRTOS 官方文档](https://www.freertos.org/Documentation/RTOS_book.html) | RM 电控必学实时操作系统 |
| [FreeRTOS 中文教程](https://www.freertos.org/zh-cn-cmn-s/Documentation/01-FreeRTOS-quick-start/01-Beginners-guide/00-Overview) | FreeRTOS 中文学习资料 |
| [CAN 总线原理与应用](https://zhuanlan.zhihu.com/p/32221803) | RM 电机通信必备知识 |
| [PID 控制算法详解](https://zhuanlan.zhihu.com/p/39573490) | 运动控制核心算法 |

### 进阶学习

| 资源 | 说明 |
|------|------|
| [卡尔曼滤波原理](https://zhuanlan.zhihu.com/p/45238681) | 传感器数据融合 |
| [IMU 姿态解算](https://zhuanlan.zhihu.com/p/338584485) | 云台角度控制关键 |
| [电机 FOC 控制原理](https://zhuanlan.zhihu.com/p/147659820) | 高性能电机控制 |
| [麦克纳姆轮运动学解算](https://zhuanlan.zhihu.com/p/75227243) | 全向底盘运动控制 |
| [裁判系统串口通信协议](https://www.robomaster.com/zh-CN/resource/pages/1016) | 与裁判系统交互 |

### 开源电控代码

| 来源 | 说明 | 链接 |
|------|------|------|
| DJI RoboMaster 开发板示例 | 官方 C 型开发板例程 | https://github.com/RoboMasterDev/RoboMaster-Development-Board-C-Examples |
| RM2024 Omni-Infantry | 全向步兵开源框架 | https://github.com/Cccccpg/RM2024 |
| RoboRTS-Firmware | 官方机器人固件 | https://github.com/RoboMasterDev/RoboRTS-Firmware |
| 上交 RM 嵌入式框架 | 成熟 RM 电控框架 | https://github.com/SJTU-RoboMaster-Team/rm-controls |
| HAL_Module 开源库 | 通用 STM32 HAL 模块 | https://github.com/HUSTLY2024-LEARNER |

### 电控开发工具

- **开发板**：RoboMaster 开发板 C 型 / A 型
- **调试工具**：Vofa+（串口波形显示）/ STM32CubeMonitor / J-Link / ST-Link
- **IDE**：Keil MDK / STM32CubeIDE / CLion + OpenOCD
- **通信协议**：CAN 总线（电机）/ UART（裁判系统、上下位机通信）/ SPI（IMU）/ I2C

---

## 视觉学习

### 基础学习

| 资源 | 说明 |
|------|------|
| [OpenCV 官方文档](https://docs.opencv.org/4.x/) | 计算机视觉基础库 |
| [OpenCV 中文教程](https://www.bookstack.cn/read/opencv-doc-zh-4.0.0/README.md) | OpenCV 中文学习资料 |
| [Python OpenCV 入门](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html) | Python 视觉入门教程 |
| [深度学习入门（李沐）](https://zh-v2.d2l.ai/) | 深度学习经典教材（中文） |
| [YOLO 系列论文解读](https://zhuanlan.zhihu.com/p/136382095) | 目标检测核心算法 |

### 进阶视觉

| 资源 | 说明 |
|------|------|
| [相机标定原理](https://zhuanlan.zhihu.com/p/94244568) | 视觉定位基础 |
| [PnP 位姿估计](https://zhuanlan.zhihu.com/p/399140251) | 装甲板位姿解算 |
| [扩展卡尔曼滤波（EKF）](https://zhuanlan.zhihu.com/p/63641724) | 目标状态预测 |
| [弹道补偿模型](https://zhuanlan.zhihu.com/p/386939355) | 自动瞄准补偿算法 |
| [ROS2 入门教程](https://docs.ros.org/en/humble/Tutorials.html) | 机器人操作系统（视觉上位机常用） |

### 开源视觉代码

| 来源 | 说明 | 链接 |
|------|------|------|
| rm_vision（ROS2 视觉框架） | 目前最流行的 RM 开源视觉方案 | https://github.com/chenjunnn/rm_vision |
| auto_aim_algorithms | 自动瞄准核心算法 | https://github.com/chenjunnn/rm_auto_aim |
| OpenRM | 多战队合作视觉框架 | https://github.com/Alliance-Algorithm/openrm |
| SRM-Vision | 步兵视觉开源 | https://github.com/nicekeywords/SRM-Vision |
| 上海交通大学视觉 | 成熟战队视觉代码 | https://github.com/SJTU-RoboMaster-Team/SJTU-Vision |

### 视觉硬件

- **工业相机**：大恒相机 / 迈德威视（MindVision）/ 海康威视
- **镜头选型**：焦距 / 视场角计算
- **算力平台**：Intel NUC / NVIDIA Jetson Nano/Xavier / 工控机
- **深度相机**：Intel RealSense（导航/哨兵常用）

---

## 优秀开源战队

以下战队提供了高质量的 RoboMaster 开源代码和文档，推荐学习参考：

| 战队 | 学校 | 开源内容 | 链接 |
|------|------|---------|------|
| 北理工 BRTR | 北京理工大学 | 电控+视觉 | https://github.com/BRTR-RoboMaster |
| 上交 RM | 上海交通大学 | 电控+视觉+机械 | https://github.com/SJTU-RoboMaster-Team |
| 哈工大 HERO | 哈尔滨工业大学 | 电控框架 | https://github.com/HIT-HERO |
| 华南理工 SCURM | 华南理工大学 | 视觉+电控 | https://github.com/SCURM-RoboMaster |
| rm_vision 社区 | 多校联合 | ROS2 视觉框架 | https://github.com/chenjunnn/rm_vision |

---

## RoboMaster 学习路线建议

### 机械方向
1. 学习 SolidWorks / Fusion 360 基础建模
2. 研究 RM 规则手册，了解机器人限制要求
3. 拆解分析官方开源设计和优秀战队开源机械
4. 从底盘开始，逐步学习云台、发射机构设计

### 电控方向
1. C 语言基础 → STM32 GPIO/定时器/UART/SPI/I2C/CAN
2. FreeRTOS 多任务编程
3. PID 控制器调参
4. 学习 RM 开发板官方例程，理解电机控制
5. 参考成熟战队开源代码，理解整体框架

### 视觉方向
1. Python / C++ 基础 → OpenCV 基础操作
2. 相机标定、PnP 位姿估计
3. 学习 YOLO 等目标检测算法
4. 参考 rm_vision 框架理解完整流水线
5. 学习 ROS2，掌握视觉-电控通信方案

---

## 如何贡献

欢迎所有人参与维护这个资源库！

1. Fork 本仓库
2. 在对应分类下添加你认为优质的资源
3. 提交 Pull Request

**资源格式建议：**
```
| [资源名称](链接) | 简短说明 |
```

---

## 免责声明

本仓库收录的所有外部链接均来自互联网公开资源，版权归原作者所有。如有侵权，请提 Issue 告知，将及时处理。

---

*最后更新：2024年 | 由长空御风战队整理维护*
