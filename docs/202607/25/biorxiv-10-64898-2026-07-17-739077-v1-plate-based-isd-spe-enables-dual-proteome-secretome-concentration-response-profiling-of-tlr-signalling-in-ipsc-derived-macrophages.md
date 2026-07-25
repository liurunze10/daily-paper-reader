---
title: Plate-based ISD-SPE enables dual proteome-secretome concentration-response profiling of TLR signalling in iPSC-derived macrophages
title_zh: 基于孔板的 ISD-SPE 技术实现了 iPSC 来源巨噬细胞中 TLR 信号传导的蛋白质组-分泌组双重浓度-反应谱分析
authors: "Tayler, C. L., Li, M., Haslam, C., Norris, K., Booty, L., Beveridge, R., Rattray, N. J., Peltier-Heap, R. E."
date: 2026-07-21
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.17.739077v1.full.pdf"
tags: ["query:ros-mp"]
score: 7.5
evidence: iPSC来源巨噬细胞中TLR信号传导和分泌组的分析
tldr: 本研究开发了基于96孔板的ISD-SPE工作流，解决了质谱分泌组学在药物发现中扩展性不足的难题。该方法实现了从同一孔中对iPSC衍生巨噬细胞进行蛋白质组与分泌组的集成分析。结合dia-PASEF技术，研究成功解析了TLR受体特异性的分泌模式及药物干预的浓度-反应关系，为系统级表征炎症反应和药物机制提供了高效、可扩展的分析工具。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-001.webp\", \"caption\": \"\", \"page\": 52, \"index\": 1, \"width\": 1391, \"height\": 1736}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-002.webp\", \"caption\": \"\", \"page\": 53, \"index\": 2, \"width\": 1366, \"height\": 1913}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-003.webp\", \"caption\": \"\", \"page\": 54, \"index\": 3, \"width\": 1366, \"height\": 766}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-004.webp\", \"caption\": \"\", \"page\": 55, \"index\": 4, \"width\": 1398, \"height\": 1645}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-005.webp\", \"caption\": \"\", \"page\": 56, \"index\": 5, \"width\": 1400, \"height\": 848}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-006.webp\", \"caption\": \"\", \"page\": 57, \"index\": 6, \"width\": 1389, \"height\": 1203}]"
motivation: 传统的质谱分泌组学分析流程复杂且难以扩展，限制了其在药物发现和高通量筛选中的应用。
method: 开发了一种基于96孔板的ISD-SPE工作流，结合dia-PASEF质谱技术，实现对同一细胞样本的蛋白质组和分泌组的集成化处理与分析。
result: 该工作流在保持蛋白质组深度的同时显著提升了定量重复性，并成功识别了TLR激活下的受体特异性分泌特征及药物抑制效应。
conclusion: 该研究提供了一种可扩展的策略，能够深入表征细胞内信号传导与下游蛋白分泌的关联，助力炎症机制研究和化合物药效评估。
---

## 摘要
蛋白质分泌是细胞信号传导的关键功能输出，捕捉了塑造免疫行为的刺激和药理扰动的动态反应。在巨噬细胞中，Toll 样受体 (TLRs) 的激活驱动了受严格调控的分泌程序，这些程序介导炎症反应并提供通路活性的生物学意义读数。虽然基于质谱 (MS) 的分泌组学能够对这些过程进行无偏见分析，但在药物研发中的广泛应用仍受限于样本制备工作流程的可扩展性。在此，我们描述了一种基于孔板的溶液内消化和固相萃取 (ISD-SPE) 工作流程，该流程能够对条件培养基进行 96 孔处理，从而在同一样本孔中进行蛋白质组和分泌组的整合分析。与基于沉淀的方法进行的基准测试表明，该方法具有相当的蛋白质组深度，同时提高了定量重现性，并在多个孔板上表现出稳健的性能。结合 dia-PASEF 采集技术，该工作流程能够深入分析巨噬细胞对 TLR 激活的反应，解析了 TLR3、TLR4 和 TLR7/8 激活后的受体特异性分泌程序。将该方法扩展到浓度-反应研究，实现了对细胞内和细胞外蛋白质景观中药理扰动的定量表征，揭示了对 TLR 抑制的共同和室室特异性反应，以及与分泌动力学相关的表观效力差异。总之，该工作流程为细胞内信号传导和下游蛋白质分泌的整合分析提供了一种可扩展的策略，能够对炎症反应和化合物作用机制进行系统级表征。

## Abstract
Protein secretion represents a key functional output of cellular signalling, capturing dynamic responses to stimulation and pharmacological perturbation that shape immune behaviour. In macrophages, activation of Toll-like receptors (TLRs) drives tightly regulated secretion programmes that mediate inflammatory responses and provide a biologically meaningful readout of pathway activity. Whilst mass spectrometry (MS)-based secretomics enables unbiased profiling of these processes, broader application in drug discovery remains constrained by sample preparation workflows that limit scalability. Here, we describe a plate-based in-solution digestion and solid-phase extraction (ISD-SPE) workflow that enables 96-well processing of conditioned media for integrated proteome and secretome analysis from the same sample well. Benchmarking against a precipitation-based approach demonstrated comparable proteomic depth with improved quantitative reproducibility and robust performance across multiple plates. Coupled with dia-PASEF acquisition, this workflow enabled in-depth profiling of macrophage responses to TLR activation, resolving receptor-specific secretory programmes following TLR3, TLR4 and TLR7/8 activation. Extension of the approach to concentration-response studies enabled quantitative characterisation of pharmacological perturbation across intracellular and extracellular protein landscapes, revealing both shared and compartment-specific responses to TLR inhibition, as well as differences in apparent potency linked to secretion dynamics. Together, this workflow provides a scalable strategy for integrated analysis of intracellular signalling and downstream protein secretion, enabling systems-level characterisation of inflammatory responses and compound mechanisms of action.