---
title: "Molecular Mimicry in Inflammatory Bowel Disease: Multi-layered Functional and Sequence-level Analysis of Gut Microbial Proteins Mimicking the Human Proteome"
title_zh: 炎症性肠病中的分子模拟：模拟人类蛋白质组的肠道微生物蛋白质的多层功能和序列水平分析
authors: "Anand, A. A., Mishra, P., Srivathsa, V. S., Yadav, V., Samanta, S. K."
date: 2026-07-21
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.20.713231v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 炎症性肠病中肠道微生物蛋白的分析
tldr: 本研究利用HMP2宏基因组数据，通过MMIP流程系统分析了肠道微生物与人类蛋白间的分子模拟。发现克罗恩病比溃疡性结肠炎具有更强的免疫相关模拟特征，且两者致病菌谱不同。研究揭示了健康肠道原有的模拟机制在IBD中被破坏，为微生物失调驱动免疫失调提供了新见解。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-001.webp\", \"caption\": \"Figure 3B — Distribution of % identity of DIAMOND hits across groups.\", \"page\": 11, \"index\": 1, \"width\": 956, \"height\": 841}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-002.webp\", \"caption\": \"Figure 1. Molecular Mimicry In Silico Pipeline (MMIP) workflow for IBD metagenomics\", \"page\": 7, \"index\": 2, \"width\": 827, \"height\": 922}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-003.webp\", \"caption\": \"Figure 9. Bacterial mimicry of the NOD2 signalling pathway in Crohn's disease: domain architecture, normal signalling, and potential points of interference.\", \"page\": 46, \"index\": 3, \"width\": 814, \"height\": 1220}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-004.webp\", \"caption\": \"Table 5. Differentially enriched GO terms identified by g:Profiler analysis of Ensembl gene IDs derived from GO ID conversion (p < 0.05).\", \"page\": 23, \"index\": 4, \"width\": 976, \"height\": 438}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-005.webp\", \"caption\": \"Figure 7C — Grouped horizontal bar chart of top 20 human protein targets.\", \"page\": 28, \"index\": 5, \"width\": 849, \"height\": 358}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-006.webp\", \"caption\": \"Table 1. Predicted ORF counts per sample across diagnostic groups, before and after removal of underrepresented samples\", \"page\": 8, \"index\": 6, \"width\": 1079, \"height\": 400}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-007.webp\", \"caption\": \"Figure 2 — ORF counts per diagnostic group with individual sample values overlaid.\", \"page\": 9, \"index\": 7, \"width\": 752, \"height\": 533}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-008.webp\", \"caption\": \"Figure 10. The NOD2 vicious cycle: molecular mimicry as a mechanistic bridge between genetic susceptibility and microbial dysbiosis in Crohn's disease.\", \"page\": 48, \"index\": 8, \"width\": 937, \"height\": 1191}]"
motivation: 探究肠道微生物与宿主蛋白间的分子模拟是否是诱发炎症性肠病自身免疫反应的潜在机制。
method: 基于HMP2宏基因组数据，结合同源搜索、功能富集和序列比对构建了多层分子模拟分析流程。
result: 克罗恩病表现出更高的免疫模拟率，且IBD患者普遍缺失健康肠道中原有的神经元和抗菌肽相关模拟特征。
conclusion: 研究首次在宏基因组层面刻画了IBD的分子模拟图谱，揭示了微生物失调贡献于免疫失调的新路径。
---

