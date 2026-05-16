---
title: A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue
title_zh: 一种利用患者组织统一单细胞图谱发现下一代 IBD 靶点的机器学习框架
authors: "Joglekar, A., Joseph, A., Honsa, P., Ruppova, K., Pizzarella, V., Honan, A., Mediratta, D., Vollmer, E., Geller, E., Valny, M., Macuchova, E., Zheng, S., Greenberg, A., Taus, P., Kline-Schoder, A., Konickova, R., Cerna, L., Sharim, H., Ness, L., Camilli, G., Chouri, E., Kaymak, I., D'Rozario, J., Castiblanco, D., Oliveira, J., Prandi, F., Popov, N., Moldoveanu, A. L., Oliphant, C., Escudero-Ibarz, L., Uhlitz, F., Freinkman, E., Sponarova, J., Vijay, P., Joyce, C., Leonardi, I., Nayar, S., Raveh-Sadka, T., Solomon, N., Platt, A., Ort, T., De Baets, G., Corridoni, D., Wroblewska, A., Rahman, A."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.06.699999v3.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 利用人类肠道单细胞图谱发现IBD靶点的机器学习框架
tldr: 本研究开发了一个集成机器学习框架，利用包含100万个细胞的人类肠道单细胞图谱来系统性发现炎症性肠病（IBD）的新治疗靶点。通过IPR框架识别出85个疾病相关转录程序和400个细胞类型特异性靶点，并结合AI推理和实验验证，成功证实了PTGIR和IL6ST等靶点在缓解炎症和纤维化方面的潜力，为IBD精准医疗提供了可扩展的新路径。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统的IBD靶点发现依赖遗传关联，缺乏识别细胞类型特异性致病通路所需的细胞分辨率。
method: 利用AMICA数据库构建百万级单细胞肠道图谱，并应用IPR机器学习框架与AI辅助推理来识别和优先排序疾病相关转录程序及靶点。
result: 框架识别出85个疾病程序和400个候选靶点，实验验证证实靶向髓系细胞的PTGIR和成纤维细胞的IL6ST能有效逆转疾病相关的炎症与纤维化表型。
conclusion: 该单细胞机器学习框架整合了计算发现与实验验证，揭示了新的细胞特异性治疗机会，为IBD及其他免疫疾病的精准靶点发现提供了可扩展方案。
---

## 摘要
炎症性肠病（IBD）的靶点发现传统上依赖于遗传关联，这缺乏识别新型、可操作、细胞类型特异性疾病通路所需的细胞分辨率。在此，我们描述了一个整合的分析和实验框架，该框架利用统一的单细胞数据系统地发现 IBD 的新型治疗策略。我们使用 Immunai 的统一单细胞 RNA 数据集数据库 AMICA DB™，构建了一个包含 100 万个单细胞的人类肠道统一图谱。我们应用了一种机器学习框架（免疫患者表征，IPR）来识别疾病相关的转录程序和细胞类型特异性的基因靶点。候选靶点使用源自图谱的指标进行优先级排序，并根据强调转化可操作性的自定义标准进行精炼，并在独立临床队列中进行了验证。选定的候选靶点在反映靶点细胞类型背景的人类原代细胞模型中进行了评估。IPR 框架识别了 85 个疾病相关的转录程序，并对免疫和基质谱系中的 400 个细胞类型特异性靶基因进行了排序。利用结构化 AI 辅助推理框架对疾病相关程序进行结构化生物学推理，将其与 IBD 相关通路联系起来，并指导新型、有前景的基因靶点的识别。对两个细胞类型特异性候选靶点（骨髓细胞中的 PTGIR 和成纤维细胞中的 IL6ST）的功能验证证实，它们减少了与 IBD 病理相关的炎症和纤维化通路。多组学分析以及体外表型向患者数据集的投影表明，通过不同于现有生物制剂的机制，可以逆转疾病相关程序。我们的以单细胞为核心的机器学习框架整合了计算机模拟发现与实验验证，揭示了新的细胞类型特异性治疗机会，并为 IBD 和其他免疫介导疾病的精准靶点发现提供了一种可扩展的方法。

## Abstract
Target discovery for IBD has traditionally relied on genetic associations, which lack the cellular resolution needed to identify novel, actionable, cell type-specific disease pathways. Here, we describe an integrated analytical and experimental framework that leverages harmonized single-cell data to systematically discover novel therapeutic strategies for IBD.

We used AMICA DBTM, Immunais harmonized database of single-cell RNA datasets to construct a harmonized 1 million single-cell atlas of the human intestine. We applied a machine learning framework (Immune Patient Representation, IPR) to identify disease-associated transcriptional programs and cell type-specific gene targets. Candidate targets were prioritized using atlas-derived metrics, refined using custom criteria emphasizing translational actionability, and validated across independent clinical cohorts. Select candidates were evaluated in human primary-cell models reflecting the targets cell-type context.

The IPR framework identified 85 disease-associated transcriptional programs and ranked 400 cell type-specific target genes across immune and stromal lineages. Disease-associated programs were interpreted using a structured AI-assisted reasoning framework for structured biological reasoning, linking them to IBD-relevant pathways and guiding the identification of novel, promising gene targets. Functional validation of two cell-type-specific candidates, PTGIR in myeloid cells and IL6ST in fibroblasts, confirmed the reduction of inflammatory and fibrotic pathways linked to IBD pathology. Multi-omic profiling and projection of in vitro phenotypes to patient datasets demonstrated the reversal of disease-associated programs via mechanisms distinct from those of existing biologics.

Our single-cell anchored, machine-learning framework integrates in silico discovery with experimental validation, revealing new cell type-specific therapeutic opportunities and supporting a scalable approach for precision target discovery in IBD and other immune-mediated diseases.

