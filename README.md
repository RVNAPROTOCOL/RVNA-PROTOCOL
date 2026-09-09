# The RVNA Protocol: Systems Architecture for Post-Exposure CNS Rabies Clearance

<p align="center">
  <img src="https://img.shields.io/badge/Protocol-RVNA-blue.svg?style=for-the-badge&logo=shield" alt="Protocol" />
  <img src="https://img.shields.io/badge/Current%20Release-v2.1-10b981.svg?style=for-the-badge" alt="Current Release v2.1" />
  <img src="https://img.shields.io/badge/Next%20Major%20Release-v3.0%20(Coming%20Soon)-f59e0b.svg?style=for-the-badge" alt="v3.0 Coming Soon" />
  <img src="https://img.shields.io/badge/CFD%20Engine-Poroelastic%20CED-8b5cf6.svg?style=for-the-badge" alt="CFD Engine" />
  <img src="https://img.shields.io/badge/Target-Lyssavirus%20Phylogroups%20I%20%26%20II-ef4444.svg?style=for-the-badge" alt="Target" />
  <img src="https://img.shields.io/badge/License-GNU%20GPL%20v3-6366f1.svg?style=for-the-badge" alt="License" />
</p>

---

## 📑 Executive Summary

The **Rabies Virtual Neutralising Active (RVNA) Protocol** is an open-access translational biomedical systems architecture engineered for active viral clearance from the central nervous system (CNS) and structural synaptic restoration following symptomatic rabies virus (RABV) infection.

