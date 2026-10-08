# IBDer Research / IBDer 开放调研

Open, traceable research for people living with inflammatory bowel disease.

面向 IBD 患者的开放、可追溯调研。

## What belongs here / 这里发布什么

This repository contains topic reviews, research methods, evidence maps, and source indexes. It does not provide diagnosis or individualized treatment advice.

本仓库用于发布主题调研、研究方法、证据地图和来源索引，不提供诊断或个体化治疗建议。

Every publication must make its question, sources, search date, evidence types, uncertainty, and review state visible. Personal experience may help define a question, but it must not be presented as universal clinical evidence.

每份调研都必须明确研究问题、来源、检索日期、证据类型、不确定性和审阅状态。个人经验可以帮助提出问题，但不能被表述为普遍适用的临床证据。

## Publication states / 发布状态

- `Draft`：开放讨论，尚未完成独立审阅。
- `Reviewed`：已审阅来源可追溯性、范围和不确定性表达；不代表临床认可。
- `Superseded`：已由更新版本替代，仅为保持历史可追溯性而保留。

## Repository structure / 仓库结构

```text
research/
├── topics/                 # Published topic reviews / 主题调研
├── templates/              # Authoring templates / 写作模板
├── methodology/            # Search and review methods / 检索与审阅方法
├── catalog/                # Machine-readable index / 机器可读索引
└── sources/                # Shared source metadata / 公共来源元数据
```

Start with [`templates/topic-review.md`](templates/topic-review.md). Add the publication to [`catalog/research.yml`](catalog/research.yml) when it is ready for review.

请从 [`templates/topic-review.md`](templates/topic-review.md) 开始写作。调研可以进入审阅阶段时，请将其加入 [`catalog/research.yml`](catalog/research.yml)。

## Reuse / 复用

Original IBDer research is intended to be released under CC BY 4.0. Third-party sources remain subject to their own terms. Each publication must distinguish original analysis from quoted or externally licensed material.

IBDer 的原创调研计划采用 CC BY 4.0 发布。第三方来源仍受其自身条款约束；每份调研必须明确区分原创分析、引用内容和外部许可材料。

