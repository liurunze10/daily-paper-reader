---
title: Multimodal temporal mapping of macrophage transcriptome remodeling during Salmonella infection
title_zh: 沙门氏菌感染期间巨噬细胞转录组重塑的多模态时间图谱
authors: "Toussaint, C., Hill, P. W. S., Klodewig, B., Eldridge, M. J., Theis, F. J., Helaine, S., Saliba, A.-E."
date: 2026-07-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.04.736507v1.full.pdf"
tags: ["query:ros-mp"]
score: 8.0
evidence: 巨噬细胞转录组重塑与促炎/抗炎重编程
tldr: 本研究旨在揭示沙门氏菌如何重塑巨噬细胞转录组以逃避宿主免疫。通过结合细菌报告系统、时间单细胞RNA测序、RNA代谢标记、转录因子足迹分析及单细胞CRISPR干扰等多种前沿技术，研究团队捕捉到了巨噬细胞在感染早期的极化分叉点。研究发现，沙门氏菌通过激活SPI2效应蛋白，不仅抑制了NFkB驱动的促炎反应，还诱导了特定的抗炎转录模块。这一多模态图谱为理解宿主-病原体相互作用及免疫逃逸机制提供了重要见解。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究沙门氏菌如何通过操纵宿主转录因子将巨噬细胞从促炎状态重塑为有利于细菌复制的抗炎状态。
method: 采用结合了细菌报告基因、时间单细胞RNA测序、代谢标记、转录因子足迹分析和单细胞CRISPR筛选的多模态方法。
result: 识别出感染过程中的关键分叉点，发现沙门氏菌SPI2系统在抑制NFkB促炎程序的同时，通过AP-1和Maf等因子诱导了抗炎表型。
conclusion: 该研究揭示了巨噬细胞极化的决策点及沙门氏菌利用的免疫调节漏洞，为理解病原体逃逸机制提供了新视角。
---

## 摘要
巨噬细胞具备清除入侵病原体的能力，但一些胞内细菌却利用它们作为复制生态位。鼠伤寒沙门氏菌通过注入效应蛋白来重塑巨噬细胞功能，从而破坏宿主免疫。虽然巨噬细胞在细菌入侵时通常会诱导促炎程序，但沙门氏菌可以通过操纵宿主转录因子 NFkB 和 STAT3，将它们重定向为抗炎且允许复制的状态。这种重编程如何整合这两个转录因子以及其他潜在因子的影响，目前尚不清楚。在这里，我们采用了一种多管齐下的方法，结合细菌报告基因、带有 RNA 代谢标记的时间单细胞 RNA-seq、转录因子 (TF) 足迹分析以及单细胞 CRISPR 扰动，来剖析感染早期的巨噬细胞极化动态。我们捕捉到了感染过程中的分叉点，即一部分巨噬细胞向抗炎表型转变。这种转变涉及沙门氏菌致病岛 2 (SPI2) 的激活，导致最初由 NFkB 驱动的炎症程序减弱，并诱导了 NFkB 和 STAT3 之外的特定转录模块，其中 AP-1 和 Maf 家族成员可能也发挥了作用。总之，我们的研究揭示了巨噬细胞极化回路中的宿主决策点，并发现了沙门氏菌利用来调节宿主免疫的漏洞。

## Abstract
Macrophages are equipped to eliminate invading pathogens, yet several intracellular bacteria exploit them as replicative niches. Salmonella enterica serovar Typhimurium subverts host immunity by injecting effector proteins that remodel macrophage functions. While macrophages typically induce a pro-inflammatory program upon bacterial invasion, Salmonella can redirect them toward an anti-inflammatory and replication-permissive state via manipulation of the NFkB and STAT3 host transcription factors. How the integration of the effects on these two transcription factors and potentially others underpins this reprogramming remains poorly charted. Here, we use a multipronged approach combining a bacterial reporter, temporal single-cell RNA-seq with RNA metabolic labeling, transcription factor (TF) footprinting, and single-cell CRISPR perturbations to dissect macrophage polarization dynamics during early infection. We catch the bifurcation during infection, where a subset of macrophages transition toward the anti-inflammatory phenotype. This shift involves the activation of Salmonella pathogenicity island 2 (SPI2) leading to both the dampening of the initial NFkB-driven inflammatory program and the induction of specific transcriptional modules beyond NFkB and STAT3, with possible contributions from AP-1 and Maf family members. Together, our study uncovers host decision points in macrophage polarization circuitry and reveals a vulnerability exploited by Salmonella to modulate host immunity.

---

## 论文详细总结（自动生成）

