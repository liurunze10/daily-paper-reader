---
title: A ML-framework for the discovery of next-generation IBD targets using a harmonized single-cell atlas of patient tissue
title_zh: 一种利用患者组织统一单细胞图谱发现下一代 IBD 靶点的机器学习框架
authors: "Joglekar, A., Joseph, A., Honsa, P., Ruppova, K., Pizzarella, V., Honan, A., Mediratta, D., Vollmer, E., Geller, E., Valny, M., Macuchova, E., Zheng, S., Greenberg, A., Taus, P., Kline-Schoder, A., Konickova, R., Cerna, L., Sharim, H., Ness, L., Camilli, G., Chouri, E., Kaymak, I., D'Rozario, J., Castiblanco, D., Oliveira, J., Prandi, F., Popov, N., Moldoveanu, A. L., Oliphant, C., Escudero-Ibarz, L., Uhlitz, F., Freinkman, E., Sponarova, J., Vijay, P., Joyce, C., Leonardi, I., Nayar, S., Raveh-Sadka, T., Solomon, N., Platt, A., Ort, T., De Baets, G., Corridoni, D., Wroblewska, A., Rahman, A."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.06.699999v3.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 发现人类肠道IBD靶点的机器学习框架
tldr: 本研究针对炎症性肠病（IBD）传统靶点发现缺乏细胞分辨率的问题，利用包含100万个单细胞的肠道图谱，开发了名为IPR的机器学习框架。该框架能系统识别疾病相关的转录程序和细胞类型特异性靶点。通过AI辅助推理和实验验证，成功发现了PTGIR和IL6ST等新靶点，为IBD及其他免疫疾病提供了可扩展的精准治疗发现方案。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统的IBD靶点发现主要依赖遗传关联，缺乏识别新型、可操作且具有细胞类型特异性疾病通路所需的细胞分辨率。
method: 利用整合了100万个单细胞的肠道图谱，结合机器学习框架IPR识别疾病相关转录程序，并通过AI辅助推理和原代细胞模型进行验证。
result: 识别出85个疾病相关转录程序并对400个候选靶点进行排序，实验证实PTGIR和IL6ST能有效减轻髓系细胞和成纤维细胞的炎症及纤维化。
conclusion: 该单细胞机器学习框架整合了计算发现与实验验证，为IBD及其他免疫介导疾病提供了精准发现细胞特异性治疗靶点的新途径。
---

## 摘要
炎症性肠病（IBD）的靶点发现传统上依赖于遗传关联，但遗传关联缺乏识别新型、具有转化价值且具备细胞类型特异性的疾病通路所需的细胞分辨率。在此，我们描述了一个整合的分析与实验框架，该框架利用统一的单细胞数据系统地发现 IBD 的新型治疗策略。我们利用 Immunai 的统一单细胞 RNA 数据集数据库 AMICA DB™，构建了一个包含 100 万个细胞的人类肠道统一单细胞图谱。我们应用了一种机器学习框架（免疫患者表征，IPR）来识别疾病相关的转录程序和细胞类型特异性的基因靶点。候选靶点根据图谱衍生的指标进行优先级排序，并利用强调转化可行性的自定义标准进行精炼，随后在独立临床队列中进行了验证。选定的候选靶点在反映靶点细胞类型背景的人类原代细胞模型中进行了评估。IPR 框架识别了 85 个疾病相关的转录程序，并对免疫和基质谱系中的 400 个细胞类型特异性靶基因进行了排序。疾病相关程序通过结构化的 AI 辅助推理框架进行解释，以进行结构化生物学推理，将其与 IBD 相关通路联系起来，并指导新型、有前景的基因靶点的识别。对两个细胞类型特异性候选靶点（髓系细胞中的 PTGIR 和成纤维细胞中的 IL6ST）的功能验证证实，它们能减少与 IBD 病理相关的炎症和纤维化通路。多组学分析以及体外表型向患者数据集的投影表明，通过不同于现有生物制剂的机制，可以逆转疾病相关程序。我们的这种以单细胞为核心的机器学习框架将计算机模拟发现与实验验证相结合，揭示了新的细胞类型特异性治疗机会，并为 IBD 及其他免疫介导疾病的精准靶点发现提供了一种可扩展的方法。

## Abstract
Target discovery for IBD has traditionally relied on genetic associations, which lack the cellular resolution needed to identify novel, actionable, cell type-specific disease pathways. Here, we describe an integrated analytical and experimental framework that leverages harmonized single-cell data to systematically discover novel therapeutic strategies for IBD. We used AMICA DBTM, Immunai's harmonized database of single-cell RNA datasets to construct a harmonized 1 million single-cell atlas of the human intestine. We applied a machine learning framework (Immune Patient Representation, IPR) to identify disease-associated transcriptional programs and cell type-specific gene targets. Candidate targets were prioritized using atlas-derived metrics, refined using custom criteria emphasizing translational actionability, and validated across independent clinical cohorts. Select candidates were evaluated in human primary-cell models reflecting the target's cell-type context. The IPR framework identified 85 disease-associated transcriptional programs and ranked 400 cell type-specific target genes across immune and stromal lineages. Disease-associated programs were interpreted using a structured AI-assisted reasoning framework for structured biological reasoning, linking them to IBD-relevant pathways and guiding the identification of novel, promising gene targets. Functional validation of two cell-type-specific candidates, PTGIR in myeloid cells and IL6ST in fibroblasts, confirmed the reduction of inflammatory and fibrotic pathways linked to IBD pathology. Multi-omic profiling and projection of in vitro phenotypes to patient datasets demonstrated the reversal of disease-associated programs via mechanisms distinct from those of existing biologics. Our single-cell anchored, machine-learning framework integrates in silico discovery with experimental validation, revealing new cell type-specific therapeutic opportunities and supporting a scalable approach for precision target discovery in IBD and other immune-mediated diseases.