---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Twaik, N., Yakov, O., Haj Yahia, D., Bistritzer, T., Abu-Rahmah, R., Turgeman, H., Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: RNA切割在巨噬细胞极化过程中重编程转录组
tldr: 该研究揭示了RNA切割（RNA dicing）作为一种瞬时转录后调控机制，在巨噬细胞极化过程中重塑成熟mRNA。通过长读长转录组学和蛋白质组学分析，研究发现这种切割发生在特定蛋白质结构域之间，产生具有翻译能力的稳定异构体，进而生成功能独特的截短蛋白（如JAK1的JH1激酶模块）。这一过程扩展了蛋白质功能多样性，是细胞状态转换的关键调节层。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v2/fig-001.webp\", \"caption\": \"Figure 4. Dicing of JAK1 is required for M1 macrophage polarization\", \"page\": 38, \"index\": 1, \"width\": 1093, \"height\": 655}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v2/fig-002.webp\", \"caption\": \"Figure 2. RNA dicing is fate-specific and spatially coordinated with protein-domain architecture\", \"page\": 34, \"index\": 2, \"width\": 1065, \"height\": 785}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v2/fig-003.webp\", \"caption\": \"Figure 3. Size-resolved proteomics links RNA dicing to truncated protein isoforms\", \"page\": 36, \"index\": 3, \"width\": 1098, \"height\": 648}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-08-18-745521-v2/fig-004.webp\", \"caption\": \"Figure 1. RNA dicing is a transient, stage-specific program during macrophage polarization\", \"page\": 32, \"index\": 4, \"width\": 1048, \"height\": 639}]"
motivation: 探究成熟mRNA在转录和加工完成后，是否存在进一步的转录后重塑机制来调节巨噬细胞极化等细胞状态转换。
method: 利用长读长转录组学和分级蛋白质组学技术，结合JAK1作为机制模型，研究巨噬细胞极化过程中的RNA切割现象。
result: 发现RNA切割在细胞状态转换早期达到峰值，能产生保留下游编码模块的稳定异构体，并证实截短的JAK1蛋白具有独特的底物偏好。
conclusion: RNA切割是一种适应性基因调节层，通过重塑转录本结构和扩展蛋白质功能多样性，在调控巨噬细胞促炎极化中发挥关键作用。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后即已固定。我们此前已证实 RNA 切割（RNA dicing）是一种转录后过程，可产生稳定、无帽且具有翻译能力的 RNA 异构体。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化过程中重塑成熟转录本。长读长转录组学揭示了广泛存在且具有细胞命运特异性的切割现象，该现象在细胞状态转变早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割过程会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为一种适应性基因调节层，能够重编程转录本架构，扩展蛋白质功能多样性，并有助于塑造细胞状态的转变。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

这是一份关于论文《Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization》的深度结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：传统观点认为成熟 mRNA 的编码潜力在转录和加工完成后是固定的。本研究探讨是否存在一种动态的转录后机制，能在不依赖新转录的情况下，通过重塑现有成熟 mRNA 来快速改变蛋白质产物，从而驱动细胞状态（如巨噬细胞极化）的转换。
*   **背景**：作者此前发现了 **RNA 切割（RNA dicing）** 现象，即成熟 mRNA 在内部多聚腺苷酸化（APA）位点被切割，产生稳定、无帽但可翻译的下游异构体。本研究旨在证明这一过程并非随机降解，而是一个受调控的、具有生物学功能的基因表达调节层。

### 2. 方法论：核心思想与关键技术
*   **核心思想**：RNA 切割作为一种“分解代谢式”的重编程程序，在细胞接收到分化信号的早期（即转录程序尚未完全建立时），通过切割现有转录本产生功能独特的蛋白质模块（如激酶域），实现蛋白质组的快速多样化。
*   **关键技术细节**：
    *   **长读长转录组学（Long-read RNA-seq）**：用于精确识别转录本的 5' 和 3' 端边界，区分全长（FL）转录本与切割产生的 3' 异构体。
    *   **分级蛋白质组学（Size-resolved Proteomics）**：通过 SDS-PAGE 将蛋白质按分子量分级（10-40, 40-80, 80-180 kDa），追踪高分子量蛋白的肽段是否出现在低分子量组分中，以证实截短蛋白的产生。
    *   **m6A 映射集成**：分析 m6A 修饰如何重新定位到切割后的新 5' 端，从而介导无帽翻译。
    *   **同义密码子置换（Synonymous Recoding）**：在不改变氨基酸序列的前提下，通过改变核苷酸序列破坏 JAK1 的切割位点，从而特异性研究切割缺失的影响。

