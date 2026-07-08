---
title: Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection
title_zh: 沙门氏菌感染期间巨噬细胞转录组重塑的多模态时间图谱
authors: "Toussaint, C., Hill, P. W. S., Klodewig, B., Eldridge, M. J., Theis, F. J., Helaine, S., Saliba, A.-E."
date: 2026-07-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.04.736507v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: 绘制巨噬细胞转录组重塑和促/抗炎状态图谱
tldr: 本研究利用多模态时间映射技术，探讨了沙门氏菌感染早期巨噬细胞转录组的重塑过程。通过结合单细胞RNA测序、代谢标记和CRISPR扰动，研究揭示了巨噬细胞在感染过程中的表型分叉，即沙门氏菌如何通过SPI2系统抑制促炎反应并诱导抗炎状态，识别了除NFkB和STAT3外的关键转录因子，为理解宿主免疫逃逸机制提供了新见解。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在阐明沙门氏菌如何通过整合多种转录因子效应，将巨噬细胞从促炎状态重塑为有利于细菌复制的抗炎状态。
method: 采用结合了细菌报告系统、时间单细胞RNA测序、RNA代谢标记、转录因子足迹分析及单细胞CRISPR扰动的多模态方法。
result: 发现了感染过程中的表型分叉点，证实沙门氏菌SPI2系统在抑制NFkB促炎程序的同时，激活了涉及AP-1和Maf家族的特定转录模块。
conclusion: 研究揭示了巨噬细胞极化电路中的宿主决策点，并识别了沙门氏菌利用来调节宿主免疫的关键漏洞。
---

## 摘要
巨噬细胞具备清除入侵病原体的能力，然而一些胞内细菌却利用它们作为复制生态位。鼠伤寒沙门氏菌（Salmonella enterica serovar Typhimurium）通过注入效应蛋白来重塑巨噬细胞功能，从而破坏宿主免疫。虽然巨噬细胞在细菌入侵时通常会启动促炎程序，但沙门氏菌可以通过操纵宿主转录因子 NFkB 和 STAT3，将它们重定向为抗炎且允许复制的状态。这两个转录因子以及潜在的其他因子的效应整合如何支撑这种重编程，目前仍不清楚。在这里，我们采用了一种多管齐下的方法，结合细菌报告基因、带有 RNA 代谢标记的时间单细胞 RNA-seq、转录因子（TF）足迹分析以及单细胞 CRISPR 扰动，来剖析感染早期巨噬细胞极化的动力学。我们捕捉到了感染过程中的分叉点，即一部分巨噬细胞向抗炎表型转变。这种转变涉及沙门氏菌致病岛 2 (SPI2) 的激活，导致最初由 NFkB 驱动的炎症程序减弱，并诱导了 NFkB 和 STAT3 之外的特定转录模块，其中 AP-1 和 Maf 家族成员可能也做出了贡献。总之，我们的研究揭示了巨噬细胞极化回路中的宿主决策点，并发现了沙门氏菌利用来调节宿主免疫的漏洞。

## Abstract
Macrophages are equipped to eliminate invading pathogens, yet several intracellular bacteria exploit them as replicative niches. Salmonella enterica serovar Typhimurium subverts host immunity by injecting effector proteins that remodel macrophage functions. While macrophages typically induce a pro-inflammatory program upon bacterial invasion, Salmonella can redirect them toward an anti-inflammatory and replication-permissive state via manipulation of the NFkB and STAT3 host transcription factors. How the integration of the effects on these two transcription factors and potentially others underpins this reprogramming remains poorly charted. Here, we use a multipronged approach combining a bacterial reporter, temporal single-cell RNA-seq with RNA metabolic labeling, transcription factor (TF) footprinting, and single-cell CRISPR perturbations to dissect macrophage polarization dynamics during early infection. We catch the bifurcation during infection, where a subset of macrophages transition toward the anti-inflammatory phenotype. This shift involves the activation of Salmonella pathogenicity island 2 (SPI2) leading to both the dampening of the initial NFkB-driven inflammatory program and the induction of specific transcriptional modules beyond NFkB and STAT3, with possible contributions from AP-1 and Maf family members. Together, our study uncovers host decision points in macrophage polarization circuitry and reveals a vulnerability exploited by Salmonella to modulate host immunity.

---

## 论文详细总结（自动生成）

这是一份关于论文《Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection》（沙门氏菌感染期间巨噬细胞转录组重塑的多模态时间图谱）的结构化分析报告：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：沙门氏菌（*Salmonella*）作为一种胞内寄生菌，如何通过其分泌系统（特别是 SPI2）操纵宿主巨噬细胞，使其从“杀菌促炎”状态转变为“允许复制的抗炎”状态？
*   **研究背景**：巨噬细胞在感染初期通常表现出促炎反应，但沙门氏菌能重塑其转录组以逃避免疫。虽然已知 NFkB 和 STAT3 参与其中，但这种重编程的动态过程、涉及的其他转录因子（TF）以及这些信号如何整合，此前尚不清晰。
*   **整体含义**：本研究旨在绘制高分辨率的动态图谱，识别宿主免疫决策的关键节点，为理解病原体-宿主相互作用提供系统级视角。

