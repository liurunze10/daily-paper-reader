---
title: Plate-based ISD-SPE enables dual proteome-secretome concentration-response profiling of TLR signalling in iPSC-derived macrophages
title_zh: 基于孔板的 ISD-SPE 实现了 iPSC 来源巨噬细胞中 TLR 信号传导的蛋白质组-分泌组双重浓度-效应谱分析
authors: "Tayler, C. L., Li, M., Haslam, C., Norris, K., Booty, L., Beveridge, R., Rattray, N. J., Peltier-Heap, R. E."
date: 2026-07-21
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.17.739077v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: iPSC来源巨噬细胞中的TLR信号和分泌组
tldr: 本研究开发了基于96孔板的ISD-SPE工作流，解决了质谱分泌组学在药物发现中扩展性不足的难题。该方法实现了对iPSC衍生巨噬细胞蛋白质组与分泌组的同步集成分析。结合dia-PASEF技术，研究成功解析了不同TLR激活的特异性分泌程序及药物干预的浓度-反应关系，为系统级表征炎症反应和药物机制提供了高效、可扩展的分析策略。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-001.webp\", \"caption\": \"\", \"page\": 52, \"index\": 1, \"width\": 1391, \"height\": 1736}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-002.webp\", \"caption\": \"\", \"page\": 53, \"index\": 2, \"width\": 1366, \"height\": 1913}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-003.webp\", \"caption\": \"\", \"page\": 54, \"index\": 3, \"width\": 1366, \"height\": 766}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-004.webp\", \"caption\": \"\", \"page\": 55, \"index\": 4, \"width\": 1398, \"height\": 1645}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-005.webp\", \"caption\": \"\", \"page\": 56, \"index\": 5, \"width\": 1400, \"height\": 848}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-17-739077-v1/fig-006.webp\", \"caption\": \"\", \"page\": 57, \"index\": 6, \"width\": 1389, \"height\": 1203}]"
motivation: 针对质谱分泌组学在药物发现中样本处理通量低、扩展性差的局限性，开发更高效的分析流程。
method: 提出一种基于96孔板的ISD-SPE工作流，结合dia-PASEF质谱技术，实现单孔样本的蛋白质组与分泌组同步分析。
result: 该流程在保持蛋白质组深度的同时提升了定量重复性，并成功区分了不同TLR通路的特异性分泌特征及药物抑制效应。
conclusion: 该自动化工作流为集成分析细胞内信号传导与下游蛋白分泌提供了可扩展的策略，有助于深入理解炎症机制和药物作用。
---

## 摘要
蛋白质分泌是细胞信号传导的关键功能输出，捕捉了塑造免疫行为的刺激和药理扰动的动态反应。在巨噬细胞中，Toll 样受体 (TLRs) 的激活驱动了受严格调控的分泌程序，这些程序介导炎症反应并提供通路活性的生物学意义读数。虽然基于质谱 (MS) 的分泌组学能够对这些过程进行无偏见的分析，但在药物发现中的广泛应用仍受限于样本制备工作流程的可扩展性。在此，我们描述了一种基于孔板的溶液内消化和固相萃取 (ISD-SPE) 工作流程，该流程能够对条件培养基进行 96 孔处理，从而实现对同一采样孔的蛋白质组和分泌组的整合分析。与基于沉淀的方法进行的基准测试表明，该方法具有相当的蛋白质组深度，同时提高了定量重复性，并在多个孔板上表现出稳健的性能。结合 dia-PASEF 采集技术，该工作流程实现了对巨噬细胞对 TLR 激活反应的深入分析，解析了 TLR3、TLR4 和 TLR7/8 激活后受体特异性的分泌程序。将该方法扩展到浓度-效应研究，实现了对细胞内和细胞外蛋白质景观药理扰动的定量表征，揭示了对 TLR 抑制的共同和区室特异性反应，以及与分泌动力学相关的表观效力差异。总之，该工作流程为细胞内信号传导和下游蛋白质分泌的整合分析提供了一种可扩展的策略，实现了对炎症反应和化合物作用机制的系统级表征。

## Abstract
Protein secretion represents a key functional output of cellular signalling, capturing dynamic responses to stimulation and pharmacological perturbation that shape immune behaviour. In macrophages, activation of Toll-like receptors (TLRs) drives tightly regulated secretion programmes that mediate inflammatory responses and provide a biologically meaningful readout of pathway activity. Whilst mass spectrometry (MS)-based secretomics enables unbiased profiling of these processes, broader application in drug discovery remains constrained by sample preparation workflows that limit scalability. Here, we describe a plate-based in-solution digestion and solid-phase extraction (ISD-SPE) workflow that enables 96-well processing of conditioned media for integrated proteome and secretome analysis from the same sample well. Benchmarking against a precipitation-based approach demonstrated comparable proteomic depth with improved quantitative reproducibility and robust performance across multiple plates. Coupled with dia-PASEF acquisition, this workflow enabled in-depth profiling of macrophage responses to TLR activation, resolving receptor-specific secretory programmes following TLR3, TLR4 and TLR7/8 activation. Extension of the approach to concentration-response studies enabled quantitative characterisation of pharmacological perturbation across intracellular and extracellular protein landscapes, revealing both shared and compartment-specific responses to TLR inhibition, as well as differences in apparent potency linked to secretion dynamics. Together, this workflow provides a scalable strategy for integrated analysis of intracellular signalling and downstream protein secretion, enabling systems-level characterisation of inflammatory responses and compound mechanisms of action.

---

