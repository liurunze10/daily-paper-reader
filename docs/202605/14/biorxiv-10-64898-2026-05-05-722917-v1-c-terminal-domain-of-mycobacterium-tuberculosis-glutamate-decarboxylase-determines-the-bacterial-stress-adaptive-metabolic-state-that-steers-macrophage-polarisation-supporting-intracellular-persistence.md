---
title: C-Terminal Domain of Mycobacterium tuberculosis Glutamate Decarboxylase determines the bacterial stress-adaptive metabolic state that steers macrophage polarisation supporting intracellular persistence
authors: "Agarwal, A., Misra, A., Saxena, S., Mohareer, K., Patel, A. B., Banerjee, S."
date: 2026-05-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.05.722917v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.0
evidence: 细菌应激适应在氧化应激下引导巨噬细胞极化
tldr: 本研究揭示了结核分枝杆菌（Mtb）谷氨酸脱羧酶（GadB）的C端结构域（CTD）在应对宿主压力中的关键作用。研究发现，CTD通过调节GadB的酶活性来控制GABA的产生，这不仅能缓解酸性和氧化压力，还能诱导巨噬细胞向M2型极化，抑制宿主免疫反应，从而促进细菌在胞内的持久存在。该发现为开发针对Mtb代谢调节机制的新型药物提供了潜在靶点。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在阐明结核分枝杆菌如何通过特定酶驱动的代谢状态适应宿主环境压力并调节宿主免疫反应。
method: 利用酶动力学、荧光光谱、代谢组学及巨噬细胞感染模型，对比分析了GadB及其C端结构域缺失株的生化特性与免疫调节效应。
result: 发现GadB的CTD通过调节GABA产量和活性氧水平，诱导巨噬细胞向M2型极化并抑制促炎细胞因子释放，从而支持细菌持久感染。
conclusion: GadB的C端结构域是决定Mtb代谢适应与宿主免疫逃逸的关键调节因子，为开发病原体特异性疗法提供了新靶点。
---

## Abstract
Mycobacterium tuberculosis (Mtb) adapts metabolically to survive hostile conditions within alveolar macrophages, but whether specific enzyme-driven metabolic states of Mtb link stress adaptation to host immunomodulation remains unclear. Using LC-MRM/MS metabolite profiling and metabolic modeling, we previously identified elevated {gamma}-aminobutyric acid (GABA) production via the GABA shunt during adaptation to oxidative and acidic stress. Here, we show that stress-responsive enzymatic efficiency of glutamate decarboxylase (GadB) in producing GABA, not only mitigates acidic and oxidative stress but also drives macrophage polarisation towards the M2 phenotype, extending its role beyond bioenergetics into host-pathogen cross-talk.

We identify the C-terminal domain (CTD) of mycobacterial GadB as a key regulator. Enzyme kinetics and fluorescence spectroscopy revealed that CTD deletion abolishes pH-dependent regulation of catalytic efficiency (kcat/Km) and substrate affinity (Ka). Under oxidative stress, the CTD enhances catalytic efficiency without altering substrate affinity, suggesting condition-specific roles. Accordingly, in vitro, Mtb::MtbGadB with higher GABA and [~]40% lower ROS outgrew Mtb::MtbGadB{Delta}Ct under acidic and oxidative conditions. These biochemical differences influenced host immunity, wherein infection with high-GABA-producing Mtb::MtbGadB strain induced M2 polarisation, with decreased CD86, reduced RNS, limited endosomal maturation, as indicated by Rab5/Rab7 ratio and Lysotracker-based confocal microscopy, and decreased TNF-, IL-12p70, and IFN-{gamma} release compared to low-GABA-producing Mtb::MtbGadB{Delta}Ct. Consequently, Mtb::MtbGadB{Delta}Ct showed higher clearance. We conclude that by enabling pH-dependent activity of GadB, the CTD orchestrates proton consumption, ROS reduction, and GABA-mediated immunomodulation. Distinct structural features of CTDs in human versus Mtb GADs highlight the CTD as a selective drug target for pathogen-specific, host-compatible therapies.

ImportanceThis work establishes a direct mechanistic link between metabolic state of Mycobacterium tuberculosis (Mtb) actively shaping host immune responses, deciding infection outcome. The study identifies the C-terminal domain (CTD) of MtbGadB in steering enzymatic efficiency, regulating intrabacterial GABA production and ROS quenching, determining the stress-responsive metabolic state of the bacteria. Infection with metabolically distinct strains had differential impacts on host immunity, wherein infection with high-GABA-producing Mtb::MtbGadB induced M2-polarisation, reduced RNS, limited endosomal maturation, and reduced proinflammatory cytokine release, compared to low-GABA-producing Mtb::MtbGadB{Delta}Ct. Consequently, Mtb::MtbGadB{Delta}Ct could be cleared, but Mtb::MtbGadB persisted, deciding the fate of the infection. Structural differences between CTDs of human and Mtb GADs, make it a therapeutically-exploitable determinant for developing pathogen-specific drugs that remain compatible with the host.

---

## 论文详细总结（自动生成）

这是一份关于论文《C-Terminal Domain of Mycobacterium tuberculosis Glutamate Decarboxylase determines the bacterial stress-adaptive metabolic state that steers macrophage polarisation supporting intracellular persistence》的结构化深入总结：

