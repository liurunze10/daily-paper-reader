---
title: Programmable synthetic cytokine receptors polarize macrophages to user-defined functional states
title_zh: 可编程合成细胞因子受体将巨噬细胞极化至用户定义的功能状态
authors: "Lunger, J. C., Sant'Anna, L. E., Salcido-Alcantar, A., Arroyo Hornero, R., Cho, W., Vaughan-Jackson, A., Gu, M., Liu, J. Y., Beckett, A. N., Parrilla-Garcia, J., Ramakrishna, S., Bassik, M. C., Daniels, K. G."
date: 2026-05-12
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.12.724672v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: 合成细胞因子受体可精确控制巨噬细胞向促炎或抗炎状态极化
tldr: 本研究开发了一种可编程合成细胞因子受体（SCR）平台，旨在精确控制原代人类巨噬细胞的极化状态。通过重组九种不同的信号基序，研究者成功模拟了促炎和抗炎特征，并生成了具有多样化功能（如吞噬能力）的合成巨噬细胞状态。实验证明，含有YLxQ基序的SCR能显著增强CAR-巨噬细胞对肿瘤细胞的吞噬作用，使小鼠肿瘤负荷降低30倍。该研究建立了一个定量预测模型，为癌症免疫治疗等领域的巨噬细胞工程化提供了新框架。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在开发一种能精确控制巨噬细胞极化至特定功能状态的技术，以深化生物学理解并改进细胞疗法。
method: 利用包含可编程信号结构域的合成细胞因子受体（SCR）平台，通过随机组合九种信号基序来诱导多样化的巨噬细胞状态。
result: 成功筛选出能显著增强吞噬作用的YLxQ基序，并在小鼠模型中实现了肿瘤负荷30倍的降低，同时建立了极化状态的定量预测模型。
conclusion: 该研究证明了通过合成信号基序编程巨噬细胞功能的可行性，为设计具有特定治疗特性的工程化免疫细胞提供了有力工具。
---

## 摘要
精确控制巨噬细胞极化至不同功能状态的技术将深化我们对巨噬细胞生物学的理解，并助力开发新型巨噬细胞细胞疗法。在本研究中，我们利用具有可编程信号结构域的合成细胞因子受体（SCR）平台来控制原代人类巨噬细胞的极化。包含来自干扰素-γ (IFN-γ) 或白细胞介素-10 (IL-10) 受体信号基序的 SCR 分别模拟了促炎或抗炎极化的关键特征。通过随机重组九种不同的信号基序来创建新的 SCR 信号结构域，产生了一系列具有多样化合成巨噬细胞状态的图谱，这些状态在炎症标志物（CD80、CD40）和抗炎标志物（CD163、CD206）的表达以及吞噬能力方面各不相同。经多个 YLxQ 基序编程的 SCR 增强了巨噬细胞对大肠杆菌的吞噬作用，以及嵌合抗原受体（CAR）巨噬细胞在小鼠体内对癌细胞的吞噬作用，使肿瘤负荷降低了 30 倍。这种依赖于基序的极化可以通过双态模型得到很好的描述，从而能够根据 SCR 信号结构域的组成定量预测巨噬细胞的极化状态。利用该模型，我们设计了一种既能增强吞噬作用又能维持巨噬细胞促炎状态的 SCR。总之，这些发现建立了一个巨噬细胞极化状态合成编程的框架，在癌症免疫治疗和其他疾病背景下具有潜在的应用价值。

## Abstract
Technology that precisely controls macrophage polarization to distinct functional states would deepen our understanding of macrophage biology and enable the development of new macrophage cell therapies. Here, we use a synthetic cytokine receptor (SCR) platform with a programmable signaling domain to control the polarization of primary human macrophages. SCRs containing signaling motifs from the interferon-gamma (IFN-{gamma}) or Interleukin-10 (IL-10) receptors mimic key features of pro-inflammatory or anti-inflammatory polarization, respectively. Random recombination of nine distinct signaling motifs to create new SCR signaling domains generates a diverse landscape of synthetic macrophage states with varied expression of inflammatory markers (CD80, CD40) and anti-inflammatory markers (CD163, CD206), and varied phagocytic capacity. SCRs programmed with multiple YLxQ motifs increase macrophage phagocytosis of E. coli and chimeric antigen receptor (CAR)-macrophage phagocytosis of cancer cells in mice, reducing tumor burden by 30-fold. The motif-dependent polarization is well-described by a two-state model, enabling quantitative prediction of macrophage polarization state from SCR signaling domain composition. Leveraging this model, we design an SCR that simultaneously enhances phagocytosis and maintains a macrophage pro-inflammatory state. Together, these findings establish a framework for synthetic programming of macrophage polarization states, with potential applications in cancer immunotherapy and other disease contexts.

---

## 论文详细总结（自动生成）

这是一份关于论文《Programmable synthetic cytokine receptors polarize macrophages to user-defined functional states》（可编程合成细胞因子受体将巨噬细胞极化至用户定义的功能状态）的深度结构化总结：

