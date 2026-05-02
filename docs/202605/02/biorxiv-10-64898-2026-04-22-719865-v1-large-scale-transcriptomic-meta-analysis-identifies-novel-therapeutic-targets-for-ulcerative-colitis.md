---
title: Large-scale transcriptomic meta-analysis identifies novel therapeutic targets for ulcerative colitis
title_zh: 大规模转录组荟萃分析确定了溃疡性结肠炎的新治疗靶点
authors: "Piernik, M., Adamiec-Organisciok, M., Skonieczna, M., Eder, P."
date: 2026-04-24
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.22.719865v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: 溃疡性结肠炎的转录组荟萃分析
tldr: 本研究通过对14个独立转录组数据集（共972份样本）进行大规模荟萃分析，旨在揭示溃疡性结肠炎（UC）中持续失调的基因和通路。研究区分了炎症依赖性变化与本征性易感性，发现UC存在炎症导致的代谢崩溃及非炎症状态下的本征代谢缺陷。这一发现提出了UC病理的双层模型，为开发针对免疫抑制的新靶点及针对代谢缺陷的预防性干预提供了理论依据。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在通过区分炎症依赖性与本征性基因表达变化，寻找溃疡性结肠炎中一致失调的治疗新靶点。
method: 对来自GEO数据库的14个微阵列数据集（包含972份粘膜活检样本）进行了随机效应荟萃分析。
result: 发现发炎期UC存在严重的代谢崩溃，而非发炎期则表现出葡萄糖醛酸化受阻和翻译上调等本征性代谢缺陷。
conclusion: 提出了UC病理的双层模型，强调了针对本征代谢缺陷进行主动干预以及针对炎症进行免疫抑制的重要性。
---

## 摘要
溃疡性结肠炎（UC）是一种慢性炎症性肠病，目前绝大多数已批准的疗法都针对免疫系统。本研究旨在识别独立 UC 转录组队列中一致失调的基因和通路，并区分本征性变化与炎症依赖性变化。我们对来自 Gene Expression Omnibus 的 14 个微阵列数据集（包含 972 份粘膜活检样本，涉及 9 个平台）进行了随机效应荟萃分析，将发炎期 UC、非发炎期 UC 以及发炎期克罗恩病（CD）与对照组进行了比较，并直接对比了 UC 与 CD。针对发炎期 UC 的分析揭示了 UC 中上调的炎症转录组特征，这为所有已批准抗炎疗法的使用提供了理论依据。与此同时，主要的下调信号与代谢相关，由 PPARGC1A、PPARGC1B 和 ESRRA 驱动，表明存在协调的、炎症依赖性的代谢崩溃。针对非发炎期 UC 的分析揭示了一组独立的潜在本征性脆弱性，包括完全受抑制的葡萄糖醛酸酸化、上调的翻译、补体启动以及改变的铁输出，且这些变化并不处于能量崩溃的下游。UC 的代谢缺陷比 CD 更为严重，而免疫通路则是共有的。这些发现提出了 UC 病理的双层模型：代谢通路的本征性损伤因炎症而进一步加剧。炎症分析揭示了免疫抑制的新靶点，而本征性分析则确定了在发作间期针对代谢缺陷进行主动干预的靶点。

## Abstract
Ulcerative colitis (UC) is a chronic inflammatory bowel disease for which the vast majority of the approved therapies target the immune system. We aimed to identify consistently dysregulated genes and pathways across independent UC transcriptomic cohorts, distinguishing constitutive from inflammation-dependent changes. We performed a random-effects meta-analysis of 14 microarray datasets from the Gene Expression Omnibus (972 mucosal biopsies, 9 platforms), comparing inflamed UC, uninflamed UC, and inflamed Crohns disease (CD) to controls, as well as UC to CD directly. The inflamed UC analysis revealed an upregulated inflammatory transcriptomic profile in UC, providing a rationale for the use of all approved anti-inflammatory therapies. In parallel, the predominant downregulated signal was metabolic, driven by PPARGC1A, PPARGC1B, and ES-RRA, indicating a coordinated, inflammation-dependent collapse. The uninflamed UC analysis revealed a separate set of potentially constitutive vulnerabilities -- fully suppressed glucuronidation, upregulated translation, complement priming, and altered iron export -- that are not downstream of the energy collapse. The metabolic deficit was more severe in UC than in CD, while immune pathways were shared. These findings suggest a two-layer model of UC pathology: a constitutive impairment of metabolic pathways that is further exacerbated by inflammation. The inflammation analysis reveals new targets for immune suppression while the constitutive analysis identifies targets for proactive intervention between flares directed at the metabolic deficiency.

---

## 论文详细总结（自动生成）

