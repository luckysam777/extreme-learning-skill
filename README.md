# Extreme Learning / 极限学习

<div align="center">

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/luckysam777/extreme-learning-skill)](https://github.com/luckysam777/extreme-learning-skill/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/luckysam777/extreme-learning-skill)](https://github.com/luckysam777/extreme-learning-skill/network)

[English](#english) · [简体中文](#简体中文) · [日本語](#日本語)

</div>

---

## English

### Description

An AI-powered deep learning method based on MIT pedagogy — master any domain from zero through **thinking model extraction**, **controversy mapping**, and **stress testing**.

### When To Use

- Rapidly learning a new field from scratch
- Analyzing textbooks, papers, lecture transcripts, or any professional materials
- Building systematic expert-level thinking frameworks
- High-intensity practice to verify true understanding
- Triggered by: `extreme learning`, `deep mastery`, `rapid learning`, `MIT method`, `thinking model`, `knowledge map`

### Workflow

#### Phase 1: Knowledge Injection (Context Building)
Ask the user to upload core materials: textbooks, seminal papers, conference proceedings, or transcribed lectures. Preprocess and build a local knowledge base.

#### Phase 2: Thinking Pattern Extraction
Analyze the uploaded materials. Identify and summarize the **5 core thinking models** or underlying logic that top experts in the field agree on.

Output: A thinking framework diagram — helps the user see problems through an expert's lens, not memorize definitions.

#### Phase 3: Map of Controversy
Search for academic conflicts or industry debates within the materials.

Output: A knowledge domain map with three zones:
- **Consensus zone** — established knowledge
- **Controversy zone** — active debates with opposing arguments
- **Frontier zone** — open, unsolved questions

List **3 core debate points** and拆解 the most representative arguments on each side.

#### Phase 4: Stress Test & Iteration
Generate **10 high-discrimination questions** (focus on logical application, not terminology).

Interactive flow:
1. Present the 10 questions
2. User answers them
3. Socratic follow-up: "What logic did you miss?" · "Why doesn't this inference hold?"
4. Iterate until user can perfectly explain all 10 questions

### Agent Prompt Fragment

> "You are a stern and wise MIT mentor. Your goal is not to give direct answers. Instead, you will first use the materials I provide to extract expert thinking models and map core controversies in the field. Then you will relentlessly torment me with 10 extremely challenging questions until I truly master the underlying logic of this domain."

### Install

```bash
git clone https://github.com/luckysam777/extreme-learning-skill.git
cp -r extreme-learning-skill/extreme-learning ~/.claude/skills/
```

---

## 简体中文

### 技能描述

一个基于 **MIT 教学法** 的 AI 深度学习技能，帮助用户在极短时间内从零掌握任意领域的底层逻辑与深度见解。

通过**思维模型构建**、**争议点对撞**和**极限压力测试**三大核心机制，实现真正的深度掌握。

### 适用场景

- 想快速入门一个陌生领域
- 拥有教材、论文、会议记录等学习材料
- 希望构建系统性的专家思维框架而非死记硬背
- 需要通过高强度练习检验和巩固真正理解
- 触发词：`极限学习`、`深度掌握`、`快速学习`、`MIT学习法`、`思维模型构建`、`知识地图`

### 工作流程

#### 第一阶段：知识注入 (Context Building)
要求用户上传核心学习材料：教材、顶级论文、会议记录或录音转译稿。Agent 预处理并建立本地知识库。

#### 第二阶段：底层逻辑萃取 (Thinking Pattern Extraction)
分析资料，识别并总结该领域顶级专家公认的 **5 个核心思维模式**或底层逻辑。

输出：思维框架图，帮助用户以专家视角看待问题，而非死记硬背定义。

#### 第三阶段：争议地图构建 (Map of Controversy)
检索资料中存在的学术冲突或行业争议，列出 **3 个核心争论点**，并拆解双方最具代表性的论据。

输出：知识领域地图（包含共识区、争议区、前沿未解区）

#### 第四阶段：极限压力自测 (Stress Test & Iteration)
基于资料生成 **10 道具有深度鉴别力的考察题**（侧重逻辑应用而非名词解释）。

交互流程：
1. 呈现 10 道问题
2. 用户回答
3. 苏格拉底式追问：「你漏掉了什么逻辑？」、「为什么这个推论不成立？」
4. 迭代直至用户能完美解释所有 10 个问题

### Agent 提示词片段

> "你现在是一个严厉且睿智的 MIT 导师。你的目标不是直接给答案，而是通过调取我提供的资料，先帮我梳理出专家的思维模型和领域内的核心争议，最后通过 10 个极具挑战性的问题不断'折磨'我，直到我真正掌握该领域的底层逻辑。"

### 安装方式

```bash
git clone https://github.com/luckysam777/extreme-learning-skill.git
cp -r extreme-learning-skill/extreme-learning ~/.claude/skills/
```

---

## 日本語

### 説明

MIT 教学法に基づいた AI 深度学習スキル。**思考モデル抽出**、**論争マッピング**、**ストレステスト**により、ゼロから任意の分野の根本論理を短時間で習得します。

### 使用場面

- 新規分野の急速な習得
- 教科書、論文、レクチャー録画などの分析
- 専門家レベルの思考フレームワーク構築
- 高強度練習による真の理解度の検証

### インストール

```bash
git clone https://github.com/luckysam777/extreme-learning-skill.git
cp -r extreme-learning-skill/extreme-learning ~/.claude/skills/
```

---

## Repository Structure / 仓库结构

```
extreme-learning-skill/
├── LICENSE
├── README.md              ← Bilingual homepage (EN + 中文 + 日本語)
├── README_zh.md            ← 简体中文完整版
├── extreme-learning/
│   ├── SKILL.md            ← Claude Code skill file
│   └── platforms/
│       └── claude-code/
│           └── extreme-learning/
│               └── SKILL.md
```

## Why This Works / 方法论原理

| 传统学习 | 极限学习 |
|---------|---------|
| 停留在"知道是什么" | 萃取"专家怎么思考" |
| 记忆定义和术语 | 构建思维模型和推理链 |
| 碎片化知识点 | 系统化知识地图 |
| 被动接受 | 主动压力测试 |

**True mastery requires application and reasoning, not recognition and recall.**

---

<div align="center">

⭐ Star this repo if it helped you learn better!

</div>