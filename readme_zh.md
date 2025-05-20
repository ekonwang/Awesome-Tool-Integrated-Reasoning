# Awesome Tool-Integrated Reasoning (Awesome TIR)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

本仓库收集了与工具集成推理（Tool-Integrated Reasoning）相关的学术研究工作，旨在为研究人员和开发者提供一个全面的参考资源。工具集成推理是一种新兴的人工智能范式，它通过将大型语言模型（LLM）或大型视觉语言模型（LVLM）与外部工具相结合，显著增强了模型的推理能力和问题解决能力。

## 目录

- [简介](#简介)
- [数学推理](#数学推理)
- [多模态与视觉推理](#多模态与视觉推理)
- [通用推理与代理](#通用推理与代理)
- [评估与基准测试](#评估与基准测试)
- [相关资源](#相关资源)
- [贡献](#贡献)

## 简介

工具集成推理（Tool-Integrated Reasoning，TIR）是人工智能领域的一个重要发展方向，它解决了传统大型语言模型在复杂推理任务中面临的幻觉和计算不准确等问题。通过将模型与外部工具（如代码执行环境、计算器、搜索引擎等）相结合，TIR 使模型能够验证其推理步骤，执行复杂计算，并获取外部知识，从而显著提高推理的准确性和可靠性。

近年来，随着 ToRA、START 等工作的出现，TIR 领域取得了显著进展，并在数学问题求解、科学推理、代码生成等多个领域展现出强大的潜力。本仓库旨在系统性地收集和整理 TIR 相关的学术研究工作，为该领域的研究者和实践者提供参考。

## 数学推理

数学推理是 TIR 最早和最成功的应用领域之一，通过集成计算工具，模型能够解决复杂的数学问题。

### ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving

ToRA 是由微软研究院开发的一系列工具集成推理代理，专门用于解决具有挑战性的数学问题。ToRA 通过与工具交互，能够解决需要多步推理的复杂数学问题，显著超越了传统的纯语言模型。

- 作者：Yue Zhang, Leyang Cui, Daya Guo, Zheng Chen, Qingxing Cao, Nigel Collier, Ting Liu, Ruihua Song, Furu Wei
- 发表时间：2023年9月
- 链接：[https://arxiv.org/abs/2309.17452](https://arxiv.org/abs/2309.17452)
- 项目主页：[https://microsoft.github.io/ToRA/](https://microsoft.github.io/ToRA/)

### START: Self-taught Reasoner with Tools

START 是阿里巴巴研究团队提出的一种新型工具集成长链思维推理 LLM，通过两种关键技术（Hint-infer 和 Hint-RFT）显著增强了推理能力。START 能够执行复杂计算、自我检查、探索多种方法和自我调试，从而解决了传统 LRM 的局限性。

- 作者：Chengpeng Li, Mingfeng Xue, Zhenru Zhang, Jiaxi Yang, Beichen Zhang, Xiang Wang, Bowen Yu, Binyuan Hui, Junyang Lin, Dayiheng Liu
- 发表时间：2025年3月
- 链接：[https://arxiv.org/abs/2503.04625](https://arxiv.org/abs/2503.04625)

## 多模态与视觉推理

多模态与视觉推理领域的 TIR 研究关注如何将视觉信息与语言推理相结合，通过工具增强多模态模型的推理能力。

### VisuoThink: Empowering LVLM Reasoning with Multimodal Tree Search

VisuoThink 是一种新型框架，无缝集成视觉空间和语言领域，通过前瞻性树搜索实现多模态慢思考。该方法受到人类认知中慢思考机制的启发，使模型能够进行渐进式的视觉-文本推理，并通过推理时间扩展显著增强推理能力。

- 作者：Yikun Wang, Siyin Wang, Qinyuan Cheng, Zhaoye Fei, Liang Ding, Qipeng Guo, Dacheng Tao, Xipeng Qiu
- 发表时间：2025年4月
- 链接：[https://arxiv.org/abs/2504.09130](https://arxiv.org/abs/2504.09130)

### Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models

Visual Sketchpad 将草图绘制作为多模态语言模型的视觉思维链，增强了模型的视觉推理能力。通过允许模型生成和利用视觉草图，该方法使模型能够更好地理解和解决涉及空间关系和视觉推理的问题。

- 发表时间：2024年6月
- 链接：[https://arxiv.org/abs/2406.09403](https://arxiv.org/abs/2406.09403)

## 通用推理与代理

通用推理与代理领域的 TIR 研究关注如何构建能够灵活使用多种工具的智能代理，以增强模型的通用推理能力。

### Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research

Agentic Reasoning 是一个通过集成外部工具使用代理来增强大型语言模型推理的框架。与传统的基于 LLM 的推理方法不同，Agentic Reasoning 动态地利用网络搜索、代码执行和结构化推理上下文记忆来解决需要深入研究和多步逻辑推理的复杂问题。

- 作者：Junde Wu, Jiayuan Zhu, Yuyuan Liu
- 发表时间：2025年2月
- 链接：[https://arxiv.org/abs/2502.04644](https://arxiv.org/abs/2502.04644)

### ReTool: Reinforcement Learning for Strategic Tool Use in LLMs

ReTool 使用强化学习方法优化 LLM 中的战略性工具使用，使模型能够学习何时以及如何有效地使用工具来解决问题。通过强化学习，模型能够根据任务需求动态选择和使用最合适的工具。

- 发表时间：2025年4月
- 链接：[https://arxiv.org/abs/2504.11536](https://arxiv.org/abs/2504.11536)

## 评估与基准测试

评估与基准测试对于衡量 TIR 方法的有效性至关重要，这些研究提供了标准化的评估框架和数据集。

### VCBENCH: 多模态数学推理基准测试

VCBENCH 是一个全面的多模态数学推理基准，具有明确的视觉依赖性。该基准测试专门设计用于评估模型在需要视觉信息进行数学推理的任务中的表现。

- 发表时间：2025年4月
- 链接：[https://paperswithcode.com/paper/2504.18589](https://paperswithcode.com/paper/2504.18589)

## 相关资源

- [LLM Reasoning Survey](https://github.com/reasoning-survey/LLM-Reasoning-Papers) - 大型语言模型推理相关论文集合
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM) - 大型语言模型相关资源集合
- [Awesome LVLM](https://github.com/Gary-code/Awesome-LVLM-paper) - 大型视觉语言模型相关论文集合

## 贡献

欢迎通过 Pull Requests 或 Issues 来贡献更多的工具集成推理相关研究！请确保您的贡献包含完整的论文信息，包括标题、作者、发表时间、链接等。

## 引用

如果您发现本仓库对您的研究有帮助，请考虑引用相关论文。

## 许可证

本项目采用 [MIT 许可证](LICENSE)。
