---
title: Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection
authors: "Toussaint, C., Hill, P. W. S., Klodewig, B., Eldridge, M. J., Theis, F. J., Helaine, S., Saliba, A.-E."
date: 2026-07-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.04.736507v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: 巨噬细胞转录组重塑与重编程
tldr: 本研究利用多模态时间序列单细胞转录组学，揭示了沙门氏菌感染早期巨噬细胞极化的动态过程。通过结合RNA代谢标记、转录因子足迹分析和单细胞CRISPR扰动技术，研究发现了感染后6小时的关键决策点，此时沙门氏菌通过SPI2系统抑制NF-κB炎症反应并诱导抗炎表型。研究还识别了Cybb和Foxo1等关键调节因子，为理解病原体如何重塑宿主免疫提供了新见解。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-001.webp\", \"caption\": \"Figure 1: Connected macrophage fate trajectories to Salmonella SPI-2 activity through scSLAM-seq. (A) Experimental (upper panel) and analytical (bottom panel) workflow depicting the time-course and multimodal scSLAM-seq analysis of infected bone marrow derived macrophages with Salmonella carrying a SPI2-reporter plasmid. (B) Aggregated scatter plot of intracellular bacterial SPI2 activity in non-infected (mock) and infected macrophages analysed and sorted by FACS across the complete time-course of the experiment time points of infection analysed. Grey background data points and contour lines correspond to the entire cell population analysed superimposed with timepoint-colored dots indicating all the individual sorted macrophages for downstream analysis color-coded by time-point further processed for scSLAM-seq. The scatter plot has been segmented in four quadrants based on bacterial intracellular activity. (C & D) UMAP (Uniform Manifold Approximation and Projection)\", \"page\": 6, \"index\": 1, \"width\": 943, \"height\": 1152}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-002.webp\", \"caption\": \"Figure 2: Dynamics of transcriptional response of macrophages. (A) UMAP visualization of 578 single-macrophage transcriptomes obtained by scSLAM-seq as in Figures 1C and 1D and colored by cell state as identified by unsupervised clustering with the Leiden algorithm. (B) Dot plot of scaled, log-normalized expression of marker selected representative genes from the different macrophage states identified (A). Top and bottom panels correspond to the inflammatory and anti-inflammatory macrophage trajectory, respectively. Dot size indicates the percentage of cells per cell state with detectable mRNA expression, and color shows Z-scores of log-normalized new RNA readcounts. (C) Analysis of differentially expressed genes overlap between different macrophage states represented by a Venn plot of differentially expressed genes (FDR < 0.05, Wilcoxon Rank Sum test with Benjamini-Hochberg correction) differentiating the early response at 2/4hpi and the inflammatory/anti-inflammatory signatures. Circle size is proportional to the total number of DEG within each group. Indicated numbers correspond to the number of specific or shared DEGs between groups. Comparisons between\", \"page\": 10, \"index\": 2, \"width\": 946, \"height\": 1050}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-003.webp\", \"caption\": \"Figure 4: A map of upstream transcription factor regulating gene modules underlying macrophage polarization states.\", \"page\": 18, \"index\": 3, \"width\": 821, \"height\": 704}]"
motivation: 旨在阐明沙门氏菌如何通过操纵宿主转录因子，将巨噬细胞从促炎状态重塑为有利于细菌复制的抗炎状态。
method: 结合了细菌报告系统、带代谢标记的时间序列单细胞RNA测序、转录因子足迹分析以及单细胞CRISPR扰动技术。
result: 发现了感染后6小时是巨噬细胞极化的关键分叉点，并识别出SPI2诱导的转录重塑涉及NF-κB、STAT3、AP-1和Maf等多个转录因子。
conclusion: 该研究揭示了巨噬细胞极化回路中的宿主决策点，并确定了沙门氏菌利用的免疫调节漏洞及关键调节基因。
---

## Abstract
Macrophages are equipped to eliminate invading pathogens, yet several intracellular bacteria exploit them as replicative niches. Salmonella enterica serovar Typhimurium subverts host immunity by injecting effector proteins that remodel macrophage functions. While macrophages typically induce a pro-inflammatory program upon bacterial invasion, Salmonella can redirect them toward an anti-inflammatory and replication-permissive state via manipulation of the NF-{kappa}B and STAT3 host transcription factors. How the integration of the effects on these two transcription factors and potentially others underpins this reprogramming remains poorly charted. Here, we use a multipronged approach combining a bacterial reporter, temporal single-cell RNA-seq with RNA metabolic labeling, transcription factor (TF) footprinting, and single-cell CRISPR perturbations to dissect macrophage polarization dynamics during early infection. We catch the bifurcation during infection, where a subset of macrophages transition toward the anti-inflammatory phenotype. This shift involves the activation of Salmonella pathogenicity island 2 (SPI2) leading to both the dampening of the initial NF-{kappa}B-driven inflammatory program and the induction of specific transcriptional modules beyond NF-{kappa}B and STAT3, with possible contributions from AP-1 and Maf family members. Together, our study uncovers host decision points in macrophage polarization circuitry and reveals a vulnerability exploited by Salmonella to modulate host immunity.

HIGHLIGHTSO_LITemporal scRNA-seq defines the emergence of inflammatory and anti-inflammatory macrophage states concomitant with Salmonella Typhimurium SPI2 induction.
C_LIO_LIA critical decision point for infection outcome is reached by 6 hours post-infection.
C_LIO_LIMacrophage reprogramming is associated with widespread chromatin remodeling and dynamic transcription factor binding.
C_LIO_LISingle-cell perturb-seq experiment uncovers Cybb and Foxo1 as modulators of infection outcome in Hoxb8 macrophages.
C_LI

