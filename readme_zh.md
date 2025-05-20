# Awesome 工具集成推理 (Awesome TIR)

[![Awesome](assets/awesome.svg)](https://awesome.re)

[English](readme.md) | [中文](readme_zh.md)

🔥 精心策划的工具集成推理(Tool-Integrated Reasoning, TIR)相关学术研究作品集合，为研究人员和开发者提供全面的参考资源。工具集成推理是一种新兴的AI范式，通过将大型语言模型(LLMs)或大型视觉-语言模型(LVLMs)与外部工具相结合，显著增强推理能力和问题解决能力。

## 目录

- [🤗 简介](#简介)
- [📚 数学推理](#数学推理)
- [🎨 多模态和视觉推理](#多模态和视觉推理)
- [🤖 通用推理和智能体](#通用推理和智能体)
- [📊 评估和基准](#评估和基准)
- [🔍 相关资源](#相关资源)
- [👥 贡献](#贡献)

## 🤗 简介

---

工具集成推理(TIR)代表了人工智能的重大进步，解决了传统大型语言模型在复杂推理任务中面临的幻觉和计算不准确问题。通过将模型与外部工具(如代码执行环境、计算器、搜索引擎等)集成，TIR使模型能够验证其推理步骤，执行复杂计算，并访问外部知识，从而显著提高推理准确性和可靠性。

近年来，随着ToRA和START等作品的出现，TIR领域取得了显著进展，并在数学问题解决、科学推理、代码生成等多个领域展示了强大的潜力。本仓库旨在系统地收集和组织与TIR相关的学术研究作品，为该领域的研究人员和实践者提供参考。

## 📚 数学推理

---

数学推理是TIR最早和最成功的应用领域之一，模型可以通过集成计算工具来解决复杂的数学问题。

### ToRA: 用于数学问题求解的工具集成推理智能体

> ToRA是由微软研究院开发的一系列工具集成推理智能体，专门设计用于解决具有挑战性的数学问题。通过与工具的交互，ToRA能够解决需要多步推理的复杂数学问题，显著优于传统的纯语言模型。
> 
> - 作者: Yue Zhang, Leyang Cui, Daya Guo, Zheng Chen, Qingxing Cao, Nigel Collier, Ting Liu, Ruihua Song, Furu Wei
> - 发布日期: 2023年9月
> - 链接: [https://arxiv.org/abs/2309.17452](https://arxiv.org/abs/2309.17452)
> - 项目页面: [https://microsoft.github.io/ToRA/](https://microsoft.github.io/ToRA/)

### START: 具有工具能力的自学习推理器

> START是由阿里巴巴研究团队提出的一种新型工具集成长链式思考推理LLM，通过两项关键技术(Hint-infer和Hint-RFT)显著增强推理能力。START可以执行复杂计算、自我检查、探索多种方法和自我调试，从而解决传统LRM的局限性。
> 
> - 作者: Chengpeng Li, Mingfeng Xue, Zhenru Zhang, Jiaxi Yang, Beichen Zhang, Xiang Wang, Bowen Yu, Binyuan Hui, Junyang Lin, Dayiheng Liu
> - 发布日期: 2025年3月
> - 链接: [https://arxiv.org/abs/2503.04625](https://arxiv.org/abs/2503.04625)

## 🎨 多模态和视觉推理

---

多模态和视觉推理领域的TIR研究关注如何将视觉信息与语言推理相结合，通过工具增强多模态模型的推理能力。

### VisuoThink: 通过多模态树搜索增强LVLM推理

> VisuoThink是一个新颖的框架，无缝集成视觉空间和语言领域，通过前瞻性树搜索实现多模态慢思考。受人类认知中慢思考机制的启发，该方法使模型能够执行渐进式视觉-文本推理，并通过推理时间扩展显著增强推理能力。
> 
> - 作者: Yikun Wang, Siyin Wang, Qinyuan Cheng, Zhaoye Fei, Liang Ding, Qipeng Guo, Dacheng Tao, Xipeng Qiu
> - 发布日期: 2025年4月
> - 链接: [https://arxiv.org/abs/2504.09130](https://arxiv.org/abs/2504.09130)

### Visual Sketchpad: 将草图绘制作为多模态语言模型的视觉思维链

> Visual Sketchpad将草图绘制作为多模态语言模型的视觉思维链，增强模型的视觉推理能力。通过允许模型生成和利用视觉草图，该方法使模型能够更好地理解和解决涉及空间关系和视觉推理的问题。
> 
> - 发布日期: 2024年6月
> - 链接: [https://arxiv.org/abs/2406.09403](https://arxiv.org/abs/2406.09403)

## 🤖 通用推理和智能体

---

通用推理和智能体领域的TIR研究关注如何构建能够灵活使用多种工具来增强模型通用推理能力的智能体。

### Agentic Reasoning: 具有工具的推理LLM用于深度研究

> Agentic Reasoning是一个通过集成外部工具使用智能体来增强大型语言模型推理的框架。与仅依赖内部推理的传统LLM推理方法不同，Agentic Reasoning动态地利用网络搜索、代码执行和结构化推理上下文记忆来解决需要深度研究和多步逻辑推理的复杂问题。
> 
> - 作者: Junde Wu, Jiayuan Zhu, Yuyuan Liu
> - 发布日期: 2025年2月
> - 链接: [https://arxiv.org/abs/2502.04644](https://arxiv.org/abs/2502.04644)

### ReTool: 用于LLM战略性工具使用的强化学习

> ReTool使用强化学习方法优化LLM中的战略性工具使用，使模型能够学习何时以及如何有效地使用工具来解决问题。通过强化学习，模型可以根据任务需求动态选择和使用最合适的工具。
> 
> - 发布日期: 2025年4月
> - 链接: [https://arxiv.org/abs/2504.11536](https://arxiv.org/abs/2504.11536)

## 📊 评估和基准

---

评估和基准对于衡量TIR方法的有效性至关重要，提供标准化的评估框架和数据集。

### VCBENCH: 多模态数学推理的综合基准

> VCBENCH是一个具有明确视觉依赖性的多模态数学推理综合基准。该基准专门设计用于评估模型在需要视觉信息进行数学推理的任务中的表现。
> 
> - 发布日期: 2025年4月
> - 链接: [https://paperswithcode.com/paper/2504.18589](https://paperswithcode.com/paper/2504.18589)

## 🔍 相关资源

---

- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM) - 与大型语言模型相关的资源集合
- [Awesome LVLM](https://github.com/Gary-code/Awesome-LVLM-paper) - 与大型视觉-语言模型相关的论文集合

## 👥 贡献

---

欢迎通过Pull Requests或Issues对本仓库进行贡献！请确保您的贡献包含完整的论文信息，包括标题、作者、发布日期、链接等。

## 📝 引用

---

如果您发现本仓库对您的研究有所帮助，请考虑引用相关论文。

## 许可证

本项目采用[MIT许可证](LICENSE)。