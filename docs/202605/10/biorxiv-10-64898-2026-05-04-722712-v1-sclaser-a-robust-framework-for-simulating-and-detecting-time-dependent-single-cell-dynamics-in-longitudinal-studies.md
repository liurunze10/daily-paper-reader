---
title: "scLASER: a robust framework for simulating and detecting time-dependent single-cell dynamics in longitudinal studies"
title_zh: scLASER：一种用于在纵向研究中模拟和检测随时间变化的单细胞动态的稳健框架
authors: "Vanderlinden, L. A., Vargas, J., Inamo, J., Young, J., Wang, C., Zhang, F."
date: 2026-05-07
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.04.722712v1.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 在炎症性肠病中的应用揭示了治疗响应性的间质细胞轨迹
tldr: 纵向单细胞临床研究在追踪个体细胞动态方面具有重要意义，但现有方法在模拟时间表型变化和评估统计效能方面存在局限。本文提出scLASER框架，能够检测随时间变化的细胞邻域动态并模拟纵向单细胞数据集。实验证明其在识别稀有细胞类型和非线性模式方面优于传统方法，并成功应用于炎症性肠病和新冠肺炎研究，为纵向单细胞分析和实验设计优化提供了有力工具。
source: biorxiv
selection_source: fresh_fetch
motivation: 针对纵向单细胞研究中缺乏有效模拟时间表型变化和评估统计效能的方法这一现状，开发了scLASER框架。
method: 该框架通过检测时间依赖性的细胞邻域动态，并提供纵向单细胞数据集的模拟功能，以支持效能评估。
result: scLASER在基准测试中表现出比传统聚类方法更高的灵敏度，并成功识别出肠病中的基质轨迹和新冠肺炎中的T细胞活动轴。
conclusion: scLASER为纵向单细胞数据的稳健分析和临床研究设计的优化提供了一个高效且高灵敏度的解决方案。
---

## 摘要
纵向单细胞临床研究能够追踪个体内的细胞动态，但用于建模时间表型变化和估计统计效能的方法仍然有限。我们提出了 scLASER，这是一个用于检测随时间变化的细胞邻域动态并模拟纵向单细胞数据集以进行效能估计的框架。在各项基准实验中，scLASER 表现出比传统基于聚类的方法更高且更一致的灵敏度，在稀有细胞类型和非线性时间模式方面的提升尤为显著。在炎症性肠病（95,813 个细胞，38 名患者）的应用中，揭示了具有高细胞类型辨别力（AUC > 0.92）的治疗响应性 NOTCH3+ 基质轨迹；而在对 COVID-19 数据（188,181 个细胞，84 名患者）的分析中，识别出了疾病进展过程中 T 细胞活动的三个不同轴（细胞毒性效应子、NK 免疫受体信号传导和干扰素刺激基因程序）。scLASER 能够实现稳健的纵向单细胞分析并优化研究设计。

## Abstract
Longitudinal single-cell clinical studies enable tracking within-individual cellular dynamics, but methods for modeling temporal phenotypic changes and estimating power remain limited. We present scLASER, a framework detecting time-dependent cellular neighborhood dynamics and simulating longitudinal single-cell datasets for power estimation. Across benchmark experiments, scLASER shows consistently higher sensitivity than traditional cluster--based approaches, with particularly pronounced gains in rare cell types and non-linear temporal patterns. Applications to inflammatory bowel disease (95,813 cells, 38 patients) reveal treatment-responsive NOTCH3+ stromal trajectories with high cell type discrimination (AUC > 0.92), while analysis of COVID-19 data (188,181 cells, 84 patients) identifies three distinct axes of T cell activity (cytotoxic effector, NK immunoreceptor signaling, and interferon-stimulated gene programs) over disease progression. scLASER enables robust longitudinal single-cell analysis and optimization of study design.