## 摘要
炎症性肠病（IBD）包括克罗恩病（CD）和溃疡性结肠炎（UC），是一种发病机制涉及复杂宿主-微生物群相互作用的慢性炎症性疾病。分子模拟（微生物与宿主蛋白质之间的结构或功能相似性）是肠道微生物群可能触发或维持自身免疫反应的一种合理机制。本研究对来自人类微生物组计划2（HMP2/IBDMDB）的39份基线鸟枪法宏基因组样本进行了全面的多层分子模拟计算机模拟流水线（MMIP）分析。通过针对SwissProt数据库的基于DIAMOND的同源性搜索，随后进行UniProt检索/ID映射（URIM），我们通过三个互补框架表征了微生物蛋白质的功能空间：(i) 不同诊断组间归一化的GO术语频率比较，(ii) 蛋白质家族（PFAM）结构域富集分析，以及 (iii) 识别与人类蛋白质具有直接同源性的微生物蛋白质的序列水平模拟分析。使用MetaPhlAn3预计算丰度谱进行的分类学分析提供了进一步的生物学背景。结果显示，与UC相比，CD微生物组表现出更显著的免疫相关生物学过程富集和更高的单样本序列水平模拟率。CD和UC还显示出截然不同的致病共生菌谱，CD富集了包括副流感嗜血杆菌在内的口腔来源分类群，而UC则富集了具核梭杆菌和普雷沃氏菌属。值得注意的是，健康的肠道微生物组维持着对宿主神经元、信号识别颗粒（SRP）相关和抗菌肽机制的协调模拟，而这一谱系在IBD中被破坏，并被疾病亚型特异性特征所取代，同时还发现了CD富集细菌与NOD2之间潜在的模拟联系。这些结果代表了首次利用鸟枪法宏基因组数据对IBD亚型分子模拟进行的宏基因组范围表征，为微生物失调如何导致IBD免疫失调提供了新的机制见解。

## Abstract
Inflammatory bowel disease (IBD), encompassing Crohn's disease (CD) and ulcerative colitis (UC), is a chronic inflammatory disorder whose pathogenesis involves intricate host-microbiome interactions. Molecular mimicry (the structural or functional resemblance between microbial and host proteins) represents a plausible mechanism by which gut microbiota may trigger or perpetuate autoimmune responses. Here we present a comprehensive, multi-layered molecular mimicry in silico pipeline (MMIP) analysis of 39 baseline shotgun metagenomic samples from Human Microbiome Project 2 (HMP2/IBDMDB). Using DIAMOND-based homology search against the SwissProt followed by UniProt Retrieve/ID Mapping (URIM), we characterized microbial protein functional space through three complementary frameworks: (i) normalized GO term frequency comparison across diagnostic groups, (ii) protein family (PFAM) domain enrichment analysis, and (iii) sequence-level mimicry analysis identifying microbial proteins with direct homology to human proteins. Taxonomic profiling using MetaPhlAn3 pre-computed abundance profiles provided further biological context. CD microbiomes exhibited greater enrichment of immune-relevant biological processes and a higher per-sample sequence-level mimicry rate than UC. CD and UC also showed distinct pathobiont profiles, with CD enriched for oral-origin taxa including Haemophilus parainfluenzae and UC enriched for Fusobacterium nucleatum and Prevotella species. Notably, healthy gut microbiome maintains coordinated mimicry of host neuronal, signal-recognition-particle-associated, and antimicrobial peptide machinery, a repertoire dismantled in IBD and replaced by disease-subtype-specific signatures, alongside a candidate mimicry link between CD-enriched bacteria and NOD2. These results represent the first metagenome-wide characterization of molecular mimicry across IBD subtypes using shotgun metagenomic data, offering new mechanistic insight into how microbial dysbiosis may contribute to immune dysregulation in IBD. Keywords: Inflammatory bowel disease (IBD), Crohn's disease (CD), Ulcerative colitis (UC), Gastroenteritis, Molecular mimicry

---

## 论文详细总结（自动生成）

这是一份关于论文《Molecular Mimicry in Inflammatory Bowel Disease: Multi-layered Functional and Sequence-level Analysis of Gut Microbial Proteins Mimicking the Human Proteome》的结构化总结：

### 1. 核心问题与整体含义
*   **研究动机**：炎症性肠病（IBD）的发病机制涉及复杂的宿主-微生物相互作用，但微生物失调如何具体诱发免疫失调仍不完全清楚。
*   **核心问题**：论文探讨了“分子模拟”（Molecular Mimicry）——即微生物蛋白在序列或功能上与宿主蛋白相似——是否是触发或维持IBD自身免疫反应的关键机制。
*   **整体含义**：研究旨在通过宏基因组学手段，系统性地刻画CD（克罗恩病）和UC（溃疡性结肠炎）中微生物对人类蛋白质组的模拟图谱，寻找疾病特异性的生物标志物和致病机制。

