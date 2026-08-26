---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Twaik, N., Yakov, O., Haj Yahia, D., Bistritzer, T., Abu-Rahmah, R., Turgeman, H., Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: RNA切割在巨噬细胞极化过程中重塑转录本
tldr: 该研究揭示了RNA切割（RNA dicing）作为一种瞬时转录后调控机制，在巨噬细胞极化过程中重塑成熟mRNA。通过长读长转录组学和蛋白质组学分析，研究发现这种切割发生在特定蛋白质结构域之间，产生具有翻译能力的稳定异构体，进而生成功能独特的截短蛋白（如JAK1的JH1激酶模块）。这一过程扩展了蛋白质功能多样性，是细胞状态转换的关键调节层。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v2/fig-001.webp\", \"caption\": \"Figure 4. Dicing of JAK1 is required for M1 macrophage polarization\", \"page\": 38, \"index\": 1, \"width\": 1093, \"height\": 655}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v2/fig-002.webp\", \"caption\": \"Figure 2. RNA dicing is fate-specific and spatially coordinated with protein-domain architecture\", \"page\": 34, \"index\": 2, \"width\": 1065, \"height\": 785}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v2/fig-003.webp\", \"caption\": \"Figure 3. Size-resolved proteomics links RNA dicing to truncated protein isoforms\", \"page\": 36, \"index\": 3, \"width\": 1098, \"height\": 648}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v2/fig-004.webp\", \"caption\": \"Figure 1. RNA dicing is a transient, stage-specific program during macrophage polarization\", \"page\": 32, \"index\": 4, \"width\": 1048, \"height\": 639}]"
motivation: 探究成熟mRNA在转录和加工完成后，是否存在进一步的转录后重塑机制来调节巨噬细胞极化等细胞状态转换。
method: 利用长读长转录组学和分级蛋白质组学技术，结合JAK1作为机制模型，研究巨噬细胞极化过程中的RNA切割现象。
result: 发现RNA切割在细胞状态转换早期达到峰值，能产生保留下游编码模块的稳定异构体，并证实截短的JAK1蛋白具有独特的底物偏好。
conclusion: RNA切割是一种适应性基因调节层，通过重塑转录本结构和扩展蛋白质功能多样性来驱动细胞命运决定。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后即已固定。我们此前已确定 RNA 切割（RNA dicing）是一种产生稳定、无帽且具有翻译能力的 RNA 异构体的转录后过程。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化期间重塑成熟转录本。长读长转录组学揭示了广泛的、命运特异性的切割现象，该现象在细胞状态转换早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为基因调节的一个适应性层级，它重编程了转录本架构，扩展了蛋白质功能多样性，并有助于塑造细胞状态转换。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

这篇论文深入探讨了巨噬细胞极化过程中一种新颖的基因表达调控机制——**RNA 切割（RNA dicing）**。以下是对该研究的结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：在成熟 mRNA 完成转录、剪接和加帽等标准加工后，其编码潜力是否就此固定？细胞在面临快速状态转换（如免疫细胞激活）时，是否存在一种更灵活的转录后机制来重塑蛋白质组？
*   **研究背景**：传统观点认为 mRNA 的结构在离开细胞核后基本稳定。然而，该研究发现了一种“瞬时 RNA 切割”现象，它能在不依赖新转录的情况下，通过切割成熟 mRNA 产生稳定的、具有翻译能力的异构体，从而快速改变细胞的功能输出。

### 2. 论文提出的方法论
*   **核心思想**：RNA 切割并非随机的降解过程，而是一种受控的、发生在特定蛋白质结构域之间的重塑机制，旨在产生功能独特的截短蛋白。
*   **关键技术细节**：
    *   **长读长转录组学（Long-read Transcriptomics）**：用于精确识别 mRNA 的断裂位点，区分全长转录本与切割产生的异构体。
    *   **分级蛋白质组学（Fractionated Proteomics）**：通过分子量大小分离蛋白质，验证 RNA 异构体是否真正翻译成了相应的截短蛋白。
    *   **JAK1 机制模型**：选取 JAK1 激酶作为典型案例，通过分子生物学手段研究其切割产物（JH1 激酶模块）的信号传导特性。

### 3. 实验设计
*   **实验场景**：小鼠/人类巨噬细胞从静息态向 M1（促炎）状态极化的动态过程。
*   **对比对象（Benchmark）**：
    *   极化过程中的不同时间点（观察瞬时性）。
    *   全长蛋白（Full-length）与切割产生的截短蛋白（Truncated isoforms）的功能对比。
    *   正常细胞与破坏了切割位点（通过基因编辑）的细胞对比。
*   **分析维度**：涵盖了从 RNA 结构、蛋白质丰度到下游磷酸化信号传导的全过程。

### 4. 资源与算力
*   **说明**：论文摘要及元数据中**未明确提及**具体的 GPU 型号、数量或训练时长。此类研究通常涉及高通量测序数据分析（Bioinformatics pipeline），主要依赖高性能计算集群（HPC）进行序列比对和组学定量，而非大规模深度学习模型的训练。

### 5. 实验数量与充分性
*   **实验规模**：研究结合了全基因组水平的筛查（转录组+蛋白质组）与针对特定基因（JAK1）的深度验证。
*   **充分性评价**：实验设计较为充分且具有多维度互证。通过时间序列采样捕捉到了切割现象的“瞬时性”；通过蛋白质组学证明了 RNA 异构体的翻译能力；通过功能实验证明了该机制对细胞命运（极化）的必要性。实验逻辑闭环，证据链较为完整。

### 6. 主要结论与发现
*   **瞬时性**：RNA 切割是一个阶段特异性的程序，在巨噬细胞极化早期达到峰值，随后消失。
*   **结构域特异性**：切割倾向于发生在编码蛋白质结构域的连接处，从而保留了具有独立功能的模块（如激酶域）。
*   **功能重塑**：以 JAK1 为例，切割产生的 JH1 模块具有与全长 JAK1 不同的底物偏好，改变了下游信号通路，这对 M1 极化至关重要。
*   **调控新层级**：确立了 RNA 切割作为一种适应性基因调节层，扩展了蛋白质组的功能多样性。

### 7. 优点
*   **理论创新**：挑战了“成熟 mRNA 编码潜力固定”的传统教条，提出了转录后调控的新维度。
*   **技术融合**：巧妙结合了长读长测序和分级蛋白质组学，解决了短读长测序难以准确识别切割异构体的难题。
*   **生物学意义明确**：直接关联到免疫细胞的命运决定，具有潜在的临床转化价值（如免疫调节药物研发）。

### 8. 不足与局限
*   **执行机制尚不完全清晰**：虽然证实了切割现象的存在，但负责执行这一精确切割过程的酶复合物（Endonucleases）的具体成分和招募机制仍需进一步阐明。
*   **普适性验证**：目前研究集中在巨噬细胞极化，该机制在其他细胞类型（如神经元突触可塑性或胚胎发育）中是否普遍存在尚待探索。
*   **技术偏差风险**：长读长测序虽然强大，但在区分“受控切割产物”与“实验操作导致的 RNA 降解”方面仍需极其严格的对照。

（完）
