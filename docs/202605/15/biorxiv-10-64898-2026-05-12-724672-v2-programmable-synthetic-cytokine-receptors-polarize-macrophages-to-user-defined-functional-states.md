---
title: Programmable synthetic cytokine receptors polarize macrophages to user-defined functional states
title_zh: 可编程合成细胞因子受体将巨噬细胞极化至用户定义的功能状态
authors: "Lunger, J. C., Sant'Anna, L. E., Salcido-Alcantar, A., Arroyo Hornero, R., Cho, W., Vaughan-Jackson, A., Gu, M., Liu, J. Y., Beckett, A. N., Parrilla-Garcia, J., Ramakrishna, S., Bassik, M. C., Daniels, K. G."
date: 2026-05-14
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.12.724672v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 将巨噬细胞极化为用户定义的功能状态
tldr: 本研究开发了一种可编程合成细胞因子受体（SCR）平台，通过重组不同的信号基序精确控制原代人类巨噬细胞的极化状态。研究人员利用该平台模拟了促炎和抗炎特征，并发现含有YLxQ基序的SCR能显著增强巨噬细胞的吞噬能力，在小鼠模型中使肿瘤负荷降低30倍。该研究建立了一个定量预测模型，为设计具有特定功能的巨噬细胞疗法提供了新框架。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在开发一种能精确控制巨噬细胞极化至特定功能状态的技术，以深化生物学理解并赋能细胞疗法。
method: 利用包含多种信号基序的可编程合成细胞因子受体（SCR）平台，通过随机重组基序来定制巨噬细胞的信号传导。
result: 成功产生多样化的合成极化状态，其中特定基序显著提升了巨噬细胞对细菌和肿瘤细胞的吞噬效率，使肿瘤负荷降低30倍。
conclusion: 该研究证明了通过合成信号域编程巨噬细胞状态的可行性，并为癌症免疫治疗等领域提供了定量设计框架。
---

## 摘要
精确控制巨噬细胞极化至不同功能状态的技术将加深我们对巨噬细胞生物学的理解，并推动新型巨噬细胞细胞疗法的发展。在本研究中，我们利用具有可编程信号结构域的合成细胞因子受体（SCR）平台来控制原代人类巨噬细胞的极化。包含来自干扰素-γ（IFN-γ）或白细胞介素-10（IL-10）受体信号基序的 SCR 分别模拟了促炎或抗炎极化的关键特征。通过随机重组九种不同的信号基序来构建新的 SCR 信号结构域，产生了一系列具有不同炎症标志物（CD80、CD40）和抗炎标志物（CD163、CD206）表达以及不同吞噬能力的合成巨噬细胞状态。编程有多个 YLxQ 基序的 SCR 增强了巨噬细胞对大肠杆菌的吞噬作用，并提高了嵌合抗原受体（CAR）-巨噬细胞在小鼠体内对癌细胞的吞噬能力，使肿瘤负荷降低了 30 倍。这种基于基序的极化可以通过双状态模型进行良好描述，从而能够根据 SCR 信号结构域的组成定量预测巨噬细胞的极化状态。利用该模型，我们设计了一种能够同时增强吞噬作用并维持巨噬细胞促炎状态的 SCR。总之，这些研究结果建立了一个巨噬细胞极化状态合成编程的框架，在癌症免疫治疗及其他疾病领域具有潜在的应用前景。

## Abstract
Technology that precisely controls macrophage polarization to distinct functional states would deepen our understanding of macrophage biology and enable the development of new macrophage cell therapies. Here, we use a synthetic cytokine receptor (SCR) platform with a programmable signaling domain to control the polarization of primary human macrophages. SCRs containing signaling motifs from the interferon-gamma (IFN-{gamma}) or Interleukin-10 (IL-10) receptors mimic key features of pro-inflammatory or anti-inflammatory polarization, respectively. Random recombination of nine distinct signaling motifs to create new SCR signaling domains generates a diverse landscape of synthetic macrophage states with varied expression of inflammatory markers (CD80, CD40) and anti-inflammatory markers (CD163, CD206), and varied phagocytic capacity. SCRs programmed with multiple YLxQ motifs increase macrophage phagocytosis of E. coli and chimeric antigen receptor (CAR)-macrophage phagocytosis of cancer cells in mice, reducing tumor burden by 30-fold. The motif-dependent polarization is well-described by a two-state model, enabling quantitative prediction of macrophage polarization state from SCR signaling domain composition. Leveraging this model, we design an SCR that simultaneously enhances phagocytosis and maintains a macrophage pro-inflammatory state. Together, these findings establish a framework for synthetic programming of macrophage polarization states, with potential applications in cancer immunotherapy and other disease contexts.

---

## 论文详细总结（自动生成）

这篇论文介绍了一种通过可编程合成细胞因子受体（SCR）精确控制原代人类巨噬细胞极化状态的创新技术。以下是对该论文的结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
巨噬细胞在免疫反应中具有极高的可塑性，能够根据环境信号极化为促炎（M1型）或抗炎（M2型）等多种功能状态。然而，传统的极化方法（如外源细胞因子刺激或基因敲除）缺乏精确性和多维度控制能力。
*   **研究动机**：如何通过工程化手段，在不依赖外部配体的情况下，精确且可编程地引导巨噬细胞进入特定的功能状态，以优化其在癌症免疫治疗（如 CAR-M）中的表现。
*   **核心问题**：能否通过重组细胞因子受体中的短线性信号基序，构建一套合成受体系统，实现对巨噬细胞表型（如吞噬能力、炎症标志物表达）的定量预测和定制化编程。

