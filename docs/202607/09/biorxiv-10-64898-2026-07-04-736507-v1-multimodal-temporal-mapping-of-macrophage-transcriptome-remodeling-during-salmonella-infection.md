---
title: Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection
title_zh: 沙门氏菌感染期间巨噬细胞转录组重塑的多模态时间图谱
authors: "Toussaint, C., Hill, P. W. S., Klodewig, B., Eldridge, M. J., Theis, F. J., Helaine, S., Saliba, A.-E."
date: 2026-07-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.04.736507v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: 巨噬细胞转录组重塑以及促炎与抗炎重编程
tldr: 本研究利用多模态时间序列单细胞转录组学，揭示了沙门氏菌感染早期巨噬细胞极化的动态过程。通过结合RNA代谢标记、转录因子足迹分析和单细胞CRISPR扰动技术，研究发现感染后6小时是决定巨噬细胞向促炎或抑炎状态转变的关键节点。沙门氏菌通过SPI2系统重塑宿主染色质并调节NF-κB、STAT3及AP-1等转录因子，从而诱导有利于细菌复制的微环境，为理解病原体逃避宿主免疫提供了新视角。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-001.webp\", \"caption\": \"Figure 1: Connected macrophage fate trajectories to Salmonella SPI-2 activity through scSLAM-seq. (A) Experimental (upper panel) and analytical (bottom panel) workflow depicting the time-course and multimodal scSLAM-seq analysis of infected bone marrow derived macrophages with Salmonella carrying a SPI2-reporter plasmid. (B) Aggregated scatter plot of intracellular bacterial SPI2 activity in non-infected (mock) and infected macrophages analysed and sorted by FACS across the complete time-course of the experiment time points of infection analysed. Grey background data points and contour lines correspond to the entire cell population analysed superimposed with timepoint-colored dots indicating all the individual sorted macrophages for downstream analysis color-coded by time-point further processed for scSLAM-seq. The scatter plot has been segmented in four quadrants based on bacterial intracellular activity. (C & D) UMAP (Uniform Manifold Approximation and Projection)\", \"page\": 6, \"index\": 1, \"width\": 943, \"height\": 1152}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-002.webp\", \"caption\": \"Figure 2: Dynamics of transcriptional response of macrophages. (A) UMAP visualization of 578 single-macrophage transcriptomes obtained by scSLAM-seq as in Figures 1C and 1D and colored by cell state as identified by unsupervised clustering with the Leiden algorithm. (B) Dot plot of scaled, log-normalized expression of marker selected representative genes from the different macrophage states identified (A). Top and bottom panels correspond to the inflammatory and anti-inflammatory macrophage trajectory, respectively. Dot size indicates the percentage of cells per cell state with detectable mRNA expression, and color shows Z-scores of log-normalized new RNA readcounts. (C) Analysis of differentially expressed genes overlap between different macrophage states represented by a Venn plot of differentially expressed genes (FDR < 0.05, Wilcoxon Rank Sum test with Benjamini-Hochberg correction) differentiating the early response at 2/4hpi and the inflammatory/anti-inflammatory signatures. Circle size is proportional to the total number of DEG within each group. Indicated numbers correspond to the number of specific or shared DEGs between groups. Comparisons between\", \"page\": 10, \"index\": 2, \"width\": 946, \"height\": 1050}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-04-736507-v1/fig-003.webp\", \"caption\": \"Figure 4: A map of upstream transcription factor regulating gene modules underlying macrophage polarization states.\", \"page\": 18, \"index\": 3, \"width\": 821, \"height\": 704}]"
motivation: 旨在阐明沙门氏菌如何通过操纵宿主转录因子，将巨噬细胞从促炎状态重塑为有利于细菌复制的抑炎状态。
method: 结合了细菌报告系统、带代谢标记的时间序列单细胞RNA测序、转录因子足迹分析以及单细胞CRISPR扰动技术。
result: 识别出感染后6小时的关键决策点，并发现沙门氏菌SPI2诱导的染色质重塑及Cybb、Foxo1等基因对感染结果的调节作用。
conclusion: 研究揭示了巨噬细胞极化电路中的宿主决策点，并阐明了沙门氏菌利用这些漏洞调节宿主免疫的分子机制。
---

