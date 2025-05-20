# Awesome Tool-Integrated Reasoning (Awesome TIR)

[![Awesome](assets/awesome.svg)](https://awesome.re)

[English](readme.md) | [中文](readme_zh.md)

🔥 A curated collection of academic research works related to Tool-Integrated Reasoning (TIR), providing a comprehensive reference resource for researchers and developers. Tool-Integrated Reasoning is an emerging AI paradigm that significantly enhances reasoning capabilities and problem-solving abilities by combining Large Language Models (LLMs) or Large Vision-Language Models (LVLMs) with external tools.

## Table of Contents

- [🤗 Introduction](#introduction)
- [📚 Mathematical Reasoning](#mathematical-reasoning)
- [🎨 Multimodal and Visual Reasoning](#multimodal-and-visual-reasoning)
- [🤖 General Reasoning and Agency](#general-reasoning-and-agency)
- [📊 Evaluation and Benchmarks](#evaluation-and-benchmarks)
- [🔍 Related Resources](#related-resources)
- [👥 Contributing](#contributing)

## 🤗 Introduction

---

Tool-Integrated Reasoning (TIR) represents a significant advancement in artificial intelligence, addressing the hallucination and computational inaccuracy issues faced by traditional large language models in complex reasoning tasks. By integrating models with external tools (such as code execution environments, calculators, search engines, etc.), TIR enables models to verify their reasoning steps, perform complex calculations, and access external knowledge, thereby significantly improving reasoning accuracy and reliability.

In recent years, with the emergence of works like ToRA and START, the TIR field has made remarkable progress and demonstrated powerful potential in mathematical problem-solving, scientific reasoning, code generation, and many other domains. This repository aims to systematically collect and organize academic research works related to TIR, providing a reference for researchers and practitioners in this field.

## 📚 Mathematical Reasoning

---

Mathematical reasoning is one of the earliest and most successful application domains of TIR, where models can solve complex mathematical problems by integrating computational tools.

### ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving

> ToRA is a series of tool-integrated reasoning agents developed by Microsoft Research, specifically designed to solve challenging mathematical problems. Through interaction with tools, ToRA can solve complex mathematical problems requiring multi-step reasoning, significantly outperforming traditional pure language models.
> 
> - Authors: Yue Zhang, Leyang Cui, Daya Guo, Zheng Chen, Qingxing Cao, Nigel Collier, Ting Liu, Ruihua Song, Furu Wei
> - Publication Date: September 2023
> - Link: [https://arxiv.org/abs/2309.17452](https://arxiv.org/abs/2309.17452)
> - Project Page: [https://microsoft.github.io/ToRA/](https://microsoft.github.io/ToRA/)

### START: Self-taught Reasoner with Tools

> START is a novel tool-integrated long Chain-of-Thought reasoning LLM proposed by the Alibaba research team, which significantly enhances reasoning capabilities through two key technologies (Hint-infer and Hint-RFT). START can perform complex computations, self-checking, explore diverse methods, and self-debugging, thereby addressing the limitations of traditional LRMs.
> 
> - Authors: Chengpeng Li, Mingfeng Xue, Zhenru Zhang, Jiaxi Yang, Beichen Zhang, Xiang Wang, Bowen Yu, Binyuan Hui, Junyang Lin, Dayiheng Liu
> - Publication Date: March 2025
> - Link: [https://arxiv.org/abs/2503.04625](https://arxiv.org/abs/2503.04625)

## 🎨 Multimodal and Visual Reasoning

---

TIR research in the multimodal and visual reasoning domain focuses on how to combine visual information with language reasoning, enhancing the reasoning capabilities of multimodal models through tools.

### VisuoThink: Empowering LVLM Reasoning with Multimodal Tree Search

> VisuoThink is a novel framework that seamlessly integrates visuospatial and linguistic domains, achieving multimodal slow thinking through look-ahead tree search. Inspired by the mechanisms of slow thinking in human cognition, this method enables models to perform progressive visual-textual reasoning and significantly enhances reasoning capabilities through inference-time scaling.
> 
> - Authors: Yikun Wang, Siyin Wang, Qinyuan Cheng, Zhaoye Fei, Liang Ding, Qipeng Guo, Dacheng Tao, Xipeng Qiu
> - Publication Date: April 2025
> - Link: [https://arxiv.org/abs/2504.09130](https://arxiv.org/abs/2504.09130)

### Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models

> Visual Sketchpad uses sketching as a visual chain of thought for multimodal language models, enhancing the model's visual reasoning capabilities. By allowing models to generate and utilize visual sketches, this method enables models to better understand and solve problems involving spatial relationships and visual reasoning.
> 
> - Publication Date: June 2024
> - Link: [https://arxiv.org/abs/2406.09403](https://arxiv.org/abs/2406.09403)

## 🤖 General Reasoning and Agency

---

TIR research in the general reasoning and agency domain focuses on how to build intelligent agents that can flexibly use multiple tools to enhance the model's general reasoning capabilities.

### Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research

> Agentic Reasoning is a framework that enhances large language model reasoning by integrating external tool-using agents. Unlike conventional LLM-based reasoning approaches, which rely solely on internal inference, Agentic Reasoning dynamically engages web search, code execution, and structured reasoning-context memory to solve complex problems requiring deep research and multi-step logical deduction.
> 
> - Authors: Junde Wu, Jiayuan Zhu, Yuyuan Liu
> - Publication Date: February 2025
> - Link: [https://arxiv.org/abs/2502.04644](https://arxiv.org/abs/2502.04644)

### ReTool: Reinforcement Learning for Strategic Tool Use in LLMs

> ReTool uses reinforcement learning methods to optimize strategic tool use in LLMs, enabling models to learn when and how to effectively use tools to solve problems. Through reinforcement learning, models can dynamically select and use the most appropriate tools based on task requirements.
> 
> - Publication Date: April 2025
> - Link: [https://arxiv.org/abs/2504.11536](https://arxiv.org/abs/2504.11536)

## 📊 Evaluation and Benchmarks

---

Evaluation and benchmarks are crucial for measuring the effectiveness of TIR methods, providing standardized evaluation frameworks and datasets.

### VCBENCH: A Comprehensive Benchmark for Multimodal Mathematical Reasoning

> VCBENCH is a comprehensive benchmark for multimodal mathematical reasoning with explicit visual dependencies. This benchmark is specifically designed to evaluate model performance in tasks requiring visual information for mathematical reasoning.
> 
> - Publication Date: April 2025
> - Link: [https://paperswithcode.com/paper/2504.18589](https://paperswithcode.com/paper/2504.18589)

## 🔍 Related Resources

---

<!-- - [LLM Reasoning Survey](https://github.com/reasoning-survey/LLM-Reasoning-Papers) - A collection of papers related to reasoning in large language models -->
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM) - A collection of resources related to large language models
- [Awesome LVLM](https://github.com/Gary-code/Awesome-LVLM-paper) - A collection of papers related to large vision-language models

## 👥 Contributing

---

Contributions to this repository are welcome through Pull Requests or Issues! Please ensure that your contributions include complete paper information, including title, authors, publication date, link, etc.

## 📝 Citation

---

If you find this repository helpful for your research, please consider citing the relevant papers.

## License

This project is licensed under the [MIT License](LICENSE).