### 1. 论文的核心问题与整体含义（研究动机和背景）
*   **核心问题**：巨噬细胞在免疫反应中具有高度可塑性，通常在促炎（M1）和抗炎（M2）状态之间切换。然而，传统的生物学方法（如添加外源细胞因子）难以精确、持久且定向地控制巨噬细胞进入特定的功能状态。
*   **研究背景**：在癌症免疫治疗中，肿瘤微环境往往使巨噬细胞转向抑制免疫的 M2 状态。如何通过工程化手段，让巨噬细胞在复杂环境中维持强大的吞噬能力和促炎特性，是当前细胞疗法的重大挑战。
*   **整体含义**：本研究旨在开发一种**可编程的合成细胞因子受体（SCR）平台**，通过模块化的信号基序组合，实现对原代人类巨噬细胞极化状态的定量控制和功能定制。

### 2. 论文提出的方法论
*   **核心思想**：利用合成生物学手段，构建一种由胞外配体结合域、跨膜域和**可编程胞内信号域**组成的受体。
*   **关键技术细节**：
    *   **SCR 架构**：胞外使用 GFP 纳米抗体（LaG17）作为感应器，胞内段则是由不同的信号基序串联而成。
    *   **基序库构建**：研究者选择了 9 种来自天然细胞因子受体（如 IFN-γR1/2, IL-10RA/B, IL-4R 等）的信号基序（如 YLxQ, YDKPH, YVMS 等）。
    *   **随机重组**：通过 DNA 组装技术，将这些基序随机组合成包含 1 到 3 个基序的信号链，构建了一个多样化的 SCR 库。
    *   **定量预测模型**：建立了一个基于基序组成的**双态模型（Two-state model）**，通过线性回归等数学方法，定量描述不同基序对促炎（CD80/CD40）和抗炎（CD163/CD206）标志物表达的贡献权重。

### 3. 实验设计
*   **实验对象**：原代人类单核细胞源性巨噬细胞（hMDMs）。
*   **实验场景**：
    *   **体外筛选**：通过流式细胞术检测 144 种不同 SCR 组合对巨噬细胞表面标志物的影响。
    *   **功能验证**：测试巨噬细胞对荧光标记大肠杆菌（E. coli）的吞噬效率。
    *   **体内实验**：在人源肿瘤异种移植小鼠模型中，使用表达特定 SCR 的 CAR-M（嵌合抗原受体巨噬细胞）进行抗肿瘤治疗。
*   **Benchmark（基准对比）**：
    *   天然极化状态：使用 IFN-γ + LPS（M1 诱导）或 IL-4 + IL-10（M2 诱导）作为对照。
    *   对照组：表达空载体或仅含跨膜域的巨噬细胞。

### 4. 资源与算力
*   **算力说明**：论文中未明确提到使用大规模 GPU 算力或深度学习训练。其建立的定量预测模型主要基于统计学回归分析，这类计算通常在标准工作站或统计软件（如 R 或 Python 的 Scikit-learn）上即可完成。
*   **实验资源**：主要资源集中在原代细胞培养、病毒转导、流式细胞分选以及小鼠活体成像（IVIS）等生物医学实验设备。

### 5. 实验数量与充分性
*   **实验规模**：
    *   构建并测试了包含 **144 种** 不同信号结构域组合的 SCR 库。
    *   进行了多轮独立的原代供体重复实验（通常 n=3 到 n=6 个不同供体），以排除个体差异。
    *   体内实验包含了肿瘤负荷随时间变化的连续监测。
*   **充分性评价**：实验设计非常充分且逻辑严密。从体外基序筛选到数学模型建立，再到最终的体内功能验证，形成了一个完整的闭环。通过随机组合库进行无偏见筛选，保证了结果的客观性。

### 6. 论文的主要结论与发现
*   **YLxQ 基序的关键作用**：发现含有多个 YLxQ（来自 IL-10 信号链）基序的 SCR 能显著增强巨噬细胞的吞噬能力。
*   **极化状态的可预测性**：巨噬细胞的极化并非简单的线性关系，但可以通过基序的线性组合进行有效预测。
*   **打破天然限制**：成功设计出一种新型 SCR，它既能诱导高水平的吞噬作用（通常是 M2 特性），又能维持 CD80/CD40 的高表达（M1 特性），实现了天然状态下罕见的“功能解耦”。
*   **显著的疗效**：在小鼠模型中，经过优化 SCR 编程的 CAR-M 细胞将肿瘤负荷降低了 **30 倍**，显著优于传统的 CAR-M。

### 7. 优点
*   **模块化与可编程性**：提供了一个通用的框架，可以根据需要定制免疫细胞的功能，而不局限于巨噬细胞。
*   **定量化研究**：将定性的细胞极化描述转化为定量的数学模型，提升了合成生物学设计的精确度。
*   **临床应用潜力**：直接在原代人类细胞上进行实验，并证明了在实体瘤治疗中的巨大潜力。

### 8. 不足与局限
*   **基序库规模**：虽然测试了 144 种组合，但相对于潜在的数百万种基序排列，探索空间仍有待扩大。
*   **长期稳定性**：合成受体在体内长期存在后的免疫原性以及是否会引起细胞因子风暴等副作用，仍需更长期的观察。
*   **微环境复杂性**：实验室模型难以完全模拟人类复杂的肿瘤微环境（TME），SCR 在多变环境下的鲁棒性有待进一步验证。

（完）
