---
title: "scLASER: a robust framework for simulating and detecting time-dependent single-cell dynamics in longitudinal studies"
title_zh: scLASER：一个用于在纵向研究中模拟和检测随时间变化的单细胞动态的稳健框架
authors: "Vanderlinden, L. A., Vargas, J., Inamo, J., Young, J., Wang, C., Zhang, F."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.04.722712v2.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 应用于炎症性肠病数据集
tldr: scLASER是一个专为纵向单细胞临床研究设计的稳健框架，旨在模拟和检测随时间变化的细胞动力学。它通过分析细胞邻域动态，克服了传统聚类方法在处理稀有细胞类型和非线性模式时的局限性。该框架不仅能识别复杂的细胞轨迹，还能进行效能评估，为优化临床研究设计和理解疾病进展提供了有力工具。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有的纵向单细胞研究在建模时间表型变化和估算统计效能方面存在局限，难以捕捉复杂的细胞动态。
method: 提出了scLASER框架，通过检测细胞邻域动态来识别时间相关的细胞变化，并支持纵向单细胞数据集的模拟。
result: 在IBD和COVID-19数据分析中，scLASER展现出比传统方法更高的灵敏度，成功识别出关键的细胞轨迹和免疫活动轴。
conclusion: scLASER为纵向单细胞分析提供了高效的检测与模拟方案，显著提升了对复杂细胞动力学的识别能力并优化了研究设计。
---

## 摘要
纵向单细胞临床研究能够追踪个体内的细胞动态，但用于建模时间表型变化和估计统计效能的方法仍然有限。我们提出了 scLASER，这是一个用于检测随时间变化的细胞邻域动态并模拟纵向单细胞数据集以进行效能估计的框架。在各项基准实验中，scLASER 表现出比传统基于聚类的方法更高的一致敏感性，在稀有细胞类型和非线性时间模式方面的提升尤为显著。在炎症性肠病（95,813 个细胞，38 名患者）的应用中，揭示了具有高细胞类型辨别力（AUC > 0.92）的治疗响应性 NOTCH3+ 基质轨迹；而对 COVID-19 数据（188,181 个细胞，84 名患者）的分析则识别出疾病进展过程中 T 细胞活性的三个不同轴（细胞毒性效应子、NK 免疫受体信号传导和干扰素刺激基因程序）。scLASER 实现了稳健的纵向单细胞分析和研究设计的优化。简述：一个新的框架可检测随时间变化的细胞动态，并为纵向临床单细胞研究提供效能估计。

## Abstract
Longitudinal single-cell clinical studies enable tracking within-individual cellular dynamics, but methods for modeling temporal phenotypic changes and estimating power remain limited. We present scLASER, a framework detecting time-dependent cellular neighborhood dynamics and simulating longitudinal single-cell datasets for power estimation. Across benchmark experiments, scLASER shows consistently higher sensitivity than traditional cluster--based approaches, with particularly pronounced gains in rare cell types and non-linear temporal patterns. Applications to inflammatory bowel disease (95,813 cells, 38 patients) reveal treatment-responsive NOTCH3+ stromal trajectories with high cell type discrimination (AUC > 0.92), while analysis of COVID-19 data (188,181 cells, 84 patients) identifies three distinct axes of T cell activity (cytotoxic effector, NK immunoreceptor signaling, and interferon-stimulated gene programs) over disease progression. scLASER enables robust longitudinal single-cell analysis and optimization of study design.

TeaserA new framework detects time-dependent cellular dynamics and enables power estimation for longitudinal clinical single-cell studies.