## 摘要
巨噬细胞具备清除入侵病原体的能力，然而一些胞内细菌却利用它们作为复制生态位。鼠伤寒沙门氏菌（Salmonella Typhimurium）通过注入效应蛋白来重塑巨噬细胞功能，从而破坏宿主免疫。虽然巨噬细胞在细菌入侵时通常会启动促炎程序，但沙门氏菌能通过操纵宿主转录因子 NF-κB 和 STAT3，将它们重定向至抗炎且允许复制的状态。目前尚不清楚这些对转录因子的影响以及潜在的其他因素是如何整合并支撑这种重编程的。本研究采用多管齐下的方法，结合细菌报告系统、带有 RNA 代谢标记的时间单细胞 RNA-seq、转录因子（TF）足迹分析以及单细胞 CRISPR 扰动，剖析了感染早期巨噬细胞极化的动态过程。我们捕捉到了感染过程中的分叉点，即一部分巨噬细胞向抗炎表型转变。这一转变涉及沙门氏菌致病岛 2（SPI2）的激活，既削弱了最初由 NF-κB 驱动的炎症程序，又诱导了 NF-κB 和 STAT3 之外的特定转录模块，其中 AP-1 和 Maf 家族成员可能也参与其中。总之，我们的研究揭示了巨噬细胞极化回路中的宿主决策点，并发现了沙门氏菌用于调节宿主免疫的漏洞。研究亮点：时间单细胞 RNA-seq 定义了伴随鼠伤寒沙门氏菌 SPI2 诱导而出现的促炎和抗炎巨噬细胞状态；感染结果的关键决策点在感染后 6 小时达到；巨噬细胞重编程与广泛的染色质重塑和动态转录因子结合相关；单细胞 Perturb-seq 实验揭示了 Cybb 和 Foxo1 是 Hoxb8 巨噬细胞感染结果的调节因子。

## Abstract
Macrophages are equipped to eliminate invading pathogens, yet several intracellular bacteria exploit them as replicative niches. Salmonella enterica serovar Typhimurium subverts host immunity by injecting effector proteins that remodel macrophage functions. While macrophages typically induce a pro-inflammatory program upon bacterial invasion, Salmonella can redirect them toward an anti-inflammatory and replication-permissive state via manipulation of the NF-{kappa}B and STAT3 host transcription factors. How the integration of the effects on these two transcription factors and potentially others underpins this reprogramming remains poorly charted. Here, we use a multipronged approach combining a bacterial reporter, temporal single-cell RNA-seq with RNA metabolic labeling, transcription factor (TF) footprinting, and single-cell CRISPR perturbations to dissect macrophage polarization dynamics during early infection. We catch the bifurcation during infection, where a subset of macrophages transition toward the anti-inflammatory phenotype. This shift involves the activation of Salmonella pathogenicity island 2 (SPI2) leading to both the dampening of the initial NF-{kappa}B-driven inflammatory program and the induction of specific transcriptional modules beyond NF-{kappa}B and STAT3, with possible contributions from AP-1 and Maf family members. Together, our study uncovers host decision points in macrophage polarization circuitry and reveals a vulnerability exploited by Salmonella to modulate host immunity.

HIGHLIGHTSO_LITemporal scRNA-seq defines the emergence of inflammatory and anti-inflammatory macrophage states concomitant with Salmonella Typhimurium SPI2 induction.
C_LIO_LIA critical decision point for infection outcome is reached by 6 hours post-infection.
C_LIO_LIMacrophage reprogramming is associated with widespread chromatin remodeling and dynamic transcription factor binding.
C_LIO_LISingle-cell perturb-seq experiment uncovers Cybb and Foxo1 as modulators of infection outcome in Hoxb8 macrophages.
C_LI

---

## 论文详细总结（自动生成）

这是一份关于论文《Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection》（沙门氏菌感染期间巨噬细胞转录组重塑的多模态时间图谱）的结构化深入总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：沙门氏菌（*Salmonella Typhimurium*）作为一种胞内寄生菌，如何通过操纵宿主巨噬细胞的转录程序，将其从“促炎/杀菌”状态重塑为“抗炎/允许复制”的状态？
*   **研究背景**：巨噬细胞在感染初期通常会启动促炎反应，但沙门氏菌能利用其致病岛2（SPI2）分泌效应蛋白，干扰宿主信号通路。目前学术界尚不清楚这种从促炎到抗炎的“极化转换”在单细胞水平上的精确时间动态、关键决策点以及背后的多模态调控机制（转录因子结合与染色质重塑的整合）。

