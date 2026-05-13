---
title: Programmable synthetic cytokine receptors polarize macrophages to user-defined functional states
title_zh: 可编程合成细胞因子受体将巨噬细胞极化至用户定义的功能状态
authors: "Lunger, J. C., Sant'Anna, L. E., Salcido-Alcantar, A., Arroyo Hornero, R., Cho, W., Vaughan-Jackson, A., Gu, M., Liu, J. Y., Beckett, A. N., Parrilla-Garcia, J., Ramakrishna, S., Bassik, M. C., Daniels, K. G."
date: 2026-05-12
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.12.724672v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 合成细胞因子受体将巨噬细胞极化为特定状态
tldr: 本研究开发了一种可编程合成细胞因子受体（SCR）平台，通过重组不同的信号基序精确控制原代人类巨噬细胞的极化状态。研究发现，包含特定YLxQ基序的SCR能显著增强巨噬细胞对细菌和癌细胞的吞噬能力，在小鼠模型中使肿瘤负荷降低30倍。此外，研究建立的双状态模型可预测并设计特定功能的巨噬细胞，为癌症免疫治疗提供了新策略。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在开发一种能精确控制巨噬细胞极化至特定功能状态的技术，以深化生物学理解并提升细胞疗法效果。
method: 利用包含九种不同信号基序的合成细胞因子受体（SCR）平台，通过随机重组构建具有多样化信号域的巨噬细胞。
result: 成功筛选出能显著增强吞噬能力并降低肿瘤负荷30倍的特定基序组合，并建立了可预测极化状态的定量模型。
conclusion: 该研究证明了通过合成信号域编程巨噬细胞状态的可行性，为设计具有定制化功能的免疫细胞疗法奠定了基础。
---

## 摘要
精确控制巨噬细胞极化至不同功能状态的技术将加深我们对巨噬细胞生物学的理解，并推动新型巨噬细胞细胞疗法的发展。在此，我们利用具有可编程信号结构域的合成细胞因子受体（SCR）平台来控制原代人类巨噬细胞的极化。包含来自干扰素-γ（IFN-γ）或白细胞介素-10（IL-10）受体信号基序的 SCR 分别模拟了促炎或抗炎极化的关键特征。通过随机重组九种不同的信号基序来创建新的 SCR 信号结构域，产生了一系列具有不同炎症标志物（CD80、CD40）和抗炎标志物（CD163、CD206）表达以及不同吞噬能力的合成巨噬细胞状态。编程有多个 YLxQ 基序的 SCR 增强了巨噬细胞对大肠杆菌的吞噬作用，以及嵌合抗原受体（CAR）-巨噬细胞在小鼠体内对癌细胞的吞噬作用，使肿瘤负荷降低了 30 倍。这种依赖于基序的极化可以通过双态模型得到很好的描述，从而能够根据 SCR 信号结构域的组成定量预测巨噬细胞的极化状态。利用该模型，我们设计了一种既能增强吞噬作用又能维持巨噬细胞促炎状态的 SCR。总之，这些发现建立了一个合成编程巨噬细胞极化状态的框架，在癌症免疫治疗和其他疾病背景中具有潜在的应用价值。

## Abstract
Technology that precisely controls macrophage polarization to distinct functional states would deepen our understanding of macrophage biology and enable development of new macrophage cell therapies. Here, we use a synthetic cytokine receptor (SCR) platform with programmable signaling domains to control primary human macrophage polarization. SCRs containing signaling motifs from the interferon-gamma (IFN-{gamma}) or Interleukin-10 (IL-10) receptors mimic key features of pro-inflammatory or anti-inflammatory polarization, respectively. Random recombination of nine distinct signaling motifs to create new SCR signaling domain generates a diverse landscape of synthetic macrophage states with varied expression of inflammatory markers (CD80, CD40) and anti-inflammatory markers (CD163, CD206), and varied phagocytic capacity. SCRs programmed with multiple YLxQ motifs increase macrophage phagocytosis of E. coli and chimeric antigen receptor (CAR)-macrophage phagocytosis of cancer cells in mice, reducing tumor burden by 30-fold. The motif-dependent polarization is well-described by a two-state model, enabling quantitative prediction of macrophage polarization state from SCR signaling domain composition. Leveraging this model, we design an SCR that simultaneously enhances phagocytosis and maintains a macrophage pro-inflammatory state. Together, these findings establish a framework to synthetically program macrophage polarization states with potential applications in cancer immunotherapy and other disease contexts.

---

## 论文详细总结（自动生成）

这是一份关于论文《Programmable synthetic cytokine receptors polarize macrophages to user-defined functional states》（可编程合成细胞因子受体将巨噬细胞极化至用户定义的功能状态）的结构化深入分析报告：

### 1. 论文的核心问题与整体含义（研究动机和背景）
*   **研究动机**：巨噬细胞在免疫反应和组织修复中具有极高的可塑性，能够极化为促炎（M1型）或抗炎（M2型）等多种状态。然而，现有的控制手段（如外源细胞因子刺激、基因敲除或过表达）往往只能进行粗调，难以精确、多维度地编程巨噬细胞的功能。
*   **核心问题**：如何开发一种可编程的平台，能够不依赖外部配体，通过内部信号传导精确控制原代人类巨噬细胞进入特定的、用户定义的功能状态，并将其应用于癌症免疫治疗（如 CAR-M 疗法）。

