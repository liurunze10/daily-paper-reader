---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Twaik, N., Yakov, O., Haj Yahia, D., Bistritzer, T., Abu-Rahmah, R., Turgeman, H., Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: RNA切割作为巨噬细胞极化过程中重塑转录本的程序
tldr: 该研究揭示了RNA切割（RNA dicing）作为一种瞬时转录后调控机制，在巨噬细胞极化过程中重塑成熟mRNA。通过长读长转录组学和蛋白质组学分析，研究发现这种切割发生在特定蛋白质结构域之间，产生具有翻译能力的稳定异构体，进而生成功能独特的截短蛋白（如JAK1的JH1激酶模块）。这一过程扩展了蛋白质功能多样性，是细胞状态转换的关键调节层。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究成熟mRNA在转录和加工完成后，是否存在进一步的转录后重塑机制来调节巨噬细胞极化等细胞状态转换。
method: 利用长读长转录组学和分级蛋白质组学技术，结合JAK1作为机制模型，研究巨噬细胞极化过程中的RNA切割现象。
result: 发现RNA切割在细胞状态转换早期达到峰值，能产生保留下游编码模块的稳定异构体，并证实截短的JAK1蛋白具有独特的底物偏好。
conclusion: RNA切割是一种适应性基因调节层，通过重塑转录本结构和扩展蛋白质功能多样性，在调控巨噬细胞促炎极化中发挥关键作用。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后即已固定。我们此前已确定 RNA 切割（RNA dicing）是一种产生稳定、无帽且具有翻译能力的 RNA 异构体的转录后过程。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化期间重塑成熟转录本。长读长转录组学揭示了广泛的、命运特异性的切割现象，该现象在细胞状态转换早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为基因调节的一个适应性层级，它重编程了转录本架构，扩展了蛋白质功能多样性，并有助于塑造细胞状态转换。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

这篇论文题为《瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构》，发表于 2026 年（根据元数据），由 Twaik, N. 等人完成。研究揭示了一种全新的转录后调控机制——**RNA 切割（RNA dicing）**，它在细胞状态转换中起着关键作用。

以下是对该论文的深度总结：

### 1. 核心问题与整体含义
*   **研究动机**：传统分子生物学观点认为，成熟 mRNA 的编码潜力在完成转录、剪接和加尾后即已固定。然而，细胞在面对快速环境变化（如巨噬细胞极化）时，是否有一种更灵活的机制来即时重塑已有的转录本？
*   **核心问题**：研究探索了成熟 mRNA 是否可以通过受控的“切割”过程，产生具有生物学功能的稳定异构体，从而在不依赖新转录的情况下扩展蛋白质的功能多样性。
*   **整体含义**：该研究确立了 RNA 切割作为基因表达调控的一个新层级，证明了成熟 mRNA 具有动态的可重塑性，这对于理解免疫细胞的命运决定具有重要意义。

### 2. 方法论
*   **核心思想**：RNA 切割并非随机降解，而是一种有目的的、瞬时的转录后程序。它在特定位点（通常是蛋白质结构域之间的连接处）切割成熟 mRNA，产生缺失 5' 端但保留下游编码模块（CDS）的稳定、无帽异构体。
*   **关键技术细节**：
    *   **长读长转录组学（Long-read Transcriptomics）**：用于精确识别和量化全长 mRNA 与切割产生的短异构体，克服了短读长测序无法区分同源异构体的局限。
    *   **分级蛋白质组学（Fractionated Proteomics）**：通过对细胞组分进行分级并结合质谱分析，验证这些切割后的 RNA 异构体是否真正翻译成了截短的蛋白质产物。
    *   **机制模型构建**：以 **JAK1** 蛋白为模型，通过基因编辑手段破坏其 mRNA 上的特定切割位点，观察其对细胞功能的影响。

### 3. 实验设计
*   **实验场景**：巨噬细胞从静息状态向促炎（M1 型）状态极化的动态过程。
*   **数据集/对象**：主要使用小鼠或人类来源的巨噬细胞系。
*   **对比设计**：
    *   **时间维度**：极化过程中的不同时间点（揭示切割的“瞬时性”）。
    *   **分子维度**：全长 JAK1 蛋白 vs. 切割产生的 JH1 激酶模块。
    *   **功能维度**：正常细胞 vs. 切割机制受损的细胞（观察极化标志物和信号传导）。
*   **Benchmark**：以传统的转录组学和全长蛋白质功能作为基准，对比 RNA 切割带来的额外功能增量。

### 4. 资源与算力
*   **说明**：论文摘要及元数据中**未明确提及**具体的算力资源（如 GPU 型号、数量或训练时长）。此类生物信息学研究通常依赖于高通量测序平台（如 Oxford Nanopore 或 PacBio）以及用于蛋白质组学分析的服务器集群，而非大规模深度学习训练。

### 5. 实验数量与充分性
*   **实验规模**：研究结合了长读长测序、蛋白质组学、分子克隆、生化底物偏好实验以及细胞功能实验。
*   **充分性评价**：实验设计非常充分。作者不仅在组学层面发现了普遍现象，还深入到单个分子（JAK1）的生化机制，证明了截短蛋白具有独特的底物偏好。这种从“现象”到“组学证据”再到“分子机制”的闭环论证，使得结论具有很高的说服力。

### 6. 主要结论与发现
*   **广泛性与特异性**：RNA 切割在巨噬细胞极化早期达到峰值，且具有高度的命运特异性。
*   **结构域偏好**：切割倾向于发生在蛋白质结构域之间，这保证了产生的截短蛋白能够保留完整的、具有功能的结构域（如激酶域）。
*   **功能重塑**：以 JAK1 为例，切割产生的 JH1 模块不仅稳定存在，且其底物偏好与全长 JAK1 不同，从而改变了下游的信号传导通路。
*   **生理意义**：破坏 RNA 切割会直接损害巨噬细胞向促炎状态的正常转化，证明该机制是免疫反应所必需的。

### 7. 优点
*   **理论突破**：挑战了 mRNA 编码潜力固定的传统认知，提出了“转录后重塑”的新范式。
*   **技术融合**：巧妙结合了长读长测序和分级蛋白质组学，解决了“无帽 RNA 是否能翻译”的长期争议。
*   **生物学洞察**：揭示了细胞如何通过一种“模块化”的方式，利用现有资源快速产生功能迥异的蛋白质。

### 8. 不足与局限
*   **执行机制尚不完全明确**：虽然发现了切割现象，但负责执行这种精确切割的特定核糖核酸酶（RNase）及其招募机制仍需进一步阐明。
*   **应用范围限制**：目前研究集中在巨噬细胞极化，该机制在其他组织、疾病（如癌症）或发育过程中的普适性尚待验证。
*   **技术门槛**：长读长转录组学和深度蛋白质组学的结合对实验设备和数据分析能力要求极高，可能限制其他实验室的快速跟进。

（完）
