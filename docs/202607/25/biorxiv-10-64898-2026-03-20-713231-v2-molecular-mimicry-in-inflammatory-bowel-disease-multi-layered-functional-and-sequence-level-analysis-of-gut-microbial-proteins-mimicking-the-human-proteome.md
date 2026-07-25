---
title: "Molecular Mimicry in Inflammatory Bowel Disease: Multi-layered Functional and Sequence-level Analysis of Gut Microbial Proteins Mimicking the Human Proteome"
title_zh: 炎症性肠病中的分子模拟：模拟人类蛋白质组的肠道微生物蛋白质的多层功能和序列水平分析
authors: "Anand, A. A., Mishra, P., Srivathsa, V. S., Yadav, V., Samanta, S. K."
date: 2026-07-21
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.20.713231v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: 分析炎症性肠病（IBD）中模拟人类蛋白质组的肠道微生物蛋白
tldr: 本研究利用HMP2宏基因组数据，通过MMIP流程系统分析了肠道微生物与人类蛋白间的分子模拟。研究发现克罗恩病（CD）比溃疡性结肠炎（UC）具有更高的免疫相关模拟率，且两者致病菌谱各异。研究揭示了健康肠道中原有的分子模拟平衡在IBD中被破坏并被疾病特异性特征取代，为理解微生物失调驱动免疫失调提供了新视角。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-001.webp\", \"caption\": \"Figure 3B — Distribution of % identity of DIAMOND hits across groups.\", \"page\": 11, \"index\": 1, \"width\": 956, \"height\": 841}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-002.webp\", \"caption\": \"Figure 1. Molecular Mimicry In Silico Pipeline (MMIP) workflow for IBD metagenomics\", \"page\": 7, \"index\": 2, \"width\": 827, \"height\": 922}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-003.webp\", \"caption\": \"Figure 9. Bacterial mimicry of the NOD2 signalling pathway in Crohn's disease: domain architecture, normal signalling, and potential points of interference.\", \"page\": 46, \"index\": 3, \"width\": 814, \"height\": 1220}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-004.webp\", \"caption\": \"Table 5. Differentially enriched GO terms identified by g:Profiler analysis of Ensembl gene IDs derived from GO ID conversion (p < 0.05).\", \"page\": 23, \"index\": 4, \"width\": 976, \"height\": 438}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-005.webp\", \"caption\": \"Figure 7C — Grouped horizontal bar chart of top 20 human protein targets.\", \"page\": 28, \"index\": 5, \"width\": 849, \"height\": 358}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-006.webp\", \"caption\": \"Table 1. Predicted ORF counts per sample across diagnostic groups, before and after removal of underrepresented samples\", \"page\": 8, \"index\": 6, \"width\": 1079, \"height\": 400}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-007.webp\", \"caption\": \"Figure 2 — ORF counts per diagnostic group with individual sample values overlaid.\", \"page\": 9, \"index\": 7, \"width\": 752, \"height\": 533}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-008.webp\", \"caption\": \"Figure 10. The NOD2 vicious cycle: molecular mimicry as a mechanistic bridge between genetic susceptibility and microbial dysbiosis in Crohn's disease.\", \"page\": 48, \"index\": 8, \"width\": 937, \"height\": 1191}]"
motivation: 探究肠道微生物蛋白与宿主蛋白间的分子模拟是否是诱发炎症性肠病（IBD）免疫失调的关键机制。
method: 基于HMP2宏基因组数据，结合DIAMOND同源搜索、GO功能分析和PFAM结构域富集，构建了多层分子模拟分析流程。
result: 克罗恩病显示出更高的序列级模拟率，且IBD患者普遍失去了健康状态下协调的神经元及抗菌肽相关模拟特征。
conclusion: 研究首次在宏基因组尺度上刻画了IBD的分子模拟图谱，为微生物失调如何通过分子模拟贡献于IBD发病提供了新见解。
---

