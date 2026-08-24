# tech-slide-feynman

> 技术课件逐页深度学习法。七步流程 + 21种学习方法 + 三个强制验证机制，把一页技术PPT从"看不懂"干到"能讲给12岁小孩听"。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skill](https://img.shields.io/badge/Type-AI%20Skill-blue.svg)]()
[![Methods](https://img.shields.io/badge/Methods-21-green.svg)]()
[![Principles](https://img.shields.io/badge/Evidence-Based-Cognitive%20Science-orange.svg)]()

---

## 解决什么问题

学技术课件时最痛苦的三件事：

1. **看不懂** — PPT上每个字都认识，连起来不知道在说什么
2. **以为懂了** — 看完觉得"哦原来是这样"，跟别人讲时说两句就卡壳（流畅幻觉）
3. **学完就忘** — 没有验证，没有持久化，过两天全忘

这个skill用一套完整流程解决这三个问题。

## 核心机制

### 七步学习流程

```
1. Survey 浏览    → 30秒抓标题/分层/关键词
2. Question 提问  → 苏格拉底追问：这页讲什么？为什么需要？不懂在哪？
3. Translate 翻译 → 逐句术语→大白话（一句不漏）
4. Bridge 架桥    → 生活类比 + ASCII图解 + 词源拆解
5. Map 映射       → 代码位置 + 反模式 + 生产场景
6. Output 输出    → 费曼讲解 + 存笔记 + 主动回忆
7. Verify 验证    → 3分钟测验 + 理解度颜色卡片
```

> 跳过第3步=没真懂，跳过第5步反模式=会踩坑，跳过第7步=不知道自己懂没懂。

### 三个强制验证（任何页都不能跳过）

| 机制 | 做什么 | 解决什么痛点 |
|------|--------|------------|
| **反模式教学** | 每个概念配"常见错+为什么诱人+正确做法" | 戳破"我以为我懂了" |
| **3分钟测验** | 讲完立刻出3-5题，错题配三步诊断 | 验证真懂没懂 |
| **理解度颜色卡片** | 每个概念标🔴弱/🟡学习中/🟢掌握，存入笔记 | 学习进度可视化+持久化 |

### 21种方法工具箱

**理解类（4种）**：费曼技巧 · 逐句翻译法 · 词源拆解法 · 苏格拉底螺旋学习

**直觉类（4种）**：生活类比法 · ASCII图解法 · 表格对比法 · 口诀记忆法

**落地类（4种）**：代码映射法 · Bug驱动法 · 反模式教学法 · 学以致用发

**深挖类（3种）**：苏格拉底提问法 · 逆向工程法 · 知识缺口诊断法

**验证类（3种）**：3分钟测验法 · 理解度颜色卡片法 · 错题三步诊断法

**记忆类（2种）**：主动回忆法 · 间隔重复法

**元方法（1种）**：渐进式降级法

## 方法来源（基于认知科学）

| 方法 | 来源 | 依据 |
|------|------|------|
| 费曼技巧 | Richard Feynman | "如果你不能简单解释，就说明你没真正理解" |
| SQ3R | Francis Robinson, 1946 | 结构化阅读法，浏览→提问→阅读→复述→复习 |
| 主动回忆 | Karpicke & Blunt, *Science*, 2011 | 检索练习效果是被动重读的3倍+ |
| 间隔重复 | Ebbinghaus, 1885 | 遗忘曲线，在遗忘临界点复习效率最高 |
| 生成效应 | Slamecka & Graf, 1978 | 自己生成答案比被动看答案记忆更深 |
| 适度困难 | Bjork, 1994 | 感觉轻松=浅层学习，感觉困难=深层学习 |
| 反模式教学 | learn-anything | 讲清楚常见错+为什么诱人，比只讲正确做法更有效 |
| 理解度颜色卡片 | mattdiep15/feynman | 知识图谱节点着色，学习进度可视化 |
| 刻意练习+渐隐脚手架 | learning-opportunities, Dr. Cat Hicks | 从高支持到低支持，逐步培养独立能力 |

## 快速开始

### 安装

将本仓库复制到你的 AI Agent skills 目录：

```bash
# 豆包 / 通用 Agent
git clone https://github.com/VonHai/tech-slide-feynman.git ~/.your-agent/skills/tech-slide-feynman

# Claude Code
git clone https://github.com/VonHai/tech-slide-feynman.git ~/.claude/skills/tech-slide-feynman

# Codex
git clone https://github.com/VonHai/tech-slide-feynman.git ~/.codex/skills/tech-slide-feynman
```

### 使用

跟 AI 说以下任一触发词：

- "讲解这页PPT"
- "第X页费曼解释"
- "直观图解这页"
- "逐句翻译这页"
- "测验我懂了吗"
- "这页讲什么"

AI 自动走七步流程，讲解内容+测验+颜色卡片存入你的笔记。

**零配置，开箱即用。**

## 项目结构

```
tech-slide-feynman/
├── SKILL.md                    # 核心：七步流程+21方法概览+检查清单（95行）
└── references/
    ├── methods.md              # 21种方法详细说明+TOC（342行）
    └── templates.md            # 18项检查清单+4套提示词模板+完整示例+复习策略（358行）
```

采用渐进式披露设计：SKILL.md 保持精简，详细内容按需加载。

## 适合谁 / 不适合谁

**适合**：
- 学技术课程（在线课程/技术书籍/技术文档/会议PPT）
- 准备技术面试需要复习概念
- 用 Obsidian/Notion 做技术笔记
- 教别人技术前需要自己先搞懂

**不适合**：
- 学英语/历史/纯文科（技术课件专属）
- 简单概念（用它太重了，3-5步即可）
- 纯实操教程（以动手为主，不是以理解概念为主）

## 设计原则

1. **验证优先** — 不讲完就完了，必须测验验证+颜色卡片持久化
2. **反模式强制** — 每个概念必须讲常见错+为什么诱人，知道坑在哪比知道路在哪更重要
3. **渐进式降级** — 用户说不懂时，技术定义→类比→图解→口诀逐级降级，每次必须换方法
4. **证据驱动** — 所有方法基于认知科学研究，不是拍脑袋
5. **零配置** — 丢进skills目录就能用，不需要API key、不需要安装依赖

## License

MIT
