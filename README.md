# 张梦洋

智能体研发 / 具身规划 / 长尾感知与 PEFT / 论文与系统工程

我主要做两条线：

1. 论文方法：围绕长尾感知、低资源适配、结构抽取和边界建模，做可复现的模型与实验系统。
2. 智能体系统：把训练好的能力放进 LangGraph runtime、ROS 接入、CommandBus 和 benchmark 框架里。

## 正在推进 / 未来展示方向

- RAG / 检索增强生成
- 多 Agent 协同与任务编排
- 大模型部署、评测和推理加速
- 面向实际业务的数据治理与算法落地

我更偏算法开发，但会把算法做成能跑、能讲、能展示的系统。

## 代表成果

| 项目 | 状态 | 亮点 |
| --- | --- | --- |
| [Hy-MoRA](https://github.com/my420254/Hy-Mora) | WISA 已接收 | 110M 级 PEFT 框架，在 SMP2020-EWECT 上对标 7B LLM，Macro-F1 提升 6.12 个百分点，吞吐量提升约 55 倍 |
| [HiPro-LoRA](https://github.com/my420254/HiPro-LoRA) | ECML-PKDD 已接收 | 严格 held-out 评测，5/6 配置 Tail-F1 最优，4/6 配置 Macro-F1 最优 |
| [SPEAR](https://github.com/my420254/ECPE) | KBS 投稿版本 | ECPE 抽取框架，DoRA biaffine + R-Drop + 窗口约束解码，10 折交叉验证 F1 达到 77.24% |
| [FASTE](https://github.com/my420254/paper) | ESWA 投稿版本 | ASTE 抽取框架，多层特征融合 + 对抗训练，兼顾边界精度与工程实时性 |
| [OurAgent](https://github.com/my420254/OurAgent) | 内部框架 | LangGraph + ROS + CommandBus + 中断恢复 + 分层反思 + 多 benchmark 接入 |

## 我在做什么

- 把原始数据整理成可训练、可审计、可复现的数据集。
- 把 LoRA / DoRA / prototype memory / hierarchical pooling 这类方法落到可跑代码里。
- 把单次推理结果变成可调度、可中断、可恢复的 agent runtime。
- 把论文里的方法对比、图表、显著性检验和部署评估做成完整链路。

## 公开仓库

- [Hy-Mora](https://github.com/my420254/Hy-Mora)
- [HiPro-LoRA](https://github.com/my420254/HiPro-LoRA)
- [ECPE / SPEAR](https://github.com/my420254/ECPE)
- [FASTE / ASTE](https://github.com/my420254/paper)
- [OurAgent](https://github.com/my420254/OurAgent)

## 关键词

Long-tailed learning, PEFT, LoRA, DoRA, prototype memory, sentiment analysis, ECPE, ASTE, LangGraph, ROS, CommandBus, benchmark orchestration.

## 联系方式

- GitHub: `my420254`
- Gitee: `my420254`
- 邮箱: `按你的正式邮箱补上`