---

## 论文详细总结（自动生成）

这篇论文介绍了一个名为 AMICA™ 的集成机器学习框架，旨在利用大规模统一的单细胞转录组数据发现炎症性肠病（IBD）的新型治疗靶点。

### 1. 核心问题与整体含义
*   **研究动机**：传统的 IBD 靶点发现主要依赖全基因组关联分析（GWAS），虽然识别了大量遗传位点，但缺乏细胞分辨率，导致现有疗法（如类固醇、TNF 抑制剂）多作用于多效性通路，产生全身性免疫抑制等副作用。
*   **核心问题**：如何利用单细胞 RNA 测序（scRNA-seq）的高分辨率特性，系统性地识别具有细胞类型特异性、高转化价值且能解决现有疗法不响应问题的下一代 IBD 治疗靶点。

### 2. 方法论
该框架包含从数据整合到实验验证的完整闭环：
*   **AMICA DB™ 数据统一化**：整合了 20 个公开的 scRNA-seq 研究，通过标准化的管线（Cell Ranger 处理、质量过滤、批次校正、细胞类型标注）构建了一个包含近 100 万个细胞的人类肠道图谱。
*   **免疫患者表征（IPR）框架**：
    1.  **构建 Pseudobulk**：按样本和细胞类型聚合基因表达。
    2.  **线性降维**：提取捕捉生物学变异的潜在分量。
    3.  **特征提取**：识别与疾病状态（如发炎 vs 非发炎）、治疗响应（如抗 TNF 响应者 vs 非响应者）显著相关的细胞类型特异性基因程序（IPR features）。
*   **AMICA-Reason™ 解释引擎**：利用大语言模型（LLM）驱动的代理推理框架，将统计学信号转化为生物学机制解释，辅助识别功能模块。
*   **多准则优先级排序**：结合 IPR 衍生指标（效应量、炎症关联度）与正交数据（遗传证据、药物可及性、安全性评分）对候选基因进行排名。

### 3. 实验设计
*   **数据集**：
    *   **构建集**：20 个公开研究，530 个肠道样本，994,206 个细胞。
    *   **验证集**：4 个独立研究，163 个样本，520,969 个细胞。
*   **Benchmark 与对比**：
    *   **靶点回收测试**：验证框架是否能识别出已上市或临床在研的 IBD 药物靶点（如 TNF, ITGA4, JAK3 等）。
    *   **机制对比**：将新靶点（如 PTGIR）的敲除效应与标准疗法（如 Infliximab/抗 TNF）进行体外对比。
*   **功能验证场景**：
    *   使用 **SystemMatch** 算法筛选最接近患者体内状态的体外原代细胞模型。
    *   在人类原代单核吞噬细胞（MNP）和肠道成纤维细胞中进行 CRISPR/Cas9 介导的基因敲除。

### 4. 资源与算力
*   论文中提到了使用 **10x Genomics Cell Ranger (v5.0.1)** 进行原始数据处理，并使用了 **Illumina NovaSeq** 系统进行体外验证实验的 Bulk RNA-seq 测序。
*   **未明确说明**：文中未详细列出训练机器学习模型所使用的具体 GPU 型号、数量或具体的计算时长。

### 5. 实验数量与充分性
*   **实验规模**：分析了超过 100 万个单细胞，识别出 85 个疾病相关程序和 400 个高优先级靶点。
*   **验证充分性**：
    *   对 19 个候选靶点进行了体外敲除筛选。
    *   重点对 **PTGIR**（巨噬细胞靶点）和 **IL6ST**（成纤维细胞靶点）进行了深入验证，涉及 6 个不同供体的原代细胞。
    *   使用了多组学手段（Bulk RNA-seq、流式细胞术、多因子分泌分析）进行表型刻画。
*   **客观性**：通过在多个独立临床队列中进行“临床投影”（Clinical Projection），证明了体外实验结果与患者组织中观察到的疾病特征具有高度一致性。

### 6. 主要结论与发现
*   **PTGIR（前列腺素 I2 受体）**：在发炎组织的脂质相关巨噬细胞（LAM）中高表达。敲除 PTGIR 可逆转促炎代谢状态，减少 VEGF-A 和 CCL7 分泌，其机制与抗 TNF 疗法互补。
*   **IL6ST（gp130）**：在成纤维细胞中具有促纤维化作用，敲除后可显著降低纤维化相关通路。
*   **细胞特异性的重要性**：研究发现 IL6ST 在巨噬细胞中敲除反而会诱发促炎反应，强调了精准靶向特定细胞类型而非全身性抑制的重要性。
*   **框架有效性**：该框架成功回收了约 50% 的已上市 IBD 药物靶点，并识别出如 IL7R 等处于临床后期的潜力靶点。

### 7. 优点
*   **数据规模与质量**：通过统一化处理解决了单细胞数据碎片化和批次效应问题，构建了目前最大的 IBD 肠道单细胞图谱之一。
*   **端到端集成**：实现了从计算发现、AI 生物学推理到实验验证的闭环，显著提升了靶点发现的转化成功率。
*   **AI 辅助推理**：引入 AMICA-Reason™ 解决了机器学习模型“黑盒”问题，使统计结果更具生物学可解释性。

### 8. 不足与局限
*   **体外模型局限性**：尽管经过计算优化，原代细胞单层培养模型仍无法完全模拟肠道复杂的空间结构、微生物群落及多细胞间的动态相互作用。
*   **数据偏差风险**：虽然整合了大量数据，但仍受限于公开数据集的质量和元数据完整性（如某些样本缺乏详细的治疗响应记录）。
*   **应用限制**：目前主要聚焦于转录组水平，对于蛋白质组学、代谢组学或翻译后修饰驱动的致病机制覆盖不足。

（完）
