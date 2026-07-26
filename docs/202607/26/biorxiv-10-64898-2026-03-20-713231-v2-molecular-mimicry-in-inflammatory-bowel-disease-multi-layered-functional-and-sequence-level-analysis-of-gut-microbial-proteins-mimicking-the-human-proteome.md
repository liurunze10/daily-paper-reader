---
title: "Molecular Mimicry in Inflammatory Bowel Disease: Multi-layered Functional and Sequence-level Analysis of Gut Microbial Proteins Mimicking the Human Proteome"
title_zh: 炎症性肠病中的分子模拟：模拟人类蛋白质组的肠道微生物蛋白质的多层功能和序列水平分析
authors: "Anand, A. A., Mishra, P., Srivathsa, V. S., Yadav, V., Samanta, S. K."
date: 2026-07-21
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.20.713231v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: 炎症性肠病（IBD）中模拟人类蛋白质组的肠道微生物蛋白分析
tldr: 本研究通过多层分子模拟分析流程（MMIP），对HMP2数据库中39个肠道宏基因组样本进行了系统分析，探讨了炎症性肠病（IBD）中微生物蛋白与人类蛋白的结构或功能相似性。研究发现克罗恩病（CD）比溃疡性结肠炎（UC）具有更高的免疫相关模拟率，并识别出不同亚型特有的致病菌谱。该研究首次在宏基因组层面揭示了IBD中分子模拟的失调，为理解微生物失调如何诱发免疫失调提供了新的机制见解。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-001.webp\", \"caption\": \"Figure 3B — Distribution of % identity of DIAMOND hits across groups.\", \"page\": 11, \"index\": 1, \"width\": 956, \"height\": 841}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-002.webp\", \"caption\": \"Figure 1. Molecular Mimicry In Silico Pipeline (MMIP) workflow for IBD metagenomics\", \"page\": 7, \"index\": 2, \"width\": 827, \"height\": 922}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-003.webp\", \"caption\": \"Figure 9. Bacterial mimicry of the NOD2 signalling pathway in Crohn's disease: domain architecture, normal signalling, and potential points of interference.\", \"page\": 46, \"index\": 3, \"width\": 814, \"height\": 1220}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-004.webp\", \"caption\": \"Table 5. Differentially enriched GO terms identified by g:Profiler analysis of Ensembl gene IDs derived from GO ID conversion (p < 0.05).\", \"page\": 23, \"index\": 4, \"width\": 976, \"height\": 438}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-005.webp\", \"caption\": \"Figure 7C — Grouped horizontal bar chart of top 20 human protein targets.\", \"page\": 28, \"index\": 5, \"width\": 849, \"height\": 358}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-006.webp\", \"caption\": \"Table 1. Predicted ORF counts per sample across diagnostic groups, before and after removal of underrepresented samples\", \"page\": 8, \"index\": 6, \"width\": 1079, \"height\": 400}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-007.webp\", \"caption\": \"Figure 2 — ORF counts per diagnostic group with individual sample values overlaid.\", \"page\": 9, \"index\": 7, \"width\": 752, \"height\": 533}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-008.webp\", \"caption\": \"Figure 10. The NOD2 vicious cycle: molecular mimicry as a mechanistic bridge between genetic susceptibility and microbial dysbiosis in Crohn's disease.\", \"page\": 48, \"index\": 8, \"width\": 937, \"height\": 1191}]"
motivation: 探究肠道微生物蛋白与宿主蛋白之间的分子模拟是否是诱发或加剧炎症性肠病自身免疫反应的潜在机制。
method: 开发并应用多层分子模拟分析流程（MMIP），结合同源搜索、功能富集及分类学分析，对HMP2宏基因组数据进行深度挖掘。
result: 发现克罗恩病具有更高的免疫相关模拟率，且健康肠道原有的协调模拟机制在IBD中被疾病特异性的致病菌特征所取代。
conclusion: 本研究首次在宏基因组尺度上刻画了IBD亚型的分子模拟图谱，为微生物失调导致免疫功能紊乱提供了新的理论依据。
---

