# 跨领域 RSI 基础方法

本文件收录**不属于任何特定应用领域**的通用 RSI 方法（自我改进算法、技能库、
Agent 架构搜索、自我博弈训练、进化方法等）。此前把它们分散计入九个应用领域，
导致「专业知识工作」等领域出现大量无领域依据的条目；现统一独立成册，
**不计入任何应用领域的高水平论文数**。

判断依据与九个领域完全一致：出版层级门槛 + 明确的自我改进机制 + 严格 L1–L7 分级。

| 编号 | 论文名称 | 年份 | 出版层级 | 发表渠道 | RSI 分级 | 定位 | 来源 |
|---|---|---|---|---|---|---|---|
| X01 | [Your Agent May Misevolve: Emergent Risks in Self-evolving LLM Agents](https://arxiv.org/abs/2509.26354) | 2025 | T1 CCF-A | ICLR（作者注明：Published in ICLR 2026） | L3 | 相关基础能力 | [官方页](https://arxiv.org/abs/2509.26354) |
| X02 | [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651) | 2023 | T1 CCF-A | neural information processing systems | L5 | 接近 RSI | [官方页](https://arxiv.org/abs/2303.17651) |
| X03 | [Reflection in the Dark: Exposing and Escaping the Black Box in Reflective Prompt Optimization](https://arxiv.org/abs/2603.18388) | 2026 | T1 CCF-A | ACL（作者注明：Accepted at ACL SRW 2026） | L2 | 接近 RSI | [官方页](https://arxiv.org/abs/2603.18388) |
| X04 | [Goal-Oriented Skill Abstraction for Offline Multi-Task Reinforcement Learning](https://arxiv.org/abs/2507.06628) | 2025 | T1 CCF-A | Proceedings of the 42nd International Conference on Machine Learning, Vancouver, Canada. PMLR 267, 2025 | L3 | 相关基础能力 | [官方页](https://arxiv.org/abs/2507.06628) |
| X05 | [FormulaSPIN: Self-Play Fine-Tuning for Natural Language to Spreadsheet Formula Generation](https://arxiv.org/abs/2607.19354) | 2026 | T1 CCF-A | ACL（作者注明：15 pages,7 figures, 14 tables. Accepted to ACL 2026 Main Conference Or） | L5 | 接近 RSI | [官方页](https://arxiv.org/abs/2607.19354) |
| X06 | [AdaptDiffuser: Diffusion Models as Adaptive Self-evolving Planners](https://arxiv.org/abs/2302.01877) | 2023 | T1 CCF-A | ICML（作者注明：Accepted by ICML 2023. Project page: https://adaptdiffuser.github.io） | L4 | 相关基础能力 | [官方页](https://arxiv.org/abs/2302.01877) |
| X07 | [CREAM: Consistency Regularized Self-Rewarding Language Models](https://arxiv.org/abs/2410.12735) | 2024 | T1 CCF-A | ICLR（作者注明：To appear at ICLR 2025） | L5 | 接近 RSI | [官方页](https://arxiv.org/abs/2410.12735) |
| X08 | [SCAFFOLD: Self-Improving Web Agents via Recursive Parametric Skill Abstraction](https://arxiv.org/abs/2609.05511) | 2026 | T3 旗舰会议/领域顶刊 | EMNLP（作者注明：Accepted by EMNLP 2026） | L3 | 直接 RSI（候选） | [官方页](https://arxiv.org/abs/2609.05511) |
| X09 | [Improving Rationality in the Reasoning Process of Language Models through Self-playing Game](https://arxiv.org/abs/2506.22920) | 2025 | T1 CCF-A | ICML（作者注明：Accepted by ICML 2025） | L5 | 接近 RSI | [官方页](https://arxiv.org/abs/2506.22920) |
| X10 | [MemMA: Coordinating the Memory Cycle through Multi-Agent Reasoning and In-Situ Self-Evolution](https://doi.org/10.18653/2026.emnlp-main.2339) | 2026 | T3 旗舰会议/领域顶刊 | Conference on Empirical Methods in Natural Language Processing (EMNLP) | L4 | 接近 RSI | [官方页](https://doi.org/10.18653/2026.emnlp-main.2339) |
| X11 | [Self-Corrected Flow Distillation for Consistent One-Step and Few-Step Text-to-Image Generation](https://arxiv.org/abs/2412.16906) | 2024 | T1 CCF-A | AAAI（作者注明：Accepted to AAAI 2025. Code: https://github.com/hao-pt/SCFlow.git） | L5 | 相关基础能力 | [官方页](https://arxiv.org/abs/2412.16906) |
| X12 | [ExpeL: LLM Agents Are Experiential Learners](https://arxiv.org/abs/2308.10144) | 2023 | T1 CCF-A | Proceedings of the AAAI Conference on Artificial Intelligence | L1 | 相关基础能力 | [官方页](https://arxiv.org/abs/2308.10144) |
| X13 | [World Models as Adversaries: Multi-Agent Self-Play Fine-Tuning for Robust Motion Planning](https://arxiv.org/abs/2607.10630) | 2026 | T1 CCF-A | NeurIPS（作者注明：Accepted at NeurIPS 2026） | L5 + L4 | 相关基础能力 | [官方页](https://arxiv.org/abs/2607.10630) |
| X14 | [Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models](https://arxiv.org/abs/2401.01335) | 2024 | T1 CCF-A | ICML（作者注明：22 pages, 6 figures, 7 tables. In ICML 2024） | L5 | 接近 RSI | [官方页](https://arxiv.org/abs/2401.01335) |
| X15 | [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) | 2023 | T1 CCF-A | neural information processing systems | L2 | 相关基础能力 | [官方页](https://arxiv.org/abs/2303.11366) |
| X16 | [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) | 2023 | T1 CCF-A | ACM Symposium on User Interface Software and Technology (UIST) | L4 | 相关基础能力 | [官方页](https://arxiv.org/abs/2304.03442) |
| X17 | [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601) | 2023 | T1 CCF-A | neural information processing systems | L1 | 相关基础能力 | [官方页](https://arxiv.org/abs/2305.10601) |
| X18 | [CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society](https://arxiv.org/abs/2303.17760) | 2023 | T1 CCF-A | neural information processing systems | L4 | 相关基础能力 | [官方页](https://arxiv.org/abs/2303.17760) |
| X19 | [Evolving Agents in the Dark: Retrospective Harness Optimization via Self-Preference](https://arxiv.org/abs/2606.05922) | 2026 | T3 旗舰会议/领域顶刊 | EMNLP（作者注明：Accepted to EMNLP 2026 (Findings). Code: https://github.com/wbopan/ret） | L4 | 接近 RSI | [官方页](https://arxiv.org/abs/2606.05922) |
| X20 | [REGREACT: Self-Correcting Multi-Agent Pipelines for Structured Regulatory Information Extraction](https://arxiv.org/abs/2604.12054) | 2026 | T3 旗舰会议/领域顶刊 | EMNLP（作者注明：Accepted to EMNLP 2026 (Findings)） | L4 | 相关基础能力 | [官方页](https://arxiv.org/abs/2604.12054) |
| X21 | [Human-like autonomy emerges from self-play and a pinch of human data](https://arxiv.org/abs/2606.19370) | 2026 | T3 旗舰会议/领域顶刊 | 10th Conference on Robot Learning (CoRL 2026), Austin TX, USA | L5 | 相关基础能力 | [官方页](https://arxiv.org/abs/2606.19370) |
| X22 | [AnchorSteer: Self-Discovered Concept Injection for Structure-Preserving Music Editing](https://arxiv.org/abs/2605.31053) | 2026 | T1 CCF-A | ACM（作者注明：Accepted by the 32nd ACM SIGKDD Conference on Knowledge Discovery and ） | L1 | 相关基础能力 | [官方页](https://arxiv.org/abs/2605.31053) |
| X23 | [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741) | 2024 | T1 CCF-A | ICLR（作者注明：Accepted by ICLR 2025; Code: https://github.com/All-Hands-AI/OpenHands） | L1 | 相关基础能力 | [官方页](https://arxiv.org/abs/2407.16741) |
| X24 | [Self-Discovering Interpretable Diffusion Latent Directions for Responsible Text-to-Image Generation](https://arxiv.org/abs/2311.17216) | 2023 | T1 CCF-A | CVPR（作者注明：Accepted to CVPR 2024） | L1 | 相关基础能力 | [官方页](https://arxiv.org/abs/2311.17216) |

共 24 篇；出版层级分布：CCF-A 19 篇、旗舰会议/领域顶刊 5 篇。

其中标注「作者自述接收」或仍为 arXiv 预印本的记录**不得视为已正式发表的高水平成果**。
