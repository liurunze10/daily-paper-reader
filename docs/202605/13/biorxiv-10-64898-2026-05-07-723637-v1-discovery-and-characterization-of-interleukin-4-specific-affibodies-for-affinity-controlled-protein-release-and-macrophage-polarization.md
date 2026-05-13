---
title: Discovery and Characterization of Interleukin-4-Specific Affibodies for Affinity-Controlled Protein Release and Macrophage Polarization
authors: "Dorogin, J., Lamichhane, A., Huang, A. J., Svendsen, J. E., Benz, M., Raghavan, S. A., Hettiaratchi, M. H."
date: 2026-05-12
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.07.723637v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: IL-4特异性亲和体驱动巨噬细胞向抗炎M2表型极化
tldr: 本研究针对IL-4在免疫调节中的作用，通过酵母表面展示筛选出两种特异性亲和体。利用结构建模分析结合机制，并将其偶联至PEG水凝胶。结果显示该系统实现了IL-4的高效负载与7天缓释，并能调节巨噬细胞极化，为细胞因子疗法的精确递送提供了新策略。
source: biorxiv
selection_source: fresh_fetch
motivation: 临床应用中需要精确控制IL-4的递送以避免免疫失调，并实现对炎症反应的有效调节。
method: 利用酵母表面展示库筛选IL-4特异性亲和体，并结合计算模拟与水凝胶偶联技术实现亲和控制释放。
result: "成功鉴定出两种亲和体，其在水凝胶中实现了超过90%的负载率及7天的持续释放，并能部分抑制IL-4诱导的信号传导。"
conclusion: IL-4特异性亲和体是调节细胞因子活性和实现受控递送的有力工具，在炎症治疗领域具有广阔应用前景。
---

## Abstract
Interleukin-4 (IL-4) is a key immunoregulatory cytokine that promotes type 2 inflammation, drives macrophage polarization toward an anti-inflammatory M2 phenotype, and supports tissue repair. However, clinical translation of IL-4 therapies to modulate the immune response is limited by the need for precise control over its delivery to avoid immune dysregulation. Here, we report an affinity-based strategy to modulate IL-4 delivery and bioactivity using engineered affibody proteins. A yeast surface display library was screened via magnetic- and fluorescence-activated cell sorting to identify two IL-4-specific affibodies with moderate binding affinities (dissociation constants, KD = 459 and 141 nM). Circular dichroism confirmed expected alpha-helical folding, and biolayer interferometry characterized the kinetics of IL-4 binding. Structural modeling using AlphaFold3 and RosettaDock and molecular dynamics simulations using GROMACS predicted distinct binding sites for each IL-4-specific affibody on the IL-4 protein and suggested potential interference with receptor complex formation. Bioactivity studies using murine bone marrow-derived macrophages demonstrated that IL-4 complexed with affibodies maintained Ym1 gene expression but significantly reduced Ym1 protein levels, indicating partial inhibition of IL-4 signaling. To enable controlled cytokine delivery via affinity interactions, affibodies were conjugated to polyethylene glycol maleimide (PEG-mal) hydrogels, which were loaded with IL-4. Affibody-conjugated hydrogels achieved high IL-4 loading efficiency (>90%) and exhibited sustained release over 7 days. Increasing affibody-to-IL-4 ratios significantly reduced both the rate and total amount of cytokine release. Overall, this work establishes IL-4-specific affibodies as versatile tools for tuning cytokine presentation and modulating bioactivity and provides a promising approach for regulating inflammatory responses and advancing cytokine-based therapies with improved temporal control.

---

## 论文详细总结（自动生成）

这篇论文题为《用于亲和受控蛋白质释放和巨噬细胞极化的白细胞介素-4特异性亲和体的发现与表征》，以下是对该研究的深度结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：白细胞介素-4 (IL-4) 是促进抗炎 M2 型巨噬细胞极化和组织修复的关键细胞因子。然而，IL-4 在体内半衰期短，且全身性给药易引起免疫失调。因此，如何实现 IL-4 的**局部、精准、受控释放**，并调节其生物活性，是免疫治疗领域亟待解决的挑战。
*   **研究背景**：传统的缓释系统（如物理包裹）往往存在初期释放过快（爆发释放）的问题。本研究旨在开发一种基于“亲和力”的递送系统，利用人工工程化的亲和体（Affibody）蛋白来精确控制 IL-4 的释放动力学。

