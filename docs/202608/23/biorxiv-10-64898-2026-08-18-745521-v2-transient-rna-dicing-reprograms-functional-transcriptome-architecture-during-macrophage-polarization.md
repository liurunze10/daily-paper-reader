---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Twaik, N., Yakov, O., Haj Yahia, D., Bistritzer, T., Abu-Rahmah, R., Turgeman, H., Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: RNA切割作为巨噬细胞极化过程中的转录后程序
tldr: 本研究揭示了RNA切割作为一种瞬时转录后调控机制，在巨噬细胞极化中重塑成熟mRNA。通过长读长转录组学和蛋白质组学，发现该过程产生稳定的翻译异构体，保留下游功能域并产生截短蛋白。以JAK1为例，证明RNA切割能改变激酶底物偏好，是调节细胞状态转换和增加蛋白质功能多样性的关键。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究成熟mRNA在加工完成后是否通过动态转录后机制重塑编码潜能以影响细胞状态。
method: 结合长读长转录组学、分级蛋白质组学及JAK1功能实验，分析巨噬细胞极化中的RNA切割。
result: 发现RNA切割在细胞转换早期达到峰值，产生保留特定结构域的异构体并改变了JAK1的信号传导。
conclusion: RNA切割是基因调节的自适应层，通过重塑转录本结构和扩展蛋白功能来驱动细胞命运决定。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后即已固定。我们此前已确定 RNA 切割（RNA dicing）是一种转录后过程，可产生稳定、无帽且具有翻译能力的 RNA 异构体。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化过程中重塑成熟转录本。长读长转录组学揭示了广泛的、命运特异性的切割现象，该现象在细胞状态转换早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为基因调节的一个适应性层级，它重编程了转录本架构，扩展了蛋白质功能多样性，并有助于塑造细胞状态转换。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

这篇论文深入探讨了成熟 mRNA 在加工完成后如何通过动态的转录后机制重塑编码潜能，以下是对该研究的详细总结：

### 1. 核心问题与整体含义
*   **研究动机：** 传统生物学观点认为，成熟 mRNA 的编码架构在转录和加工完成后是固定的。然而，细胞在快速状态转换（如免疫激活）时，如何通过现有转录本快速增加蛋白质功能多样性仍不清楚。
*   **核心问题：** 论文研究了“RNA 切割”（RNA dicing）这一机制是否作为一种受调控的程序，在巨噬细胞极化过程中动态重塑转录组架构，从而产生具有不同功能的蛋白质异构体。

### 2. 方法论
*   **核心思想：** RNA 切割通过在内部替代聚腺苷酸化（APA）位点切割成熟 mRNA，产生稳定、无帽但具有翻译能力的下游 RNA 片段。
*   **关键技术细节：**
    *   **长读长转录组学（Long-read RNA-seq）：** 用于精确解析转录本的 5' 和 3' 边界，将转录本分为 5' 端、全长（FL）和 3' 端（切割产物）三类。
    *   **DRIMSeq 统计框架：** 独立于总基因表达量，专门建模转录本异构体比例的变化，以捕捉切割事件。
    *   **同义密码子重编码（Synonymous Recoding）：** 通过改变 JAK1 的核苷酸序列但不改变氨基酸序列，破坏其 RNA 切割位点，从而在不影响全长蛋白序列的前提下研究切割的功能。
    *   **m6A 整合分析：** 结合 m6A-RIP 数据，证明切割产生的 neo-5' 端通过重新定位 m6A 修饰来获得非帽依赖性翻译能力。

### 3. 实验设计
*   **数据集与场景：** 使用 HL-60 人类早幼粒细胞白血病细胞系，通过 PMA 诱导分化，并分别使用 IFN-γ+LPS（M1 型）或 IL-4+IL-13（M2 型）进行极化。
*   **时间点：** 极化后的 12h、24h 和 72h。
*   **对比方法与 Benchmark：**
    *   **转录组：** 对比 DESeq2（基因水平丰度）与 DRIMSeq（异构体比例）。
    *   **蛋白质组：** 采用分级蛋白质组学（Size-resolved proteomics），将裂解物按分子量分为 10-40、40-80、80-180 kDa 三个组分进行质谱分析。
    *   **激酶活性：** 使用 PamChip 肽阵列对比全长 JAK1 与切割产生的 JH1 结构域对 166 种底物的磷酸化偏好。

### 4. 资源与算力
*   论文中**未明确说明**具体的 GPU 型号、数量或训练时长。其分析主要依赖于标准的生物信息学流程（如 HISAT2、DESeq2、DRIMSeq 等）和公共数据库（ENCODE、GEO、dbPTM）。

### 5. 实验数量与充分性
*   **实验规模：** 涵盖了从全局多组学（转录组、蛋白质组、m6A 图谱）到特定基因（JAK1）的功能验证。
*   **充分性：** 实验设计较为充分。通过时间序列采样捕捉到了切割的“瞬时性”特征；通过生化实验验证了切割产物的激酶活性差异；通过基因编辑（同义突变）验证了该机制对巨噬细胞极化的必要性。
*   **客观性：** 结合了计算预测与湿实验验证，使用了多种统计模型互补，实验逻辑闭环较强。

### 6. 主要结论与发现
*   **瞬时性程序：** RNA 切割是巨噬细胞极化早期的瞬时反应，在 12-24h 达到峰值，到 72h 基本恢复基线。
*   **结构域保留：** 切割位点优先位于蛋白质结构域之间，确保产生的截短蛋白保留完整的下游功能模块。
*   **功能重编程：** 以 JAK1 为例，切割产生的 JH1 模块具有更强的激酶活性和不同的底物偏好（偏向核蛋白和促炎信号），且该过程对 M1 型极化至关重要。
*   **蛋白质组重塑：** 证明了高分子量蛋白在极化期间会产生低分子量的稳定异构体，直接改变了细胞的信号传导状态。

### 7. 亮点与优点
*   **概念创新：** 挑战了“成熟 mRNA 架构固定”的教条，提出了 RNA 切割作为基因表达调节的自适应层。
*   **多组学整合：** 成功将长读长测序、分级质谱和生化底物分析结合，提供了从 RNA 到蛋白功能的完整证据链。
*   **机制深度：** 不仅发现了现象，还通过同义突变实验证明了 RNA 序列本身的调控功能，具有很强的说服力。

### 8. 不足与局限
*   **细胞系局限：** 主要研究集中在 HL-60 细胞系，尚需在原代巨噬细胞或其他组织类型中进一步验证。
*   **切割酶未知：** 虽然确定了切割现象受 APA 和 m6A 调控，但执行切割的具体内切核糖核酸酶（Endonuclease）尚未明确。
*   **机制普适性：** 虽然在数千个基因中观察到切割，但除了 JAK1 外，其他基因切割产物的具体生物学功能仍有待挖掘。

（完）