## 摘要
炎症性肠病（IBD）包括克罗恩病（CD）和溃疡性结肠炎（UC），是一种发病机制涉及复杂宿主-微生物群相互作用的慢性炎症性疾病。分子模拟（微生物与宿主蛋白质之间的结构或功能相似性）是肠道微生物群可能触发或维持自身免疫反应的一种合理机制。在此，我们对来自人类微生物组计划2（HMP2/IBDMDB）的39份基线鸟枪法宏基因组样本进行了全面的多层分子模拟计算机模拟管线（MMIP）分析。通过针对SwissProt数据库的基于DIAMOND的同源性搜索，随后进行UniProt检索/ID映射（URIM），我们通过三个互补框架表征了微生物蛋白质的功能空间：(i) 不同诊断组间归一化的GO术语频率比较，(ii) 蛋白质家族（PFAM）结构域富集分析，以及 (iii) 识别与人类蛋白质具有直接同源性的微生物蛋白质的序列水平模拟分析。使用MetaPhlAn3预计算丰度谱进行的分类学分析提供了进一步的生物学背景。CD微生物组表现出比UC更高程度的免疫相关生物过程富集和更高的单样本序列水平模拟率。CD和UC还显示出截然不同的致病共生菌谱，其中CD富集了包括副流感嗜血杆菌在内的口腔来源分类群，而UC则富集了具核梭杆菌和普雷沃氏菌属。值得注意的是，健康的肠道微生物组维持着对宿主神经元、信号识别颗粒（SRP）相关和抗菌肽机制的协调模拟，而这一谱系在IBD中被破坏，并被疾病亚型特异性特征所取代，同时还发现了CD富集细菌与NOD2之间潜在的模拟联系。这些结果代表了首次利用鸟枪法宏基因组数据对IBD亚型分子模拟进行的宏基因组范围表征，为微生物失调如何导致IBD免疫失调提供了新的机制见解。

## Abstract
Inflammatory bowel disease (IBD), encompassing Crohn's disease (CD) and ulcerative colitis (UC), is a chronic inflammatory disorder whose pathogenesis involves intricate host-microbiome interactions. Molecular mimicry (the structural or functional resemblance between microbial and host proteins) represents a plausible mechanism by which gut microbiota may trigger or perpetuate autoimmune responses. Here we present a comprehensive, multi-layered molecular mimicry in silico pipeline (MMIP) analysis of 39 baseline shotgun metagenomic samples from Human Microbiome Project 2 (HMP2/IBDMDB). Using DIAMOND-based homology search against the SwissProt followed by UniProt Retrieve/ID Mapping (URIM), we characterized microbial protein functional space through three complementary frameworks: (i) normalized GO term frequency comparison across diagnostic groups, (ii) protein family (PFAM) domain enrichment analysis, and (iii) sequence-level mimicry analysis identifying microbial proteins with direct homology to human proteins. Taxonomic profiling using MetaPhlAn3 pre-computed abundance profiles provided further biological context. CD microbiomes exhibited greater enrichment of immune-relevant biological processes and a higher per-sample sequence-level mimicry rate than UC. CD and UC also showed distinct pathobiont profiles, with CD enriched for oral-origin taxa including Haemophilus parainfluenzae and UC enriched for Fusobacterium nucleatum and Prevotella species. Notably, healthy gut microbiome maintains coordinated mimicry of host neuronal, signal-recognition-particle-associated, and antimicrobial peptide machinery, a repertoire dismantled in IBD and replaced by disease-subtype-specific signatures, alongside a candidate mimicry link between CD-enriched bacteria and NOD2. These results represent the first metagenome-wide characterization of molecular mimicry across IBD subtypes using shotgun metagenomic data, offering new mechanistic insight into how microbial dysbiosis may contribute to immune dysregulation in IBD. Keywords: Inflammatory bowel disease (IBD), Crohn's disease (CD), Ulcerative colitis (UC), Gastroenteritis, Molecular mimicry

---

## 论文详细总结（自动生成）

这是一份关于论文《Molecular Mimicry in Inflammatory Bowel Disease: Multi-layered Functional and Sequence-level Analysis of Gut Microbial Proteins Mimicking the Human Proteome》的结构化深入总结：

### 1. 核心问题与整体含义（研究动机和背景）
该研究聚焦于**炎症性肠病（IBD）**，包括克罗恩病（CD）和溃疡性结肠炎（UC）。尽管已知肠道微生物失调与 IBD 密切相关，但其诱发免疫失调的具体分子机制尚不完全明确。
*   **核心问题**：探讨“**分子模拟**”（Molecular Mimicry）机制，即微生物蛋白在序列或功能上与宿主蛋白相似，是否是导致宿主免疫系统误攻击自身组织、引发慢性炎症的关键。
*   **研究背景**：以往研究多依赖 16S rRNA 测序，缺乏蛋白质编码序列的分辨率。本文旨在通过宏基因组数据，系统性地刻画 IBD 患者肠道中微生物对人类蛋白质组的模拟图谱。

