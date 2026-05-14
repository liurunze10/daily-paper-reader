---
title: Discovery and Characterization of Interleukin-4-Specific Affibodies for Affinity-Controlled Protein Release and Macrophage Polarization
title_zh: 白细胞介素-4特异性Affibody分子的发现与表征，用于亲和力控制的蛋白质释放和巨噬细胞极化
authors: "Dorogin, J., Lamichhane, A., Huang, A. J., Svendsen, J. E., Benz, M., Raghavan, S. A., Hettiaratchi, M. H."
date: 2026-05-12
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.07.723637v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: IL-4递送用于M2巨噬细胞极化
tldr: 本研究针对白细胞介素-4（IL-4）在免疫调节中递送受限的问题，利用酵母表面展示技术筛选并表征了两种特异性亲和体（Affibody）。通过结构建模和生物活性实验，证实了亲和体能调节IL-4诱导的巨噬细胞极化。此外，将亲和体共轭至PEG水凝胶中，实现了IL-4的高效负载与长达7天的缓释，为细胞因子疗法的精确时空控制提供了新工具。
source: biorxiv
selection_source: fresh_fetch
motivation: 为了克服IL-4在临床应用中因缺乏精确递送控制而导致的免疫失调风险。
method: 利用酵母展示筛选亲和体，结合分子动力学模拟预测结合位点，并将其应用于亲和控制的水凝胶递送系统。
result: 成功鉴定出两种具有中等亲和力的亲和体，能部分抑制IL-4信号，并在水凝胶系统中实现高负载率和持续7天的受控释放。
conclusion: 该研究建立了一套基于亲和体的IL-4调节平台，为优化炎症反应调节和推进细胞因子递送技术提供了有效方案。
---

## 摘要
白细胞介素-4 (IL-4) 是一种关键的免疫调节细胞因子，可促进2型炎症，驱动巨噬细胞向抗炎M2表型极化，并支持组织修复。然而，IL-4疗法在调节免疫反应方面的临床转化受到限制，因为需要对其递送进行精确控制以避免免疫失调。在此，我们报告了一种基于亲和力的策略，利用工程化的Affibody蛋白质来调节IL-4的递送和生物活性。通过磁珠和荧光激活细胞分选筛选了酵母表面展示库，鉴定了两种具有中等结合亲和力（解离常数 KD = 459 和 141 nM）的IL-4特异性Affibody。圆二色性实验证实了预期的α-螺旋折叠，生物层干涉技术表征了IL-4结合的动力学。使用AlphaFold3和RosettaDock进行的结构建模以及使用GROMACS进行的分子动力学模拟预测了每种IL-4特异性Affibody在IL-4蛋白上的不同结合位点，并提示可能干扰受体复合物的形成。使用小鼠骨髓源性巨噬细胞进行的生物活性研究表明，与Affibody结合的IL-4维持了Ym1基因表达，但显著降低了Ym1蛋白水平，表明IL-4信号传导受到部分抑制。为了通过亲和相互作用实现受控的细胞因子递送，将Affibody偶联到负载有IL-4的聚乙二醇马来酰亚胺 (PEG-mal) 水凝胶上。偶联Affibody的水凝胶实现了较高的IL-4负载效率（>90%），并在7天内表现出持续释放。增加Affibody与IL-4的比例显著降低了细胞因子的释放速率和总量。总之，这项工作确立了IL-4特异性Affibody作为调节细胞因子呈递和生物活性的多功能工具，并为调节炎症反应和推进具有改进时间控制的细胞因子疗法提供了一种有前景的方法。

## Abstract
Interleukin-4 (IL-4) is a key immunoregulatory cytokine that promotes type 2 inflammation, drives macrophage polarization toward an anti-inflammatory M2 phenotype, and supports tissue repair. However, clinical translation of IL-4 therapies to modulate the immune response is limited by the need for precise control over its delivery to avoid immune dysregulation. Here, we report an affinity-based strategy to modulate IL-4 delivery and bioactivity using engineered affibody proteins. A yeast surface display library was screened via magnetic- and fluorescence-activated cell sorting to identify two IL-4-specific affibodies with moderate binding affinities (dissociation constants, KD = 459 and 141 nM). Circular dichroism confirmed expected alpha-helical folding, and biolayer interferometry characterized the kinetics of IL-4 binding. Structural modeling using AlphaFold3 and RosettaDock and molecular dynamics simulations using GROMACS predicted distinct binding sites for each IL-4-specific affibody on the IL-4 protein and suggested potential interference with receptor complex formation. Bioactivity studies using murine bone marrow-derived macrophages demonstrated that IL-4 complexed with affibodies maintained Ym1 gene expression but significantly reduced Ym1 protein levels, indicating partial inhibition of IL-4 signaling. To enable controlled cytokine delivery via affinity interactions, affibodies were conjugated to polyethylene glycol maleimide (PEG-mal) hydrogels, which were loaded with IL-4. Affibody-conjugated hydrogels achieved high IL-4 loading efficiency (>90%) and exhibited sustained release over 7 days. Increasing affibody-to-IL-4 ratios significantly reduced both the rate and total amount of cytokine release. Overall, this work establishes IL-4-specific affibodies as versatile tools for tuning cytokine presentation and modulating bioactivity and provides a promising approach for regulating inflammatory responses and advancing cytokine-based therapies with improved temporal control.

