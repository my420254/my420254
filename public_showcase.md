# 项目总览

这里汇总我的研究和工程项目，重点覆盖智能体运行时、参数高效微调、结构化 NLP 和大模型应用工程。

## 技术主线

```text
数据集清洗与重构
  -> LoRA / DoRA / PEFT 微调
  -> 长尾与结构化 NLP 建模
  -> vLLM 部署与并行评测
  -> LangGraph 智能体运行时
  -> ROS / 前端 / CLI 文本接入
  -> RAG、Redis 记忆与流式服务
```

## 项目矩阵

| 项目 | 类型 | 状态 | 关键词 |
| --- | --- | --- | --- |
| [Embodied Agent Runtime](https://github.com/my420254/Embodied-Agent-Runtime) | 具身智能体运行时 | 实习核心项目 | LangGraph、ROS2、CommandBus、任务栈、中断恢复、反思重试 |
| [Embodied VLM Explorer](https://github.com/my420254/Embodied-VLM-Explorer) | VLM/VLA 预研 | 路线探索项目 | 视觉语言动作闭环、状态回写、技能接口、路线取舍 |
| [HiPro-LoRA](https://github.com/my420254/HiPro-LoRA) | PEFT 论文项目 | ECML-PKDD 已接收，CCF B | LoRA、长尾学习、严格 held-out、LLM baseline |
| [Hy-MoRA](https://github.com/my420254/Hy-Mora) | PEFT 论文项目 | WISA 中文会议已接收 | 中文社交媒体、尾部记忆、层次化语义聚合、部署效率 |
| [FASTE](https://github.com/my420254/FASTE) | ASTE 论文项目 | ESWA 投稿版本 | 三元组抽取、span-based、MLFF、AT-FGM |
| [SPEAR / ECPE](https://github.com/my420254/ECPE) | ECPE 论文项目 | KBS 投稿版本 | 情绪原因对抽取、DoRA-biaffine、R-Drop、窗口解码 |
| [Agentic-RAG-Platform](https://github.com/my420254/Agentic-RAG-Platform) | 大模型应用工程 | 展示项目 | FastAPI、SSE、Redis、RAG、Vue3、工具调用 |

## 代表能力

- **从数据到模型**：能够处理原始数据清洗、类别分布重构、训练/验证/测试协议设计和可复现实验输出。
- **从方法到论文**：能够完成方法设计、消融实验、敏感性分析、图表生成、实验对比和投稿材料整理。
- **从模型到系统**：能够把大模型能力接入 LangGraph runtime、ROS 文本入口、CommandBus、执行后端和 benchmark 评测链路。
- **从原型到展示**：能够把 RAG、Redis、SSE、工具调用和前端工作台组织成可阅读、可运行、可扩展的工程骨架。

## 当前公开入口

- GitHub：<https://github.com/my420254>
- Gitee：<https://gitee.com/my420254>
- Portfolio：<https://my420254.github.io/my420254/>
- Email：1127141319@qq.com