### 1. 核心问题与整体含义（研究动机和背景）
结核分枝杆菌（Mtb）在宿主巨噬细胞内面临酸性环境、氧化应激（ROS）和营养匮乏等严苛挑战。虽然已知 Mtb 会通过代谢重塑来适应这些压力，但**特定的酶驱动代谢状态如何直接调控宿主的免疫调节**仍不清楚。
本研究聚焦于 **GABA 支路（GABA shunt）** 的限速酶——**谷氨酸脱羧酶（GadB）**。研究旨在探究 GadB 如何通过产生 $\gamma$-氨基丁酸（GABA）来同时实现细菌自身的应激适应（维持 pH 和氧化还原平衡）以及对宿主巨噬细胞极化状态的远程操控，从而支持其在胞内的长期存续。

### 2. 方法论：核心思想与关键技术
*   **核心思想**：提出 Mtb GadB 的 **C 端结构域（CTD）** 是一个关键的分子开关，它感知环境压力（pH 和氧化还原状态）并调节酶的催化效率，进而通过 GABA 产量决定细菌的代谢状态和宿主的免疫命运。
*   **关键技术细节**：
    *   **同源建模与突变设计**：利用大肠杆菌 Gad 结构为模板建立 Mtb GadB 模型，识别出 CTD（Val447-His460）为潜在调节区，并设计了 CTD 缺失突变株（$\Delta Ct$）和活性位点突变株（SDM）。
    *   **酶动力学分析**：通过 Michaelis-Menten 方程测定不同 pH 和氧化应激下的 $K_m$、$V_{max}$ 和 $k_{cat}/K_m$。
    *   **荧光光谱法**：利用 Stern-Volmer 方程计算配体（谷氨酸）与酶的结合常数（$K_a$）。
    *   **代谢组学监测**：使用 LC-MRM/MS 和 NMR 技术定量分析细菌胞内外及巨噬细胞内的 GABA 含量。
    *   **宿主反应评估**：通过流式细胞术、Confocal 活细胞成像（监测溶酶体酸化和 Rab5/Rab7 转换）以及 ELISA 评估巨噬细胞的极化状态（M1 vs M2）。

### 3. 实验设计与对比基准
*   **实验场景**：体外应激模拟（pH 5.5, 10mM $H_2O_2$）和 THP-1 巨噬细胞感染模型。
*   **对比菌株（Benchmark）**：
    *   野生型 Mtb H37Rv 及其过表达株（$Mtb::MtbGadB$）。
    *   空载体对照株（$Mtb::pVV16$）。
    *   C 端缺失突变株（$Mtb::MtbGadB\Delta Ct$）。
    *   催化位点失活突变株（$Mtb::MtbGadBSDM$）。
    *   非致病性的耻垢分枝杆菌（Msmeg）作为活细胞成像的替代模型。
*   **对比维度**：酶活性、细菌生长曲线、胞内 ROS 水平、吞噬体成熟度、细胞因子分泌谱、巨噬细胞表面标志物（CD86/CD206）。

### 4. 资源与算力
*   论文主要涉及生物化学与分子生物学实验，计算部分主要集中在**蛋白质同源建模与分子动力学模拟**。
*   使用了 **Schrodinger Maestro Suite 2024** 软件包进行建模、能量最小化（OPLS4 场）和丙氨酸扫描。
*   **未明确说明**具体的硬件算力（如 GPU/CPU 型号）或计算时长，这在生物类论文中较为常见，因为此类模拟计算量相对较小。

### 5. 实验数量与充分性
*   **实验规模**：涵盖了从分子水平（酶动力学）、细胞水平（细菌代谢与生长）到宿主水平（巨噬细胞极化）的全链条实验。
*   **重复性**：所有生物学实验均至少进行了 **3 次独立生物学重复**，并进行了统计学显著性分析（Student's t-test）。
*   **充分性评价**：实验设计非常充分且逻辑严密。通过对比 CTD 缺失和催化位点突变，成功区分了“酶的基础催化功能”与“应激调节功能”，证明了 CTD 的特异性调节作用。

### 6. 主要结论与发现
*   **CTD 的调节作用**：CTD 缺失会导致 GadB 失去对 pH 的敏感性，无法在酸性环境下提高底物亲和力。
*   **代谢驱动免疫**：高产 GABA 的菌株（野生型 GadB）能显著降低巨噬细胞内的 ROS 和 RNS，抑制吞噬体酸化和成熟（Rab5/7 比例升高）。
*   **诱导 M2 极化**：Mtb 通过 GadB 产生的 GABA 诱导巨噬细胞向 **M2 型（抗炎型）** 极化，表现为 CD206 表达增加、促炎细胞因子（TNF-$\alpha$, IFN-$\gamma$）减少，从而逃避宿主清除。
*   **治疗潜力**：人类 GAD 酶与 Mtb GadB 的 CTD 结构存在显著差异，这使得 CTD 成为一个理想的、不影响宿主功能的抗结核药物靶点。

### 7. 优点与亮点
*   **跨学科整合**：成功将精细的酶结构生物学与宏观的宿主-病原体免疫相互作用联系起来。
*   **机制深入**：不仅观察到现象，还通过突变实验明确了 CTD 在 pH 感知和氧化还原稳定中的具体生化贡献。
*   **发现新功能**：将 GABA 的作用从单纯的细菌能量代谢扩展到了复杂的免疫信号跨界通讯（Cross-talk）。

### 8. 不足与局限
*   **GABA 来源模糊**：虽然观察到感染后巨噬细胞内总 GABA 增加，但尚无法完全区分这些 GABA 是细菌直接分泌的、细菌裂解释放的，还是细菌诱导宿主自身合成的。
*   **受体机制未明**：虽然检测到宿主 GABA 受体（GABRA2）表达变化，但 GABA 究竟通过哪种具体的受体通路触发 M2 极化的分子细节仍需进一步研究。
*   **模型限制**：主要使用了 THP-1 细胞系，未来需在原代巨噬细胞或动物模型中进一步验证这一代谢-免疫轴。

（完）
