---
title: An Exponential Scale Mixture Model for Metatranscriptomics Data with Application to Inflammatory Bowel Disease
title_zh: 一种用于宏转录组数据的指数尺度混合模型及其在炎症性肠病中的应用
authors: "Kim, H., Ma, L."
date: 2026-05-15
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.15.725552v1.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 应用于炎症性肠病的长元转录组数据分析
tldr: 针对宏转录组数据标准化丰度处理的局限，本研究提出一种基于指数尺度混合分布的新型建模框架。该方法整合DNA丰度校正基因组潜力，并利用左截断处理零值及混合先验应对稀疏性。在炎症性肠病数据集应用中，该模型识别出传统方法漏检的差异表达基因，为理解菌群失调提供了更灵敏的统计工具。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有的宏转录组分析方法在处理标准化丰度、数据稀疏性及转换假设方面存在不足。
method: 提出一种基于指数尺度混合分布的框架，结合DNA丰度校正、随机效应及左截断零值处理。
result: 该模型在IBD数据集中发现了传统高斯方法无法识别的候选基因，且估算的效应值更大。
conclusion: 该模型为宏转录组差异表达分析提供了更有效的统计方案，有助于揭示疾病相关的转录模式。
---

## 摘要
宏转录组（MTX）测序能够分析微生物群落中的基因表达，为将遗传潜力与功能活性联系起来提供了框架。然而，标准流程报告的是归一化丰度而非原始计数，这限制了基于计数的 RNA-seq 方法的使用，而基于高斯分布的替代方案则依赖于通常不太适用于 MTX 数据的转换和假设。我们提出了一种用于 MTX 数据差异表达分析的新建模框架，该框架基于指数分布的尺度混合，整合了 DNA 丰度以调整基因组潜力，容纳了受试者特有的随机效应，将零值视为左删失，并采用混合先验来处理极度稀疏性。应用于 IBDMDB 多组学队列时，不同模型之间的差异表达结果存在显著差异，包括采用不同伪计数选择的高斯方法。我们的方法识别出了一组现有高斯方法未检测到的独特候选基因子集；这些基因可能为深入理解与炎症性肠病菌群失调相关的转录组模式提供有用的线索。我们模型估计的菌群失调效应方向与基于高斯的方法一致，而我们模型的效应大小在绝对值上往往更大。

## Abstract
Metatranscriptomic (MTX) sequencing enables profiling of gene expression across microbial communities, providing a framework for linking genetic potential with functional activity. However, standard pipelines report normalized abundances rather than raw counts, limiting the use of count-based RNA-seq methods, while Gaussian-based alternatives rely on transformations and assumptions that are often poorly suited to MTX data. We propose a new modeling framework for differential expression analysis of MTX data, built on a scale mixture of exponential distributions, that incorporates DNA abundance to adjust for genomic potential, accommodates subject-specific random effects, treats zeros as left-censored, and employs a mixture prior to handle extreme sparsity. Applied to the IBDMDB multi-omics cohort, differential expression results vary substantially across models, including among Gaussian approaches with different pseudocount choices. Our approach identifies a distinct subset of candidate genes not detected by existing Gaussian methods; these may provide useful leads toward a novel understanding of transcriptomic patterns associated with dysbiosis in inflammatory bowel disease. Estimated dysbiosis effect directions are consistent between our model and Gaussian-based approaches, while effect sizes from our model tend to be larger in absolute value.