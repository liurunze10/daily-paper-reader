---
title: Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection
title_zh: 沙门氏菌感染期间巨噬细胞转录组重塑的多模态时间图谱
authors: "Toussaint, C., Hill, P. W. S., Klodewig, B., Eldridge, M. J., Theis, F. J., Helaine, S., Saliba, A.-E."
date: 2026-07-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.04.736507v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: 绘制巨噬细胞转录组重塑以及促炎向抗炎状态重编程的图谱
tldr: 本研究通过多模态时间序列单细胞转录组学，系统解析了沙门氏菌感染早期巨噬细胞的重编程动态。利用RNA代谢标记、转录因子足迹分析和单细胞CRISPR扰动，研究揭示了感染后6小时的关键决策点，即巨噬细胞在SPI2诱导下从促炎向抑炎状态的表型分化，并识别了Cybb和Foxo1等关键免疫调节因子。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-001.webp\", \"caption\": \"Figure 1: Connected macrophage fate trajectories to Salmonella SPI-2 activity through scSLAM-seq. (A) Experimental (upper panel) and analytical (bottom panel) workflow depicting the time-course and multimodal scSLAM-seq analysis of infected bone marrow derived macrophages with Salmonella carrying a SPI2-reporter plasmid. (B) Aggregated scatter plot of intracellular bacterial SPI2 activity in non-infected (mock) and infected macrophages analysed and sorted by FACS across the complete time-course of the experiment time points of infection analysed. Grey background data points and contour lines correspond to the entire cell population analysed superimposed with timepoint-colored dots indicating all the individual sorted macrophages for downstream analysis color-coded by time-point further processed for scSLAM-seq. The scatter plot has been segmented in four quadrants based on bacterial intracellular activity. (C & D) UMAP (Uniform Manifold Approximation and Projection)\", \"page\": 6, \"index\": 1, \"width\": 943, \"height\": 1152}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-002.webp\", \"caption\": \"Figure 2: Dynamics of transcriptional response of macrophages. (A) UMAP visualization of 578 single-macrophage transcriptomes obtained by scSLAM-seq as in Figures 1C and 1D and colored by cell state as identified by unsupervised clustering with the Leiden algorithm. (B) Dot plot of scaled, log-normalized expression of marker selected representative genes from the different macrophage states identified (A). Top and bottom panels correspond to the inflammatory and anti-inflammatory macrophage trajectory, respectively. Dot size indicates the percentage of cells per cell state with detectable mRNA expression, and color shows Z-scores of log-normalized new RNA readcounts. (C) Analysis of differentially expressed genes overlap between different macrophage states represented by a Venn plot of differentially expressed genes (FDR < 0.05, Wilcoxon Rank Sum test with Benjamini-Hochberg correction) differentiating the early response at 2/4hpi and the inflammatory/anti-inflammatory signatures. Circle size is proportional to the total number of DEG within each group. Indicated numbers correspond to the number of specific or shared DEGs between groups. Comparisons between\", \"page\": 10, \"index\": 2, \"width\": 946, \"height\": 1050}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-003.webp\", \"caption\": \"Figure 4: A map of upstream transcription factor regulating gene modules underlying macrophage polarization states.\", \"page\": 18, \"index\": 3, \"width\": 821, \"height\": 704}]"
motivation: 探究沙门氏菌如何通过操纵宿主转录因子，将巨噬细胞从促炎防御状态重编程为有利于细菌复制的抑炎状态。
method: 采用结合了细菌报告系统、时间序列单细胞RNA测序、代谢标记及单细胞CRISPR扰动的多模态分析方法。
result: 识别出感染后6小时是巨噬细胞极化的关键分叉点，并证实了SPI2激活对NF-κB通路的抑制及对特定转录模块的诱导。
conclusion: 该研究揭示了巨噬细胞极化过程中的关键宿主决策点，为理解沙门氏菌逃避宿主免疫的机制提供了新见解。
---