这篇论文对溃疡性结肠炎（UC）的转录组学进行了深入的大规模荟萃分析，旨在通过区分炎症反应与本征性病理特征，寻找新的治疗靶点。以下是该研究的结构化总结：

### 1. 核心问题与整体含义
*   **研究背景**：溃疡性结肠炎（UC）目前的治疗手段主要集中在免疫抑制，但许多患者疗效不佳或容易复发。
*   **核心问题**：在 UC 的基因表达变化中，哪些是由于炎症引起的“结果”，哪些是疾病本身固有的、导致易感性的“本征特征”？
*   **整体含义**：研究试图打破单一的免疫治疗视角，通过识别非炎症状态下的代谢和功能缺陷，为 UC 的预防性干预和精准治疗提供新思路。

### 2. 方法论
*   **核心思想**：利用荟萃分析（Meta-analysis）整合多个独立研究的数据，以消除单一研究的批次效应和样本量局限，从而识别跨人群、跨平台的稳健生物标志物。
*   **关键技术细节**：
    *   **数据检索与筛选**：从 Gene Expression Omnibus (GEO) 数据库中筛选出 14 个符合条件的微阵列数据集。
    *   **随机效应模型**：采用随机效应荟萃分析方法处理 972 份粘膜活检样本，计算合并后的效应量（Effect Size）。
    *   **多维度对比分析**：分别对比了发炎期 UC vs. 对照、非发炎期 UC vs. 对照、发炎期克罗恩病（CD）vs. 对照，以及 UC vs. CD。
    *   **通路分析**：使用 GSEA 等工具进行功能富集，重点关注代谢通路和免疫信号。

### 3. 实验设计
*   **数据集**：包含 14 个独立数据集，涉及 9 个不同的微阵列平台，总计 972 份样本。
*   **对比场景（Benchmark）**：
    *   以健康人群的肠粘膜组织作为基准（Control）。
    *   对比发炎（Inflamed）与非发炎（Uninflamed）组织，用以剥离炎症依赖性信号。
    *   对比 UC 与 CD，用以识别溃疡性结肠炎特异性的病理机制。

### 4. 资源与算力
*   **算力说明**：论文中未明确提及具体的 GPU 或高性能计算集群型号。
*   **分析性质**：由于该研究主要基于已有的微阵列转录组数据进行统计学荟萃分析，而非深度学习模型训练，其对算力的需求主要集中在 CPU 大规模数据处理和统计建模上，通常一般的生物信息学工作站即可完成。

### 5. 实验数量与充分性
*   **实验规模**：研究整合了近千份临床样本，是目前该领域规模较大的转录组荟萃分析之一。
*   **充分性评价**：
    *   **客观性**：通过跨平台、跨研究的整合，有效降低了单一实验的偶然性。
    *   **公平性**：研究同时纳入了 CD 作为对照疾病，能够区分出 IBD 的共性特征与 UC 的特异性特征，实验设计逻辑严密且互为补充。

### 6. 主要结论与发现
*   **双层病理模型**：提出了 UC 的“双层”模型——底层是本征性的代谢功能障碍，上层是炎症诱导的代谢崩溃。
*   **发炎期特征**：表现为剧烈的炎症信号上调和由 *PPARGC1A*、*PPARGC1B* 及 *ESRRA* 驱动的协调性代谢崩溃（能量代谢全面下调）。
*   **非发炎期（本征性）缺陷**：即使在没有炎症的组织中，也观察到**葡萄糖醛酸化（解毒功能）完全受阻**、蛋白质翻译上调、补体系统预激活以及铁输出改变。
*   **UC vs. CD**：UC 的代谢缺陷（尤其是线粒体和解毒功能）比 CD 更为严重，而两者的免疫激活通路高度相似。

### 7. 优点
*   **视角独特**：成功区分了“炎症的结果”与“疾病的诱因”，为非发炎期的维持治疗提供了理论依据。
*   **数据稳健**：荟萃分析方法确保了发现的基因（如葡萄糖醛酸化相关基因）在多个独立队列中具有高度一致性。
*   **临床转化潜力**：识别出的代谢驱动因子（如 PPAR 激动剂）为开发非免疫抑制类药物提供了明确靶点。

### 8. 不足与局限
*   **技术平台限制**：主要依赖微阵列数据，可能无法捕捉到单细胞水平的异质性或新型非编码 RNA 的变化。
*   **缺乏实验验证**：研究结果完全基于生物信息学推导，尚未在动物模型或临床试验中对识别出的新靶点进行功能性验证。
*   **因果律探讨**：虽然识别了非发炎期的异常，但仍难以完全确定这些“本征缺陷”是导致 UC 的原发原因，还是既往炎症留下的永久性表观遗传印记。

（完）
