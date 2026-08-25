# OurAgent

一个面向具身任务与多 benchmark 评测的智能体运行时。

## 项目定位

这个仓库的目标不是单点推理，而是把一个可用的规划能力放进完整的 agent runtime 里：

- 外部指令如何进入系统
- 新任务如何插单
- 旧任务如何挂起和恢复
- 失败后如何分层反思
- 多 benchmark 如何统一调度

## 核心架构

- `main.py`：稳定的 LangGraph 主入口，只负责启动全局应用。
- `scripts/run_console.py`：终端交互与调试入口，负责把流式状态渲染成可读输出。
- `graph/`：Understanding / Planning / Task Management / Reflection 四阶段编排。
- `execution/`：执行层与后端封装。
- `benchmark/`：不同论文、数据集和 evaluator 的适配层。
- `config/`：场景、规则、技能和模型配置。

## 关键能力

- CommandBus 统一命令通道
- ROS 文本服务接入
- 任务栈式中断与恢复
- 分层反思和局部重试
- 多 benchmark 并行调度

## 支持的 benchmark

- DELTA
- EAI BEHAVIOR
- EAI VirtualHome
- ReAcTree WAH
- ReAcTree ALFRED

## 你可以怎么讲这个项目

“我把训练好的规划能力接入了一个真正能跑的智能体 runtime，解决的不是模型分数，而是任务接入、任务中断、恢复、反思和多 benchmark 调度这些系统问题。”

## 运行说明

当前仓库的正式入口是 `main.py`。`scripts/run_console.py` 适合做终端可视化和调试，不是额外的业务核心。