---

## 论文详细总结（自动生成）

这是一份关于论文《Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection》的结构化深入分析总结：

### 1. 论文的核心问题与整体含义（研究动机和背景）
巨噬细胞是机体抵御病原体的重要防线，但鼠伤寒沙门氏菌（*Salmonella Typhimurium*）能够通过分泌效应蛋白重塑宿主功能，将其转化为有利于细菌复制的“避难所”。
*   **核心问题**：沙门氏菌如何通过操纵宿主转录因子（TF），将巨噬细胞从促炎（清除型）状态重编程为抗炎（允许复制型）状态？
*   **研究背景**：虽然已知沙门氏菌利用其致病岛2（SPI2）系统干扰 NF-κB 和 STAT3 等信号通路，但这种重塑在单细胞水平上的动态演变过程、关键决策点以及涉及的完整转录调控网络仍不清晰。

### 2. 论文提出的方法论
研究采用了一种**多模态时间序列单细胞分析框架**，核心技术包括：
*   **scSLAM-seq（单细胞硫醇代谢标记测序）**：通过 4-硫代尿苷（4sU）标记新合成的 RNA，能够区分“新合成”与“原有”转录本，从而捕捉极短时间内的转录组动态变化。
*   **SPI2 荧光报告系统**：在沙门氏菌中引入受 SPI2 启动子驱动的 GFP 报告基因，通过流式细胞术（FACS）分选出不同感染阶段和细菌活性的巨噬细胞。
*   **TF Footprinting（转录因子足迹分析）**：结合 scATAC-seq 数据，利用染色质可及性的细微差异推断转录因子在基因组上的实时结合活性。
*   **Perturb-seq（单细胞 CRISPR 扰动）**：在 Hoxb8 来源的巨噬细胞中靶向 24 个候选调节基因，通过单细胞测序观察基因敲除对感染结局和细胞状态的影响。

### 3. 实验设计
*   **实验对象**：小鼠骨髓来源巨噬细胞（BMDM）及 Hoxb8 永生化巨噬细胞。
*   **感染模型**：使用带有 SPI2 报告系统的鼠伤寒沙门氏菌进行感染。
*   **时间点设置**：感染后 2, 4, 6, 12, 24 小时（hpi）。
*   **对比组（Benchmark）**：
    *   非感染对照组（Mock）。
    *   不同细菌活性组（SPI2-low vs. SPI2-high）。
    *   不同极化状态组（促炎轨迹 vs. 抗炎轨迹）。
*   **验证实验**：通过 CRISPR 扰动实验验证从多组学数据中筛选出的关键调节因子。

### 4. 资源与算力
*   **算力说明**：论文中未明确提及具体的 GPU 型号、数量或训练时长。
*   **数据处理**：主要依赖于生物信息学标准流程，包括 CellRanger（测序定量）、Scanpy/Seurat（单细胞分析）、CellRank（轨迹推断）以及用于 TF 足迹分析的专用工具。

### 5. 实验数量与充分性
*   **实验规模**：研究涵盖了数百个单细胞的代谢标记测序（scSLAM-seq）和数千个细胞的单细胞扰动测序（Perturb-seq）。
*   **充分性评价**：
    *   **多维度验证**：结合了转录组（RNA）、染色质可及性（ATAC）和功能扰动（CRISPR），实验设计非常全面。
    *   **时间分辨率**：通过代谢标记和多时间点采样，捕捉到了感染早期的细微变化。
    *   **客观性**：通过无监督聚类和轨迹分析，客观地识别出了细胞状态的分叉，而非预设分类。

### 6. 主要结论与发现
*   **关键决策点**：感染后 **6 小时（6 hpi）** 是巨噬细胞极化的关键分叉点。此时，一部分细胞在 SPI2 活性的驱动下脱离促炎轨迹，转向抗炎状态。
*   **转录重塑机制**：沙门氏菌 SPI2 的激活不仅抑制了 NF-κB 驱动的炎症程序，还诱导了由 **STAT3、AP-1（如 Junb/Jund）和 Maf** 家族成员介导的特定转录模块。
*   **关键调节因子**：
    *   **Cybb（编码 NADPH 氧化酶组分）**：被识别为限制细菌复制的关键因子。
    *   **Foxo1**：被证实是调节宿主反应的重要转录因子，其扰动会显著改变感染后的细胞命运。
*   **染色质重塑**：观察到广泛的染色质开放性变化，证实了细菌感染诱导了宿主表观遗传层面的重编程。

### 7. 优点（亮点）
*   **高时间分辨率**：scSLAM-seq 的应用解决了传统 scRNA-seq 无法区分瞬时转录变化的痛点。
*   **病原体-宿主关联**：通过 SPI2 报告系统，直接将细菌的毒力状态与单个宿主细胞的转录反应联系起来。
*   **系统性视角**：不仅发现了基因表达的变化，还通过足迹分析揭示了上游转录因子的动态网络。

### 8. 不足与局限
*   **样本量限制**：由于 scSLAM-seq 技术复杂且成本高，早期时间点的细胞数量相对较少（数百个），可能遗漏一些罕见的细胞亚态。
*   **体外模型**：研究主要基于体外培养的巨噬细胞（BMDM/Hoxb8），虽然具有代表性，但可能无法完全模拟体内复杂的组织微环境。
*   **效应蛋白特异性**：虽然确定了 SPI2 的整体作用，但具体是哪一种效应蛋白（沙门氏菌有几十种效应蛋白）导致了特定的转录因子改变，仍需进一步拆解。

（完）