### 2. 论文提出的方法论
研究者开发了**合成细胞因子受体（SCR）平台**，其核心思想是利用模块化设计模拟天然受体的信号传导：
*   **SCR 结构**：包含胞外二聚化结构域（Put3 卷曲螺旋）、跨膜域（EpoR）和胞内信号域。胞内域由 JAK 结合基序（gp130 box）和可更换的**短线性信号基序（Motifs）**组成。
*   **信号基序库**：筛选了 9 种来自天然受体（如 IFNGR1, IL-10R, IL-4R 等）的信号基序（S1-S9），这些基序作为下游效应分子的对接位点。
*   **双状态模型（Two-state Model）**：
    *   假设细胞表型在“开启（ON）”和“关闭（OFF）”两个状态间平衡。
    *   通过公式 $K = K_i \cdot \prod K_s$（其中 $K_i$ 是固有极化常数，$K_s$ 是每个基序的贡献系数）来定量描述基序组合对表型的影响。
    *   该模型允许研究者根据已知的基序数据，预测未测试过的复杂基序组合产生的表型。

### 3. 实验设计
*   **实验对象**：原代人类单核细胞衍生的巨噬细胞（来自多个健康供体）。
*   **基序组合库**：构建了包含 131 种独特 SCR 的库（包含 0 到 3 个基序的随机组合）。
*   **Benchmark（基准对比）**：
    *   外源配体刺激：LPS + IFN-γ, IFN-γ, IL-10, IL-4, GM-CSF。
    *   对照组：不含信号基序的 SCR0。
*   **评估维度**：
    *   **表型测量**：流式细胞术检测表面标志物（CD40, CD80, CD163, CD206, PDL1）及大肠杆菌吞噬实验。
    *   **转录组分析**：Bulk RNA-seq 验证 SCR 诱导的状态是否能模拟天然细胞因子的转录特征。
    *   **临床相关性**：将 SCR(S1-S1) 的基因特征与接受 CAR-T 治疗的脑胶质瘤患者的单细胞 RNA-seq 数据进行比对。
    *   **功能验证**：体外 CAR-M 杀伤实验（针对 HER2+ 肿瘤细胞）及体内 NSG 小鼠卵巢癌（SKOV3）异种移植模型。

### 4. 资源与算力
*   论文中**未明确说明**具体的 GPU 型号或计算时长。
*   计算工作主要集中在：RNA-seq 数据处理（Salmon, DESeq2）、双状态模型的拟合（使用 R 和 Mathematica 软件）以及 scRNA-seq 的 UMAP 降维分析。这些任务通常对算力要求适中，标准工作站即可完成。

### 5. 实验数量与充分性
*   **实验规模**：进行了 131 种 SCR 组合的阵列化筛选，每种组合至少有 3 个生物学重复。
*   **充分性**：
    *   **多供体验证**：RNA-seq 使用了 3 个不同供体，确保了结果的普适性。
    *   **模型验证**：采用了 10 折交叉验证（10-fold cross-validation）来评估双状态模型的预测准确性。
    *   **体内外结合**：从体外表型筛选到体内肿瘤模型验证，逻辑链条完整。
*   **客观性**：通过与多种标准细胞因子刺激效果进行横向对比，客观展示了 SCR 系统的优越性和独特性。

### 6. 论文的主要结论与发现
*   **功能模拟与超越**：SCR(S1-S1) 和 SCR(S3-S3) 能分别完美模拟 IFN-γ 和 IL-10 诱导的转录程序，且效应强度往往超过天然细胞因子。
*   **吞噬能力增强**：含有 S2 或 S3 基序（YLxQ 序列）的 SCR 显著提升了巨噬细胞的吞噬效率。在小鼠模型中，CAR-SCR(S2-S2-S2)-M 使肿瘤负荷比常规 CAR-M 降低了 **30 倍**。
*   **打破表型权衡**：通过模型预测，设计出了 SCR(S3-S3-S3-S1)，成功解决了“高吞噬能力”与“高促炎状态”难以兼得的矛盾，实现了多维度表型的协同优化。
*   **临床一致性**：SCR 诱导的巨噬细胞状态与临床响应 CAR-T 治疗的患者体内观察到的髓系细胞特征高度相关。

### 7. 优点
*   **高度可编程性**：通过简单的基序重组即可导航复杂的极化景观，无需复杂的基因编辑。
*   **定量预测能力**：引入双状态模型，使免疫细胞工程从“试错法”转向“理性设计”。
*   **模块化兼容性**：SCR 作为一个独立模块，可以与现有的各种 CAR 结构结合，具有极强的应用灵活性。

### 8. 不足与局限
*   **基序库规模有限**：目前仅测试了 9 种基序，自然界中存在数百种细胞因子受体基序，潜在的组合空间尚未完全开发。
*   **长期稳定性风险**：SCR 采用组成型激活（Constitutive activation），虽然在实验周期内表现良好，但在长期临床应用中可能存在信号过载或细胞耗竭的风险。
*   **安全性考量**：强效的促炎极化可能在体内诱发细胞因子风暴（CRS），论文中对系统毒性的评估尚处于初步阶段。

（完）