## 摘要
巨噬细胞具备清除入侵病原体的能力，但一些胞内细菌却利用它们作为复制生态位。鼠伤寒沙门氏菌（Salmonella enterica serovar Typhimurium）通过注入效应蛋白来重塑巨噬细胞功能，从而破坏宿主免疫。虽然巨噬细胞在细菌入侵时通常会启动促炎程序，但沙门氏菌可以通过操纵宿主转录因子 NF-κB 和 STAT3，将它们重定向为抗炎且允许复制的状态。目前尚不清楚对这两个转录因子（以及潜在的其他因子）影响的整合是如何支撑这种重编程的。在本研究中，我们采用了一种多管齐下的方法，结合细菌报告基因、带有 RNA 代谢标记的时间单细胞 RNA-seq、转录因子（TF）足迹分析以及单细胞 CRISPR 扰动，来剖析感染早期巨噬细胞极化的动态过程。我们捕捉到了感染过程中的分叉点，即一部分巨噬细胞向抗炎表型转变。这种转变涉及沙门氏菌致病岛 2 (SPI2) 的激活，导致最初由 NF-κB 驱动的炎症程序减弱，并诱导了除 NF-κB 和 STAT3 之外的特定转录模块，其中 AP-1 和 Maf 家族成员可能也发挥了作用。总之，我们的研究揭示了巨噬细胞极化回路中的宿主决策点，并发现了沙门氏菌利用来调节宿主免疫的漏洞。研究亮点：时间单细胞 RNA-seq 定义了促炎和抗炎巨噬细胞状态的出现，这与鼠伤寒沙门氏菌 SPI2 的诱导相伴随；感染结果的关键决策点在感染后 6 小时达到；巨噬细胞重编程与广泛的染色质重塑和动态转录因子结合相关；单细胞 Perturb-seq 实验揭示了 Cybb 和 Foxo1 是 Hoxb8 巨噬细胞感染结果的调节因子。

## Abstract
Macrophages are equipped to eliminate invading pathogens, yet several intracellular bacteria exploit them as replicative niches. Salmonella enterica serovar Typhimurium subverts host immunity by injecting effector proteins that remodel macrophage functions. While macrophages typically induce a pro-inflammatory program upon bacterial invasion, Salmonella can redirect them toward an anti-inflammatory and replication-permissive state via manipulation of the NF-{kappa}B and STAT3 host transcription factors. How the integration of the effects on these two transcription factors and potentially others underpins this reprogramming remains poorly charted. Here, we use a multipronged approach combining a bacterial reporter, temporal single-cell RNA-seq with RNA metabolic labeling, transcription factor (TF) footprinting, and single-cell CRISPR perturbations to dissect macrophage polarization dynamics during early infection. We catch the bifurcation during infection, where a subset of macrophages transition toward the anti-inflammatory phenotype. This shift involves the activation of Salmonella pathogenicity island 2 (SPI2) leading to both the dampening of the initial NF-{kappa}B-driven inflammatory program and the induction of specific transcriptional modules beyond NF-{kappa}B and STAT3, with possible contributions from AP-1 and Maf family members. Together, our study uncovers host decision points in macrophage polarization circuitry and reveals a vulnerability exploited by Salmonella to modulate host immunity.

HIGHLIGHTSO_LITemporal scRNA-seq defines the emergence of inflammatory and anti-inflammatory macrophage states concomitant with Salmonella Typhimurium SPI2 induction.
C_LIO_LIA critical decision point for infection outcome is reached by 6 hours post-infection.
C_LIO_LIMacrophage reprogramming is associated with widespread chromatin remodeling and dynamic transcription factor binding.
C_LIO_LISingle-cell perturb-seq experiment uncovers Cybb and Foxo1 as modulators of infection outcome in Hoxb8 macrophages.
C_LI

---

## 论文详细总结（自动生成）

这是一份关于论文《沙门氏菌感染期间巨噬细胞转录组重塑的多模态时间图谱》（*Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection*）的深度学术总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：沙门氏菌（*Salmonella*）如何通过操纵宿主巨噬细胞，将其从防御性的“促炎”状态重编程为有利于细菌复制的“抗炎/抑炎”状态？
*   **背景**：巨噬细胞是免疫系统的第一道防线，但沙门氏菌进化出了复杂的机制（如 SPI2 型分泌系统）来逃避清除。虽然已知 NF-κB 和 STAT3 等转录因子参与其中，但这种重编程在单细胞水平上的动态演变过程、关键决策点以及完整的转录调控网络仍不清晰。