---

## 论文详细总结（自动生成）

这篇论文详细介绍了针对白细胞介素-4（IL-4）的特异性亲和体（Affibody）的开发及其在生物材料递送系统中的应用。以下是对该论文的结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：IL-4 是促进组织修复和抗炎（M2型）巨噬细胞极化的关键细胞因子，但其体内半衰期极短（约19分钟），且长期不受控的暴露会导致免疫失调（如过敏、哮喘）。
*   **研究动机**：现有的递送系统（如单纯扩散释放）缺乏对释放速率和生物活性的精确调控。研究团队旨在开发一种基于“亲和力控制”的平台，利用人工设计的 Affibody 蛋白作为“锚点”，实现 IL-4 的缓释并调节其生物活性。

### 2. 方法论
*   **核心思想**：通过酵母表面展示技术筛选出能与 IL-4 特异性结合的 Affibody，并将其共轭到水凝胶基质中，利用非共价亲和相互作用来“拉住”IL-4，从而延缓其释放。
*   **关键技术细节**：
    *   **筛选技术**：使用包含 $4 \times 10^8$ 个序列的酵母展示库，通过 5 轮磁珠分选（MACS）和 2 轮荧光激活细胞分选（FACS）鉴定出两种亲和体（Affibody 1 和 2）。
    *   **结构建模与模拟**：利用 **AlphaFold3** 预测结合结构，**RosettaDock** 计算结合能，并使用 **GROMACS** 进行 100ns 的分子动力学（MD）模拟，分析结合界面的稳定性及极性接触。
    *   **递送系统**：将合成的 Affibody 通过半胱氨酸-马来酰亚胺反应共轭到 4 臂 PEG-mal 水凝胶上。

### 3. 实验设计
*   **实验场景**：
    *   **生化表征**：使用 MALDI-TOF 质谱验证分子量，圆二色性（CD）分析二级结构，生物层干涉技术（BLI）测量结合动力学（$K_D$ 值）。
    *   **细胞实验**：使用小鼠永生化骨髓源性巨噬细胞（iBMDMs），观察 IL-4 与亲和体复合物对 M2 极化标志物 Ym1（基因和蛋白水平）的影响。
    *   **释放实验**：在含有 10% FBS 的 PBS 缓冲液中模拟体内环境，测试不同 Affibody 浓度（100x, 500x, 5000x 摩尔过量）下的释放曲线。
*   **对比基准（Benchmark）**：
    *   对照组包括：无处理组、仅 IL-4 处理组、无亲和体的纯 PEG 水凝胶组。
    *   对比了两种不同的亲和体（Affibody 1 vs. Affibody 2）。

### 4. 资源与算力
*   **计算资源**：文中提到了使用 AlphaFold3、Rosetta FastRelax、RosettaDock 和 GROMACS 2023.4 进行模拟。
*   **具体说明**：未明确列出具体的 GPU 型号或训练/模拟的总时长，但提到分子动力学模拟执行了四次独立的 100ns 轨迹运行。

### 5. 实验数量与充分性
*   **实验规模**：
    *   生化实验均有重复验证（如 BLI 动力学拟合）。
    *   细胞实验包含 3 个生物学独立样本，qPCR 为技术三重复。
    *   释放实验每组 $n=4$。
*   **充分性评价**：实验设计较为充分，涵盖了从分子发现、结构预测、体外细胞功能验证到生物材料递送的全流程。通过改变亲和体与配体的比例（摩尔比）展示了良好的剂量依赖性，实验结果具有统计学意义且逻辑自洽。

### 6. 主要结论与发现
*   **亲和力**：筛选出的两种 Affibody 具有中等亲和力（$K_D$ 分别为 459 nM 和 141 nM），远弱于 IL-4 与其受体的结合（~1 nM）。
*   **生物活性调节**：Affibody 结合 IL-4 后，虽然不影响 Ym1 的基因转录，但显著降低了 Ym1 蛋白的表达，表明亲和体可能通过空间位阻部分干扰了受体复合物的形成。
*   **递送控制**：Affibody 显著提高了水凝胶对 IL-4 的负载效率（>90%），并实现了 7 天的持续释放。释放速率可通过调整 Affibody 的浓度进行精确微调。

### 7. 优点
*   **高可调性**：通过调整“亲和体：细胞因子”的比例而非改变材料化学性质来控制释放，提供了极高的灵活性。
*   **多功能性**：Affibody 不仅是递送工具，还表现出作为 IL-4 抑制剂/调节剂的潜力。
*   **计算与实验结合**：利用前沿的 AlphaFold3 和 MD 模拟深入解释了分子水平的结合机制，增强了结果的说服力。

### 8. 不足与局限
*   **生物活性抑制**：亲和体对 IL-4 诱导的 M2 极化有部分抑制作用，这在某些需要全效生物活性的组织修复场景中可能是负面因素。
*   **体内验证缺失**：目前所有实验均在体外（In vitro）完成，尚未在复杂的动物炎症模型中验证其治疗效果和免疫安全性。
*   **筛选难度**：作者提到 IL-4 的不稳定性增加了筛选难度，导致最终获得的候选分子种类较少。

（完）