### 2. 方法论
论文构建了一个名为 **MMIP（分子模拟计算机模拟流水线）** 的多层分析框架：
*   **数据预处理**：从HMP2数据库提取39份基线鸟枪法宏基因组样本，将核苷酸序列翻译为蛋白质序列。
*   **同源性搜索**：利用 **DIAMOND** 算法将微生物蛋白序列与 **SwissProt** 数据库（经过人工审核的高质量蛋白库）进行比对。
*   **多层功能表征**：
    *   **GO频率分析**：通过UniProt ID映射获取基因本体（GO）注释，计算并归一化各诊断组间的GO术语频率差异。
    *   **PFAM结构域分析**：识别富集的蛋白质家族结构域，评估其是否具有真核生物特征。
    *   **序列水平模拟**：专门提取与人类蛋白（*Homo sapiens*）具有直接同源性的微生物序列。
*   **分类学关联**：使用 MetaPhlAn3 进行物种丰度分析，将功能模拟信号回溯至具体的微生物分类群。
*   **高分辨率溯源**：采用“自下而上”的验证流程，排除宿主DNA污染，确保模拟序列确实源自细菌。

### 3. 实验设计
*   **数据集**：来自人类微生物组计划2（HMP2/IBDMDB）的39份基线样本，包括12名健康对照（non-IBD）、17名CD患者和10名UC患者。
*   **对比场景**：CD vs. 健康对照、UC vs. 健康对照、CD vs. UC。
*   **基准与对比**：以健康人的肠道宏基因组功能谱为基准，对比不同疾病亚型在功能模拟（GO/PFAM）和序列模拟上的定量与定性差异。

### 4. 资源与算力
*   **软件环境**：使用了 Python 3.13 (Pandas, NumPy, BioPython)、DIAMOND (v2.1.9/2.1.11)、g:Profiler 等工具。
*   **算力细节**：文中提到在进行序列比对时使用了分布式计算，将序列划分为每组20万条的小块，并配置了多线程（`--threads 4`）。
*   **明确说明**：论文**未明确提及**具体的 GPU 型号、服务器硬件配置或总训练/计算时长。

### 5. 实验数量与充分性
*   **实验规模**：分析了超过178万条预测蛋白序列，识别出约4.5万条经过验证的细菌来源模拟序列。
*   **充分性**：实验涵盖了功能（GO）、结构（PFAM）、序列（Sequence）和分类学（Taxonomy）四个维度，并进行了单分子分辨率的溯源验证。
*   **客观性**：通过对样本蛋白总数（ORF counts）进行归一化处理，消除了测序深度不一带来的偏差；剔除了低质量离群样本，确保了统计的公平性。

### 6. 主要结论与发现
*   **CD的显著性**：CD微生物组的功能偏离程度远高于UC，具有更高的免疫相关过程富集率和序列模拟率。
*   **SRNM轴的破坏**：健康肠道微生物组维持着一套协调的“信号识别与神经元模拟（SRNM）轴”，涉及神经元发育、SRP蛋白靶向和抗菌肽（AMP）机制。这套系统在IBD中被瓦解。
*   **疾病特异性替代**：
    *   **CD** 转向模拟应激、凋亡、线粒体干扰和 **NOD2** 信号通路（NOD2是CD的主要遗传风险位点）。
    *   **UC** 转向模拟免疫放大信号，如细胞因子通路、T细胞受体和组胺产生。
*   **分类学特征**：CD富集口腔来源细菌（如副流感嗜血杆菌），UC富集具核梭杆菌。

### 7. 优点
*   **多维度视角**：不局限于简单的序列比对，而是从功能、结构域和系统发育多个层面定义“模拟”。
*   **机制性见解**：首次提出了微生物模拟 NOD2 通路这一“恶性循环”模型，为解释遗传易感性与微生物失调的关联提供了新假说。
*   **高分辨率验证**：通过严格的跨界过滤流程，有效区分了真正的微生物模拟蛋白与潜在的人类DNA污染。

### 8. 不足与局限
*   **计算推导局限**：所有结论均基于计算机模拟（in silico），尚未在体外（in vitro）或体内（in vivo）实验中验证这些模拟蛋白是否真的能干扰人类免疫信号。
*   **样本量限制**：39份样本虽然来自高质量队列，但对于复杂的IBD亚型研究来说，样本量仍相对较小。
*   **静态分析**：仅使用了基线数据，未能捕捉分子模拟信号随疾病活动度或治疗过程的动态变化。
*   **同源性阈值**：序列比对的平均一致性在35%-45%之间，处于同源性判定的“灰色地带”，其免疫原性需进一步验证。

（完）