## 论文详细总结（自动生成）

这是一份关于论文《Plate-based ISD-SPE enables dual proteome-secretome concentration-response profiling of TLR signalling in iPSC-derived macrophages》的深度结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **研究动机**：蛋白质分泌（分泌组）是免疫细胞（如巨噬细胞）功能的关键输出，也是药物发现中评估通路活性的重要指标。然而，传统的质谱分泌组学依赖于**丙酮沉淀**等样本制备方法，存在操作繁琐、难以自动化、低输入样本回收率不稳定等问题，限制了其在药物筛选等高通量场景中的应用。
*   **核心问题**：如何开发一种可扩展、自动化且能同时分析细胞内蛋白质组和细胞外分泌组的分析流程，以实现对炎症信号通路（如 TLR 通路）的系统级药理学表征。

### 2. 方法论：核心思想与关键技术
*   **核心思想**：开发了一种基于 96 孔板的**溶液内消化与固相萃取（ISD-SPE）**工作流，取代传统的沉淀法。
*   **关键技术细节**：
    *   **ISD-SPE 流程**：在 96 孔板中直接对条件培养基进行还原、烷基化和胰蛋白酶消化，随后使用 µElution 固相萃取板进行脱盐。
    *   **双重分析**：从同一个细胞培养孔中分别收集超清培养上清液（分泌组）和细胞裂解液（蛋白质组）。
    *   **质谱采集**：采用 **dia-PASEF** 技术（结合捕获离子迁移谱 TIMS），在极短的梯度内实现高灵敏度和高深度的蛋白质覆盖。
    *   **浓度-效应建模**：使用 R 语言的 `drc` 包，通过**四参数对数逻辑模型（4-parameter log-logistic model）**对数千个蛋白的丰度变化进行曲线拟合，计算 $EC_{50}$。

### 3. 实验设计与基准测试
*   **实验场景**：使用人诱导多能干细胞（iPSC）衍生的巨噬细胞，通过 TLR3、TLR4 和 TLR7/8 激动剂诱导炎症反应。
*   **基准测试（Benchmark）**：
    *   将 ISD-SPE 与传统的**丙酮沉淀法**进行直接对比。
    *   评估指标包括：蛋白质鉴定数量、定量重复性（CV%）、漏切率、孔板边缘效应及板间相关性。
*   **对比方法**：在药理学实验中，对比了选择性 TLR4 抑制剂（TAK-242）和 TLR7/8 抑制剂（MHV370）在 11 个浓度梯度下的表现。

### 4. 资源与算力
*   **硬件设备**：使用了 Evosep One 液相系统耦合 **Bruker timsTOF HT** 质谱仪。
*   **软件工具**：数据处理使用 **DIA-NN (v2.2.0)** 进行无库搜索和定量。
*   **算力说明**：文中未详细列出具体的 GPU/CPU 计算时长，但提到使用了 DIA-NN Enterprise 版本进行高通量数据分析，这是目前蛋白质组学领域处理大规模 dia-PASEF 数据的标准高效工具。

### 5. 实验数量与充分性
*   **实验规模**：
    *   **方法验证**：每种方法 48 个重复（24 个对照，24 个刺激），并进行了全板 96 孔的重复性测试。
    *   **动力学研究**：3 个生物学重复，覆盖 8 小时内的多个时间点。
    *   **浓度-效应**：3 个生物学重复 × 3 个技术重复，共 11 个浓度点。
*   **充分性评价**：实验设计非常充分且严谨。作者不仅验证了方法的稳健性（板内/板间），还通过多供体样本考虑了生物学差异，并利用浓度-效应曲线（而非单一浓度点）来识别真正的药理学响应，极大地提高了结论的客观性和可靠性。

### 6. 主要结论与发现
*   **方法学优势**：ISD-SPE 的定量重复性（中位数 CV 5.1%）优于丙酮沉淀法（8.8%），且完全消除了板边缘效应，适合自动化。
*   **受体特异性**：解析了不同 TLR 的分泌特征。TLR3 驱动纯干扰素（ISG）反应；TLR7/8 驱动促炎细胞因子反应；TLR4 则兼具两者特征。
*   **区室差异**：发现细胞内蛋白质组和分泌组的 $EC_{50}$ 存在相关性但有生物学滞后，分泌组的表观效力通常略低于细胞内水平。
*   **稳态恢复**：药理学抑制不仅降低了促炎蛋白，还观察到 CD163、STAT3 等稳态/抗炎标志物的浓度依赖性恢复。

### 7. 优点与亮点
*   **集成化**：实现了单孔双读数（蛋白质组+分泌组），提供了从信号传导（内）到功能输出（外）的全景视图。
*   **高通量潜力**：96 孔板格式与 ISD-SPE 流程非常容易整合到自动化液体处理工作站中。
*   **药理学深度**：将传统的“单点触发”分析提升为“全蛋白质组浓度-效应”分析，能够更准确地评估药物的效力和脱靶风险。

### 8. 不足与局限
*   **血清干扰**：为了减少质谱背景，实验必须在减血清培养基（Opti-MEM）中进行，这可能与生理状态下的全血清环境存在差异。
*   **低丰度蛋白限制**：尽管 dia-PASEF 灵敏度很高，但对于极低丰度的细胞因子（如 IL-10 在某些早期时间点），质谱的检测限仍可能低于 ELISA。
*   **应用范围**：目前仅在 iPSC 来源的巨噬细胞中验证，对于分泌量较少或对无血清环境敏感的其他细胞类型，可能需要进一步优化。

（完）
