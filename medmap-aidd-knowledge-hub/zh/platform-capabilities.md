---
title: MedMap AIDD 平台能力详解
permalink: /zh/platform-capabilities.html
description: MedMap AIDD 技术能力总览，包括 DMTA、ADMET-AI、智能对接、Smart Optimize、强化学习、ADC 与 PK/PD 模拟。
---
<link rel="stylesheet" href="../assets/style.css">

# MedMap AIDD 平台能力详解

[返回中文首页](./) | [English](../en/platform-capabilities.html)

## 闭环 DMTA

MedMap AIDD 打通 Design–Make–Test–Analyze 闭环。每一轮实验数据都可以进入项目知识库，反哺下一轮分子设计。

## 分层设计管线

1. 输入 SMILES 或参考分子
2. 使用 MolGPT、REINVENT、Diffusion、RDKit 生成分子
3. 多样性逃逸与种子注入
4. RDKit 标准化与理化性质过滤
5. QSAR GNN / Chemprop 活性预测
6. ADMET-AI 与 Dock-AI 筛查
7. Smart Optimize 与 FTO 预筛

## ADMET-AI

MedMap ADMET-AI 提供 42 个端点的机器学习预测，覆盖吸收、代谢、排泄与毒性。相比简单规则代理，它可提供 hERG、AMES、DILI、HLM、Caco-2 与 CYP 面板等专门预测。

## 智能分子对接

Docking 微服务可自动识别配体类型，并选择合适的 box size、exhaustiveness 与 scoring weights，用于 fragment、lead-like、drug-like、macrocycle、PPI inhibitor 和带电/极性分子等场景。

## 强化学习优化

AIDD-RL 模块结合生成探索、多目标奖励、不确定性控制与经验记忆，把计算资源集中到低风险、高潜力、可解释的候选分子上。

## ADC 拓展模块

平台还包含 ADC 设计能力，包括 CQA 评分、缺陷驱动优化、临床成功概率预测、linker 生成、ADC 知识图谱和 ADC 三室 PK/PD 模拟。

<script type="application/ld+json">
{"@context":"https://schema.org","@type":"TechArticle","headline":"MedMap AIDD 平台能力详解","keywords":"MedMap AIDD, AI药物研发, ADMET-AI, docking, DMTA, ADC, PKPD simulation","inLanguage":"zh-CN"}
</script>