### 3. 实验设计
*   **数据集/场景**：使用人早幼粒白血病细胞系 **HL-60** 作为模型，通过 PMA 诱导分化为单核/巨噬细胞，再分别用 IFNγ+LPS 诱导为 M1 型（促炎）或用 IL-4+IL-13 诱导为 M2 型（抗炎）。
*   **Benchmark 与对比**：
    *   **分析框架对比**：对比了常规差异基因表达分析（DESeq2，关注总量）与差异异构体使用分析（DRIMSeq，关注结构变化）。
    *   **时间点对比**：分析了 12h、24h 和 72h 三个关键时间点。
    *   **分子模型对比**：对比了野生型（WT）JAK1 与切割缺陷型（CO+）JAK1 在极化过程中的表现。
    *   **生化对比**：利用 PamChip 肽阵列对比了全长 JAK1 与切割产生的 JH1 激酶模块的底物偏好。

### 4. 资源与算力
*   **算力说明**：论文中**未明确说明**具体的 GPU 型号、数量或训练时长。由于该研究主要涉及生物信息学分析（长读长测序比对、蛋白质组数据处理）和湿实验，其计算需求主要集中在测序数据的比对和统计建模上，而非大规模深度学习训练。

### 5. 实验数量与充分性
*   **实验规模**：
    *   涵盖了转录组（长读长）、蛋白质组（分级质谱）、生化（激酶阵列）、分子生物学（qPCR、WB）等多个维度。
    *   针对 M1/M2 两种极化路径进行了完整的时间序列采样。
    *   对 JAK1 进行了深入的机制验证，包括底物动力学分析（14 点滴定曲线）。
*   **充分性与公平性**：实验设计较为充分，通过同义突变排除蛋白质序列改变的影响，确保了观察到的表型源于 RNA 结构的改变。使用了生物学重复和多种统计校正方法（如 Benjamini-Hochberg），结果具有较高的客观性。

### 6. 主要结论与发现
*   **瞬时性**：RNA 切割是一个瞬时程序，在极化早期（12-24h）达到峰值，到 72h 基本恢复基线，与长期转录程序形成互补。
*   **空间特异性**：切割位点优先位于蛋白质结构域之间，保护了下游功能模块的完整性。
*   **功能重塑**：以 JAK1 为例，切割产生的 JH1 模块失去了 N 端调节域，导致其激酶活性增强、入核能力提升，且底物偏好从细胞骨架/膜相关蛋白转向核内/应激相关信号蛋白。
*   **生理必要性**：破坏 JAK1 的切割会显著抑制巨噬细胞向促炎 M1 状态的转化，证明该机制对细胞命运决定至关重要。

### 7. 优点：亮点与创新
*   **视角创新**：挑战了“成熟 mRNA 编码潜力固定”的教条，提出了“成熟转录本是可编程底物”的新观点。
*   **多组学整合**：成功将长读长测序的 RNA 结构变化与分级质谱的蛋白质分子量变化联系起来，提供了完整的证据链。
*   **机制深入**：不仅发现了现象，还通过激酶底物阵列从生化动力学角度解释了为什么截短蛋白具有不同的生物学功能。

### 8. 不足与局限
*   **机制细节尚不完全**：虽然确定了 APA 位点和 m6A 的作用，但具体是哪些内切酶负责切割、这些酶如何受信号通路调控仍不清楚。
*   **细胞系局限**：主要研究集中在 HL-60 细胞系，虽然具有代表性，但在原代巨噬细胞或体内环境中的普遍性仍需进一步验证。
*   **预测性偏差**：部分信号通路的重塑是基于生化实验的预测模型，实际细胞内的复杂反馈网络可能更为复杂。

（完）
