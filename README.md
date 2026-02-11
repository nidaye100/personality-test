# 🧠 性格底色深度测评 | Personality Background Depth Test

[中文](#zh) | [English](#en) | [日本語](#jp)

---

<a id="zh"></a>

## 🇨🇳 中文说明

### 1. 功能简介
这是一个基于网页的纯算法性格测评工具。通过 30 道精心设计的题目，从五个关键维度分析用户的性格底色。项目完全运行于前端，不依赖 AI 接口，确保了测评结果的稳定性和极速响应。

### 2. 计算原理与心理学支撑
本系统采用学术界公认的 **“大五人格模型”（Big Five Personality Traits / OCEAN）** 为核心架构：



* **维度划分**：外向性 (E)、尽责性 (C)、情绪性 (N)、宜人性 (A)、开放性 (O)。
* **计分公式**：采用**维度加权累加法**。每个维度包含 6 道题目，选项分值分布为 `[-1, 1, 3]`。
* **判定逻辑**：
    $$Score_{dim} = \sum_{i=1}^{6} Score_{option}$$
    系统设定了显著特征阈值（Score > 6）。只有当某一维度得分超过阈值时，才会被判定为该性格特征。

### 3. 交流与反馈
欢迎加入项目交流群进行反馈或获取最新动态：
* **QQ 群号**：`425032548`

### 4. 声明
本自目前处于**试验阶段**，测评结果仅供个人参考。**请勿用于任何商业用途。**

---

<a id="en"></a>

## 🇺🇸 English Description

### 1. Introduction
A pure-algorithm-based personality assessment tool analyzing 5 key dimensions via 30 designed questions. 100% frontend execution for privacy and speed.

### 2. Methodology & Psychology
Built upon the **"Big Five Personality Traits" (OCEAN)** model:
* **Scoring**: Uses weighted summation. Each trait has 6 questions ($Score \in [-1, 1, 3]$).
* **Logic**: 
    $$Score_{dim} = \sum_{i=1}^{6} Score_{option}$$
    A threshold ($Score > 6$) identifies significant traits.

### 3. Community
* **QQ Group**: `425032548`

### 4. Disclaimer
**Experimental stage.** For personal reference only. **Commercial use is strictly prohibited.**

---

<a id="jp"></a>

## 🇯🇵 日本語説明

### 1. 機能概要
アルゴリズムに基づいた性格診断ツール。30の質問を通じて、5つの主要な次元から性格を分析します。

### 2. 計算原理と心理学的背景
**「ビッグファイブ（特性5因子モデル）」** を採用しています：
* **計算式**: **重み付け累積法**。各次元6問、スコアは `[-1, 1, 3]` です。
* **ロジック**: 
    $$Score_{dim} = \sum_{i=1}^{6} Score_{option}$$
    しきい値（Score > 6）に基づき、顕著な特性を抽出します。

### 3. コミュニティ
* **QQグループ**: `425032548`

### 4. 免責事項
**試験段階**のプロジェクトです。診断結果は参考用です。**商用利用は固く禁止されています。**
