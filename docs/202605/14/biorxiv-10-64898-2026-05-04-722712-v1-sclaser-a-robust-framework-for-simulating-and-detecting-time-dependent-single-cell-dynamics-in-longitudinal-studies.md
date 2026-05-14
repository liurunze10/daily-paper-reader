---
title: "scLASER: a robust framework for simulating and detecting time-dependent single-cell dynamics in longitudinal studies"
title_zh: scLASER：一个用于在纵向研究中模拟和检测随时间变化的单细胞动态的稳健框架
authors: "Vanderlinden, L. A., Vargas, J., Inamo, J., Young, J., Wang, C., Zhang, F."
date: 2026-05-07
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.04.722712v1.full.pdf"
tags: ["query:ros-mp"]
score: 6.5
evidence: 应用于炎症性肠病数据集
tldr: 纵向单细胞临床研究对于追踪个体内的细胞动态至关重要，但现有建模和效能评估方法有限。本文提出scLASER框架，通过检测细胞邻域动态并模拟纵向数据集，实现了对时间依赖性细胞变化的稳健分析。在基准测试中，scLASER在稀有细胞类型和非线性模式检测上优于传统方法，并成功应用于炎症性肠病和新冠肺炎研究，揭示了关键的细胞轨迹和免疫反应轴。
source: biorxiv
selection_source: fresh_fetch
motivation: 针对纵向单细胞临床研究中缺乏有效建模时间表型变化及评估统计效能工具的问题。
method: 开发了scLASER框架，利用细胞邻域动态检测和纵向单细胞数据模拟技术来识别时间依赖性特征。
result: 实验表明scLASER在检测灵敏度上显著优于传统聚类方法，并成功识别出肠病治疗响应轨迹及新冠肺炎中的T细胞活动轴。
conclusion: scLASER为纵向单细胞分析提供了稳健的工具，有助于优化临床研究设计并深入理解疾病进展中的细胞动态。
---

## 摘要
纵向单细胞临床研究能够追踪个体内的细胞动态，但用于建模时间表型变化和估计统计效能的方法仍然有限。我们提出了 scLASER，这是一个检测随时间变化的细胞邻域动态并模拟纵向单细胞数据集以进行效能估计的框架。在各项基准实验中，scLASER 表现出比传统基于聚类的方法更高的一致敏感性，特别是在稀有细胞类型和非线性时间模式方面增益显著。在炎症性肠病（95,813 个细胞，38 名患者）的应用中，揭示了具有高细胞类型辨别力（AUC > 0.92）的治疗响应性 NOTCH3+ 基质轨迹；而对 COVID-19 数据（188,181 个细胞，84 名患者）的分析则识别出疾病进展过程中 T 细胞活性的三个不同轴（细胞毒性效应器、NK 免疫受体信号传导和干扰素刺激基因程序）。scLASER 实现了稳健的纵向单细胞分析和研究设计的优化。核心提示：一个新的框架可检测随时间变化的细胞动态，并为纵向临床单细胞研究提供效能估计。

## Abstract
Longitudinal single-cell clinical studies enable tracking within-individual cellular dynamics, but methods for modeling temporal phenotypic changes and estimating power remain limited. We present scLASER, a framework detecting time-dependent cellular neighborhood dynamics and simulating longitudinal single-cell datasets for power estimation. Across benchmark experiments, scLASER shows consistently higher sensitivity than traditional cluster--based approaches, with particularly pronounced gains in rare cell types and non-linear temporal patterns. Applications to inflammatory bowel disease (95,813 cells, 38 patients) reveal treatment-responsive NOTCH3+ stromal trajectories with high cell type discrimination (AUC > 0.92), while analysis of COVID-19 data (188,181 cells, 84 patients) identifies three distinct axes of T cell activity (cytotoxic effector, NK immunoreceptor signaling, and interferon-stimulated gene programs) over disease progression. scLASER enables robust longitudinal single-cell analysis and optimization of study design.

TeaserA new framework detects time-dependent cellular dynamics and enables power estimation for longitudinal clinical single-cell studies.