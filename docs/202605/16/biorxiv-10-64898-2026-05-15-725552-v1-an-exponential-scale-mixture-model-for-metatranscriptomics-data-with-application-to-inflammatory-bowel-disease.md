---
title: An Exponential Scale Mixture Model for Metatranscriptomics Data with Application to Inflammatory Bowel Disease
title_zh: 用于宏转录组数据的指数尺度混合模型及其在炎症性肠病中的应用
authors: "Kim, H., Ma, L."
date: 2026-05-15
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.15.725552v1.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 将宏转录组模型应用于炎症性肠病数据
tldr: 针对宏转录组数据标准化丰度而非原始计数的特点，本研究提出了一种基于指数尺度混合分布的新型建模框架。该方法整合了DNA丰度以校正基因组潜力，并有效处理了零值截断和极端稀疏性问题。在炎症性肠病（IBD）队列的应用中，该模型识别出了现有高斯方法无法检测到的候选基因，为理解肠道菌群失调提供了新的功能活性视角。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有的宏转录组分析方法难以处理非计数型标准化数据，且传统高斯模型在处理稀疏性和数据转换方面存在局限。
method: 提出一种基于指数尺度混合分布的模型，结合DNA丰度校正、随机效应处理及左截断零值建模来分析差异表达。
result: 在IBD数据集上，该模型不仅与高斯方法在效应方向上保持一致，还发现了更多独特的差异表达基因且效应值更大。
conclusion: 该模型为宏转录组差异表达分析提供了更精准的统计工具，有助于深入挖掘与炎症性肠病相关的微生物功能模式。
---

## 摘要
宏转录组（MTX）测序能够分析微生物群落中的基因表达，为将遗传潜力与功能活性联系起来提供了框架。然而，标准流程报告的是归一化丰度而非原始计数，这限制了基于计数的 RNA-seq 方法的使用，而基于高斯分布的替代方案则依赖于通常不太适用于 MTX 数据的转换和假设。我们提出了一种用于 MTX 数据差异表达分析的新建模框架，该框架建立在指数分布的尺度混合之上，结合了 DNA 丰度以调整基因组潜力，容纳了受试者特有的随机效应，将零值视为左截断，并采用混合先验来处理极度稀疏性。应用于 IBDMDB 多组学队列时，差异表达结果在不同模型之间存在显著差异，包括采用不同伪计数选择的高斯方法。我们的方法识别出了一组现有高斯方法未检测到的独特候选基因子集；这些基因可能为深入理解与炎症性肠病菌群失调相关的转录组模式提供有用的线索。我们的模型与基于高斯的方法在估计的菌群失调效应方向上是一致的，而我们模型的效应量在绝对值上往往更大。

## Abstract
Metatranscriptomic (MTX) sequencing enables profiling of gene expression across microbial communities, providing a framework for linking genetic potential with functional activity. However, standard pipelines report normalized abundances rather than raw counts, limiting the use of count-based RNA-seq methods, while Gaussian-based alternatives rely on transformations and assumptions that are often poorly suited to MTX data. We propose a new modeling framework for differential expression analysis of MTX data, built on a scale mixture of exponential distributions, that incorporates DNA abundance to adjust for genomic potential, accommodates subject-specific random effects, treats zeros as left-censored, and employs a mixture prior to handle extreme sparsity. Applied to the IBDMDB multi-omics cohort, differential expression results vary substantially across models, including among Gaussian approaches with different pseudocount choices. Our approach identifies a distinct subset of candidate genes not detected by existing Gaussian methods; these may provide useful leads toward a novel understanding of transcriptomic patterns associated with dysbiosis in inflammatory bowel disease. Estimated dysbiosis effect directions are consistent between our model and Gaussian-based approaches, while effect sizes from our model tend to be larger in absolute value.