### 2. 论文提出的方法论
研究采用了一种**多模态、时间序列的单细胞分析框架**，核心技术包括：
*   **scSLAM-seq（单细胞硫醇特异性测序）**：通过 4-硫尿苷（4sU）代谢标记新合成的 RNA，从而区分“新合成”与“既有”转录本，极大地提高了捕捉瞬时转录变化的时间分辨率。
*   **细菌报告系统**：使用携带 SPI2 启动子驱动 GFP 表达的沙门氏菌株，通过流式细胞术（FACS）根据细菌的致病性状态（SPI2 活性）对巨噬细胞进行分选。
*   **scATAC-seq 与 TF 足迹分析**：利用单细胞转录组与染色质可及性测序，结合转录因子（TF）足迹分析，推断感染过程中转录因子的动态结合模式。
*   **单细胞 Perturb-seq**：结合 CRISPR 扰动与单细胞测序，对筛选出的候选基因（如 *Cybb*, *Foxo1* 等）进行功能验证，观察其对感染结局的影响。

### 3. 实验设计
*   **实验模型**：小鼠骨髓来源巨噬细胞（BMDMs）以及 Hoxb8 永生化巨噬细胞。
*   **时间梯度**：感染后 0, 2, 4, 6, 12, 24 小时（hpi）。
*   **对比组（Benchmark）**：
    *   未感染细胞（Mock）与感染细胞的对比。
    *   携带不同 SPI2 活性细菌的细胞对比（SPI2-low vs. SPI2-high）。
    *   促炎轨迹（Inflammatory）与抗炎轨迹（Anti-inflammatory）的平行对比。
*   **分析流程**：利用 CellRank 算法推断细胞命运轨迹，识别驱动分叉的关键基因。

### 4. 资源与算力
*   **算力说明**：论文中**未明确提及**具体的 GPU 型号、数量或训练时长。
*   **软件工具**：分析主要依赖于生物信息学标准工具链，包括 Cell Ranger (10x Genomics)、Seurat、Scanpy、CellRank、pySCENIC（用于 TF 网络推断）以及用于 scATAC-seq 分析的 ArchR。

### 5. 实验数量与充分性
*   **实验规模**：
    *   scSLAM-seq 覆盖了数百个高质量单细胞，并结合了代谢标记的时间导数分析。
    *   scATAC-seq 捕获了数千个细胞的表观遗传图谱。
    *   Perturb-seq 针对 15 个候选基因进行了扰动实验。
*   **充分性评价**：实验设计非常充分且具有高度的互补性。通过从“描述性观察（测序）”到“机制推断（TF 分析）”再到“功能验证（CRISPR）”的闭环，客观地证明了沙门氏菌对宿主重塑的逻辑。

### 6. 主要结论与发现
*   **关键决策点**：感染后 **6 小时（6hpi）** 是巨噬细胞命运分叉的关键节点，此时细胞决定走向促炎清除路径或抗炎允许路径。
*   **SPI2 的作用**：SPI2 的激活不仅削弱了由 NF-κB 驱动的初始炎症程序，还诱导了特定的转录模块。
*   **转录因子重组**：发现除了已知的 NF-κB 和 STAT3 外，**AP-1 家族（如 Jun, Fos）和 Maf 家族**成员在维持抗炎状态中起到了核心作用。
*   **功能调节因子**：通过 Perturb-seq 证实，**Cybb（编码 NOX2）** 和 **Foxo1** 是调节巨噬细胞感染结局的关键宿主因子，它们的缺失会显著改变细菌在胞内的生存环境。

### 7. 优点（亮点）
*   **高时间分辨率**：scSLAM-seq 的应用解决了传统 scRNA-seq 无法区分转录滞后效应的问题，精准捕捉了“新合成”的应答信号。
*   **多模态整合**：将细菌的生理状态（SPI2 活性）与宿主的转录组、表观组直接关联，提供了病原体-宿主互作的深度视角。
*   **因果验证**：不仅停留在相关性分析，通过单细胞水平的 CRISPR 扰动实验增强了结论的生物学说服力。

### 8. 不足与局限
*   **体外模型限制**：研究主要基于体外培养的 BMDMs 和 Hoxb8 细胞，可能无法完全模拟体内复杂组织微环境（如脾脏或肝脏）中的多细胞互作。
*   **样本量限制**：scSLAM-seq 虽然时间分辨率高，但受限于技术成本，其分析的细胞绝对数量（数百个）相比标准 scRNA-seq 较少，可能遗漏极少数的细胞亚群。
*   **物种差异**：研究基于小鼠模型，沙门氏菌在人类巨噬细胞中的重塑机制可能存在物种特异性差异。

（完）
