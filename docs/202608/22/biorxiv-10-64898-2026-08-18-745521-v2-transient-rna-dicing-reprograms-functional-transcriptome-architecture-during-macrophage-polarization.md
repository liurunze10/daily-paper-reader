---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Twaik, N., Yakov, O., Haj Yahia, D., Bistritzer, T., Abu-Rahmah, R., Turgeman, H., Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: RNA切割在巨噬细胞极化过程中重编程功能性转录组
tldr: 本研究揭示了RNA切割（dicing）作为一种瞬时转录后调控程序，在巨噬细胞极化中重塑成熟转录本。通过长读长转录组学和蛋白质组学，研究发现切割产生的稳定RNA异构体能翻译成功能独特的截短蛋白（如JAK1激酶模块），从而改变信号传导并驱动细胞状态转换。该发现确立了RNA切割是扩展蛋白质功能多样性和调节基因表达的新机制。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在探索成熟mRNA在转录完成后是否通过动态的转录后修饰来重塑其编码功能并调节免疫细胞极化。
method: 采用长读长转录组学和分级蛋白质组学分析巨噬细胞极化过程，并以JAK1为模型研究其分子机制。
result: 证实了RNA切割在细胞转换早期广泛发生，能产生保留特定结构域的稳定异构体，并改变了JAK1等蛋白的底物偏好。
conclusion: RNA切割是基因调节的一个适应性层面，通过重构转录本架构和增加蛋白质功能多样性来协同塑造细胞状态。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后就已固定。我们此前已确定 RNA 切割（RNA dicing）是一种转录后过程，可产生稳定、无帽且具有翻译能力的 RNA 异构体。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化过程中重塑成熟转录本。长读长转录组学揭示了广泛存在的、细胞命运特异性的切割现象，该现象在细胞状态转换早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割过程会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为一种适应性基因调节层，能够重编程转录本架构，扩展蛋白质功能多样性，并有助于塑造细胞状态转换。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

### 论文总结：瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构

#### 1. 核心问题与整体含义（研究动机和背景）
传统的分子生物学观点认为，成熟 mRNA 的编码潜力在转录和加工完成后是固定的。然而，本研究挑战了这一假设，探讨了 **RNA 切割（RNA dicing）** 这一转录后调控机制。研究背景聚焦于巨噬细胞极化（向促炎 M1 或抗炎 M2 状态转换）这一动态生理过程。核心问题是：细胞是否通过在成熟转录本内部进行受控的二次切割，从而在不依赖新转录的情况下，快速产生功能迥异的蛋白质异构体，以应对环境变化。

#### 2. 论文提出的方法论
研究提出了一种整合多组学的分析框架，旨在识别并验证 RNA 切割的功能：
*   **长读长转录组分析（Long-read RNA-seq）**：通过精确解析转录本的 5' 和 3' 边界，将转录本分类为 5' 截短型、全长型（FL）和 3' 异构体（即切割产物）。
*   **同义密码子置换技术**：以 JAK1 激酶为模型，通过改变约 20% 的核苷酸序列（保持氨基酸序列不变）来破坏其内部的切割信号（如 APA 位点、RNA 结构），从而在不改变蛋白质序列的前提下特异性抑制 RNA 切割。
*   **分级蛋白质组学（Size-resolved Proteomics）**：利用 SDS-PAGE 将蛋白质按分子量分级（10-40, 40-80, 80-180 kDa），通过质谱检测高分子量基因是否产生了低分子量的稳定蛋白产物。
*   **激酶底物阵列（PamChip）**：对比全长 JAK1 与切割产生的 JH1 激酶模块在 166 种肽段底物上的磷酸化动力学，量化其功能差异。

#### 3. 实验设计
*   **细胞模型与场景**：使用人早幼粒白血病细胞系 HL-60，通过 PMA 诱导分化，再分别使用 IFNγ+LPS（M1 极化）或 IL-4+IL-13（M2 极化）处理，观察 12h、24h 和 72h 的动态变化。
*   **数据集与 Benchmark**：
    *   使用了 ENCODE 门户的公开长读长 RNA-seq 数据。
    *   整合了公开的 m6A-RIP-seq 数据分析修饰位点。
    *   **对比方法**：使用 DESeq2（常规基因水平差异表达）与 DRIMSeq（异构体比例差异分析）进行对比，证明常规分析会掩盖切割导致的转录本重塑。
*   **功能验证**：对比野生型（WT）JAK1 与切割缺陷型（CO+）JAK1 在巨噬细胞分化标志物（如 TNFα, IRF1）表达上的差异。

#### 4. 资源与算力
论文中**未明确说明**具体的计算资源（如 GPU 型号、数量或训练时长）。由于该研究主要涉及生物信息学管线分析（HISAT2, DESeq2, DRIMSeq 等）和湿实验生化分析，而非深度学习模型训练，因此对高性能 GPU 算力的需求相对较低，重点在于高通量测序数据的处理。

#### 5. 实验数量与充分性
实验设计非常全面且具有多维度互证性：
*   **多组学覆盖**：涵盖了转录组（长读长）、修饰组（m6A）、蛋白质组（分级质谱）和生化表型。
*   **时间序列**：设置了极化前后的多个关键时间点，捕捉到了切割现象的“瞬时性”特征。
*   **模型深度**：对 JAK1 进行了深入的机制研究，包括同义突变体验证和体外激酶活性动力学分析。
*   **客观性**：通过随机打乱（shuffled control）和内源性对照（如天然小分子蛋白的分级对照）确保了实验结果的客观性。实验组数足以支持其关于“RNA 切割是受控程序而非随机降解”的结论。

#### 6. 主要结论与发现
*   **瞬时性重塑**：RNA 切割是巨噬细胞极化早期的普遍现象，在 12-24h 达到峰值，到 72h 基本恢复，与长期转录程序形成互补。
*   **空间特异性**：切割位点优先位于蛋白质结构域之间，从而保留了完整的下游功能模块（如激酶域）。
*   **翻译许可**：切割产生的无帽 3' 异构体通过重新定位内部 m6A 修饰到新生成的 5' 端，获得了翻译能力。
*   **功能多样化**：以 JAK1 为例，切割产生的 JH1 模块失去了抑制性结构域，表现出更强的核定位能力和完全不同的底物偏好（偏向核蛋白和应激信号通路），这对 M1 极化是必需的。

#### 7. 优点：方法或实验设计上的亮点
*   **视角独特**：打破了“成熟 mRNA 即终点”的传统认知，提出了“转录本作为模块化底物”的新模型。
*   **同义突变设计的精妙**：通过同义密码子改变 RNA 结构而不改变蛋白序列，完美解决了如何特异性研究转录后切割功能的问题。
*   **功能关联紧密**：不仅发现了现象，还通过激酶底物阵列从生化本质上解释了异构体如何改变细胞信号传导。

#### 8. 不足与局限
*   **机制细节尚缺**：虽然确定了 APA 和 m6A 的参与，但具体是哪些内切核酸酶负责执行切割，以及这些酶如何被信号通路精确调控，仍不清楚。
*   **细胞系局限**：主要研究集中在 HL-60 细胞系，虽然使用了单核细胞的公开数据验证，但在原代巨噬细胞或体内模型中的普遍性仍待进一步证实。
*   **应用限制**：目前尚不清楚这种机制在免疫系统之外（如神经系统或发育过程）的贡献比例。

（完）