### 2. 方法论：核心思想与技术流程
研究者开发了**分子模拟计算机分析管线（MMIP）**，其核心思想是从功能、结构域和序列三个维度进行多层评估：
1.  **蛋白质序列准备**：从 HMP2 宏基因组数据中提取 Prodigal 预测的开放阅读框（ORF），并翻译为氨基酸序列。
2.  **同源性搜索**：利用 **DIAMOND** 算法将微生物蛋白序列与 **SwissProt** 手动注释数据库进行比对（E-value ≤ 1e-5）。
3.  **功能映射（URIM）**：通过 UniProt 检索/ID 映射服务获取基因本体（GO）注释、PFAM 结构域和人类蛋白交叉引用。
4.  **多层分析框架**：
    *   **功能层**：计算归一化的 GO 术语频率，识别各组间差异显著的生物过程。
    *   **结构域层**：进行 PFAM 结构域富集分析，寻找具有真核特征的微生物蛋白。
    *   **序列层**：直接识别与人类蛋白具有高同源性的微生物序列。
5.  **溯源验证**：采用单 ORF 分辨率的发现方法，将模拟信号精确回溯到特定的细菌物种。

### 3. 实验设计与对比方案
*   **数据集**：使用人类微生物组计划 2（HMP2/IBDMDB）的 39 个基线鸟枪法宏基因组样本。
    *   **分组**：12 名非 IBD（健康对照）、17 名 CD 患者、10 名 UC 患者。
*   **Benchmark（基准）**：以健康对照组的微生物功能谱和人类参考蛋白质组（SwissProt）为基准。
*   **对比方法**：
    *   **组间对比**：CD vs. Healthy、UC vs. Healthy、CD vs. UC。
    *   **分类学关联**：使用 MetaPhlAn3 丰度谱验证功能变化是否与特定致病菌（Pathobionts）的扩张一致。

### 4. 资源与算力
*   **软件环境**：Python 3.13、BioPython 1.81、DIAMOND 2.1.9/2.1.11、pandas、NumPy。
*   **算力说明**：文中提到在进行 DIAMOND 比对时使用了 4 个 CPU 线程（`--threads 4`）。
*   **缺失信息**：论文未明确提及具体的 GPU 型号或总计算时长，但考虑到处理的是约 179 万条蛋白质序列，该分析主要依赖高性能 CPU 集群而非大规模 GPU 训练。

### 5. 实验数量与充分性
*   **实验规模**：分析了近 180 万条预测蛋白序列，涵盖了 GO 术语频率分析、PFAM 富集、g:Profiler 统计富集以及单分子级别的序列溯源。
*   **充分性评价**：
    *   **多维度验证**：实验不仅做了宏观的功能富集，还深入到了单条序列的物种溯源，逻辑链条完整。
    *   **统计严谨性**：采用了三层过滤机制（排除通用代谢术语、限制人类基因集大小等）来降低假阳性。
    *   **局限性**：样本量（n=39）相对较小，虽然作为计算生物学探索已足够深入，但结论的普适性仍需在更大规模的队列中验证。

### 6. 主要结论与发现
*   **CD 的功能偏离更显著**：CD 微生物组在免疫相关过程的富集程度和序列模拟率上均显著高于 UC。
*   **SRNM 轴的破坏**：健康肠道微生物维持着对宿主**神经元、信号识别颗粒（SRP）和抗菌肽（AMP）**机制的协调模拟（称为 SRNM 轴），而在 IBD 中这一稳态被彻底破坏。
*   **NOD2 模拟联系**：首次发现 CD 富集细菌（如大肠杆菌、嗜血杆菌）携带模拟 **NOD2** 信号通路的蛋白。由于 NOD2 是 CD 最主要的遗传风险位点，这暗示了微生物通过模拟该通路来逃避监测或干扰宿主免疫。
*   **致病菌谱差异**：CD 富集口腔来源细菌（如副流感嗜血杆菌），而 UC 富集具核梭杆菌和普雷沃氏菌。

### 7. 优点与亮点
*   **视角独特**：首次在宏基因组尺度上系统性地研究 IBD 中的分子模拟，而非仅关注物种丰度。
*   **机制关联**：成功将微生物功能模拟与宿主遗传易感性（如 NOD2 突变）联系起来，提出了“遗传缺陷-微生物模拟”的恶性循环模型。
*   **高分辨率**：通过单 ORF 溯源技术，消除了宿主 DNA 污染的干扰，确保了模拟序列确实来源于细菌。

### 8. 不足与局限
*   **缺乏湿实验验证**：所有结论均基于计算机模拟（In silico），尚未通过体外细胞实验或动物模型证明这些模拟蛋白确实能诱发交叉反应性免疫。
*   **序列相似度限制**：识别出的序列相似度平均在 35%-45% 之间，处于同源性识别的“灰色地带”（Twilight Zone），其结构相似性需进一步通过 AlphaFold 等工具验证。
*   **横断面研究**：基于基线样本，无法确定分子模拟是炎症的“因”还是“果”。

（完）
