---
title: C-Terminal Domain of Mycobacterium tuberculosis Glutamate Decarboxylase determines the bacterial stress-adaptive metabolic state that steers macrophage polarisation supporting intracellular persistence
authors: "Agarwal, A., Misra, A., Saxena, S., Mohareer, K., Patel, A. B., Banerjee, S."
date: 2026-05-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.05.722917v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 结核分枝杆菌对氧化应激的适应驱动巨噬细胞极化
tldr: 本研究揭示了结核分枝杆菌（Mtb）通过谷氨酸脱羧酶（GadB）的C端结构域（CTD）调节代谢状态，进而影响宿主免疫。研究发现，CTD通过调控GABA产量，不仅帮助细菌抵抗酸性和氧化压力，还能诱导巨噬细胞向M2型极化，抑制促炎细胞因子释放并限制内体成熟，从而支持细菌在胞内持久存在。该发现建立了细菌代谢与宿主免疫调节之间的直接机械联系，并指出CTD可作为特异性药物靶点。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究结核分枝杆菌如何通过特定代谢酶驱动的代谢状态适应环境压力并调控宿主免疫反应。
method: 利用代谢组学、酶动力学及巨噬细胞感染模型，分析了GadB酶及其C端结构域在压力适应中的作用。
result: 发现GadB的CTD通过调节GABA产量来驱动巨噬细胞M2型极化，从而抑制宿主免疫并促进细菌持久感染。
conclusion: GadB的CTD是决定Mtb压力适应和免疫逃逸的关键代谢调节因子，是极具潜力的病原体特异性药物靶点。
---

## Abstract
Mycobacterium tuberculosis (Mtb) adapts metabolically to survive hostile conditions within alveolar macrophages, but whether specific enzyme-driven metabolic states of Mtb link stress adaptation to host immunomodulation remains unclear. Using LC-MRM/MS metabolite profiling and metabolic modeling, we previously identified elevated {gamma}-aminobutyric acid (GABA) production via the GABA shunt during adaptation to oxidative and acidic stress. Here, we show that stress-responsive enzymatic efficiency of glutamate decarboxylase (GadB) in producing GABA, not only mitigates acidic and oxidative stress but also drives macrophage polarisation towards the M2 phenotype, extending its role beyond bioenergetics into host-pathogen cross-talk.

We identify the C-terminal domain (CTD) of mycobacterial GadB as a key regulator. Enzyme kinetics and fluorescence spectroscopy revealed that CTD deletion abolishes pH-dependent regulation of catalytic efficiency (kcat/Km) and substrate affinity (Ka). Under oxidative stress, the CTD enhances catalytic efficiency without altering substrate affinity, suggesting condition-specific roles. Accordingly, in vitro, Mtb::MtbGadB with higher GABA and [~]40% lower ROS outgrew Mtb::MtbGadB{Delta}Ct under acidic and oxidative conditions. These biochemical differences influenced host immunity, wherein infection with high-GABA-producing Mtb::MtbGadB strain induced M2 polarisation, with decreased CD86, reduced RNS, limited endosomal maturation, as indicated by Rab5/Rab7 ratio and Lysotracker-based confocal microscopy, and decreased TNF-, IL-12p70, and IFN-{gamma} release compared to low-GABA-producing Mtb::MtbGadB{Delta}Ct. Consequently, Mtb::MtbGadB{Delta}Ct showed higher clearance. We conclude that by enabling pH-dependent activity of GadB, the CTD orchestrates proton consumption, ROS reduction, and GABA-mediated immunomodulation. Distinct structural features of CTDs in human versus Mtb GADs highlight the CTD as a selective drug target for pathogen-specific, host-compatible therapies.

ImportanceThis work establishes a direct mechanistic link between metabolic state of Mycobacterium tuberculosis (Mtb) actively shaping host immune responses, deciding infection outcome. The study identifies the C-terminal domain (CTD) of MtbGadB in steering enzymatic efficiency, regulating intrabacterial GABA production and ROS quenching, determining the stress-responsive metabolic state of the bacteria. Infection with metabolically distinct strains had differential impacts on host immunity, wherein infection with high-GABA-producing Mtb::MtbGadB induced M2-polarisation, reduced RNS, limited endosomal maturation, and reduced proinflammatory cytokine release, compared to low-GABA-producing Mtb::MtbGadB{Delta}Ct. Consequently, Mtb::MtbGadB{Delta}Ct could be cleared, but Mtb::MtbGadB persisted, deciding the fate of the infection. Structural differences between CTDs of human and Mtb GADs, make it a therapeutically-exploitable determinant for developing pathogen-specific drugs that remain compatible with the host.

---

## 论文详细总结（自动生成）

这是一份关于论文《C-Terminal Domain of Mycobacterium tuberculosis Glutamate Decarboxylase determines the bacterial stress-adaptive metabolic state that steers macrophage polarisation supporting intracellular persistence》的结构化深入总结：

### 1. 核心问题与整体含义（研究动机和背景）
结核分枝杆菌（*Mtb*）在宿主巨噬细胞内面临酸性环境和氧化应激（ROS）等严酷挑战。虽然已知 *Mtb* 会通过代谢重塑来适应这些压力，但**特定的酶驱动代谢状态如何直接调控宿主的免疫反应（免疫调节）**仍不清楚。
本研究的核心在于探索**谷氨酸脱羧酶（GadB）**及其产生的代谢物**γ-氨基丁酸（GABA）**在 *Mtb* 胞内持久感染中的作用。研究重点揭示了 GadB 的 **C 端结构域（CTD）** 是如何作为“开关”来调节细菌代谢状态，并诱导巨噬细胞向有利于细菌生存的 M2 型极化的。

