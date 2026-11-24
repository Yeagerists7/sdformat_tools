# sdformat_tools｜个人适配记录

本仓库是对上游 `sdformat_tools` 的个人 Fork，用于维护机器人描述文件转换工具在当前仿真工作空间中的适配修改。

## 仓库用途

该项目提供面向 SDF（Simulation Description Format）的辅助工具，主要包括：

- **xmacro4sdf**：通过 XMacro 编写模块化 SDF
- **sdf2urdf**：将 SDF 转换为 URDF（存在格式支持限制）
- **urdf_generator**：提供 URDF 生成与处理接口

这些工具用于连接 Gazebo 仿真模型描述与 ROS 生态中的 URDF 使用场景。

## 当前状态

- 目标环境：Ubuntu 24.04、ROS 2 Jazzy、Gazebo Harmonic
- 用途：个人哨兵机器人描述与仿真适配的配套工具
- 状态：适配与验证中，不代表上游已正式支持上述环境

## 上游项目

- 上游仓库：[gezp/sdformat_tools](https://github.com/gezp/sdformat_tools)
- [查看上游原始 README（galactic 分支）](https://github.com/gezp/sdformat_tools/blob/galactic/README.md)

本仓库是个人维护的 Fork，不代表上游项目的官方发布。原始代码及其许可证、版权声明仍以各自文件中的说明为准。
