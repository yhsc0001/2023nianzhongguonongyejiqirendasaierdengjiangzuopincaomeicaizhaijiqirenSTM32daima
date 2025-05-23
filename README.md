# 2023年中国农业机器人大赛二等奖作品：草莓采摘机器人资源

## 项目简介

本项目源于2023年中国农业机器人大赛，荣获二等奖的创新之作——草莓采摘机器人。该项目巧妙地结合了硬件技术创新与软件智能算法，展现了在自动化农业领域的前沿应用。

## 技术栈与硬件配置

- **主控制器**：正点原子F4核心板，为核心系统提供强大的处理能力。
- **视觉识别**：利用Jetson Nano配合USB摄像头进行高精度的颜色识别，定位草莓目标。
- **通讯机制**：实现STM32与Jetson Nano之间的高效数据交换，确保信息实时同步。
- **移动平台**：选用酷点机器人350*400底盘，支持稳定移动。
- **机械臂执行**：集成幻尔科技的leArm机械臂，负责精准的采摘动作。
- **传感器技术**：
    - GY-53激光测距传感器，实现精确定位与避障。
    - 维特智能MPU6050陀螺仪，保障机器人姿态控制的稳定性。

## 代码特色

提供的STM32代码覆盖了全面的功能模块：

- **设备驱动**：详尽的驱动程序，确保每个硬件组件都能有效运作。
- **控制逻辑**：包含针对机械臂精确控制及底盘导航的算法实现。
- **多任务调度**：通过任务调度策略，优化处理多个并发操作，如识别、规划与执行等。
- **通讯协议**：实现了与Jetson Nano的通讯协议，保证数据传输的准确性和及时性。

## 使用指南

1. **环境准备**：确保开发环境已安装相应的编译工具链，如STM32CubeIDE或Keil MDK。
2. **硬件连接**：正确连线各部分硬件，包括但不限于STM32与其它外设的通讯接口。
3. **代码编译**：导入提供的源代码到你的IDE中，根据具体硬件配置调整相关参数后进行编译。
4. **调试与测试**：建议先在仿真环境下验证逻辑正确性，再进行实际硬件测试。

## 注意事项

- 在使用过程中，请仔细阅读各硬件的官方文档，以确保正确设置和安全操作。
- 由于技术快速迭代，部分硬件库或通信协议可能需要适配最新的固件版本。
- 此代码库为大赛项目的一部分，可能需要根据具体的硬件版本进行适当的调整与优化。

## 致谢

向所有参与项目的学生、指导老师及技术支持团队致以诚挚感谢，是他们智慧的结晶造就了这一精彩的作品。希望这份资源能激发更多对农业自动化感兴趣的朋友进行探索和创新。

## 下载链接
[2023年中国农业机器人大赛二等奖作品草莓采摘机器人STM32代码](https://pan.quark.cn/s/91e075bbdd24) 

(备用: [备用下载](https://pan.baidu.com/s/1HvELMXp2k7WlwvMEA7yXDA?pwd=1234))
