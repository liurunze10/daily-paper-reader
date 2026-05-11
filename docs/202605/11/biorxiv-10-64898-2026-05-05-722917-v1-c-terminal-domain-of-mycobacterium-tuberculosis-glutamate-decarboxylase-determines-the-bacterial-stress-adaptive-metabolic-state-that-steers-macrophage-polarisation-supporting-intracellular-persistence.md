---
title: C-Terminal Domain of Mycobacterium tuberculosis Glutamate Decarboxylase determines the bacterial stress-adaptive metabolic state that steers macrophage polarisation supporting intracellular persistence
authors: "Agarwal, A., Misra, A., Saxena, S., Mohareer, K., Patel, A. B., Banerjee, S."
date: 2026-05-06
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.05.722917v1.full.pdf"
tags: ["query:ros-mp"]
score: 9.5
evidence: 结核杆菌代谢状态减轻氧化应激并驱动巨噬细胞极化
tldr: 本研究揭示了结核分枝杆菌（Mtb）通过谷氨酸脱羧酶（GadB）的C端结构域（CTD）调节代谢状态，进而影响宿主免疫。研究发现，CTD通过调控GABA产量，不仅帮助细菌抵抗酸性和氧化压力，还能诱导巨噬细胞向M2型极化，抑制促炎细胞因子释放并限制内体成熟，从而支持细菌在胞内持久存在。该发现建立了细菌代谢与宿主免疫调节之间的直接机械联系，并指出CTD可作为特异性药物靶点。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究结核分枝杆菌如何通过特定代谢酶驱动的代谢状态适应压力并调节宿主免疫反应。
method: 结合酶动力学、代谢组学建模及巨噬细胞感染实验，重点分析了GadB酶及其C端结构域的功能。
result: 发现GadB的CTD调节GABA产量，高产GABA菌株能诱导M2型巨噬细胞极化并抑制免疫清除。
conclusion: GadB的CTD是决定Mtb压力适应和免疫逃逸的关键代谢调节因子，可作为新型抗结核药物靶点。
---

## Abstract
Mycobacterium tuberculosis (Mtb) adapts metabolically to survive hostile conditions within alveolar macrophages, but whether specific enzyme-driven metabolic states of Mtb link stress adaptation to host immunomodulation remains unclear. Using LC-MRM/MS metabolite profiling and metabolic modeling, we previously identified elevated {gamma}-aminobutyric acid (GABA) production via the GABA shunt during adaptation to oxidative and acidic stress. Here, we show that stress-responsive enzymatic efficiency of glutamate decarboxylase (GadB) in producing GABA, not only mitigates acidic and oxidative stress but also drives macrophage polarisation towards the M2 phenotype, extending its role beyond bioenergetics into host-pathogen cross-talk.

We identify the C-terminal domain (CTD) of mycobacterial GadB as a key regulator. Enzyme kinetics and fluorescence spectroscopy revealed that CTD deletion abolishes pH-dependent regulation of catalytic efficiency (kcat/Km) and substrate affinity (Ka). Under oxidative stress, the CTD enhances catalytic efficiency without altering substrate affinity, suggesting condition-specific roles. Accordingly, in vitro, Mtb::MtbGadB with higher GABA and [~]40% lower ROS outgrew Mtb::MtbGadB{Delta}Ct under acidic and oxidative conditions. These biochemical differences influenced host immunity, wherein infection with high-GABA-producing Mtb::MtbGadB strain induced M2 polarisation, with decreased CD86, reduced RNS, limited endosomal maturation, as indicated by Rab5/Rab7 ratio and Lysotracker-based confocal microscopy, and decreased TNF-, IL-12p70, and IFN-{gamma} release compared to low-GABA-producing Mtb::MtbGadB{Delta}Ct. Consequently, Mtb::MtbGadB{Delta}Ct showed higher clearance. We conclude that by enabling pH-dependent activity of GadB, the CTD orchestrates proton consumption, ROS reduction, and GABA-mediated immunomodulation. Distinct structural features of CTDs in human versus Mtb GADs highlight the CTD as a selective drug target for pathogen-specific, host-compatible therapies.

ImportanceThis work establishes a direct mechanistic link between metabolic state of Mycobacterium tuberculosis (Mtb) actively shaping host immune responses, deciding infection outcome. The study identifies the C-terminal domain (CTD) of MtbGadB in steering enzymatic efficiency, regulating intrabacterial GABA production and ROS quenching, determining the stress-responsive metabolic state of the bacteria. Infection with metabolically distinct strains had differential impacts on host immunity, wherein infection with high-GABA-producing Mtb::MtbGadB induced M2-polarisation, reduced RNS, limited endosomal maturation, and reduced proinflammatory cytokine release, compared to low-GABA-producing Mtb::MtbGadB{Delta}Ct. Consequently, Mtb::MtbGadB{Delta}Ct could be cleared, but Mtb::MtbGadB persisted, deciding the fate of the infection. Structural differences between CTDs of human and Mtb GADs, make it a therapeutically-exploitable determinant for developing pathogen-specific drugs that remain compatible with the host.

---

## 论文详细总结（自动生成）

这篇论文深入探讨了结核分枝杆菌（*Mycobacterium tuberculosis*, Mtb）如何通过特定的代谢酶调节自身代谢状态，进而操纵宿主免疫反应以实现长期胞内寄生。以下是对该论文的结构化总结：

