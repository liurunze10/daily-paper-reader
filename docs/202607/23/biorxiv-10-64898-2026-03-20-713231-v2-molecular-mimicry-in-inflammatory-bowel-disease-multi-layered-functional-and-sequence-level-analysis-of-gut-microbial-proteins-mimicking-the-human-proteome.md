---
title: "Molecular Mimicry in Inflammatory Bowel Disease: Multi-layered Functional and Sequence-level Analysis of Gut Microbial Proteins Mimicking the Human Proteome"
title_zh: 炎症性肠病中的分子模拟：模拟人类蛋白质组的肠道微生物蛋白质的多层功能和序列水平分析
authors: "Anand, A. A., Mishra, P., Srivathsa, V. S., Yadav, V., Samanta, S. K."
date: 2026-07-21
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.20.713231v2.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 炎症性肠病（IBD）发病机制中的分子模拟分析
tldr: 本研究通过多层分子模拟分析流程（MMIP），对炎症性肠病（IBD）患者的肠道宏基因组进行了系统分析。研究揭示了克罗恩病（CD）和溃疡性结肠炎（UC）在微生物蛋白与人类蛋白相似性上的显著差异，发现健康肠道的分子模拟模式在IBD中被破坏，并识别出与免疫失调相关的特定微生物模拟特征，为理解微生物失调如何诱发自身免疫反应提供了新视角。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-001.webp\", \"caption\": \"Figure 3B — Distribution of % identity of DIAMOND hits across groups.\", \"page\": 11, \"index\": 1, \"width\": 956, \"height\": 841}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-002.webp\", \"caption\": \"Figure 1. Molecular Mimicry In Silico Pipeline (MMIP) workflow for IBD metagenomics\", \"page\": 7, \"index\": 2, \"width\": 827, \"height\": 922}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-003.webp\", \"caption\": \"Figure 9. Bacterial mimicry of the NOD2 signalling pathway in Crohn's disease: domain architecture, normal signalling, and potential points of interference.\", \"page\": 46, \"index\": 3, \"width\": 814, \"height\": 1220}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-004.webp\", \"caption\": \"Table 5. Differentially enriched GO terms identified by g:Profiler analysis of Ensembl gene IDs derived from GO ID conversion (p < 0.05).\", \"page\": 23, \"index\": 4, \"width\": 976, \"height\": 438}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-005.webp\", \"caption\": \"Figure 7C — Grouped horizontal bar chart of top 20 human protein targets.\", \"page\": 28, \"index\": 5, \"width\": 849, \"height\": 358}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-006.webp\", \"caption\": \"Table 1. Predicted ORF counts per sample across diagnostic groups, before and after removal of underrepresented samples\", \"page\": 8, \"index\": 6, \"width\": 1079, \"height\": 400}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-007.webp\", \"caption\": \"Figure 2 — ORF counts per diagnostic group with individual sample values overlaid.\", \"page\": 9, \"index\": 7, \"width\": 752, \"height\": 533}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-03-20-713231-v2/fig-008.webp\", \"caption\": \"Figure 10. The NOD2 vicious cycle: molecular mimicry as a mechanistic bridge between genetic susceptibility and microbial dysbiosis in Crohn's disease.\", \"page\": 48, \"index\": 8, \"width\": 937, \"height\": 1191}]"
motivation: 旨在探究肠道微生物蛋白与人类蛋白之间的分子模拟如何通过宿主-微生物相互作用触发或加剧炎症性肠病。
method: 开发了多层分子模拟分析流程（MMIP），利用DIAMOND同源搜索、GO功能分析及PFAM结构域富集等方法对HMP2宏基因组数据进行深度挖掘。
result: 发现克罗恩病具有更高的序列级模拟率，且健康肠道原有的神经元及抗菌肽模拟机制在IBD患者中被疾病特异性特征所取代。
conclusion: 研究首次在宏基因组层面刻画了IBD亚型的分子模拟图谱，为微生物失调导致免疫失调提供了新的机械论见解。
---

