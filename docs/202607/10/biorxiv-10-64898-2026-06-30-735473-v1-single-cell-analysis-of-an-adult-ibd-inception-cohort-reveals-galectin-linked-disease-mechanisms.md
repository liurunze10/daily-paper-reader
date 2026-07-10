---
title: Single-cell analysis of an adult IBD INCEPTION cohort reveals Galectin-linked disease mechanisms
title_zh: 成年炎症性肠病（IBD）INCEPTION 队列的单细胞分析揭示了半乳糖凝集素（Galectin）相关的疾病机制
authors: "Leipner, M., Rimmer, P., Tull, S., Paun, A., Sandrin, V., Begum, J., Mansour, A. A., Saviano, A., Sharma, N., Cheesbrough, J., Maione, F., Trenkle, P., Klein, A., Danilin, S., Iqbal, T. H., Iqbal, A. J., Regan-Komito, D."
date: 2026-07-03
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.30.735473v1.full.pdf"
tags: ["query:ros-mp"]
score: 7.0
evidence: 初治IBD的单细胞图谱及巨噬细胞刺激
tldr: 本研究通过对137名初治炎症性肠病（IBD）患者的100万个单细胞进行转录组测序，构建了高分辨率免疫图谱。研究发现炎症单核细胞的扩张是克罗恩病和溃疡性结肠炎的共同特征，并识别出Galectin-9是驱动黏膜炎症的关键信号分子。该研究不仅揭示了早期IBD的分子发病机制，还证明了血清Galectin-9可作为评估病情和治疗反应的生物标志物。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-06-30-735473-v1/fig-001.webp\", \"caption\": \"Table 3: Criteria utilised to determine treatment response\", \"page\": 21, \"index\": 1, \"width\": 946, \"height\": 1481}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-06-30-735473-v1/fig-002.webp\", \"caption\": \"Figure 5. Profiling of Galectin-positive vs. Galectin-negative Inflammatory Monocytes.\", \"page\": 18, \"index\": 2, \"width\": 911, \"height\": 211}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-06-30-735473-v1/fig-003.webp\", \"caption\": \"Figure 6. Gene expression changes in human macrophages following Galectin-9 treatment\", \"page\": 18, \"index\": 3, \"width\": 939, \"height\": 182}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-06-30-735473-v1/fig-004.webp\", \"caption\": \"Figure 7. Serum Galectin levels as a marker of disease activity in IBD\", \"page\": 18, \"index\": 4, \"width\": 940, \"height\": 735}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-06-30-735473-v1/fig-005.webp\", \"caption\": \"Table 1: Patient demographics and baseline disease indices for treatment naïve IBD patients and symptomatic controls contributing samples to the scRNA seq dataset.\", \"page\": 19, \"index\": 5, \"width\": 946, \"height\": 1418}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-06-30-735473-v1/fig-006.webp\", \"caption\": \"Figure 2. Distribution of cell types across disease and health status\", \"page\": 17, \"index\": 6, \"width\": 933, \"height\": 239}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-06-30-735473-v1/fig-007.webp\", \"caption\": \"Figure 3. Cell-Cell Communication (CCC) within Disease-Associated Cell Types.\", \"page\": 17, \"index\": 7, \"width\": 939, \"height\": 822}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-06-30-735473-v1/fig-008.webp\", \"caption\": \"Table 2: Demographics and baseline disease indices for the patients contributing serum samples.\", \"page\": 20, \"index\": 8, \"width\": 1050, \"height\": 1437}]"
motivation: 旨在通过分析初治IBD患者的高分辨率免疫图谱，识别疾病发作的核心驱动因素和早期致病信号。
method: 利用137名受试者的肠道活检组织生成了包含百万细胞的单细胞图谱，并结合共变邻域分析和细胞间通讯网络分解进行研究。
result: 发现炎症单核细胞显著扩张，并识别出以Galectin-9为核心的疾病特异性信号模块，其在体外能诱导巨噬细胞促炎表型。
conclusion: 半乳糖凝集素-单核细胞轴是早期IBD的统一炎症特征，Galectin-9可作为治疗靶点和疾病监测的动态生物标志物。
---

## 摘要
背景与目的：炎症性肠病（IBD）的分子发病机制尚不明确。本研究旨在建立初治 IBD 的高分辨率免疫图谱，以识别疾病发作的核心驱动因素和早期致病信号。方法：我们利用来自 137 名受试者（包括初治克罗恩病（CD）、溃疡性结肠炎（UC）和有症状的非 IBD 对照组）的大型成年初始队列的肠道活检样本，构建了单细胞图谱。我们将单细胞转录组测序（scRNA-seq，100 万个细胞）与共变邻域分析（CNA）以及细胞间通讯（CCC）网络的无偏张量分解相结合。研究结果通过体外巨噬细胞刺激模型和患者血清进行了验证。结果：与基准参考研究相比，该初始队列表现出显著更高的区室多样性同质性（p < 0.001）。CD 和 UC 的炎症特征均表现为炎性单核细胞的显著扩张。无偏 CCC 分析识别出一个以半乳糖凝集素家族（LGALS1 和 LGALS9）为核心的主导疾病特异性信号模块。Galectin-9 的表达在炎性单核细胞中特异性富集，这些细胞表现出与抗原呈递和微生物感知相关的独特转录程序。在体外实验中，Galectin-9 作为一种强效刺激物，驱动巨噬细胞向促炎表型转化。临床上，IBD 患者的血清 Galectin-9 水平显著升高，并与全身炎症标志物及治疗反应相关。结论：我们的数据确定了半乳糖凝集素-单核细胞信号轴是早期 IBD 的统一炎症特征。Galectin-9 既是粘膜炎症的功能驱动因素，也是一种动态生物标志物，为从诊断开始的治疗靶向和疾病监测提供了新机遇。

## Abstract
Background and AimsThe molecular pathogenesis of Inflammatory Bowel Disease (IBD) remains unclear. We aimed to establish a high-resolution immune landscape of treatment-naive IBD to identify central drivers of disease onset and early pathogenic signalling.

MethodsWe generated a single-cell atlas using intestinal biopsies from a large adult inception cohort of 137 individuals, including treatment-naive Crohns disease (CD), ulcerative colitis (UC), and symptomatic non-IBD controls. We integrated scRNA-seq (1 million cells) with co-varying neighbourhood analysis (CNA) and unbiased tensor decomposition of cell-cell communication (CCC) networks. Findings were validated in vitro macrophage stimulation model and using serum from patients.

ResultsThe inception cohort exhibited significantly more homogenous compartmental diversity compared to benchmark reference studies (p < 0.001). Inflammation in both CD and UC was characterized by a marked expansion of inflammatory monocytes. Unbiased CCC analysis identified a dominant disease-specific signalling module centred on the Galectin family (LGALS1 and LGALS9). Galectin-9 expression was specifically enriched in inflammatory monocytes, which exhibited distinct transcriptional programs linked to antigen presentation and microbial sensing. In vitro, Galectin-9 acted as a potent stimulus, driving macrophages toward a pro-inflammatory phenotype. Clinically, serum Galectin-9 levels were significantly elevated in IBD patients and correlated with systemic inflammatory markers and treatment response.

ConclusionsOur data identify a galectin-monocyte signalling axis as a unifying inflammatory hallmark of early IBD. Galectin-9 serves as both a functional driver of mucosal inflammation and a dynamic biomarker, offering new opportunities for therapeutic targeting and disease monitoring from diagnosis.