## 摘要
炎症性肠病（IBD）包括克罗恩病（CD）和溃疡性结肠炎（UC），是一种发病机制涉及复杂宿主-微生物群相互作用的慢性炎症性疾病。分子模拟（微生物与宿主蛋白质之间的结构或功能相似性）是肠道微生物群可能触发或维持自身免疫反应的一种合理机制。在此，我们对来自人类微生物组计划 2（HMP2/IBDMDB）的 39 个基线鸟枪法宏基因组样本进行了全面的多层分子模拟计算机模拟管线（MMIP）分析。通过针对 SwissProt 的基于 DIAMOND 的同源性搜索以及随后的 UniProt 检索/ID 映射（URIM），我们通过三个互补框架表征了微生物蛋白质的功能空间：(i) 不同诊断组间归一化的 GO 术语频率比较，(ii) 蛋白质家族（PFAM）结构域富集分析，以及 (iii) 识别与人类蛋白质具有直接同源性的微生物蛋白质的序列水平模拟分析。使用 MetaPhlAn3 预计算丰度谱进行的分类学分析提供了进一步的生物学背景。CD 微生物组表现出比 UC 更高的免疫相关生物过程富集和更高的单样本序列水平模拟率。CD 和 UC 还显示出截然不同的致病共生菌谱，CD 富含包括副流感嗜血杆菌（Haemophilus parainfluenzae）在内的口腔来源分类群，而 UC 富含具核梭杆菌（Fusobacterium nucleatum）和普雷沃氏菌属（Prevotella species）。值得注意的是，健康的肠道微生物组维持着对宿主神经元、信号识别颗粒相关和抗菌肽机制的协调模拟，而这一套模拟机制在 IBD 中被拆解，并被疾病亚型特异性特征所取代，同时还发现了 CD 富集细菌与 NOD2 之间潜在的模拟联系。这些结果代表了首次利用鸟枪法宏基因组数据对 IBD 亚型分子模拟进行的宏基因组范围表征，为微生物失调如何导致 IBD 免疫失调提供了新的机制见解。

## Abstract
Inflammatory bowel disease (IBD), encompassing Crohn's disease (CD) and ulcerative colitis (UC), is a chronic inflammatory disorder whose pathogenesis involves intricate host-microbiome interactions. Molecular mimicry (the structural or functional resemblance between microbial and host proteins) represents a plausible mechanism by which gut microbiota may trigger or perpetuate autoimmune responses. Here we present a comprehensive, multi-layered molecular mimicry in silico pipeline (MMIP) analysis of 39 baseline shotgun metagenomic samples from Human Microbiome Project 2 (HMP2/IBDMDB). Using DIAMOND-based homology search against the SwissProt followed by UniProt Retrieve/ID Mapping (URIM), we characterized microbial protein functional space through three complementary frameworks: (i) normalized GO term frequency comparison across diagnostic groups, (ii) protein family (PFAM) domain enrichment analysis, and (iii) sequence-level mimicry analysis identifying microbial proteins with direct homology to human proteins. Taxonomic profiling using MetaPhlAn3 pre-computed abundance profiles provided further biological context. CD microbiomes exhibited greater enrichment of immune-relevant biological processes and a higher per-sample sequence-level mimicry rate than UC. CD and UC also showed distinct pathobiont profiles, with CD enriched for oral-origin taxa including Haemophilus parainfluenzae and UC enriched for Fusobacterium nucleatum and Prevotella species. Notably, healthy gut microbiome maintains coordinated mimicry of host neuronal, signal-recognition-particle-associated, and antimicrobial peptide machinery, a repertoire dismantled in IBD and replaced by disease-subtype-specific signatures, alongside a candidate mimicry link between CD-enriched bacteria and NOD2. These results represent the first metagenome-wide characterization of molecular mimicry across IBD subtypes using shotgun metagenomic data, offering new mechanistic insight into how microbial dysbiosis may contribute to immune dysregulation in IBD. Keywords: Inflammatory bowel disease (IBD), Crohn's disease (CD), Ulcerative colitis (UC), Gastroenteritis, Molecular mimicry

---

## 论文详细总结（自动生成）

这篇论文对炎症性肠病（IBD）中的分子模拟现象进行了系统性的生物信息学研究。以下是详细的结构化总结：

### 1. 核心问题与整体含义（研究动机和背景）
*   **核心问题**：探讨肠道微生物蛋白质与人类宿主蛋白质之间的**分子模拟（Molecular Mimicry）**——即结构或功能上的相似性——是否是诱发或加剧炎症性肠病（包括克罗恩病 CD 和溃疡性结肠炎 UC）免疫失调的关键机制。
*   **研究背景**：IBD 的发病涉及复杂的宿主-微生物相互作用。传统的 16S rRNA 测序无法提供蛋白质编码序列的解析度，而鸟枪法宏基因组学（Shotgun Metagenomics）为在宏基因组尺度上系统表征分子模拟提供了可能。

