---
title: "Single-cell, label-free morphology profiling of iPSC-derived microglia reveals dynamic state transitions"
title_zh: iPSC 来源的小胶质细胞单细胞、无标记形态分析揭示了动态状态转换
authors: "Chen, T., Li, X., Dolga, A. M."
date: 2026-04-29
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.28.721424v1.full.pdf"
tags: ["query:ros-mp"]
score: 6.0
evidence: 追踪小胶质细胞（脑巨噬细胞）在炎症反应中的状态转变和形态变化
tldr: 本研究针对人类iPSC衍生小胶质细胞（iMGLs）形态表征受限于荧光标记和粗略分类的问题，开发了一种无标记单细胞追踪流程。通过结合活细胞成像与Cellpose-SAM分割技术，研究揭示了iMGLs在炎症刺激下的动态形态演变。研究发现，不同刺激诱导了连续形态空间中的特定分布模式，而非简单的离散状态切换，为理解小胶质细胞的功能状态提供了高维度的形态学视角。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统小胶质细胞形态分析依赖荧光标记和终点成像，难以捕捉动态且连续的状态转换。
method: 开发了结合活细胞成像、Cellpose-SAM分割及CellProfiler特征提取的无标记单细胞形态分析流程。
result: 发现iMGLs在炎症刺激下呈现出四种主要形态状态，且不同刺激在连续形态空间中具有独特的分布模式和纹理特征。
conclusion: 小胶质细胞通过在连续形态景观中的分级占用而非离散状态切换来响应炎症，形态重塑与特定功能激活密切相关。
---

## 摘要
小胶质细胞在响应环境和炎症信号时会呈现出反映其功能状态的多样形态。然而，表征人类 iPSC 来源的小胶质细胞（iMGLs）的这些形态变化仍受限于对荧光标记、终点成像以及粗略分类（如分枝状与阿米巴状）的依赖。在此，我们开发了一种结合活细胞成像、Cellpose-SAM 分割和基于 CellProfiler 特征提取的无标记流程，以在单细胞分辨率下随时间追踪 iMGL 的形态。将该框架应用于 LPS 和 IFNγ 共同刺激的 24 小时时间序列，揭示了快速且瞬时的形态重塑，反应在 2-4 小时内达到峰值，随后部分减弱。在单细胞分辨率下，四种形态状态捕捉到了主要的变异轴，共同刺激驱动了向单一“铺展状态”（Spread state）的显著重新分布。将分析扩展到单个炎症刺激（LPS、IFNγ、IL-1β、IL-6 和 TNF）揭示了状态组成中梯度但重叠的转变，其中 IFNγ 诱导的反应最强，而 IL-1β 的影响最小。重要的是，仅靠状态层面的变化不足以区分特定刺激的反应。相反，单细胞密度图揭示了共享形态景观中截然不同的占据模式。此外，纹理复杂度提供了一个独立的特征层，进一步区分了不同处理，表明刺激身份是由超出离散状态分配的连续、高维形态特征所代表的。将形态与功能联系起来，IFNγ 产生了最大的形态重新分布，也是唯一在 24 小时显著提高细胞内 ROS 的刺激，表明形态重塑和氧化还原激活可以由特定的炎症信号协同启动。总之，这些发现支持了一个模型，即小胶质细胞通过梯度占据连续的形态景观来响应炎症刺激，每种刺激产生一种超出离散状态分配的特定刺激占据模式。

## Abstract
In response to environmental and inflammatory cues, microglia adopt diverse morphologies reflecting their functional state. However, characterizing these morphological alterations in human iPSC-derived microglia (iMGLs) remains limited by reliance on fluorescent labeling, endpoint imaging, and coarse categorical classifications (e.g., ramified vs amoeboid states). Here, we developed a label-free pipeline combining live-cell imaging, Cellpose-SAM segmentation, and CellProfiler-based feature extraction to track iMGL morphology at single-cell resolution over time. Applying this framework to a 24-hour time course of LPS and IFN{gamma} co-stimulation revealed rapid and transient morphological remodeling, with responses peaking within 2-4 hours and partially attenuating thereafter. At single-cell resolution, four morphological states captured the major axes of variation, with co-stimulation driving a pronounced redistribution toward a single "Spread state". Extending the analysis to individual inflammatory stimuli (LPS, IFN{gamma}, IL-1{beta}, IL-6, and TNF) revealed graded but overlapping shifts in state composition, with IFN{gamma} inducing the strongest response, whereas IL-1{beta} showed minimal effects. Importantly, state-level changes alone were insufficient to distinguish stimulus-specific responses. Instead, single-cell density mapping revealed distinct occupancy patterns within a shared morphological landscape. In addition, texture complexity provided an independent feature layer that further separated among treatments, indicating that stimulus identity is represented by continuous, high-dimensional morphological features beyond discrete state assignments. Linking morphology to function, IFN{gamma} produced the largest morphological redistribution and was also the only stimulus to significantly elevate intracellular ROS at 24 h, indicating that morphological remodeling and redox activation can be coordinately engaged by specific inflammatory signals. Together, these findings support a model in which microglia respond to inflammatory stimuli by graded occupancy of a continuous morphological landscape, with each stimulus producing a stimulus-specific occupancy pattern that extends beyond discrete state assignments.