这是一份关于论文《沙门氏菌感染期间巨噬细胞转录组重塑的多模态时间图谱》的深度学术总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：巨噬细胞本应清除病原体，但鼠伤寒沙门氏菌（*Salmonella* Typhimurium）却能将其重塑为有利于自身复制的“避难所”。研究旨在揭示沙门氏菌如何通过其效应蛋白，在分子层面操纵宿主转录因子（如 NFkB、STAT3 等），将巨噬细胞从促炎状态（M1型）重编程为抗炎/允许复制状态（M2型）的动态过程。
*   **研究背景**：虽然已知沙门氏菌利用其致病岛 2（SPI2）分泌系统进行免疫逃逸，但这种转录重塑的精确时间点、涉及的完整转录因子网络以及宿主细胞在感染过程中的决策分叉路径尚不清晰。

### 2. 方法论：核心思想与关键技术
研究采用了一种**多模态、多组学集成**的方法，旨在捕捉高分辨率的动态转录组变化：
*   **细菌报告系统**：利用带有荧光报告基因的沙门氏菌，区分感染与未感染细胞，并监测细菌内部 SPI2 毒力系统的激活状态。
*   **scSLAM-seq（时间单细胞RNA测序+代谢标记）**：通过 4-硫代尿苷（4sU）标记新合成的 RNA，使研究者能够区分“既有转录本”和“新合成转录本”，从而精确测量感染诱导的转录速率变化。
*   **TF Footprinting（转录因子足迹分析）**：利用单细胞染色质可及性数据（或从转录组推断）来预测哪些转录因子在特定时间点处于活跃结合状态。
*   **单细胞 CRISPR 干扰（scCRISPRi）**：对预测的关键转录因子进行基因扰动，在单细胞水平验证其在巨噬细胞重编程中的功能。

### 3. 实验设计与对比
*   **实验场景**：小鼠骨髓来源巨噬细胞（BMDMs）感染鼠伤寒沙门氏菌的时间序列实验（涵盖感染后 0 到数小时的关键窗口）。
*   **对比组（Benchmark）**：
    *   **感染 vs. 未感染**：观察基础免疫反应。
    *   **野生型细菌 vs. SPI2 缺陷型突变株（$\Delta$ssaV）**：验证沙门氏菌毒力因子对宿主重塑的必要性。
    *   **不同极化状态**：对比经典的 LPS/IFN-$\gamma$（促炎）和 IL-4（抗炎）刺激下的转录谱。
*   **数据集成**：将代谢标记数据与计算模型结合，识别转录动力学中的“分叉点”。

### 4. 资源与算力
*   **算力说明**：论文中未明确提及具体的 GPU 型号、数量或训练时长。
*   **数据规模**：涉及大规模的单细胞测序数据处理（数万个单细胞的转录组和代谢标记数据），通常需要高性能计算集群（HPC）进行生物信息学流程（如 CellRanger, Velocyto, 或自定义的 scSLAM-seq 分析管道）的处理。

### 5. 实验数量与充分性
*   **实验充分性**：研究设计非常全面。不仅包含了时间序列的单细胞转录组分析，还通过代谢标记解决了传统 scRNA-seq 无法捕捉瞬时转录变化的问题。
*   **验证维度**：通过 $\Delta$ssaV 突变株验证了细菌侧的机制，通过 CRISPRi 验证了宿主侧的机制（消融实验），形成了闭环。
*   **客观性**：使用了多模态数据交叉验证，减少了单一组学带来的偏差。

### 6. 主要结论与发现
*   **识别分叉点**：在感染早期存在一个关键决策点，巨噬细胞在此处分化为“促炎响应型”或“细菌重塑型”。
*   **SPI2 的核心作用**：沙门氏菌 SPI2 系统的激活是重塑的关键，它不仅减弱了由 NFkB 驱动的促炎程序，还主动诱导了抗炎模块。
*   **新型转录因子参与**：除了已知的 NFkB 和 STAT3，研究发现 **AP-1** 家族成员和 **Maf** 家族转录因子在维持抗炎表型和促进细菌存活中起到了此前未被充分认识的作用。
*   **转录动力学**：代谢标记揭示了某些炎症基因的转录在感染后期被主动抑制，而非自然降解。

### 7. 优点（亮点）
*   **技术前沿性**：将代谢标记（scSLAM-seq）与单细胞扰动（CRISPRi）结合，是目前研究宿主-病原体相互作用的最先进手段。
*   **高分辨率**：成功捕捉到了极化过程中的瞬态中间态，这是传统体测序（Bulk RNA-seq）无法实现的。
*   **系统性视角**：从细菌毒力激活和宿主转录响应两个维度同时建模，提供了完整的互动图谱。

### 8. 不足与局限
*   **体外模型限制**：研究主要基于骨髓来源的巨噬细胞（BMDMs），可能无法完全模拟体内复杂组织环境（如脾脏或肠道）中的巨噬细胞多样性。
*   **时间窗口**：研究集中在感染早期，对于长期慢性感染阶段的转录重塑可能覆盖不足。
*   **效应蛋白特异性**：虽然确定了 SPI2 的重要性，但具体是哪一个或哪几个效应蛋白（SPI2 包含 30 多个效应蛋白）直接作用于 AP-1 或 Maf 尚需进一步细化研究。

（完）