## 摘要
炎症性肠病（IBD）包括克罗恩病（CD）和溃疡性结肠炎（UC），是一种发病机制涉及复杂宿主-微生物群相互作用的慢性炎症性疾病。分子模拟（微生物与宿主蛋白质之间的结构或功能相似性）是肠道微生物群可能触发或维持自身免疫反应的一种合理机制。在此，我们对来自人类微生物组计划2（HMP2/IBDMDB）的39份基线鸟枪法宏基因组样本进行了全面的多层分子模拟计算机模拟管线（MMIP）分析。通过针对SwissProt的基于DIAMOND的同源性搜索，随后进行UniProt检索/ID映射（URIM），我们通过三个互补框架表征了微生物蛋白质的功能空间：(i) 不同诊断组间归一化的GO术语频率比较，(ii) 蛋白质家族（PFAM）结构域富集分析，以及 (iii) 识别与人类蛋白质具有直接同源性的微生物蛋白质的序列水平模拟分析。使用MetaPhlAn3预计算丰度谱进行的分类学分析提供了进一步的生物学背景。CD微生物组表现出比UC更高程度的免疫相关生物过程富集和更高的单样本序列水平模拟率。CD和UC还显示出截然不同的致病共生菌谱，CD富集了包括副流感嗜血杆菌在内的口腔来源分类群，而UC则富集了具核梭杆菌和普雷沃氏菌属。值得注意的是，健康的肠道微生物组维持着对宿主神经元、信号识别颗粒相关和抗菌肽机制的协调模拟，而这一套模拟库在IBD中被拆解，并被疾病亚型特异性的特征所取代，同时还发现了CD富集细菌与NOD2之间潜在的模拟联系。这些结果代表了首次利用鸟枪法宏基因组数据对IBD亚型分子模拟进行的宏基因组范围表征，为微生物失调如何导致IBD免疫失调提供了新的机制见解。

## Abstract
Inflammatory bowel disease (IBD), encompassing Crohn's disease (CD) and ulcerative colitis (UC), is a chronic inflammatory disorder whose pathogenesis involves intricate host-microbiome interactions. Molecular mimicry (the structural or functional resemblance between microbial and host proteins) represents a plausible mechanism by which gut microbiota may trigger or perpetuate autoimmune responses. Here we present a comprehensive, multi-layered molecular mimicry in silico pipeline (MMIP) analysis of 39 baseline shotgun metagenomic samples from Human Microbiome Project 2 (HMP2/IBDMDB). Using DIAMOND-based homology search against the SwissProt followed by UniProt Retrieve/ID Mapping (URIM), we characterized microbial protein functional space through three complementary frameworks: (i) normalized GO term frequency comparison across diagnostic groups, (ii) protein family (PFAM) domain enrichment analysis, and (iii) sequence-level mimicry analysis identifying microbial proteins with direct homology to human proteins. Taxonomic profiling using MetaPhlAn3 pre-computed abundance profiles provided further biological context. CD microbiomes exhibited greater enrichment of immune-relevant biological processes and a higher per-sample sequence-level mimicry rate than UC. CD and UC also showed distinct pathobiont profiles, with CD enriched for oral-origin taxa including Haemophilus parainfluenzae and UC enriched for Fusobacterium nucleatum and Prevotella species. Notably, healthy gut microbiome maintains coordinated mimicry of host neuronal, signal-recognition-particle-associated, and antimicrobial peptide machinery, a repertoire dismantled in IBD and replaced by disease-subtype-specific signatures, alongside a candidate mimicry link between CD-enriched bacteria and NOD2. These results represent the first metagenome-wide characterization of molecular mimicry across IBD subtypes using shotgun metagenomic data, offering new mechanistic insight into how microbial dysbiosis may contribute to immune dysregulation in IBD. Keywords: Inflammatory bowel disease (IBD), Crohn's disease (CD), Ulcerative colitis (UC), Gastroenteritis, Molecular mimicry

---

## 论文详细总结（自动生成）

这篇论文对炎症性肠病（IBD）中肠道微生物蛋白质与人类蛋白质之间的“分子模拟”现象进行了深入的计算生物学分析。以下是详细总结：

### 1. 核心问题与整体含义
*   **研究动机**：IBD（包括克罗恩病 CD 和溃疡性结肠炎 UC）的发病机制涉及宿主与微生物群之间的复杂相互作用。尽管已知微生物失调是关键因素，但其诱发免疫失调的具体分子机制尚不完全清楚。
*   **核心问题**：微生物蛋白质是否通过结构或功能上模仿人类蛋白质（分子模拟），从而触发或维持宿主的自身免疫反应？
*   **背景**：分子模拟包括序列水平（氨基酸相似性）和功能水平（共享生物路径或功能注释）的相似性。