### 1. 论文的核心问题与整体含义（研究动机和背景）
*   **核心问题**：结核杆菌在巨噬细胞内面临酸性和氧化应激等严酷环境，它如何通过代谢重塑来适应这些压力？更重要的是，细菌的特定代谢产物是否直接参与了对宿主免疫系统的“重编程”？
*   **背景**：以往研究发现 Mtb 在压力下会积累 $\gamma$-氨基丁酸（GABA），但其背后的分子机制（尤其是谷氨酸脱羧酶 GadB 的作用）以及 GABA 对宿主巨噬细胞极化的具体影响尚不明确。

### 2. 论文提出的方法论
*   **核心思想**：研究 GadB 酶的结构域功能，特别是 C 端结构域（CTD）在感知环境压力和调节 GABA 产量中的作用，并建立“细菌代谢-宿主免疫”的直接机械联系。
*   **关键技术细节**：
    *   **蛋白质工程**：构建了野生型（WT）、C 端缺失突变体（$\Delta Ct$）和活性位点突变体（SDM）的重组蛋白及相应 Mtb 菌株。
    *   **酶动力学与光谱分析**：利用 Michaelis-Menten 方程测定催化效率（$k_{cat}/K_m$），通过荧光猝灭实验和 Stern-Volmer 方程计算底物结合常数（$K_a$）。
    *   **同源建模**：基于大肠杆菌 Gad 结构，利用 Schrodinger Maestro 软件对 Mtb GadB 进行 3D 建模和分子动力学模拟。
    *   **代谢组学**：采用 LC-MS/MS、NMR 和改良的 Berthelot 显色法定量分析胞内外 GABA 含量。
    *   **免疫学检测**：通过流式细胞术检测表面标志物（CD86/CD206），ELISA 检测细胞因子，共聚焦显微镜观察内体成熟（Rab5/Rab7）。

### 3. 实验设计
*   **实验场景**：
    *   **体外压力模型**：模拟巨噬细胞内的酸性（pH 5.5）和氧化（10 mM $H_2O_2$）环境。
    *   **细胞感染模型**：使用人单核细胞系 THP-1 诱导的巨噬细胞。
*   **对比方法（Benchmark）**：
    *   **菌株对比**：Mtb H37Rv 野生型、过表达 WT GadB 菌株、过表达 $\Delta Ct$ 突变体、过表达 SDM 突变体、空载体对照组（pVV16/pMSP）。
    *   **极化对照**：使用 LPS+IFN-$\gamma$ 诱导 M1 型，IL-4 诱导 M2 型作为标准参照。

### 4. 资源与算力
*   论文主要侧重于生物化学与细胞生物学实验。
*   **计算资源**：提到了使用 **Schrodinger Maestro Suite 2024** 进行蛋白质同源建模、环路精修（Loop refinement）和能量最小化（OPLS4 力场）。
*   **硬件说明**：文中未明确提及具体的 GPU/CPU 型号或计算时长，这在生物类论文中较为常见，因为计算量主要集中于静态结构模拟而非大规模深度学习训练。

### 5. 实验数量与充分性
*   **实验规模**：涵盖了从分子水平（纯化蛋白的酶活实验）、细菌水平（生长曲线、ROS 测定）到宿主细胞水平（细胞因子、流式、显微成像）的多维度实验。
*   **充分性与客观性**：
    *   所有实验均包含至少 3 次生物学重复。
    *   采用了突变体回补逻辑（虽然主要是过表达模型），通过 SDM 和 $\Delta Ct$ 的对比，清晰地分离了“催化功能”与“调节功能”。
    *   使用了多种检测手段（如 NMR 与显微色法互相验证 GABA 产量），实验设计严谨、客观。

### 6. 论文的主要结论与发现
*   **CTD 的关键作用**：GadB 的 C 端结构域是 pH 感应器。缺失 CTD 会使酶失去对酸性环境的响应性，导致 GABA 产量下降。
*   **代谢驱动免疫极化**：高产 GABA 的 Mtb 菌株能显著诱导巨噬细胞向 **M2 型（抗炎型）** 极化，表现为 CD86 下降、CD206 上升、促炎细胞因子（TNF-$\alpha$, IFN-$\gamma$）减少、抑炎细胞因子（IL-10）增加。
*   **生存机制**：GABA 的产生消耗了质子并淬灭了 ROS，同时通过诱导 M2 极化抑制了内体成熟（Rab5 向 Rab7 的转换），从而保护细菌免受清除，促进其在胞内存活。
*   **药物靶点**：发现 Mtb GadB 的 CTD 结构与人类同源酶存在显著差异，使其成为潜在的特异性抗结核药物靶点。

### 7. 优点
*   **跨学科视角**：成功将细菌的底层代谢（GABA 支路）与宏观的宿主免疫表型（巨噬细胞极化）结合，揭示了“代谢物介导的跨界通讯”。
*   **机制深入**：不仅发现了现象，还通过结构建模和突变实验定位到了具体的调节结构域（CTD）。
*   **临床潜力**：通过对比人与细菌酶的结构差异，为开发低副作用的新型抗生素提供了理论依据。

### 8. 不足与局限
*   **转运机制不明**：虽然观察到胞外 GABA 增加，但 Mtb 基因组中尚未发现明确的 GABA 外排蛋白，细菌如何将 GABA 释放到宿主胞质的机制仍是谜团。
*   **细胞系局限**：主要研究集中在 THP-1 细胞系，虽然方便控制变量，但其免疫反应可能与人类原代肺泡巨噬细胞存在差异。
*   **缺乏动物实验**：研究止步于细胞水平，尚未在小鼠或非人灵长类感染模型中验证 GadB 缺失对结核病病理进展的长期影响。

（完）
