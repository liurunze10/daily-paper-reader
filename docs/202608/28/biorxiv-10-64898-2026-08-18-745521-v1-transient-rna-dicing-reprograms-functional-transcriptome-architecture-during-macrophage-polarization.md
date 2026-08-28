---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 确定RNA切割是巨噬细胞极化过程中重塑转录本的转录后程序。
tldr: 本研究发现RNA切割（dicing）是一种在巨噬细胞极化过程中发生的瞬时转录后调控机制。通过长读长转录组学和蛋白质组学分析，研究揭示了该过程能重塑成熟mRNA，产生保留特定功能域的稳定异构体，进而生成截短蛋白。以JAK1为例，切割产生的激酶模块改变了底物偏好并影响信号传导，证明了RNA切割在扩展蛋白质功能多样性和调控细胞状态转换中的关键作用。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v1/fig-001.webp\", \"caption\": \"Figure 4. Dicing of JAK1 is required for M1 macrophage polarization\", \"page\": 38, \"index\": 1, \"width\": 1093, \"height\": 655}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v1/fig-002.webp\", \"caption\": \"Figure 2. RNA dicing is fate-specific and spatially coordinated with protein-domain architecture\", \"page\": 34, \"index\": 2, \"width\": 1065, \"height\": 785}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v1/fig-003.webp\", \"caption\": \"Figure 3. Size-resolved proteomics links RNA dicing to truncated protein isoforms\", \"page\": 36, \"index\": 3, \"width\": 1098, \"height\": 648}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v1/fig-004.webp\", \"caption\": \"Figure 1. RNA dicing is a transient, stage-specific program during macrophage polarization\", \"page\": 32, \"index\": 4, \"width\": 1048, \"height\": 639}]"
motivation: 探究成熟mRNA在转录和加工完成后，是否存在动态的转录后重塑机制来调节巨噬细胞极化等细胞状态转换。
method: 结合长读长转录组学和分级蛋白质组学技术，分析巨噬细胞极化过程中RNA异构体及其对应蛋白产物的动态变化。
result: 发现RNA切割在细胞状态转换早期达到峰值，能产生保留下游编码模块的稳定异构体，并以JAK1激酶模块为例展示了其对信号传导的重塑作用。
conclusion: RNA切割是基因调节的一个自适应层，通过重塑转录本结构和扩展蛋白质功能多样性来协同调控细胞命运。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后即已固定。我们此前已确定 RNA 切割（dicing）是一种产生稳定、无帽且具有翻译能力的 RNA 异构体的转录后过程。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化期间重塑成熟转录本。长读长转录组学揭示了广泛的、细胞命运特异性的切割现象，该现象在细胞状态转换早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为一种适应性基因调节层，能够重编程转录本架构，扩展蛋白质功能多样性，并有助于塑造细胞状态转换。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

这是一份关于论文《Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization》（瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构）的深度学术总结。

---

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：在细胞发生状态转换（如巨噬细胞极化）时，成熟的 mRNA 是否在转录和常规加工（如剪接、加帽）完成后，仍存在一种动态的、功能性的转录后重塑机制？
*   **研究背景**：传统分子生物学认为，成熟 mRNA 的编码潜力在离开细胞核后基本固定。虽然已知存在 RNA 降解，但作者此前发现了一种名为 **“RNA 切割”（RNA dicing）** 的现象，它能产生稳定、无帽且具备翻译能力的 RNA 异构体。
*   **整体含义**：本研究证明了 RNA 切割并非随机的降解过程，而是一种受控的、瞬时的转录后程序。它通过在特定蛋白质结构域之间“裁剪”mRNA，产生截短的蛋白异构体，从而在不改变基因组序列的情况下，快速重塑细胞的蛋白质组功能，驱动细胞命运的转变。