### 2. 方法论：多层分子模拟分析流程 (MMIP)
研究者开发了一套名为 **MMIP** 的计算管线，核心步骤包括：
*   **同源性搜索**：使用 **DIAMOND** 算法将宏基因组预测的蛋白质序列（ORF）与 UniProt SwissProt 手性注释数据库进行比对。
*   **功能映射 (URIM)**：通过 UniProt 检索/ID 映射获取功能元数据，包括基因本体（GO）注释和 PFAM 结构域。
*   **三层分析框架**：
    1.  **归一化 GO 频率分析**：比较不同诊断组间 GO 术语的出现频率（每 10 万个 ORF 的频率）。
    2.  **PFAM 结构域富集**：识别在疾病组中显著增加的蛋白质家族结构域。
    3.  **序列级模拟检测**：专门提取与人类蛋白质（Homo sapiens）具有直接同源性的微生物蛋白。
*   **底层验证 (Bottom-Up)**：通过单分子分辨率的追踪，将模拟信号回溯到具体的细菌物种，并排除真核生物序列污染。

### 3. 实验设计
*   **数据集**：来自人类微生物组计划 2 (HMP2/IBDMDB) 的 **39 份基线鸟枪法宏基因组样本**（12 份健康对照 non-IBD，17 份 CD，10 份 UC）。
*   **对比基准**：以健康人群（non-IBD）为基准，对比 CD 和 UC 的差异，以及 CD 与 UC 之间的直接对比。
*   **分类学分析**：使用 MetaPhlAn3 预计算的丰度谱来关联功能变化与物种组成。

### 4. 资源与算力
*   **软件环境**：Python 3.13, pandas, NumPy, BioPython, DIAMOND (v2.1.9/2.1.11)。
*   **算力说明**：文中提到在进行 DIAMOND 比对时使用了 **4 个 CPU 线程**（--threads 4）。
*   **未明确说明**：未提及具体的 GPU 型号或总训练/计算时长，考虑到是宏基因组比对而非深度学习模型训练，算力需求主要集中在 CPU 和内存上。

### 5. 实验数量与充分性
*   **实验规模**：分析了超过 178 万个预测蛋白质序列。针对 GO 术语应用了“三过滤器”方法（生物过程、排除通用术语、人类术语规模 < 500 基因）以确保结果的特异性。
*   **充分性**：研究结合了功能富集、结构域分析、序列比对和分类学追踪，多维度验证了结论。
*   **客观性**：通过归一化处理解决了不同样本间测序深度和 ORF 数量差异的问题，剔除了低质量离群样本，实验设计较为严谨。

### 6. 主要结论与发现
*   **CD 的功能偏离更显著**：CD 微生物组在免疫相关生物过程的富集程度和序列级模拟率上均显著高于 UC。
*   **健康模拟库的丧失**：健康肠道微生物会模拟宿主的**神经元、信号识别颗粒（SRP）和抗菌肽（AMP）**机制，这被称为 **SRNM 轴**。在 IBD 患者中，这一维持稳态的模拟库被破坏。
*   **疾病特异性补偿**：
    *   **CD**：转向模拟应激、凋亡和线粒体干扰路径。
    *   **UC**：转向模拟细胞因子信号传导和 T 细胞受体路径。
*   **NOD2 模拟联系**：首次发现 CD 富集细菌（如副流感嗜血杆菌）携带模拟 **NOD2 信号通路**的蛋白质。由于 NOD2 是 CD 的主要遗传风险位点，这种模拟可能形成了“遗传易感性-微生物利用”的恶性循环。

### 7. 优点与亮点
*   **多层级视角**：不仅看序列相似性，还从功能和结构域角度全面刻画分子模拟图谱。
*   **机制创新**：提出了 **SRNM 轴** 概念，将微生物功能与肠道神经系统和免疫防御联系起来。
*   **临床关联**：成功将计算发现与已知的 IBD 遗传风险因子（如 NOD2）和临床表现（如 CD 的骨重塑异常、厌食症）联系起来。

### 8. 不足与局限
*   **纯计算研究**：所有结论均基于生物信息学预测，缺乏体外（in vitro）或体内（in vivo）的功能验证（如 T 细胞交叉反应实验）。
*   **样本量限制**：39 份样本虽然深度足够，但对于异质性极强的 IBD 临床研究来说规模较小。
*   **“灰区”同源性**：序列比对的平均一致性在 34-35% 左右，处于同源性检测的“黄昏区”，结构是否真正相似仍需 AlphaFold2 等结构预测工具进一步验证。
*   **横断面设计**：基于基线样本，无法确定分子模拟的变化是疾病的原因还是结果。

（完）