### 2. 方法论：核心思想与关键技术
研究采用了一种**多模态、时间序列的单细胞分析框架**，整合了以下关键技术：
*   **scSLAM-seq（单细胞代谢标记测序）**：通过 4-硫代尿苷（4sU）标记新合成的 RNA，能够区分“新合成”和“预存在”的转录本，从而精确捕捉感染初期的瞬时转录动态。
*   **细菌报告系统**：利用带有 SPI2 启动子驱动的 GFP 报告基因的沙门氏菌，通过流式细胞术（FACS）根据细菌的致病性状态（SPI2 活性）对巨噬细胞进行分选。
*   **TF 结合足迹分析（TF Footprinting）**：结合单细胞 ATAC-seq 数据，推断不同感染阶段转录因子（如 NF-κB, AP-1, Maf 家族）在染色质上的动态结合活性。
*   **Perturb-seq（单细胞 CRISPR 扰动测序）**：在 Hoxb8 永生化巨噬细胞中针对候选基因进行大规模基因敲除，并观察其对感染结果和细胞状态的影响。

### 3. 实验设计与对比
*   **实验对象**：小鼠骨髓来源巨噬细胞（BMDMs）和 Hoxb8 来源巨噬细胞。
*   **感染模型**：鼠伤寒沙门氏菌（*S. Typhimurium*）感染，设置非感染（Mock）作为对照。
*   **时间梯度**：涵盖感染后 2、4、6、12、24 小时等多个关键时间点。
*   **对比维度**：
    *   **感染 vs 非感染**：识别基础免疫反应。
    *   **SPI2 高活性 vs SPI2 低活性**：区分成功重编程的细胞与维持促炎状态的细胞。
    *   **新合成 RNA vs 总 RNA**：揭示转录速率的实时变化。

### 4. 资源与算力
*   论文中**未明确说明**具体的 GPU 型号、数量或训练时长。
*   实验主要涉及高通量测序数据的生物信息学分析（如 CellRanger 流程、Scanpy/Seurat 分析、Milo 差异丰度测试等），这类分析通常依赖高性能计算集群（HPC）而非单一的深度学习训练卡。

### 5. 实验数量与充分性
*   **实验规模**：分析了数千个单细胞的转录组和染色质可及性图谱。
*   **消融与验证**：
    *   通过 scSLAM-seq 验证了转录爆发的动态。
    *   通过单细胞 ATAC-seq 验证了转录因子结合的物理基础。
    *   通过 Perturb-seq 对 20 多个候选基因进行了功能性验证。
*   **充分性评价**：实验设计非常全面，结合了观察性（测序）和干预性（CRISPR）手段，从相关性研究深入到了因果性验证，实验结果具有高度的客观性和说服力。

### 6. 主要结论与发现
*   **关键决策点**：感染后 **6 小时 (6hpi)** 是巨噬细胞命运分化的关键窗口期。
*   **表型分叉**：一部分细胞维持促炎状态（由 NF-κB 驱动），而另一部分在 SPI2 激活后转向抗炎状态（由 STAT3、Maf、AP-1 等驱动）。
*   **调控机制**：沙门氏菌通过 SPI2 效应蛋白抑制 NF-κB 介导的炎症信号，同时诱导特定的转录模块。
*   **关键因子识别**：通过 Perturb-seq 证实了 **Cybb**（编码 NOX2）和 **Foxo1** 是调节巨噬细胞感染结果和极化状态的核心节点。

### 7. 优点（亮点）
*   **高分辨率动态观察**：利用代谢标记（scSLAM-seq）解决了传统单细胞测序无法区分“正在发生”和“已经发生”转录变化的痛点。
*   **多模态整合**：将细菌的生理状态（SPI2 活性）与宿主的转录组、表观组及功能扰动数据完美结合。
*   **系统性视角**：不仅关注已知的 NF-κB，还揭示了 Maf 和 AP-1 家族在宿主重编程中的潜在作用。

### 8. 不足与局限
*   **体外模型限制**：主要基于骨髓来源的巨噬细胞（BMDMs），可能无法完全模拟体内复杂组织环境（如肠道或脾脏）中的巨噬细胞异质性。
*   **效应蛋白特异性**：虽然观察到了 SPI2 的整体影响，但具体是哪一个或哪几个效应蛋白（如 SseL, SteE 等）直接作用于特定的转录因子，仍需更精细的分子生物学实验。
*   **物种差异**：小鼠模型与人类在沙门氏菌感染后的免疫反应存在差异，结论在人体中的适用性有待验证。

（完）