### 2. 方法论：核心思想与关键技术
研究采用了一种**多模态时间映射（Multimodal temporal mapping）**框架，核心思想是将时间分辨率与功能扰动相结合：
*   **scSLAM-seq（代谢标记单细胞测序）**：通过 4-硫代尿苷（4sU）标记新合成的 RNA，区分“新合成”与“预存”的转录本，从而更灵敏地捕捉感染诱导的瞬时转录变化。
*   **细菌报告系统**：利用荧光报告基因区分感染了活菌、死菌或未感染的细胞，并监测 SPI2 系统的激活状态。
*   **转录因子足迹分析（TF Footprinting）**：基于单细胞转录组数据推断不同感染阶段转录因子的活性动态。
*   **单细胞 CRISPR 扰动（scCRISPRi）**：在单细胞水平上对推断出的关键转录因子进行基因敲低，验证其在巨噬细胞极化中的功能。

### 3. 实验设计
*   **实验模型**：小鼠骨髓源性巨噬细胞（BMDMs）感染鼠伤寒沙门氏菌（*S. Typhimurium*）。
*   **对比组（Benchmark）**：
    *   **野生型（WT）细菌** vs. **SPI2 缺陷型（ΔssaV）细菌**：用于识别 SPI2 效应蛋白的作用。
    *   **感染细胞** vs. **旁观者细胞（Bystanders）**：区分直接感染诱导的变化与旁路信号（如细胞因子）的影响。
*   **时间序列**：感染后 0、2、4、6 小时的多个采样点。
*   **验证实验**：针对识别出的 10 余个候选转录因子（如 *Jun*, *Mafb*, *Atf3* 等）进行 CRISPRi 筛选。

### 4. 资源与算力
*   **算力说明**：论文中未明确提及具体的 GPU 型号、数量或训练时长。
*   **数据规模**：涉及大规模的单细胞测序数据处理（scRNA-seq 和 scSLAM-seq），通常需要高性能计算集群（HPC）进行比对、定量及下游的轨迹推断和足迹分析。

### 5. 实验数量与充分性
*   **实验组设置**：涵盖了不同感染时间、不同细菌菌株、不同细胞状态（感染 vs 旁观者）的多维度对比。
*   **充分性**：研究不仅停留在观察层面（测序），还通过代谢标记增强了时间分辨率，并最终通过 CRISPRi 进行了功能性验证（闭环研究）。
*   **客观性**：通过单细胞技术排除了细胞群体异质性的干扰，实验设计逻辑严密，对照组设置合理。

### 6. 主要结论与发现
*   **表型分叉点**：识别出感染后约 2-4 小时存在一个关键分叉点，此时一部分巨噬细胞在 SPI2 的作用下开始偏离促炎路径。
*   **SPI2 的双重作用**：SPI2 既能主动抑制 NFkB 驱动的促炎程序，又能诱导特定的抗炎/修复模块。
*   **新型调控因子**：除了已知的 NFkB 和 STAT3，研究发现 **AP-1 家族（如 Jun, Fos）**和 **Maf 家族（如 Mafb）**成员在驱动巨噬细胞向抗炎状态转变中起到了核心作用。
*   **代谢重塑**：新合成 RNA 的分析揭示了感染早期代谢基因转录的快速重编程，早于表型标志物的出现。

### 7. 优点：亮点与创新
*   **高时间分辨率**：结合代谢标记（scSLAM-seq），能够比传统 scRNA-seq 更早、更准地捕捉到转录起始信号。
*   **多模态整合**：将细菌状态（SPI2 活性）与宿主转录组实时关联，实现了“双系统”同步观测。
*   **因果关系验证**：利用单细胞 CRISPRi 直接在复杂感染背景下验证转录因子的功能，增强了结论的可信度。

### 8. 不足与局限
*   **体外模型局限**：研究主要基于 BMDMs，虽然是经典模型，但可能无法完全模拟体内组织微环境（如组织驻留巨噬细胞的特殊性）。
*   **效应蛋白特异性**：虽然确定了 SPI2 的整体作用，但尚未完全厘清是哪一个具体的 SPI2 效应蛋白（共 30 余种）对应哪一个宿主转录因子的改变。
*   **时间跨度**：研究集中在感染早期（6 小时内），对于长期慢性感染阶段的转录重塑揭示有限。

（完）