### 2. 论文提出的方法论
*   **核心思想**：通过整合多组学手段，追踪从 mRNA 切割到截短蛋白产生，再到细胞功能改变的全过程。
*   **关键技术细节**：
    *   **长读长转录组学（Long-read Transcriptomics）**：利用长读长测序技术识别全长 mRNA 及其被切割后产生的特定异构体，解决了传统短读长测序无法准确区分截短转录本的难题。
    *   **分级蛋白质组学（Fractionated Proteomics）**：通过对蛋白质进行大小分级处理后再进行质谱分析，精准定位并验证由切割后的 RNA 翻译而来的截短蛋白产物。
    *   **生物信息学架构分析**：分析切割位点在蛋白质二级结构中的分布，探讨其与蛋白质结构域（Domain）边界的关系。
    *   **机制模型验证**：以 **JAK1** 蛋白为模型，通过分子生物学手段（如破坏切割位点）研究其对信号传导和细胞极化的影响。

### 3. 实验设计
*   **实验场景**：小鼠/人类巨噬细胞向 M1（促炎）状态极化的过程。
*   **数据集与 Benchmark**：
    *   使用了极化过程中的时间序列采样（早期 vs 晚期）。
    *   对比了全长转录本与切割产生的异构体。
    *   **对照组**：未受刺激的巨噬细胞（M0）以及破坏了特定切割位点的突变细胞株。
*   **对比方法**：通过对比正常极化与切割受阻后的极化效率，评估该机制的必要性。

### 4. 资源与算力
*   **算力说明**：论文中未明确提及具体的 GPU 型号、数量或具体的训练时长。
*   **资源消耗**：该研究的资源消耗主要集中在**高深度长读长测序**和**高分辨率质谱分析**上，属于典型的生物信息学与湿实验结合的重资源消耗型研究。

### 5. 实验数量与充分性
*   **实验规模**：
    *   涵盖了全转录组范围的扫描，识别出大量受切割调控的基因。
    *   针对 JAK1 进行了深入的生化实验，包括激酶活性分析、底物偏好测试和下游信号通路（如 STAT 磷酸化）的检测。
    *   包含了时间序列分析，证明了切割现象的“瞬时性”（在极化早期达到峰值）。
*   **充分性评价**：实验设计形成了从“现象发现”到“组学关联”再到“单分子机制验证”的完整闭环。通过多组学数据的交叉验证，实验结果具有较高的客观性和说服力。

### 6. 主要结论与发现
*   **瞬时性与特异性**：RNA 切割是巨噬细胞极化早期的一个瞬时程序，具有高度的细胞命运特异性。
*   **结构域保留**：切割倾向于发生在蛋白质结构域之间的连接区，从而保留了具有独立功能的下游编码模块（如激酶域）。
*   **功能重塑（以 JAK1 为例）**：JAK1 被切割后产生的 **JH1 激酶模块** 表现出与全长 JAK1 不同的底物偏好，这种改变对于巨噬细胞成功转向促炎状态至关重要。
*   **调控新层级**：确立了 RNA 切割作为一种自适应的基因调节层，能够扩展蛋白质的功能多样性。

### 7. 优点
*   **理论突破**：挑战了“成熟 mRNA 功能固定”的传统教条，为理解细胞状态转换提供了全新的视角。
*   **技术融合**：巧妙结合了长读长测序和分级蛋白质组学，克服了检测截短蛋白和 RNA 异构体的技术瓶颈。
*   **生物学意义重大**：揭示了细胞如何在不依赖新转录的情况下，通过“裁剪”现有转录本来实现功能的快速转换。

### 8. 不足与局限
*   **执行机制尚不明确**：虽然确定了切割现象，但具体是哪些核糖核酸酶（RNases）或分子机器执行了这种精确的“裁剪”动作，文中未做详尽的生化解析。
*   **普适性验证**：研究主要集中在巨噬细胞极化模型，该机制在其他细胞类型（如神经元分化或肿瘤细胞转化）中的普遍性仍需进一步验证。
*   **偏差风险**：长读长测序和质谱分析可能对低丰度的切割产物存在检测偏差。

---
（完）