### 2. 论文提出的方法论
论文结合了生物化学、分子建模、代谢组学和细胞免疫学等多种手段：
*   **核心思想**：通过改变 GadB 酶的结构（特别是 CTD 区域），观察其对细菌 GABA 产量、应激耐受力以及宿主巨噬细胞极化状态的影响。
*   **关键技术细节**：
    *   **分子建模与突变**：利用大肠杆菌 GadB 结构作为模板进行同源建模，识别出 *Mtb* GadB 的 CTD（Val447-His460）。构建了 CTD 缺失突变体（$\Delta Ct$）和活性位点突变体（SDM）。
    *   **酶动力学分析**：通过荧光光谱法和改进的 Berthelot 显色法测定酶的底物亲和力（$K_a$）、米氏常数（$K_m$）和催化效率（$k_{cat}/K_m$）。
    *   **代谢谱分析**：利用 LC-MS/MS 和 NMR 技术定量分析细菌内外及巨噬细胞内的 GABA 水平。
    *   **宿主反应监测**：通过流式细胞术检测表面标志物（CD86/CD206），ELISA 检测细胞因子，共聚焦显微镜观察内体成熟（Rab5/Rab7 比例及 LysoTracker 染色）。

### 3. 实验设计
*   **实验场景**：体外应激模拟（pH 5.5 酸性应激、$H_2O_2$ 氧化应激）及 THP-1 巨噬细胞感染模型。
*   **对比方法（Benchmark）**：
    *   **菌株对比**：野生型 *Mtb* H37Rv、过表达野生型 GadB 菌株（$Mtb::MtbGadB$）、过表达 CTD 缺失菌株（$Mtb::MtbGadB\Delta Ct$）、过表达催化突变菌株（$Mtb::MtbGadB^{SDM}$）以及空载体对照（$Mtb::pVV16$）。
    *   **极化对照**：使用 LPS+IFN-γ 诱导 M1 极化，IL-4 诱导 M2 极化作为标准参照。

### 4. 资源与算力
*   论文属于生物医学实验研究，**未明确提到使用 GPU 算力或大规模计算集群**。
*   主要的计算工作集中在**分子同源建模**（使用 Schrödinger Maestro Suite 2024 软件）和**代谢组学数据处理**。

### 5. 实验数量与充分性
*   **实验规模**：研究涵盖了从纯化蛋白的生化表征到活菌感染细胞的完整链条。每项实验均包含生物学重复（通常为 3 次）和技术重复。
*   **充分性评价**：实验设计非常充分且逻辑严密。作者不仅证明了 GadB 在应激下的表达上调，还通过截断实验证明了 CTD 在 pH 感知中的特异性作用，并进一步在细胞水平验证了这种生化差异如何转化为免疫表型差异。消融实验（突变体对比）有力地支持了结论。

### 6. 主要结论与发现
*   **CTD 的调节作用**：GadB 的 C 端结构域决定了酶的 pH 依赖性活性。缺失 CTD 会使酶失去对酸性环境的敏感性，导致 GABA 产量下降。
*   **代谢驱动极化**：高产 GABA 的菌株（WT）能显著降低巨噬细胞内的 ROS 和 RNS 水平，抑制促炎细胞因子（TNF-α, IL-12, IFN-γ）释放，并诱导抗炎的 **M2 型极化**。
*   **逃避溶酶体**：高产 GABA 的菌株能中和吞噬体 pH，提高 Rab5/Rab7 比例，从而**阻断内体成熟**，避免被溶酶体降解。
*   **持久性**：CTD 缺失菌株在巨噬细胞内的存活率显著降低，证明了 GadB 介导的代谢状态是 *Mtb* 胞内持久感染的关键。

### 7. 优点
*   **跨学科视角**：成功将细菌的底层生化酶动力学与宏观的宿主免疫表型联系起来，提供了一个清晰的“结构-功能-代谢-免疫”逻辑链。
*   **靶点潜力**：通过对比人类与 *Mtb* 的 GAD 酶结构，发现 CTD 具有显著差异，这为开发**病原体特异性、宿主兼容**的新型抗结核药物提供了理想靶点。
*   **机制深入**：不仅观察到现象，还深入探讨了质子消耗、ROS 淬灭与免疫信号之间的机械联系。

### 8. 不足与局限
*   **GABA 来源模糊**：虽然证明了感染后巨噬细胞内 GABA 增加，但尚无法完全区分这些 GABA 是细菌直接分泌的、细菌裂解释放的，还是细菌诱导宿主细胞自身产生的。
*   **受体机制缺失**：虽然观察到了 M2 极化，但 GABA 是通过哪种具体的宿主受体（如 GABA-A 或 GABA-B 受体）触发信号转导的，文中未做深入探讨。
*   **模型单一**：主要依赖 THP-1 细胞系，缺乏原代巨噬细胞或动物模型（如小鼠感染模型）的验证，这可能限制了结论在复杂生物系统中的普适性。

（完）
