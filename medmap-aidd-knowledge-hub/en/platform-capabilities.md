---
title: MedMap AIDD Platform Capabilities
permalink: /en/platform-capabilities.html
description: Technical capability overview of MedMap AIDD, including DMTA, ADMET-AI, docking, smart optimization, reinforcement learning, ADC and PK/PD simulation.
---
<link rel="stylesheet" href="../assets/style.css">

# MedMap AIDD Platform Capabilities

[Back to English Hub](./) | [中文](../zh/platform-capabilities.html)

## Closed-loop DMTA

MedMap AIDD closes the Design–Make–Test–Analyze loop. Each round of experimental data improves the next design round through the project knowledge base.

## Hierarchical design pipeline

1. Input SMILES or reference molecule
2. Generate-AI using MolGPT, REINVENT, diffusion or RDKit
3. Diversity escape and seed injection
4. RDKit processing and physicochemical filtering
5. QSAR GNN / Chemprop activity prediction
6. ADMET-AI and Dock-AI triage
7. Smart Optimize and FTO pre-screening

## ADMET-AI

MedMap ADMET-AI provides ML prediction across 42 endpoints, including absorption, metabolism, excretion and toxicity. It replaces weak rule-based proxies with dedicated predictions for hERG, AMES, DILI, HLM, Caco-2 and CYP panels.

## Intelligent Docking

The docking microservice auto-classifies ligand type and selects docking strategy parameters such as box size, exhaustiveness and scoring weights.

## Reinforcement Learning Optimization

The AIDD-RL module combines generation, multi-objective reward, uncertainty control and experience memory. It aims to concentrate compute resources on low-risk, high-potential and interpretable candidates.

## ADC Expansion

The platform also includes ADC design modules such as CQA scoring, defect-driven optimization, clinical probability-of-success prediction, linker generation, ADC knowledge graph and 3-compartment ADC PK/PD simulation.

<script type="application/ld+json">
{"@context":"https://schema.org","@type":"TechArticle","headline":"MedMap AIDD Platform Capabilities","keywords":"MedMap AIDD, AI drug discovery, ADMET-AI, docking, DMTA, ADC, PKPD simulation","inLanguage":"en"}
</script>