### 2. 方法论：核心思想与关键技术
*   **核心思想**：通过筛选对 IL-4 具有特异性结合能力的亲和体，并将其偶联至水凝胶支架上，利用亲和力相互作用（结合/解离平衡）来减缓 IL-4 的扩散速度。
*   **关键技术细节**：
    *   **筛选技术**：利用**酵母表面展示（Yeast Surface Display）**技术，从大规模随机文库中通过磁珠分选（MACS）和荧光激活细胞分选（FACS）筛选出两种 IL-4 特异性亲和体（命名为 A1 和 A2）。
    *   **结构表征**：使用圆二色谱（CD）验证蛋白质折叠，利用生物层干涉技术（BLI）测量结合动力学（$K_D$ 值）。
    *   **计算模拟**：采用 **AlphaFold3** 和 **RosettaDock** 预测亲和体与 IL-4 的结合位点，并通过 **GROMACS** 进行分子动力学（MD）模拟，分析其对 IL-4 与受体结合的潜在干扰。
    *   **递送系统**：将亲和体偶联至聚乙二醇-马来酰亚胺（PEG-mal）水凝胶中，构建亲和受控释放平台。

### 3. 实验设计
*   **实验场景与基准**：
    *   **结合力测试**：以无亲和体或非特异性蛋白作为对照。
    *   **生物活性验证**：使用小鼠骨髓源性巨噬细胞（BMDMs），观察 IL-4 与亲和体络合后对 M2 极化标志物（如 Ym1）的影响。
    *   **释放实验**：对比了不同亲和体浓度（摩尔比）对 IL-4 释放速率的影响，基准为不含亲和体的普通 PEG 水凝胶。
*   **对比方法**：对比了 A1 和 A2 两种亲和体在结合亲和力、结构稳定性和释放控制力上的差异。

### 4. 资源与算力
*   **计算资源**：论文提到了使用 AlphaFold3 进行结构预测，RosettaDock 进行对接，以及 GROMACS 进行分子动力学模拟。
*   **具体参数**：文中**未明确说明**具体的 GPU 型号、数量或训练/模拟的总时长。这在生物工程类论文中较为常见，重点通常在于算法的应用而非算力消耗。

### 5. 实验数量与充分性
*   **实验规模**：
    *   筛选了包含数亿个变体的酵母文库。
    *   对两种候选亲和体进行了详尽的动力学分析（$K_D$ 分别为 459 nM 和 141 nM）。
    *   进行了为期 7 天的体外释放实验，涵盖了多种亲和体与配体的比例。
*   **充分性评价**：实验设计较为全面，涵盖了从分子发现、结构模拟、体外释放到细胞功能验证的完整链路。通过调整亲和体比例来控制释放速率的消融实验证明了系统的可调控性，实验结果具有统计学意义。

### 6. 主要结论与发现
*   **成功筛选**：鉴定出两种新型 IL-4 特异性亲和体，具有中等强度的亲和力，适合用于受控释放（过强会导致无法释放，过弱则无法阻滞）。
*   **高效负载与缓释**：亲和体偶联水凝胶对 IL-4 的负载效率超过 90%，并实现了长达 7 天的持续释放。通过增加亲和体比例，可以显著降低释放速率。
*   **生物活性调节**：亲和体与 IL-4 结合后，虽然维持了 Ym1 基因的表达，但显著降低了 Ym1 蛋白水平，表明亲和体可以作为 IL-4 信号传导的“调节阀”，部分抑制其生物活性。

### 7. 优点（亮点）
*   **多学科融合**：结合了合成生物学（文库筛选）、计算生物学（结构模拟）和材料科学（水凝胶递送）。
*   **高度可调控性**：通过改变亲和体的种类或浓度，能够精细调节细胞因子的释放曲线，这比传统的物理包裹更具预测性。
*   **结构洞察**：利用 AlphaFold3 等前沿工具深入分析了结合机制，为后续优化亲和力提供了理论依据。

### 8. 不足与局限
*   **生物活性抑制**：实验发现亲和体会部分抑制 IL-4 的生物效应，这在某些需要全效活性的治疗场景下可能是个缺点。
*   **缺乏体内数据**：目前所有实验均在体外（In vitro）完成，尚未在动物模型中验证其在复杂生理环境下的稳定性及免疫调节效果。
*   **物种局限性**：研究主要针对小鼠 IL-4，若要临床转化，需针对人类 IL-4 重新筛选和验证。

（完）