### 2. 论文提出的方法论
*   **核心思想**：利用**合成细胞因子受体（SCR）**平台，通过重组来自天然受体的短线性信号基序（Signaling Motifs），在胞内模拟特定的信号级联反应。
*   **关键技术细节**：
    *   **SCR 结构设计**：包含胞外二聚化结构域（Put3 卷曲螺旋）、跨膜域（TMD）、JAK 激酶结合域（gp130 box）以及末端的可变信号基序区。
    *   **基序库构建**：从天然受体（如 IFNGR1, IL-10R, IL-4R 等）中筛选出 9 种功能明确的信号基序（S1-S9）。
    *   **组合重组**：通过随机重组构建了包含 0 到 3 个基序的 131 种 SCR 文库。
*   **定量模型（双状态模型）**：
    *   论文引入了一个**双状态平衡模型（Two-state model）**，假设每个表型（如 CD40 表达或吞噬率）在“开启”和“关闭”状态间平衡。
    *   通过极化常数 $K$ 描述基序对表型的影响，公式考虑了固有极化常数 $K_i$ 和每个基序的贡献 $K_s$。该模型允许研究者通过已知的基序组合预测未测试组合的表型。

### 3. 实验设计
*   **实验对象**：原代人类单核细胞诱导的巨噬细胞（hMDMs）。
*   **Benchmark（基准对比）**：
    *   **外源配体刺激**：LPS + IFN-γ（促炎）、IL-10（抗炎）、IL-4、GM-CSF 等。
    *   **对照组**：未转导细胞（UT）和不含信号基序的受体（SCR0）。
*   **测量指标**：
    *   **表面标志物**：CD163, CD206（抗炎/修复）；CD80, CD40, PDL1（促炎/激活）。
    *   **功能实验**：pHrodo 标记的大肠杆菌吞噬实验、CAR-M 介导的癌细胞（BT474, K562-HER2）杀伤实验。
    *   **转录组分析**：Bulk RNA-seq，并与临床 CAR-T 治疗患者的单细胞测序（scRNA-seq）数据进行交叉验证。
    *   **体内实验**：NSG 小鼠 SKOV3 卵巢癌异种移植模型。

### 4. 资源与算力
*   **算力说明**：论文主要侧重于生物实验和生物信息学分析。
*   **软件与算法**：使用了 R 语言（v4.3.2）进行统计分析和模型拟合，Mathematica 进行公式推导，Salmon 和 DESeq2 处理 RNA-seq 数据。
*   **硬件提及**：文中**未明确提及**使用了高性能 GPU 集群或具体的训练时长，因为其核心模型（双状态模型）属于参数较少的解析模型，而非深度学习大模型，对算力需求较低。

### 5. 实验数量与充分性
*   **实验规模**：
    *   测试了 131 种 SCR 组合，涵盖了从单基序到三基序的多种排列。
    *   使用了来自至少 3 名不同人类供体的原代细胞以消除个体差异。
    *   体内实验每组包含 4-5 只小鼠。
*   **充分性与客观性**：
    *   **消融实验**：通过 SCR0 证明了信号增强是由基序而非受体骨架引起的。
    *   **预测验证**：利用模型预测并成功合成了一种既能高吞噬又能维持促炎特征（CD40+/CD80+）的新型 SCR（S3-S3-S3-S1），验证了模型的泛化能力。
    *   **临床相关性**：将 SCR(S1-S1) 的转录特征与实际癌症患者的髓系细胞反应进行对比，增强了结果的客观说服力。

### 6. 论文的主要结论与发现
*   **SCR 可模拟天然极化**：包含 IFNGR1 基序的 SCR 能诱导强烈的促炎特征，而包含 IL-10R 基序的 SCR 则诱导抗炎特征，且效果往往超过外源细胞因子。
*   **吞噬能力增强**：发现包含 YLxQ 基序（S2, S3）的 SCR 能显著提升巨噬细胞的吞噬效率。在体内模型中，CAR-SCR(S2-S2-S2)-M 使肿瘤负荷比常规 CAR-M 降低了 **30 倍**。
*   **打破表型权衡**：通过模型指导，成功设计出克服“吞噬能力”与“促炎状态”之间天然权衡（Trade-off）的合成受体。
*   **可预测性**：证明了巨噬细胞的复杂表型可以通过简单的模块化信号基序组合进行定量预测和编程。

### 7. 优点：方法或实验设计上的亮点
*   **模块化与可编程性**：将复杂的细胞因子信号拆解为短肽基序，实现了类似“乐高”式的细胞功能组装。
*   **数据驱动的理性设计**：不依赖盲目的高通量筛选，而是结合生物物理模型（双状态模型）进行理性设计，极大地缩小了搜索空间。
*   **临床转化潜力**：直接在原代人类细胞中验证，并展示了在实体瘤治疗中的显著优势，具有很强的应用前景。

### 8. 不足与局限
*   **基序多样性有限**：目前仅测试了 9 种基序，自然界中存在成百上千种信号基序，SCR 平台的潜力尚未完全挖掘。
*   **位置效应的简化**：模型假设基序位置不影响功能，虽然在当前数据下成立，但在更长、更复杂的信号链中，基序间的空间位阻或协同效应可能会使模型失效。
*   **长期稳定性与安全性**：SCR 是组成型激活（Constitutively active）的，长期表达是否会导致巨噬细胞耗竭、过度炎症反应或在体内的非靶向毒性仍需长期观察。
*   **应用场景局限**：目前主要集中在癌症治疗，对于纤维化、自身免疫病等其他巨噬细胞相关疾病的覆盖较少。

（完）
