---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重塑功能性转录组架构
authors: "Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: RNA切割作为巨噬细胞极化过程中的转录后程序
tldr: 该研究揭示了RNA切割（RNA dicing）作为一种瞬时转录后调控机制，在巨噬细胞极化过程中重塑成熟mRNA。通过长读长转录组学和蛋白质组学分析，研究发现这种切割发生在特定蛋白质结构域之间，产生具有翻译能力的稳定异构体，进而生成功能独特的截短蛋白（如JAK1的JH1激酶模块）。这一过程扩展了蛋白质功能多样性，是细胞状态转换的关键调节层。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究成熟mRNA在转录和加工完成后，是否存在进一步的转录后重塑机制来调节巨噬细胞极化等细胞状态转换。
method: 利用长读长转录组学和分级蛋白质组学技术，结合JAK1作为机制模型，研究巨噬细胞极化过程中的RNA切割现象。
result: 发现RNA切割在细胞状态转换早期达到峰值，能产生保留下游编码模块的稳定异构体，并证实截短的JAK1蛋白具有独特的底物偏好。
conclusion: RNA切割是一种适应性基因调节层，通过重塑转录本结构和扩展蛋白质功能多样性，在调控巨噬细胞促炎极化中发挥关键作用。
---

## 摘要
成熟 mRNA 的编码潜力通常被认为在转录和 RNA 加工完成后即已固定。我们此前已确定 RNA 切割（RNA dicing）是一种转录后过程，可产生稳定、无帽且具有翻译能力的 RNA 异构体。在此，我们发现 RNA 切割是一种瞬时转录后程序，可在巨噬细胞极化过程中重塑成熟转录本。长读长转录组学揭示了广泛的、命运特异性的切割现象，该现象在细胞状态转换早期达到峰值，并优先发生在蛋白质结构域之间，从而保留了下游编码模块。分级蛋白质组学将这些 RNA 异构体与截短的蛋白质产物联系起来，表明切割重塑了蛋白质组输出。以 JAK1 作为机制模型，我们证明破坏切割会损害巨噬细胞向促炎状态的极化。从机制上讲，切割产生的 JH1 激酶模块表现出独特的底物偏好，并改变了相对于全长 JAK1 的下游信号传导。这些发现确立了 RNA 切割作为基因调节的一个适应性层级，它重编程了转录本架构，扩展了蛋白质功能多样性，并有助于塑造细胞状态转换。

## Abstract
The coding potential of mature mRNAs is generally considered fixed once transcription and RNA processing are complete. We previously established RNA dicing as a post-transcriptional process that generates stable, uncapped, translation-competent RNA isoforms. Here, we identify RNA dicing as a transient post-transcriptional program that remodels mature transcripts during macrophage polarization. Long-read transcriptomics reveals widespread, fate-specific dicing that peaks during early cell-state transitions and preferentially occurs between protein domains, preserving downstream coding modules. Fractionated proteomics links these RNA isoforms to truncated protein products, indicating that dicing reshapes proteomic output. Using JAK1 as a mechanistic model, we show that disruption of dicing, impairs macrophage polarization towards pro-inflammatory states. Mechanistically, a diced JH1 kinase module displayed distinct substrate preferences and alters downstream signaling relative to full-length JAK1. These findings establish RNA dicing as an adaptive layer of gene regulation that reprograms transcript architecture, expands protein functional diversity, and helps shape cell-state transitions.

---

## 论文详细总结（自动生成）

这是一份关于论文《Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization》的深度结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：传统观点认为成熟 mRNA 的编码架构在转录和加工后是固定的。本研究探讨是否存在一种动态的转录后机制，能在不依赖新转录的情况下，通过重塑现有成熟 mRNA 来快速改变蛋白质功能，从而驱动细胞状态（如巨噬细胞极化）的转换。
*   **背景**：作者此前发现了 **RNA 切割（RNA dicing）** 现象，即成熟 mRNA 在内部多聚腺苷酸化（APA）位点被切割，产生稳定、无帽但可翻译的下游 RNA 片段。本研究旨在证明这一过程在生理状态转换中是受调控的程序，而非随机的降解。

