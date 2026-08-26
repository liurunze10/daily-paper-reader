---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.5
evidence: RNA切割作为巨噬细胞极化过程中的转录后程序
tldr: 该研究揭示了RNA切割（RNA dicing）作为一种瞬时转录后调控机制，在巨噬细胞极化过程中重塑成熟mRNA。通过长读长转录组学和蛋白质组学分析，研究发现这种切割发生在特定蛋白质结构域之间，产生具有翻译能力的稳定异构体，进而生成功能独特的截短蛋白（如JAK1的JH1激酶模块）。这一过程扩展了蛋白质功能多样性，是细胞状态转换的关键调节层。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v1/fig-001.webp\", \"caption\": \"Figure 4. Dicing of JAK1 is required for M1 macrophage polarization\", \"page\": 38, \"index\": 1, \"width\": 1093, \"height\": 655}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v1/fig-002.webp\", \"caption\": \"Figure 2. RNA dicing is fate-specific and spatially coordinated with protein-domain architecture\", \"page\": 34, \"index\": 2, \"width\": 1065, \"height\": 785}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v1/fig-003.webp\", \"caption\": \"Figure 3. Size-resolved proteomics links RNA dicing to truncated protein isoforms\", \"page\": 36, \"index\": 3, \"width\": 1098, \"height\": 648}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v1/fig-004.webp\", \"caption\": \"Figure 1. RNA dicing is a transient, stage-specific program during macrophage polarization\", \"page\": 32, \"index\": 4, \"width\": 1048, \"height\": 639}]"
motivation: 探究成熟mRNA在转录和加工完成后，是否存在进一步的转录后重塑机制来调节巨噬细胞极化等细胞状态转换。
method: 利用长读长转录组学和分级蛋白质组学技术，结合JAK1作为机制模型，研究巨噬细胞极化过程中的RNA切割现象。
result: 发现RNA切割在细胞状态转换早期达到峰值，能产生保留下游编码模块的稳定异构体，并证实截短的JAK1蛋白具有独特的底物偏好。
conclusion: RNA切割是一种适应性基因调节层，通过重塑转录本结构和扩展蛋白质功能多样性来驱动细胞命运决定。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后即已固定。我们此前已确定 RNA 切割（dicing）是一种产生稳定、无帽且具有翻译能力的 RNA 异构体的转录后过程。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化期间重塑成熟转录本。长读长转录组学揭示了广泛的、命运特异性的切割现象，该现象在细胞状态转换早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为基因调节的一个适应性层级，它重编程了转录本架构，扩展了蛋白质功能多样性，并有助于塑造细胞状态转换。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

这篇论文由 Y. Malka 等人撰写，发表于 2026 年（注：根据元数据日期，可能为预印本或前瞻性研究），探讨了巨噬细胞极化过程中一种新颖的转录后调控机制。以下是对该论文的深度总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：在成熟 mRNA 完成转录和常规加工（如剪接、加帽、加尾）后，其编码潜力是否已经完全固定？
*   **研究背景**：传统的分子生物学中心法则认为，成熟 mRNA 的序列决定了最终蛋白质的结构。然而，细胞在面对快速环境变化（如巨噬细胞从静息态 M0 向促炎态 M1 极化）时，可能需要比重新转录更高效的机制来重塑蛋白质组。
*   **整体含义**：研究揭示了 **RNA 切割（RNA dicing）** 这一瞬时程序。它不是为了降解 mRNA，而是通过精准切割成熟转录本，产生稳定的、可翻译的异构体，从而快速产生功能独特的截短蛋白，扩展了细胞的蛋白质功能库。

### 2. 论文提出的方法论
*   **核心思想**：将 RNA 切割视为一种“适应性基因调节层”，通过在特定蛋白质结构域之间切割 mRNA，保留下游的功能模块（如激酶域）。
*   **关键技术细节**：
    *   **长读长转录组学（Long-read transcriptomics）**：用于捕捉 mRNA 的完整结构，识别出那些失去 5' 端帽子但依然稳定存在的切割异构体。
    *   **分级蛋白质组学（Fractionated proteomics）**：通过分子量大小分离蛋白质，验证切割后的 RNA 异构体是否真正翻译成了对应的截短蛋白。
    *   **机制模型构建**：以 **JAK1** 蛋白为核心模型，研究其 mRNA 被切割后生成的 JH1 激酶模块的功能。
    *   **生物信息学分析**：分析切割位点与蛋白质结构域（Domain）空间分布的关系。

### 3. 实验设计
*   **实验场景**：巨噬细胞极化过程（M0 诱导为 M1 促炎状态或 M2 抑炎状态）。
*   **数据集/对象**：原代巨噬细胞或巨噬细胞系。
*   **对比设计（Benchmark）**：
    *   **全长 vs. 截短**：对比全长 JAK1 蛋白与切割产生的 JH1 模块在底物偏好和信号传导上的差异。
    *   **正常 vs. 缺陷**：通过分子手段破坏 JAK1 的切割位点，观察巨噬细胞极化效率的变化。
    *   **时间序列对比**：观察极化不同阶段（早期 vs. 晚期）RNA 切割现象的丰度。

### 4. 资源与算力
*   **算力说明**：论文摘要及元数据中未明确提及具体的 GPU 型号、数量或训练时长。此类研究通常涉及大量的高通量测序数据处理（如 Nanopore 或 PacBio 数据），主要依赖高性能计算集群（HPC）进行序列比对和异构体定量分析。

### 5. 实验数量与充分性
*   **实验规模**：研究结合了全基因组水平的组学分析（转录组+蛋白质组）和针对特定基因（JAK1）的深度机制验证。
*   **充分性评价**：
    *   **多组学交叉验证**：通过转录组发现异构体，再通过蛋白质组证实其翻译产物，逻辑链条完整。
    *   **功能性验证**：不仅观察到了现象，还通过破坏实验证明了该现象对“细胞命运决定”（极化）是必需的。
    *   **客观性**：实验设计包含了时间序列动态观察，证明了该过程的“瞬时性”，排除了随机降解的可能性。

### 6. 主要结论与发现
*   **瞬时性**：RNA 切割是一个阶段特异性的程序，在细胞状态转换的早期达到峰值。
*   **空间精准性**：切割并非随机，而是优先发生在蛋白质结构域之间的连接区，确保了产生的截短蛋白具有完整的功能模块。
*   **功能重塑**：以 JAK1 为例，切割产生的 JH1 激酶模块失去了全长蛋白的某些调节域，表现出**独特的底物偏好**，从而改变了下游信号通路。
*   **生理意义**：破坏 RNA 切割会直接损害巨噬细胞向促炎（M1）状态的转化，说明这是免疫反应的关键调节步骤。

### 7. 优点
*   **理论突破**：挑战了成熟 mRNA 编码潜力固定的传统认知，提出了转录后调控的新维度。
*   **技术融合**：成功将长读长测序技术应用于发现非常规 RNA 异构体，并与蛋白质组学紧密结合。
*   **机制深入**：不仅发现了现象，还深入到了蛋白质底物偏好改变这一分子细节。

### 8. 不足与局限
*   **执行酶尚不明确**：虽然称为“dicing”，但具体是哪种核酸酶（RNase）负责这种精准切割，以及该酶如何被招募到特定位点，摘要中未详细说明。
*   **细胞类型局限**：研究主要集中在巨噬细胞，这种机制在其他快速发育或应激反应的细胞（如神经元、干细胞）中是否普遍存在尚待验证。
*   **应用转化**：虽然发现了该机制对炎症很重要，但如何利用这一机制开发抗炎药物仍处于理论阶段。

（完）
