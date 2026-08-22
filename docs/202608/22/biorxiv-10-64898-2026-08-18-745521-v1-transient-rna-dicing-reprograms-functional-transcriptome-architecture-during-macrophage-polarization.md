---
title: Transient RNA dicing reprograms functional transcriptome architecture during macrophage polarization
title_zh: 瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构
authors: "Malka, Y."
date: 2026-08-20
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.18.745521v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: RNA切割作为一种转录后程序，在巨噬细胞极化过程中重塑成熟转录本
tldr: 该研究揭示了RNA切割（RNA dicing）作为一种瞬时转录后调控机制，在巨噬细胞极化过程中重塑成熟mRNA。通过长读长转录组学和蛋白质组学分析，研究发现这种切割发生在特定蛋白质结构域之间，产生具有翻译能力的稳定异构体，进而生成功能独特的截短蛋白（如JAK1的JH1激酶模块）。这一过程扩展了蛋白质功能多样性，是细胞状态转换的关键调节层。
source: biorxiv
selection_source: fresh_fetch
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

### 论文总结：瞬时 RNA 切割在巨噬细胞极化过程中重编程功能性转录组架构

#### 1. 核心问题与整体含义（研究动机和背景）
传统的分子生物学教条认为，成熟 mRNA 的编码潜力在转录和加工完成后是固定的。然而，该研究挑战了这一观点。研究背景基于作者此前发现的 **RNA 切割（RNA dicing）** 现象——即成熟 mRNA 可以在内部多聚腺苷酸化（APA）位点发生切割，产生稳定、无帽且具有翻译能力的下游 RNA 异构体。

**核心问题**：这种 RNA 切割机制是否在生理性的细胞状态转换（如巨噬细胞极化）中发挥动态调节作用？它如何通过重塑现有的转录组来扩展蛋白质的功能多样性，从而在不依赖大规模新生转录的情况下实现细胞命运的快速转变？

#### 2. 方法论：核心思想与关键技术
*   **核心思想**：RNA 切割不是随机的降解，而是一个受调控的、瞬时的转录后程序，它通过在蛋白质结构域之间精确切割，产生功能独特的截短蛋白模块。
*   **关键技术细节**：
    *   **长读长转录组学（Long-read RNA-seq）**：用于精确解析转录本的 5' 和 3' 边界，将转录本分类为 5' 端片段、全长（FL）和 3' 端切割异构体。
    *   **DRIMSeq 统计框架**：不同于传统的 DESeq2（衡量基因总丰度），DRIMSeq 用于检测异构体组成比例的变化，从而识别“切割”事件。
    *   **分级蛋白质组学（Size-resolved Proteomics）**：通过 SDS-PAGE 将蛋白质按分子量分级（10-40, 40-80, 80-180 kDa）并进行质谱分析，验证 RNA 切割是否产生了对应的截短蛋白。
    *   **同义密码子重编码（Synonymous Recoding）**：以 JAK1 为模型，通过改变约 20% 的核苷酸序列（保留氨基酸序列不变）来破坏其 RNA 结构/切割位点，从而特异性干扰切割过程。
    *   **激酶底物阵列（PamChip PTK Array）**：对比全长 JAK1 与切割产生的 JH1 模块在 166 种肽段底物上的磷酸化动力学。

#### 3. 实验设计
*   **实验模型**：使用人早幼粒白血病细胞系 **HL-60**，通过 PMA 诱导分化为巨噬细胞，再分别使用 IFNγ+LPS 诱导 M1 型（促炎）极化，或使用 IL-4+IL-13 诱导 M2 型（抗炎）极化。
*   **时间序列**：设置了 12h、24h 和 72h 三个关键时间点，捕捉极化的动态过程。
*   **对比基准（Benchmark）**：
    *   未处理状态 vs. PMA 处理状态。
    *   M1 极化 vs. M2 极化。
    *   野生型（WT）JAK1 vs. 切割缺陷型（CO+）JAK1。
*   **验证场景**：通过整合 m6A-RIP-seq 数据，分析 m6A 修饰在切割位点附近的分布，验证其对无帽转录本翻译的许可作用。

#### 4. 资源与算力
*   论文中**未明确说明**具体的计算资源（如 GPU 型号、数量或训练时长）。
*   由于该研究主要涉及生物信息学分析（长读长测序比对、差异表达统计）和生化实验数据处理，而非深度学习模型训练，因此对大规模 GPU 算力的需求相对较低，更多依赖于高通量测序平台和标准的生物信息学服务器集群。

#### 5. 实验数量与充分性
*   **实验规模**：研究涵盖了从全局组学（转录组、蛋白质组）到单基因机制（JAK1）的深入分析。
    *   分析了数千个基因的切割动态。
    *   对 JAK1 进行了详细的生化表征（底物偏好、信号通路 ELISA、Western Blot）。
    *   利用了公开的 ENCODE 数据集和 m6A 映射数据进行交叉验证。
*   **充分性与客观性**：实验设计较为充分且具有多维度证据链。通过同义突变实验排除了蛋白质序列改变的影响，增强了结论的客观性。时间序列的设计揭示了该过程的“瞬时性”，这在以往研究中常被忽略。

#### 6. 主要结论与发现
*   **瞬时性**：RNA 切割在极化早期（12-24h）达到峰值，随后在 72h 趋于消退，与长期稳定的转录程序形成互补。
*   **空间特异性**：切割位点优先位于蛋白质结构域之间，保护了下游功能模块（如激酶域）的完整性。
*   **功能重塑**：以 JAK1 为例，切割产生的 JH1 模块失去了抑制性的 JH2 域，表现出更高的激酶活性和截然不同的底物偏好（更偏向核蛋白和应激信号通路）。
*   **生理必要性**：破坏 JAK1 的切割会显著损害巨噬细胞向 M1 型极化的能力，证明该机制对细胞命运决定至关重要。

#### 7. 优点与亮点
*   **概念创新**：打破了成熟 mRNA 是“静态产物”的传统认知，提出了“转录后重编程”的新层级。
*   **技术融合**：巧妙结合了长读长测序和分级蛋白质组学，解决了短读长测序无法区分异构体完整性的痛点。
*   **机制深入**：不仅发现了现象，还通过 JAK1 模型深入到了生化动力学（底物偏好改变）和细胞功能层面。

#### 8. 不足与局限
*   **细胞系局限**：主要研究基于 HL-60 细胞系，虽然这是一个经典模型，但在原代巨噬细胞中的普适性仍需进一步验证。
*   **内切酶身份未知**：虽然确定了 APA 位点和 m6A 的参与，但直接负责执行切割的内切酶（Endonuclease）身份尚未完全明确。
*   **因果链条细节**：m6A 如何在切割后被精确“重新定位”并激活翻译的分子细节仍有待进一步阐明。
*   **应用限制**：目前尚不清楚这种机制在其他快速反应系统（如神经元激活或热休克反应）中的普遍程度。

（完）
