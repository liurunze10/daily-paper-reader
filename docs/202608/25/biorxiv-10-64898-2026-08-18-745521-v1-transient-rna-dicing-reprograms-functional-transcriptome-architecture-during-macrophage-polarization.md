---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.5
evidence: RNA切割在巨噬细胞极化过程中重塑成熟转录本
tldr: 该研究揭示了RNA切割（RNA dicing）作为一种瞬时转录后调控机制，在巨噬细胞极化过程中重塑成熟mRNA。通过长读长转录组学和蛋白质组学分析，研究发现这种切割发生在特定蛋白质结构域之间，产生具有翻译能力的稳定异构体，进而生成功能独特的截短蛋白（如JAK1的JH1激酶模块）。这一过程扩展了蛋白质功能多样性，是细胞状态转换的关键调节层。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究成熟mRNA在转录和加工完成后，是否存在进一步的转录后重塑机制来调节巨噬细胞极化等细胞状态转换。
method: 利用长读长转录组学和分级蛋白质组学技术，结合JAK1作为机制模型，研究巨噬细胞极化过程中的RNA切割现象。
result: 发现RNA切割在细胞状态转换早期达到峰值，能产生保留下游编码模块的稳定异构体，并证实截短的JAK1蛋白具有独特的底物偏好。
conclusion: RNA切割是一种适应性基因调节层，通过重塑转录本结构和扩展蛋白质功能多样性来驱动细胞命运决定。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后即已固定。我们此前已确定 RNA 切割（RNA dicing）是一种转录后过程，可产生稳定、无帽且具有翻译能力的 RNA 异构体。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化过程中重塑成熟转录本。长读长转录组学揭示了广泛的、命运特异性的切割现象，该现象在细胞状态转换早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为基因调节的一个适应性层级，它重编程了转录本架构，扩展了蛋白质功能多样性，并有助于塑造细胞状态转换。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

这是一份关于论文《Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization》的深度学术总结：

### 1. 核心问题与整体含义
该研究挑战了“成熟 mRNA 编码潜力在转录和加工后即固定”的传统生物学假设。研究的核心问题是：**RNA 切割（RNA dicing）是否作为一种受调控的程序，在细胞状态转换（如巨噬细胞极化）过程中动态重塑转录组并扩展蛋白质功能多样性？** 
研究发现，RNA 切割并非随机的降解过程，而是一种瞬时的、命运特异性的转录后调节机制，通过在成熟 mRNA 内部产生新的稳定异构体，快速改变细胞的蛋白质输出，从而驱动巨噬细胞向特定功能状态转换。

### 2. 方法论：核心思想与关键技术
*   **核心思想：** 利用成熟 mRNA 作为“模块化底物”，通过内源性切割产生无帽但具有翻译能力的下游 RNA 片段，这些片段保留了特定的蛋白质结构域，从而生成功能迥异的截短蛋白。
*   **关键技术细节：**
    *   **长读长转录组学（Long-read RNA-seq）：** 用于精确解析转录本的 5' 和 3' 端边界，区分全长转录本与切割产生的异构体。
    *   **DRIMSeq 统计框架：** 不同于传统的 DESeq2（关注基因总丰度），DRIMSeq 用于建模转录本的使用比例变化，捕捉切割驱动的异构体转换。
    *   **m6A 映射与整合：** 验证 m6A 修饰如何在新生成的 5' 端重新定位，从而许可无帽 RNA 的非依赖性翻译。
    *   **同义密码子重编程（Synonymous Recoding）：** 针对 JAK1 基因，在不改变氨基酸序列的前提下修改核苷酸，破坏其 RNA 切割位点，以此作为实验模型验证切割的功能必要性。
    *   **激酶底物谱分析（PamChip）：** 对比全长 JAK1 与切割产生的 JH1 模块在底物偏好和信号动力学上的差异。

### 3. 实验设计
*   **数据集与场景：** 使用 HL-60（人原髓细胞白血病细胞系）作为模型，通过 PMA 诱导分化，再分别使用 IFNγ+LPS 诱导 M1 型（促炎）极化，或使用 IL-4+IL-13 诱导 M2 型（抗炎）极化。
*   **时间点：** 选取了极化过程中的 12h、24h 和 72h 三个关键节点。
*   **对比方法（Benchmark）：** 
    *   将 **DRIMSeq（异构体水平）** 与 **DESeq2（基因水平）** 进行对比，证明传统分析会掩盖大量的转录后重塑信息。
    *   对比了 M1 和 M2 两种不同命运下的切割图谱差异。
    *   对比了野生型 JAK1 与切割缺陷型（CO+）JAK1 对巨噬细胞功能的影响。

### 4. 资源与算力
论文中**未明确说明**具体的 GPU 型号、数量或训练时长等算力细节。这主要是因为该研究侧重于生物信息学分析（如序列比对、统计建模）和湿实验验证，而非深度学习模型的大规模训练。

### 5. 实验数量与充分性
*   **实验规模：** 研究涵盖了从全局转录组（长读长测序）、全局蛋白质组（分级质谱）、单基因机制研究（JAK1 突变体）到体外生化实验（激酶阵列）的完整链路。
*   **充分性与客观性：** 
    *   通过多组学数据（RNA-seq, m6A-RIP, Proteomics）的交叉验证，证明了切割现象的普遍性。
    *   设置了同义突变对照，排除了蛋白质序列改变带来的干扰，实验设计严谨。
    *   使用了多个时间点和两种极化方向，确保了结论的动态性和特异性。整体实验非常充分且具有高度的客观性。

### 6. 主要结论与发现
*   **瞬时性：** RNA 切割是一个在极化早期（12-24h）达到峰值、随后在终末分化期（72h）消退的瞬时程序。
*   **空间特异性：** 切割位点优先位于蛋白质结构域之间（Inter-domain），从而保护了下游功能模块的完整性。
*   **功能重编程：** 以 JAK1 为例，切割产生的 JH1 模块失去了抑制性结构域，表现出更强的激酶活性和截然不同的底物偏好（更偏向核蛋白和促炎信号）。
*   **生物学必要性：** 破坏 JAK1 的切割会显著抑制巨噬细胞向 M1 型极化的能力，证明该机制是细胞命运决定的关键。

### 7. 优点与亮点
*   **视角新颖：** 提出了成熟 mRNA 并非终点而是“可编程底物”的观点，为基因表达调控增加了新的维度。
*   **技术融合：** 成功将长读长测序与分级蛋白质组学结合，解决了短读长测序无法识别转录本完整性的痛点。
*   **机制深入：** 不仅发现了现象，还通过 JAK1 模型深入到了生化底物偏好和信号通路重构的层面。

### 8. 不足与局限
*   **上游机制不明：** 虽然确定了切割受调控，但具体是哪些内切酶（Endonucleases）负责在特定位点执行切割尚不完全清楚。
*   **模型局限：** 主要基于 HL-60 细胞系，虽然具有代表性，但在原代巨噬细胞或更多生理环境下的普适性仍需进一步验证。
*   **调控因子未知：** 触发这种“瞬时波”的信号通路和反式作用因子（Trans-acting factors）有待挖掘。

（完）
