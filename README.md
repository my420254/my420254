# 张梦洋

智能体研发 / 具身规划 / 长尾感知与 PEFT / 论文与系统工程

我做的不是单点模型，而是把论文方法、实验协议和运行时系统做成闭环。
论文、代码、实验、图表和稿件整理均由本人主导完成。

## 我最强的几件事

- 能把原始数据清洗成可训练、可审计、可复现的数据集
- 能把 LoRA / DoRA / prototype memory / hierarchical pooling 落到可跑代码
- 能把模型接进 LangGraph / ROS / CommandBus / benchmark runtime
- 能把并行推理、评测协议、部署吞吐和结果复盘一起管住

## 代表成果

| 项目 | 状态 | 我做的核心工作 | 结果亮点 |
| --- | --- | --- | --- |
| [Hy-MoRA](https://github.com/my420254/Hy-Mora) | WISA 已接收 | 设计层次化语义聚合 + 尾部感知记忆对齐，完成实验与图表整理 | 110M 级 PEFT 框架，在 SMP2020-EWECT 上对标 7B LLM，Macro-F1 提升 6.12 个百分点，吞吐量提升约 55 倍 |
| [HiPro-LoRA](https://github.com/my420254/HiPro-LoRA) | ECML-PKDD 已接收 | 做严格 held-out 协议、完成结果整理和稳定性验证 | 5/6 配置 Tail-F1 最优，4/6 配置 Macro-F1 最优 |
| [SPEAR](https://github.com/my420254/ECPE) | KBS 投稿版本 | 设计 span-aware 表征、DoRA biaffine、R-Drop 和窗口约束解码 | 10 折交叉验证 F1 达到 77.24% |
| [FASTE](https://github.com/my420254/FASTE) | ESWA 投稿版本 | 设计多层特征融合 + 对抗训练，并完成论文图表与实验闭环 | ASTE 抽取达到强基线水平，兼顾边界精度与工程实时性 |
| [OurAgent-he1](https://github.com/my420254/OurAgent-he1) | 实习核心项目 | 把规划能力接入 LangGraph runtime、ROS 文本服务和 CommandBus | 支持外部文本接入、任务插单、栈式恢复、取消暂停、反思重试 |
| [OurAgent](https://github.com/my420254/OurAgent) | benchmark 版本 | 多 benchmark 适配、论文方法对比、裸基线公平评测 | 支持 DELTA / EAI / ReAcTree 等多任务评测链路 |

## 我的工作风格

我更偏算法开发，但不会只停在算法本身。
我会把方法、数据、评测、部署、文档和演示一起做完，让一个项目能被真正看懂、跑通、复现和展示。

## 我在做什么

- 把原始数据整理成可训练、可审计、可复现的数据集
- 把论文里的方法对比、图表、显著性检验和部署评估做成完整链路
- 把单次推理结果变成可调度、可中断、可恢复的 agent runtime
- 把模型能力扩展到多 benchmark、多模型、多进程并行的实际环境

## 正在推进 / 未来展示方向

- RAG / 检索增强生成
- 多 Agent 协同与任务编排
- 大模型部署、评测和推理加速
- 面向实际业务的数据治理与算法落地

## 公开仓库

- [Hy-Mora](https://github.com/my420254/Hy-Mora)
- [HiPro-LoRA](https://github.com/my420254/HiPro-LoRA)
- [ECPE / SPEAR](https://github.com/my420254/ECPE)
- [FASTE / ASTE](https://github.com/my420254/FASTE)
- [OurAgent-he1 / ROS-LangGraph Runtime](https://github.com/my420254/OurAgent-he1)
- [OurAgent / Benchmark Runtime](https://github.com/my420254/OurAgent)

## 关键词

Long-tailed learning, PEFT, LoRA, DoRA, prototype memory, sentiment analysis, ECPE, ASTE, LangGraph, ROS, CommandBus, benchmark orchestration.

## 联系方式

- GitHub: `my420254`
- Gitee: `my420254`
- 邮箱: `按你的正式邮箱补上`