### 2. 方法论：核心思想与关键技术
*   **核心思想**：RNA 切割作为一种“分解式”的转录后重编程手段，在细胞接收到分化信号后，迅速将现有的全长转录本切割成功能模块化的异构体，从而产生与全长蛋白功能迥异（甚至相反）的截短蛋白。
*   **关键技术细节**：
    *   **长读长转录组学（Long-read RNA-seq）**：用于精确识别转录本的 5' 和 3' 端边界，区分全长（FL）与切割产生的 3' 异构体。
    *   **DRIMSeq 统计框架**：不同于常规的 DESeq2（检测基因总丰度），DRIMSeq 用于建模转录本比例的变化，从而识别“差异切割”事件。
    *   **m6A 映射集成**：分析 m6A 修饰如何重新定位到切割后的新 5' 端，从而介导无帽翻译。
    *   **同义密码子置换（Synonymous Recoding）**：通过改变 JAK1 的核苷酸序列但不改变氨基酸，破坏其 RNA 上的切割信号，以此作为实验模型验证切割的功能必要性。
    *   **激酶底物谱分析（PamChip）**：对比全长 JAK1 与切割产生的 JH1 结构域在 166 种肽段底物上的磷酸化动力学。

### 3. 实验设计与对比
*   **实验场景**：人类早幼粒白血病细胞系 HL-60，通过 PMA 诱导分化为单核/巨噬细胞，再分别用 IFNγ+LPS 诱导为 M1 型（促炎）或用 IL-4+IL-13 诱导为 M2 型（抗炎）。
*   **时间点**：分化后的 12h、24h 和 72h。
*   **对比对象（Benchmark）**：
    *   **方法对比**：对比了 DESeq2（基因水平）与 DRIMSeq（异构体水平）在识别细胞状态转换中的差异。
    *   **模型对比**：对比了野生型（WT）JAK1 与切割缺陷型（CO+）JAK1 对巨噬细胞极化标志物（如 TNFα, IRF1）的影响。
    *   **生化对比**：对比了重组全长 JAK1 蛋白与单独的 JH1 激酶结构域的底物偏好。

### 4. 资源与算力
*   **数据来源**：使用了 ENCODE 数据库的公开长读长 RNA-seq 数据（GSE219923）以及公开的 m6A-RIP-seq 数据。
*   **算力说明**：文中**未明确说明**具体的 GPU 型号、数量或训练时长。由于该研究侧重于生物信息学分析和分子生物学实验，而非深度学习模型训练，其算力需求主要集中在序列比对和统计建模上。

### 5. 实验数量与充分性
*   **实验规模**：
    *   分析了数千个基因在不同极化方向和时间点的切割动态。
    *   进行了分级蛋白质组学验证（10-40, 40-80, 80-180 kDa 三个组分）。
    *   针对 JAK1 进行了详细的分子机制实验，包括 qPCR、Western Blot、ELISA 阵列和体外激酶活性分析。
*   **充分性评价**：实验设计非常充分且具有多维度互证（转录组+蛋白质组+生化活性+表型功能）。通过同义突变排除蛋白质序列改变的影响，使得结论非常客观、公平。

### 6. 主要结论与发现
*   **瞬时性**：RNA 切割是一个瞬时程序，在极化早期（12-24h）达到峰值，随后在 72h 趋于平息，与长期稳定的转录程序形成互补。
*   **空间特异性**：切割位点优先位于蛋白质结构域之间，确保了产生的截短蛋白保留完整的下游功能模块。
*   **功能重塑**：以 JAK1 为例，切割产生的 JH1 模块失去了膜定位和抑制性结构域，转而进入细胞核，且对底物的偏好发生了显著偏移（更偏向核蛋白和应激信号通路）。
*   **生理必要性**：破坏 JAK1 的切割会显著抑制巨噬细胞向 M1 型促炎状态的转化。

### 7. 优点与亮点
*   **视角独特**：挑战了“成熟 mRNA 架构固定”的传统教条，提出了“分解式”基因调控的新层级。
*   **技术融合**：巧妙结合了长读长测序和分级蛋白质组学，解决了短读长测序无法区分转录本完整性的痛点。
*   **机制深入**：不仅发现了现象，还通过 JAK1 模型深入到了底物动力学和信号通路重构的层面。

### 8. 不足与局限
*   **机制细节尚缺**：虽然确定了 APA 和 m6A 的参与，但具体是哪些内切酶（Endonucleases）负责执行切割，以及这些酶如何被极化信号特异性激活，仍不清楚。
*   **细胞系局限**：主要实验基于 HL-60 细胞系，虽然使用了原代单核细胞数据进行验证，但其在更多原代组织和复杂体内环境中的普适性有待进一步证实。
*   **应用限制**：目前尚不清楚如何通过药物手段特异性地干预 RNA 切割过程而不影响正常的 APA 或翻译机制。

（完）