### 2. 论文提出的方法论
论文开发并应用了**多层分子模拟分析流程（MMIP）**，核心步骤包括：
*   **序列准备**：从 HMP2 数据库提取基因调用序列，翻译为蛋白质序列。
*   **同源性搜索**：使用 **DIAMOND** 算法将微生物蛋白序列与 UniProt SwissProt 手动注释库进行比对（E-value ≤ 1e-5）。
*   **功能空间表征**：通过 UniProt 检索/ID 映射（URIM）获取功能元数据。
*   **多层分析框架**：
    1.  **归一化 GO 术语频率分析**：比较不同诊断组间基因本体（GO）术语的出现频率，并应用三层过滤（生物过程、排除通用术语、限制人类术语规模）。
    2.  **PFAM 结构域富集分析**：识别富集的蛋白质家族结构域。
    3.  **序列水平模拟分析**：直接识别与人类蛋白质具有高度同源性的微生物蛋白。
    4.  **单 ORF 分辨率溯源**：建立从特定模拟蛋白到其来源样本及具体细菌物种的追踪机制。

### 3. 实验设计
*   **数据集**：使用人类微生物组计划 2（HMP2/IBDMDB）的 39 个基线鸟枪法宏基因组样本（12 名健康对照 non-IBD，17 名 CD 患者，10 名 UC 患者）。
*   **Benchmark（基准）**：以健康人群（non-IBD）的肠道宏基因组作为基准。
*   **对比方法**：进行三组两两对比（CD vs non-IBD, UC vs non-IBD, CD vs UC），并结合 MetaPhlAn3 的分类学丰度谱进行生物学背景校验。

### 4. 资源与算力
*   **算力说明**：文中提到使用 DIAMOND（版本 2.1.9 和 2.1.11）进行高通量比对，配置为 4 个 CPU 线程（--threads 4）。
*   **未明确事项**：论文未详细列出具体的服务器硬件型号（如 CPU 具体型号、内存容量）或总训练/计算时长，但从流程看，该研究主要依赖 CPU 集群进行生物信息学运算，而非 GPU 加速的深度学习。

### 5. 实验数量与充分性
*   **实验规模**：分析了超过 178 万个预测蛋白序列。
*   **充分性**：研究采用了多层过滤机制（如 3-filter GO 分析）和交叉验证（如将功能富集与分类学丰度结合），并进行了单分子水平的“自下而上”验证。
*   **局限性**：样本量（n=39）相对较小，虽然对于基线特征表征具有代表性，但在统计效力上可能存在局限。

### 6. 主要结论与发现
*   **CD 的显著性**：克罗恩病（CD）微生物组表现出比 UC 更强的功能发散性，其免疫相关生物过程的富集程度和序列水平模拟率均显著更高。
*   **SRNM 轴的提出**：发现健康肠道维持着对宿主神经元、信号识别颗粒（SRP）和抗菌肽（AMP）机制的协调模拟，而这套“稳态模拟库”在 IBD 中被拆解。
*   **NOD2 模拟联系**：首次发现 CD 富集细菌（如口腔来源分类群）携带模拟 **NOD2**（CD 最主要的遗传风险因子）信号通路的蛋白质，暗示了遗传易感性与微生物失调之间的分子桥梁。
*   **亚型特异性特征**：CD 倾向于模拟压力、凋亡和线粒体干扰路径；UC 则倾向于模拟细胞因子信号和免疫扩增路径。

### 7. 优点
*   **视角新颖**：首次在宏基因组尺度上系统刻画 IBD 亚型的分子模拟图谱。
*   **多维整合**：将序列同源性、功能域富集、GO 术语频率和分类学信息有机整合，提供了比单一分析更稳健的证据。
*   **机制洞察**：提出的 SRNM 轴和 NOD2 模拟循环为 IBD 的病理生理学提供了极具吸引力的假设。

### 8. 不足与局限
*   **计算推导性质**：所有结果均基于计算机模拟（In silico），缺乏体外（In vitro）或体内（In vivo）的实验验证（如 T 细胞交叉反应实验）。
*   **同源性阈值**：序列水平模拟的平均一致性在 35% 左右，处于序列比对的“灰色地带”（Twilight Zone），其免疫学意义仍需结构生物学验证。
*   **样本量限制**：39 个样本虽来自高质量队列，但不足以完全排除个体差异和环境混杂因素的影响。

（完）
