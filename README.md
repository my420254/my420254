# 张梦洋

**智能体研发 / 大模型应用算法 / NLP 与参数高效微调**

邮箱：1127141319@qq.com

GitHub Pages：<https://my420254.github.io/my420254/>

Gitee 镜像：<https://gitee.com/my420254>

我关注大模型智能体、具身任务规划、NLP 结构化抽取和参数高效微调。过去的工作覆盖了从数据集清洗、模型训练、论文实验，到 LangGraph 运行时、ROS/前端文本接入、vLLM 并行评测和 RAG 工程化展示的完整链路。

## 研究与工程方向

- **智能体运行时**：LangGraph 图编排、CommandBus 外部命令通道、任务栈式中断恢复、执行反馈、失败反思与局部重试。
- **参数高效微调**：LoRA / DoRA / PEFT、长尾学习、原型记忆、层次化语义聚合、低资源情感分析。
- **结构化 NLP**：情感原因对抽取、方面级情感三元组抽取、span-based 表示、biaffine 关系建模、对抗训练。
- **大模型工程化**：vLLM 部署、多端口并行实验、RAG 检索增强生成、Redis 会话记忆、FastAPI/SSE 流式服务。

## 代表项目

| 项目 | 状态 | 核心内容 | 价值 |
| --- | --- | --- | --- |
| [Embodied Agent Runtime](https://github.com/my420254/Embodied-Agent-Runtime) | 实习核心项目 | 面向 ROS / 前端 / CLI 的 LangGraph 具身智能体运行时 | 统一文本接入、任务插单、中断恢复、取消暂停、失败反思和 benchmark 对齐 |
| [Embodied VLM Explorer](https://github.com/my420254/Embodied-VLM-Explorer) | 具身 VLM/VLA 预研 | 看一帧、出一步动作、执行后回写状态的轻量闭环原型 | 解释端到端视觉路线在延迟、状态记忆、动作可控性和评测稳定性上的边界 |
| [ALFRED SFT Brain](https://github.com/my420254/ALFRED-SFT-Brain) | 实习前期模型项目 | ALFRED 轨迹清洗、focused observation、Qwen2.5-7B LoRA 下一步动作微调 | valid_unseen 上 Strict Step 94.36%、Relaxed Task 86.47%，支撑从单步模型到 runtime 的演进 |
| [HiPro-LoRA](https://github.com/my420254/HiPro-LoRA) | ECML-PKDD 已接收，CCF B | 低资源长尾情感分析的参数高效微调方法与严格 held-out 评测包 | 在多组配置中提升 Tail-F1 / Macro-F1，并保持可复现实验口径 |
| [Hy-MoRA](https://github.com/my420254/Hy-Mora) | WISA 中文会议已接收 | 中文社交媒体长尾情感分析 PEFT 框架，结合层次化语义聚合与尾部记忆对齐 | 以 110M 级模型对标 7B LLM，在精度、吞吐和部署成本之间取得更优平衡 |
| [FASTE](https://github.com/my420254/FASTE) | ESWA 投稿版本 | 面向 ASTE 的 span-based 三元组抽取框架，多层特征融合 + 对抗训练 | 强化边界对齐和跨词关系建模，适合结构化情感分析任务 |
| [SPEAR / ECPE](https://github.com/my420254/ECPE) | KBS 投稿版本 | 情绪原因对抽取框架，结合 span-aware 表征、DoRA-biaffine 打分和 R-Drop 正则 | 面向文档级结构化抽取，提升配对精度和训练稳定性 |
| [Agentic-RAG-Platform](https://github.com/my420254/Agentic-RAG-Platform) | 工程展示项目 | FastAPI + SSE + Redis + RAG + Vue3 的企业知识库智能体骨架 | 展示检索、重排、记忆、工具调用、流式输出和前后端服务化能力 |

## 技术栈

`Python` · `PyTorch` · `Transformers` · `PEFT` · `LoRA` · `DoRA` · `LangGraph` · `LangChain` · `FastAPI` · `Redis` · `SSE` · `Vue3` · `vLLM` · `ROS2` · `RAG`

## 项目阅读顺序

1. [Embodied VLM Explorer](https://github.com/my420254/Embodied-VLM-Explorer)：了解具身 VLM/VLA 闭环预研和路线取舍。
2. [ALFRED SFT Brain](https://github.com/my420254/ALFRED-SFT-Brain)：了解 ALFRED 数据清洗、Qwen2.5-7B LoRA 微调和动作预测评估。
3. [Embodied Agent Runtime](https://github.com/my420254/Embodied-Agent-Runtime)：了解具身智能体运行时、外部文本接入和任务管理。
4. [HiPro-LoRA](https://github.com/my420254/HiPro-LoRA) 与 [Hy-MoRA](https://github.com/my420254/Hy-Mora)：了解 PEFT、长尾学习和严格实验协议。
5. [Agentic-RAG-Platform](https://github.com/my420254/Agentic-RAG-Platform)：了解大模型应用服务化、RAG、Redis 记忆和 SSE 流式输出。
6. [FASTE](https://github.com/my420254/FASTE) 与 [SPEAR / ECPE](https://github.com/my420254/ECPE)：了解结构化 NLP 抽取任务与论文级实验组织。