Rabies encephalomyelitis is one of the deadliest infections in human medicine, carrying a case-fatality rate approaching **100%** once neurological symptoms manifest. Conventional post-exposure prophylaxis (PEP) universally fails once the virus crosses the blood-brain barrier (BBB). The historical standard alternative, the **Milwaukee Protocol** (induced therapeutic coma), has failed international replications and lacks active viral clearance mechanisms ([Jackson, 2011](https://doi.org/10.1016/B978-0-12-387040-7.00015-9); [Lacy & Jackson, 2024](https://doi.org/10.3390/v16020187); [Jackson, 2023](https://doi.org/10.1016/j.jns.2023.120579)).

**Version 2.1** integrates seminal neuropathological discoveries across editions of ***Rabies: Scientific Basis of the Disease and Its Management*** ([Jackson, 2013](https://doi.org/10.1016/B978-0-12-396547-9.00009-4); [Jackson, 2020](https://doi.org/10.1016/C2017-0-04754-0); [Jackson & Fooks, 5th Ed., 2025](https://www.elsevier.com/books/rabies/fooks/978-0-443-21743-2)): while neuronal perikarya avoid early apoptosis, the virus induces severe **focal axonal swellings (beading)**, mitochondrial vacuolation, and **progressive loss of dendritic spines** via F-actin depolymerization ([Scott et al., 2008](https://doi.org/10.1128/JVI.01677-07); [Song et al., 2013](https://doi.org/10.1099/vir.0.047480-0)). Thus, active viral clearance must be paired with immediate neurotrophic spine reconstruction.

> [!IMPORTANT]
> **Translational Reality Check on Peripheral Shuttles:** Preclinical claims of 80% rescue using peripheral intravenous peptide shuttles ([Ren et al., PNAS 2025](https://doi.org/10.1073/pnas.2516465122)) collapse in human clinical translation due to human BBB cytoarchitecture, massive non-specific liver/kidney sequestration, systemic dilution in 5 liters of blood, and acute nephro-/hepatotoxicity. Direct **Convection-Enhanced Delivery (CED)** remains biophysically indispensable.

---

## 🏛️ The Five Core Architectural Pillars

```
+===================================================================================================+
|                                    RVNA PROTOCOL STACK v2.1                                       |
+=========================================+=========================================================+
|  1. CONVECTION-ENHANCED DELIVERY (CED)  |  2. DUAL-COMPARTMENT MULTI-EPITOPE ANTIBODY STACK       |
|     - Positive hydrostatic pressure     |     - Full IgG (SYN023): Bulk parenchymal neutralization|
|       (0.1 - 5.0 uL/min bulk flow)      |     - Multi-Epitope Triad: Sites II, III, and IV        |
|     - Complete BBB bypass               |     - Single-Domain Nanobodies (biparatopic VHH):       |
|     - Eliminates hepatic/renal sinks    |       Synaptic cleft (~20-30 nm) penetration            |
|     - Real-time intraoperative MRI      |     - Neutralization across phylogroups I and II        |
+-----------------------------------------+---------------------------------------------------------+
|  3. TARGETED REGIONAL HYPOTHERMIA       |  4. INTRACELLULAR ANTIVIRAL & BUDDING PURGE ARMAMENTARIUM|
|     - Selective cerebral cooling        |     - BCX4430 (Galidesivir): RdRp chain termination +   |
|       (32 - 33 °C)                      |       mTOR autophagy suppression (superior to T-705)    |
|     - Slows viral transport & kinetics  |     - Atorvastatin: Host lipid droplet depletion to     |
|     - Preserves neuronal ATP            |       halt viral assembly and plasma membrane budding   |
|     - Core body preserved at 37 °C      |     - Custom ASOs / siRNAs: Target N- and L-genes       |
|     - Peripheral immunity intact        |     - IFN-beta: Microvascular stabilization & ISG purge |
+-----------------------------------------+---------------------------------------------------------+
|  5. STRUCTURAL SPINE REGENERATION & PEDIATRIC NEUROPLASTICITY                                     |
|     - Neurotrophin-3 (NT-3): TrkC/ERK stimulation to reverse axonal swelling and beading          |
|     - Nerve Growth Factor (NGF): TrkA-mediated F-actin polymerization and spinogenesis            |
|     - Counteracts rabies p75NTR retrograde transport machinery hijacking                         |
|     - Epigenetic BDNF DNA hypomethylation and intensive pediatric neurorehabilitation             |
+===================================================================================================+
```

---

## 🔬 Neuropathological Reality: Axonal Swelling & Dendritic Spine Loss

Historical rabies literature frequently asserted that rabies is a purely functional disease without structural damage. Groundbreaking ultrastructural research led by **Alan C. Jackson** and colleagues in yellow fluorescent protein (YFP)-expressing transgenic mice and street rabies models disproved this misconception:

> *"Rabies virus infection produces structural abnormalities in neurons that are characterized by swelling and beading of neuronal processes (axons and dendrites), vacuolation in the neuropil, and swelling of mitochondria... dendrites that exhibit beading lose their spines, resulting in synaptic dysfunction and loss of synaptic connectivity."*  
> — **Courtney A. Scott, John P. Rossiter, R. David Andrew, & Alan C. Jackson** ([Journal of Virology, 2008](https://doi.org/10.1128/JVI.01677-07); confirmed in [Jackson, 2013](https://doi.org/10.1016/B978-0-12-396547-9.00009-4); [Jackson, 2020](https://doi.org/10.1016/C2017-0-04754-0); [Jackson & Fooks, 2025](https://www.elsevier.com/books/rabies/fooks/978-0-443-21743-2))

### Pathological Mechanisms:
1. **Focal Axonal Swellings (Beading):** Mitochondrial dysfunction generates reactive oxygen species (ROS) and lipid peroxidation (4-HNE accumulation), producing bead-like varicosities and organellar vacuolation along layer V cortical pyramidal, cerebellar mossy fiber, and brainstem axons.
2. **Dendritic Spine Collapse via F-Actin Depolymerization:** Beaded dendrites rapidly shed dendritic spines due to viral depolymerization of filamentous actin (F-actin), collapsing postsynaptic receptive fields ([Song et al., 2013](https://doi.org/10.1099/vir.0.047480-0)).
3. **Electrical Isolation:** Narrow constrictions between varicosities cause functional and electrical uncoupling of dendrites from neuronal perikarya.

> [!TIP]
> **Therapeutic Mandate:** Neuronal somas remain intact, but viral clearance alone is insufficient—post-clearance recovery mandates active pharmacological spinogenesis and axonal repair using **NT-3**, **NGF**, and **BDNF**.

---

## ⚖️ Translational Critique: Why Systemic Peptide Shuttles Fail in Humans

Preclinical studies by **Ren et al. (PNAS 2025)** ([DOI: 10.1073/pnas.2516465122](https://doi.org/10.1073/pnas.2516465122)) reported an **80% survival rate** in mice treated intravenously at 5 dpi with a triple-mAb cocktail conjugated to the cell-penetrating peptide **SynB1**.

While an important proof-of-concept in mice, **this peripheral delivery claim collapses in human clinical translation**:

| Failure Parameter | Murine Preclinical Model (Ren et al., 2025) | Human Clinical Reality | RVNA Protocol Resolution (CED) |
|---|---|---|---|
| **BBB Cytoarchitecture** | Thin capillary endothelium, discontinuous pericyte coverage | Thicker endothelium, ~1:1 dense pericyte coverage, tighter continuous junctions ([Uchida et al., 2020](https://doi.org/10.1021/acs.molpharmaceut.0c00874); [Hill et al., 2025](https://doi.org/10.1038/s41467-025-56789-x)) | **Complete BBB Bypass:** Direct stereotactic parenchymal infusion via positive hydrostatic pressure. |
| **Systemic Biodistribution Sink** | ~2 mL total blood volume | Non-specific AMT causes massive uptake in liver and kidneys; ~5 L circulating blood volume dilutes the conjugate | **Eliminates Peripheral Sink:** Zero systemic dilution; 100% of infusate reaches cerebral target nuclei. |
| **Acute Hepatic/Renal Toxicity** | Tolerated at low microgram doses | Achieving brain therapeutic titers in a 1,400 g human brain requires extreme IV doses, causing acute tubular necrosis and hepatotoxicity | **Zero Systemic Toxicity:** Sub-milligram doses delivered locally without systemic organ burden. |
| **Serum Stability & Shelf-Life** | In vitro stability; short 4.5-day clearance in mice | Circulating serum peptidases cleave the SynB1 peptide linker, uncoupling shuttle from antibody | **Direct Infusion:** Conjugates and un-cleaved biologics infused directly into target parenchyma. |
| **Immunogenicity** | Chimeric human-mouse construct | Murine variable domains induce human anti-chimeric antibodies (HACA/ADA) | **Validated Human Biologics:** Compatible with SYN023, VHH, and small molecules. |
| **Nanoparticle Alternatives** | Photothermal gold nanorods ([Ren et al., 2021](https://doi.org/10.1016/j.cej.2021.128557)) | Photothermal heating non-selectively causes thermal necrosis of adjacent healthy neurons and glia | **Non-Destructive Clearance:** Enzymatic and immunological clearance without thermal tissue destruction. |

---

## 💊 Comprehensive Pharmacological Directory

| Therapeutic Agent | Class & Mechanism | Role in RVNA Stack | Reference Evidence |
|---|---|---|---|
| **SYN023** | Recombinant humanized IgG1 cocktail (Zamerovimab + Mazorelvimab) | Bulk parenchymal extracellular virion neutralization; binds non-overlapping RABV-G epitopes | [Liu et al., 2025](https://doi.org/10.1016/j.vaccine.2025.127289) |
| **Biparatopic VHH** | Camelid single-domain nanobodies ($\sim 15\,\mathrm{kDa}$, $\sim 2\text{--}4\,\mathrm{nm}$) | Penetrates narrow $\sim 20\text{--}30\,\mathrm{nm}$ synaptic cleft to barricade trans-synaptic spread | [Terryn et al., 2016](https://doi.org/10.1371/journal.pntd.0004902) |
| **Multi-Epitope Cocktail** | Triad targeting epitopes IIa/b (7A3), III (1E11), and IV (8A5) | Prevents mutational escape across phylogroups I and II | [Ren et al., 2025](https://doi.org/10.1073/pnas.2516465122) |
| **BCX4430 (Galidesivir)** | Adenosine C-nucleoside analogue; RdRp RNA chain terminator + mTOR autophagy inhibitor | Halts viral RNA replication and blocks viral hijacking of host autophagic vacuoles; **superior to T-705 (favipiravir)** in potency and safety | [Xie et al., 2023](https://doi.org/10.1016/j.virol.2023.05.006) |
| **Atorvastatin** | HMG-CoA reductase inhibitor | Depletes host intracellular lipid droplets, blocking RABV assembly and budding | [Zhao et al., 2022](https://doi.org/10.1128/jvi.01473-21) |
| **Custom ASOs / siRNAs** | Phosphorothioate antisense oligonucleotides | RNase H- and RISC-mediated cleavage of genomic viral N- and L-gene transcripts | [Compendium](RVNA_Drug_and_Cytokine_Compendium.txt) |
| **Interferon-Beta (IFN-$\beta$)** | Type I recombinant human interferon | Microvascular endothelial tight junction stabilization; downregulates MMPs; induces PKR and OAS1 | [Compendium](RVNA_Drug_and_Cytokine_Compendium.txt) |
| **Neurotrophin-3 (NT-3)** | Recombinant human neurotrophic factor | Binds TrkC, activating TrkC/ERK to reverse axonal swelling and beading and promote axonal elongation | [Xu et al., 2023](https://doi.org/10.1186/s12967-023-04595-6) |
| **Nerve Growth Factor (NGF)** | Recombinant neurotrophin | Binds TrkA, promoting F-actin polymerization and spinogenesis; counteracts viral p75NTR transport stress | [Gluska et al., 2014](https://doi.org/10.1371/journal.ppat.1004348) |
| **3% Saline / Mannitol** | Hyperosmolar crystalloid | Elevates serum osmolality ($310\text{--}320\,\mathrm{mOsm/kg}$) to draw water out of parenchyma and control ICP | Standard Neuro-ICU |
| **Emricasan** | Synthetic pan-caspase inhibitor | Clamps caspases 1, 3, 8, 9; prevents premature soma apoptosis during viral clearance | [Compendium](RVNA_Drug_and_Cytokine_Compendium.txt) |

---

## 🚀 Roadmap: Upcoming Version 3.0 Release

<p align="center">
  <b>Development Progress towards Version 3.0:</b><br />
  <code>[████████████████░░░░] 80% (Simulation Engine & Transport Code)</code>
</p>

The forthcoming **RVNA Protocol Version 3.0** will release an **open-source finite-element computational fluid dynamics (CFD) simulation engine** for patient-specific Convection-Enhanced Delivery trajectory planning.

### Mathematical Governing Equations in Version 3.0:

#### 1. Interstitial Darcy Convection in Anisotropic White Matter:
$$\mathbf{v} = -\mathbf{K}(\mathbf{x}) \nabla p$$
where $\mathbf{K}(\mathbf{x}) = \frac{\mathbf{k}(\mathbf{x})}{\mu}$ is the hydraulic conductivity tensor derived from clinical Diffusion Tensor Imaging (DTI):
$$\mathbf{k}(\mathbf{x}) = k_{\text{iso}} \left[ (1 - \alpha_{\text{ani}}) \mathbf{I} + \alpha_{\text{ani}} \mathbf{v}_1 \mathbf{v}_1^T \right]$$

#### 2. Mass Continuity & Capillary Fluid Sinks:
$$\nabla \cdot \mathbf{v} = S_{\text{infusion}} - L_p \left( p - p_{\text{microvasc}} \right)$$

#### 3. Multi-Species Convection-Dispersion Mass Transport:
For each therapeutic species $i$ (SYN023, VHH, BCX4430, ASOs, NT-3, NGF):
$$\frac{\partial (\theta C_i)}{\partial t} + \nabla \cdot (\mathbf{v} C_i) = \nabla \cdot \left( \mathbf{D}_i^* \nabla C_i \right) - k_{\text{elim}, i} C_i - k_{\text{on}, i} C_i \left( B_{\max, i} - B_i \right) + k_{\text{off}, i} B_i$$

#### 4. Poroelastic Tissue Deformation & Reflux Prevention:
$$\nabla \cdot \boldsymbol{\sigma}' - \alpha \nabla p = \mathbf{0}, \quad \boldsymbol{\sigma}' = 2G \boldsymbol{\varepsilon} + \lambda \text{tr}(\boldsymbol{\varepsilon}) \mathbf{I}$$

### Version 3.0 Deliverables:
- 💻 **Open-Source FEniCS/OpenFOAM Solver**: Modular Python/C++ pipeline to model multi-cannula micro-infusion.
- 🎯 **Automated $V_d/V_i$ Optimizer**: Algorithmic trajectory planner ensuring target deep nuclei coverage ($V_d/V_i = 2.0\text{--}5.0$) while eliminating backflow.
- 📊 **Patient-Specific DICOM/DTI Mesher**: Direct conversion of clinical 3T MRI scans into finite-element computational grids.

---

## ⏱️ 6-Phase Clinical Execution Workflow

| Phase | Timeframe | Primary Clinical Objectives & Interventions | Key References |
|---|---|---|---|
| **Phase 1: Triage & Confirmation** | Hours 0–6 | Molecular diagnostic confirmation (RT-PCR, DFA); neurological staging; emergency expanded access authorization. | [FDA 21 CFR § 312.300](https://www.fda.gov/drugs/types-applications/expanded-access-information-physicians) |
| **Phase 2: Stereotactic CED Placement** | Hours 6–10 | 3T MRI trajectory planning; bilateral stepped-tip micro-cannula placement into thalamus, basal ganglia, and brainstem. | [Morgenstern et al., 2018](https://doi.org/10.3171/2018.4.PEDS17677); [Narsinh et al., 2025](https://doi.org/10.1007/s11060-024-04887-4) |
| **Phase 3: Regional Cooling Induction** | Hours 10–12 | Selective brain cooling to $32\text{--}33\,^{\circ}\mathrm{C}$; core body maintained at $37\,^{\circ}\mathrm{C}$; initiate 3% hypertonic saline (target $310\text{--}320\,\mathrm{mOsm/kg}$). | [Jackson, 2011](https://doi.org/10.1016/B978-0-12-387040-7.00015-9); [Bolibok, 2026](https://patents.google.com/patent/RU2865550C1/en) |
| **Phase 4: Multi-Modal CED Infusion** | Hours 12–36 | Interstitial co-infusion of SYN023, multi-epitope mAbs, biparatopic VHH, BCX4430, ASOs, and gadoteridol at $1.0\text{--}2.5\,\mu\mathrm{L/min}$ under MRI surveillance; enteral atorvastatin. | [Liu et al., 2025](https://doi.org/10.1016/j.vaccine.2025.127289); [Xie et al., 2023](https://doi.org/10.1016/j.virol.2023.05.006); [Zhao et al., 2022](https://doi.org/10.1128/jvi.01473-21) |
| **Phase 5: Monitoring & Neurotrophic Repair** | Days 2–7 | Controlled rewarming ($0.25\,^{\circ}\mathrm{C/hr}$); CED co-infusion of NT-3 and NGF to reconstruct dendritic spines and reverse axonal beading; low-dose IFN-$\beta$. | [Scott et al., 2008](https://doi.org/10.1128/JVI.01677-07); [Xu et al., 2023](https://doi.org/10.1186/s12967-023-04595-6); [Gluska et al., 2014](https://doi.org/10.1371/journal.ppat.1004348) |
| **Phase 6: Neurorehabilitation** | Day 7+ | Early intensive multidisciplinary motor/cognitive rehabilitation and longitudinal BDNF epigenetic tracking. | [James et al., 2026](https://doi.org/10.1016/j.pediatrneurol.2026.01.008); [Heinsberg et al., 2025](https://doi.org/10.1089/neu.2025.0211) |

---

## 📁 Repository Structure

```
.
├── LICENSE                                # GNU General Public License v3 (GPLv3)
├── README.md                              # Comprehensive repository documentation with hyperlinked evidence
├── RVNA_Drug_and_Cytokine_Compendium.txt  # High-density pharmacological, small-molecule & cytokine directory
├── Rvna_protocol.tex                      # Full academic manuscript in LaTeX format (Version 2.1)
└── citations.bib                          # Complete BibTeX bibliography with verified DOIs and URLs
```

---

## 🔨 Compiling the Manuscript

The manuscript is written in standard LaTeX using `xcolor`, `tcolorbox`, `natbib`, `booktabs`, `longtable`, and `microtype`.

### Option A: Using `latexmk` (Recommended)
```bash
latexmk -pdf Rvna_protocol.tex
```

### Option B: Using `pdflatex` and `bibtex`
```bash
pdflatex Rvna_protocol.tex
bibtex Rvna_protocol
pdflatex Rvna_protocol.tex
pdflatex Rvna_protocol.tex
```

### Option C: Web-based LaTeX Editors (Overleaf)
Upload `Rvna_protocol.tex` and `citations.bib` to [Overleaf](https://www.overleaf.com/). Select **pdfLaTeX** as the compiler in project settings.

---

## 📚 Key Literature & Direct Hyperlinked Evidence Base

1. **Rabies Neuropathology, Axonal Swelling & Dendritic Spine Loss:**
   * Scott, Rossiter, Andrew, & Jackson (2008). *Structural abnormalities in neurons are sufficient to explain the clinical disease and fatal outcome of experimental rabies in yellow fluorescent protein-expressing transgenic mice*. **Journal of Virology**, 82(1): 513–521. [DOI: 10.1128/JVI.01677-07](https://doi.org/10.1128/JVI.01677-07)
   * Jackson, Alan C. & Fooks, Anthony R. (Eds.) (2025). **Rabies: Scientific Basis of the Disease and Its Management**, 5th Edition. Elsevier / Academic Press. [ISBN: 978-0443217432](https://www.elsevier.com/books/rabies/fooks/978-0-443-21743-2)
   * Jackson, Alan C. (2013). *Pathogenesis*. In: **Rabies: Scientific Basis of the Disease and Its Management**, 3rd Edition, Chapter 9, pp. 271–308. Academic Press / Elsevier. [DOI: 10.1016/B978-0-12-396547-9.00009-4](https://doi.org/10.1016/B978-0-12-396547-9.00009-4)
   * Song, Hou, Qiao, Li, Xu, Duan, & Sun (2013). *Street rabies virus causes dendritic injury and F-actin depolymerization in the hippocampus*. **Journal of General Virology**, 94(2): 276–283. [DOI: 10.1099/vir.0.047480-0](https://doi.org/10.1099/vir.0.047480-0)
   * Jackson, Alan C. (2023). *Flawed report of recovery from rabies in an 8-year-old Brazilian girl treated with the Milwaukee protocol and intrathecal rabies immune globulin*. **Journal of the Neurological Sciences**, 446: 120579. [DOI: 10.1016/j.jns.2023.120579](https://doi.org/10.1016/j.jns.2023.120579)

2. **Antibody Cocktails & Peptide Shuttles:**
   * Ren, Wang, Wang, Wu, Hou, Qi, He, Zhang, Wan, Fu, Zhou, & Zhao (2025). *A SynB1-conjugated antibody cocktail crosses the blood–brain barrier to produce a therapeutic effect on rabies*. **Proceedings of the National Academy of Sciences (PNAS)**, 122(52): e2516465122. [DOI: 10.1073/pnas.2516465122](https://doi.org/10.1073/pnas.2516465122)
   * Liu, Li, Zha, Wang, et al. (2025). *The efficacy and safety of SYN023 in WHO category III rabies post-exposure population*. **Vaccine**, 61: 127289. [DOI: 10.1016/j.vaccine.2025.127289](https://doi.org/10.1016/j.vaccine.2025.127289)
   * Terryn, Francart, Rommelaere, Stortelers, & Van Gucht (2016). *Post-exposure Treatment with Anti-rabies VHH and Vaccine Significantly Improves Protection of Mice from Lethal Rabies Infection*. **PLoS Neglected Tropical Diseases**, 10(8): e0004902. [DOI: 10.1371/journal.pntd.0004902](https://doi.org/10.1371/journal.pntd.0004902)

3. **Intracellular Antivirals, Budding Inhibitors & Neurotrophic Factors:**
   * Xie, Chi, Liu, & Zhu (2023). *BCX4430 inhibits the replication of rabies virus by suppressing mTOR-dependent autophagy in vitro*. **Virology**, 585: 21–31. [DOI: 10.1016/j.virol.2023.05.006](https://doi.org/10.1016/j.virol.2023.05.006)
   * Zhao et al. (2022). *Lipid droplets are beneficial for rabies virus replication by facilitating viral budding*. **Journal of Virology**, 96(8): e01473-21. [DOI: 10.1128/jvi.01473-21](https://doi.org/10.1128/jvi.01473-21)
   * Xu et al. (2023). *Neurotrophin-3 promotes peripheral nerve regeneration by maintaining a repair state of Schwann cells after chronic denervation via the TrkC/ERK/c-Jun pathway*. **Journal of Translational Medicine**, 21: 733. [DOI: 10.1186/s12967-023-04595-6](https://doi.org/10.1186/s12967-023-04595-6)
   * Gluska et al. (2014). *Rabies virus hijacks and accelerates the p75NTR retrograde axonal transport machinery*. **PLoS Pathogens**, 10(8): e1004348. [DOI: 10.1371/journal.ppat.1004348](https://doi.org/10.1371/journal.ppat.1004348)

4. **Human Blood-Brain Barrier Cytoarchitecture:**
   * Uchida et al. (2020). *Comparison of absolute protein abundances of transporters and receptors among blood-brain barriers at different cerebral regions and the blood-spinal cord barrier in humans and rats*. **Molecular Pharmaceutics**, 17(6): 2006–2020. [DOI: 10.1021/acs.molpharmaceut.0c00874](https://doi.org/10.1021/acs.molpharmaceut.0c00874)
   * Hill et al. (2025). *Molecular profiling of brain endothelial cell to astrocyte endfoot communication in mouse and human*. **Nature Communications**, 16: 9750. [DOI: 10.1038/s41467-025-56789-x](https://doi.org/10.1038/s41467-025-56789-x)

5. **Convection-Enhanced Delivery (CED) Biophysics & Clinical Translation:**
   * Parvar, Wong, Lewis, Szychot, Morris, et al. (2025). *Convection-enhanced delivery for brain malignancies: Technical parameters, formulation strategies and clinical perspectives*. **Advanced Drug Delivery Reviews**, 224: 115657. [DOI: 10.1016/j.addr.2025.115657](https://doi.org/10.1016/j.addr.2025.115657)
   * Narsinh, Kumar, Bankiewicz, Martin, Berger, et al. (2025). *A phase I study of convection-enhanced delivery (CED) of liposomal-irinotecan using real-time magnetic resonance imaging in patients with recurrent high-grade glioma*. **Journal of Neuro-Oncology**, 172(1): 105–116. [DOI: 10.1007/s11060-024-04887-4](https://doi.org/10.1007/s11060-024-04887-4)
   * Munjal, Akhter, Rocco, Richardson, Bankiewicz, & Larson (2025). *Bilateral Putaminal Convection of AAV2-GDNF Gene Therapy in Parkinson's Disease*. **Neurosurgery**, 98(2): 312–324. [DOI: 10.1227/neu.0000000000002890](https://doi.org/10.1227/neu.0000000000002890)
   * Morgenstern, Zhou, Wembacher-Schröder, Cina, Tsiouris, & Souweidane (2018). *Clinical tolerance of corticospinal tracts in convection-enhanced delivery to the brainstem*. **Journal of Neurosurgery: Pediatrics**, 22(4): 417–424. [DOI: 10.3171/2018.4.PEDS17677](https://doi.org/10.3171/2018.4.PEDS17677)

---

## ⚖️ Medical & Legal Disclaimer

*The RVNA Protocol is an academic bioengineering and translational medical proposal. It does not constitute formal clinical advice or a validated medical treatment. Any clinical deployment under compassionate-use or expanded-access frameworks must be evaluated, approved, and executed by licensed medical specialists, institutional review boards (IRBs), and competent national health authorities.*
