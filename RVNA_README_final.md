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

The **Rabies Virtual Neutralising Active (RVNA) Protocol** is an open-access translational biomedical systems architecture proposing a research framework for studying active viral clearance from the central nervous system (CNS) and potential structural recovery following symptomatic rabies virus (RABV) infection. It is a hypothesis-generating proposal, not a validated treatment protocol.

Rabies encephalomyelitis is among the most lethal human infectious diseases, and clinical rabies has an extremely high fatality rate. PEP is designed to prevent infection after exposure; it is not an established treatment for symptomatic CNS rabies. The **Milwaukee Protocol** (an approach that has included induced coma and other intensive therapies) remains controversial. Jackson's 2025 viewpoint argues that it should be abandoned after numerous reported failures, while a 2025 response by Willoughby disputes that interpretation. The evidence therefore supports describing the approach as **unproven and debated**, rather than universally ineffective ([Jackson, 2025](https://doi.org/10.1093/cid/ciaf157); [Willoughby, 2025](https://doi.org/10.1093/cid/ciaf275)).

**Version 2.1** draws on experimental neuropathology showing that rabies can produce relatively limited neuronal cell-body pathology alongside structural abnormalities in neuronal processes, including axonal and dendritic changes and loss of dendritic spines in experimental models ([Scott et al., 2008](https://doi.org/10.1128/JVI.01677-07); [Song et al., 2013](https://doi.org/10.1099/vir.0.047480-0)). These observations motivate the hypothesis that successful viral control could potentially need to be accompanied by rehabilitation or future strategies aimed at structural and functional recovery; whether neurotrophic treatment can accomplish this in rabies has not been established.

> [!IMPORTANT]
> **Translational Reality Check on Peripheral Shuttles:** Ren et al. reported therapeutic effects from a SynB1-conjugated antibody cocktail in a mouse rabies model, including improved survival after intravenous administration. These findings are promising preclinical evidence, but they do not establish human efficacy or safety. Differences in species, biodistribution, BBB transport, dosing, immunogenicity, and toxicity remain to be determined. Direct **Convection-Enhanced Delivery (CED)** is therefore presented here as a proposed experimental delivery strategy, not as a demonstrated necessity.

---

## 🏛️ The Five Core Architectural Pillars

```
+===================================================================================================+
|                                    RVNA PROTOCOL STACK v2.1                                       |
+=========================================+=========================================================+
|  1. CONVECTION-ENHANCED DELIVERY (CED)  |  2. DUAL-COMPARTMENT MULTI-EPITOPE ANTIBODY STACK       |
|     - Direct parenchymal delivery    |     - SYN023: extracellular neutralization candidate     |
|       under positive pressure          |     - Multi-epitope antibodies: escape-resistance hypothesis|
|     - Experimental BBB bypass          |     - VHH: small-format antibody candidate              |
|     - May alter tissue exposure        |     - Broad neutralization is a research objective      |
|     - MRI-guided CED studied           |     - Clinical CNS efficacy remains unestablished      |
+-----------------------------------------+---------------------------------------------------------+
|  3. TARGETED REGIONAL HYPOTHERMIA       |  4. INTRACELLULAR ANTIVIRAL & BUDDING PURGE ARMAMENTARIUM|
|     - Selective cerebral cooling        |     - BCX4430: preclinical antiviral candidate         |
|       is a proposed intervention       |       (evidence is in vitro)                           |
|     - Temperature effects are testable  |     - Atorvastatin: host lipid-metabolism hypothesis   |
|     - Neuroprotection is a hypothesis   |     - ASOs/siRNAs: sequence-specific research tools    |
|     - Systemic temperature is a research variable |     - IFN-beta: mechanistic adjunct hypothesis |
|     - Clinical rabies efficacy unknown  |     - Human safety/efficacy not established             |
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

Earlier descriptions emphasized relatively limited neuronal cell-body injury in rabies, but experimental work has identified structural abnormalities in neuronal processes. In particular, studies in experimental rabies models reported axonal and dendritic changes and reduced dendritic spine density:

> *"Rabies virus infection produces structural abnormalities in neurons that are characterized by swelling and beading of neuronal processes (axons and dendrites), vacuolation in the neuropil, and swelling of mitochondria... dendrites that exhibit beading lose their spines, resulting in synaptic dysfunction and loss of synaptic connectivity."*  
> — **Courtney A. Scott, John P. Rossiter, R. David Andrew, & Alan C. Jackson** ([Journal of Virology, 2008](https://doi.org/10.1128/JVI.01677-07); confirmed in [Jackson, 2013](https://doi.org/10.1016/B978-0-12-396547-9.00008-0); [Jackson, 2020](https://doi.org/10.1016/C2017-0-04754-0); [Jackson & Fooks, 2025](https://www.elsevier.com/books/rabies/fooks/978-0-443-21743-2))

### Pathological Mechanisms:
1. **Focal Axonal Swellings (Beading):** Mitochondrial dysfunction generates reactive oxygen species (ROS) and lipid peroxidation (4-HNE accumulation), producing bead-like varicosities and organellar vacuolation along layer V cortical pyramidal, cerebellar mossy fiber, and brainstem axons.
2. **Dendritic Spine Collapse via F-Actin Depolymerization:** Beaded dendrites rapidly shed dendritic spines due to viral depolymerization of filamentous actin (F-actin), collapsing postsynaptic receptive fields ([Song et al., 2013](https://doi.org/10.1099/vir.0.047480-0)).
3. **Electrical Isolation:** Narrow constrictions between varicosities cause functional and electrical uncoupling of dendrites from neuronal perikarya.

> [!TIP]
> **Research hypothesis:** Experimental neuropathology motivates investigation of whether viral control plus rehabilitation and/or neurotrophic interventions could improve structural and functional recovery. No clinical evidence currently establishes NT-3, NGF, or BDNF as effective treatments for symptomatic rabies.

---

## ⚖️ Translational Critique: Why Systemic Peptide Shuttles Fail in Humans

Preclinical studies by **Ren et al. (PNAS 2025)** ([DOI: 10.1073/pnas.2516465122](https://doi.org/10.1073/pnas.2516465122)) reported an **80% survival rate** in mice treated intravenously at 5 dpi with a triple-mAb cocktail conjugated to the cell-penetrating peptide **SynB1**.

While an important proof-of-concept in mice, **human translation remains uncertain rather than resolved**. The following matrix separates observations that were actually demonstrated from questions that still require experimental study:

| Failure Parameter | Murine Preclinical Model (Ren et al., 2025) | Human Clinical Reality | RVNA Protocol Resolution (CED) |
|---|---|---|---|
| **BBB biology** | Species differences are reported in BBB transporter/receptor profiles | Human and animal barriers differ, but the cited studies do not establish SynB1 failure in humans ([Uchida et al., 2020](https://doi.org/10.1021/acs.molpharmaceut.0c00178); [Hill et al., 2025](https://doi.org/10.1038/s41467-025-65487-4)) | CED could provide a local delivery route; distribution and safety require validation. |
| **Systemic biodistribution** | Mouse biodistribution was measured experimentally | Human exposure cannot be inferred directly from the mouse study | CED is intended to increase local exposure, but cannot guarantee zero systemic distribution. |
| **Toxicity** | Preclinical tolerability was assessed in the mouse study | The claimed human organ toxicity threshold was not demonstrated by the cited rabies study | Toxicity would have to be characterized experimentally for any candidate delivery system. |
| **Stability** | Preclinical pharmacokinetic/biodistribution observations are model-specific | A human SynB1-antibody half-life and linker-cleavage profile are not established by the cited rabies paper | Formulation and stability would require dedicated pharmacology studies. |
| **Immunogenicity** | The antibody constructs used in preclinical experiments have their own species-specific properties | Human anti-drug responses require direct clinical assessment | Humanized candidates such as SYN023 have clinical PEP data, but that does not validate CNS use. |
| **Nanoparticle alternatives** | Experimental delivery platforms require model-specific safety testing | The cited evidence does not justify a universal statement that all such approaches cause neuronal necrosis | Any alternative carrier would require its own biodistribution and toxicity evaluation. |

---

## 💊 Comprehensive Pharmacological Directory

| Therapeutic Agent | Class & Mechanism | Role in RVNA Stack | Reference Evidence |
|---|---|---|---|
| **SYN023** | Recombinant humanized anti-rabies monoclonal antibody mixture | Established evidence is in rabies PEP; CNS treatment remains investigational | [Liu et al., 2025](https://doi.org/10.1016/j.vaccine.2025.127289) |
| **Anti-rabies VHH** | Single-domain antibody fragments ($\sim 15\,\mathrm{kDa}$) | Small-format antibodies are a research candidate for improving tissue access; therapeutic penetration of human synaptic clefts has not been established | [Terryn et al., 2016](https://doi.org/10.1371/journal.pntd.0004902) |
| **Multi-Epitope Cocktail** | Multiple rabies-glycoprotein antibodies | Proposed to broaden neutralization and reduce single-epitope escape; clinical CNS efficacy is unestablished | [Ren et al., 2025](https://doi.org/10.1073/pnas.2516465122) |
| **BCX4430 (Galidesivir)** | Adenosine C-nucleoside analogue with reported anti-rabies activity in vitro | Candidate for preclinical investigation; no established clinical efficacy for symptomatic rabies | [Xie et al., 2023](https://doi.org/10.1016/j.virol.2023.05.012) |
| **Atorvastatin** | HMG-CoA reductase inhibitor | Host lipid-droplet biology provides a mechanistic research hypothesis; therapeutic use in rabies is unestablished | [Zhao et al., 2022](https://doi.org/10.1128/JVI.01473-21) |
| **Custom ASOs / siRNAs** | Sequence-specific nucleic-acid therapeutics | Proposed research tools for testing intracellular viral RNA targeting; no cited clinical rabies evidence | *Not independently verified in the present reference set* |
| **Interferon-Beta (IFN-$\beta$)** | Type I interferon | Included as a mechanistic research candidate because of antiviral signaling; any effect on BBB stability or rabies clearance would require direct testing | *Not independently verified in the present reference set* |
| **Neurotrophin-3 (NT-3)** | Recombinant neurotrophin acting through TrkC signaling | Regenerative effects are supported in peripheral nerve models; application to rabies CNS injury remains a hypothesis | [Xu et al., 2023](https://doi.org/10.1186/s12967-023-04609-2) |
| **Nerve Growth Factor (NGF)** | Recombinant neurotrophin | Rabies-p75NTR transport biology supports mechanistic study; therapeutic NGF benefit in rabies is unestablished | [Gluska et al., 2014](https://doi.org/10.1371/journal.ppat.1004348) |
| **3% Saline / Mannitol** | Hyperosmolar therapies | Generic neurocritical-care options for intracranial-pressure management when clinically indicated; exact targets are patient-specific | Standard neurocritical care |
| **Emricasan** | Pan-caspase inhibition | Experimental anti-apoptotic concept; no cited rabies treatment evidence in this reference set | *Not independently verified in the present reference set* |

---

## 🚀 Roadmap: Upcoming Version 3.0 Release

<p align="center">
  <b>Development Progress towards Version 3.0:</b><br />
  <code>[████████████████░░░░] 80% (Simulation Engine & Transport Code)</code>
</p>

The forthcoming **RVNA Protocol Version 3.0** is proposed as an **open-source finite-element computational fluid dynamics (CFD) research engine** for studying patient-specific CED transport and sensitivity to infusion parameters. It should be regarded as a modeling project rather than a clinically validated planning system.

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

## ⏱️ 6-Phase Hypothetical Translational Workflow

| Phase | Timeframe | Primary Clinical Objectives & Interventions | Key References |
|---|---|---|---|
| **Phase 1: Triage & Confirmation** | Conceptual | Diagnostic confirmation and neurological staging according to established rabies diagnostic practice; regulatory/ethics review would be required before any investigational intervention. | [FDA Expanded Access](https://www.fda.gov/drugs/types-applications/expanded-access-information-physicians) |
| **Phase 2: Experimental Delivery Planning** | Conceptual | Modeling and preclinical assessment of potential CED trajectories and distribution; no specific rabies target map is clinically validated. | [Morgenstern et al., 2018](https://doi.org/10.3171/2018.6.JNS18854); [Parvar et al., 2025](https://doi.org/10.1016/j.addr.2025.115657) |
| **Phase 3: Temperature/Neuroprotection Study** | Conceptual | Evaluate regional cooling and supportive neurocritical-care concepts in appropriate preclinical models; no rabies-specific clinical cooling target is asserted. | *Hypothesis requiring validation* |
| **Phase 4: Multi-Modal Preclinical Evaluation** | Research | Evaluate candidate components individually and in controlled combinations for antiviral activity, distribution, toxicity, and interactions; the source literature does not establish a clinical co-infusion regimen. | [Liu et al., 2025](https://doi.org/10.1016/j.vaccine.2025.127289); [Xie et al., 2023](https://doi.org/10.1016/j.virol.2023.05.012); [Zhao et al., 2022](https://doi.org/10.1128/JVI.01473-21) |
| **Phase 5: Monitoring & Recovery Research** | Research | Monitor neurological function, imaging, virological markers, and safety; investigate neurotrophic and rehabilitation concepts only after preclinical evidence supports progression. | [Scott et al., 2008](https://doi.org/10.1128/JVI.01677-07); [Xu et al., 2023](https://doi.org/10.1186/s12967-023-04609-2); [Gluska et al., 2014](https://doi.org/10.1371/journal.ppat.1004348) |
| **Phase 6: Neurorehabilitation** | Long-term | Standard neurorehabilitation as clinically appropriate, with research measurements of cognition, motor recovery, and other biomarkers where scientifically justified. | *No rabies-specific efficacy claim made here* |

---

## 📁 Repository Structure

```
.
├── LICENSE                                # GNU General Public License v3 (GPLv3)
├── README.md                              # Comprehensive repository documentation with hyperlinked evidence
├── RVNA_Drug_and_Cytokine_Compendium.txt  # High-density pharmacological, small-molecule & cytokine directory
├── RVNA_protocol.tex                      # Full academic manuscript in LaTeX format (Version 2.1)
└── RVNA_references_verified.bib                          # Curated BibTeX bibliography for the manuscript
```

---

## 🔨 Compiling the Manuscript

The manuscript is written in standard LaTeX using `xcolor`, `tcolorbox`, `natbib`, `booktabs`, `longtable`, and `microtype`.

### Option A: Using `latexmk` (Recommended)
```bash
latexmk -pdf RVNA_protocol.tex
```

### Option B: Using `pdflatex` and `bibtex`
```bash
pdflatex RVNA_protocol.tex
bibtex Rvna_protocol
pdflatex RVNA_protocol.tex
pdflatex RVNA_protocol.tex
```

### Option C: Web-based LaTeX Editors (Overleaf)
Upload `RVNA_protocol.tex` and `RVNA_references_verified.bib` to [Overleaf](https://www.overleaf.com/). Select **pdfLaTeX** as the compiler in project settings.

---

## 📚 Key Literature & Direct Hyperlinked Evidence Base

> **Evidence note:** The references below are used according to the scope of the cited study or publication. Preclinical, in-vitro, and technical literature is presented as such and is not treated as evidence of established clinical efficacy for symptomatic CNS rabies.

1. **Rabies Neuropathology, Axonal Swelling & Dendritic Spine Loss:**
   * Scott, Rossiter, Andrew, & Jackson (2008). *Structural abnormalities in neurons are sufficient to explain the clinical disease and fatal outcome of experimental rabies in yellow fluorescent protein-expressing transgenic mice*. **Journal of Virology**, 82(1): 513–521. [DOI: 10.1128/JVI.01677-07](https://doi.org/10.1128/JVI.01677-07)
   * Jackson, Alan C. & Fooks, Anthony R. (Eds.) (2025). **Rabies: Scientific Basis of the Disease and Its Management**, 5th Edition. Elsevier / Academic Press. [ISBN: 978-0443217432](https://www.elsevier.com/books/rabies/fooks/978-0-443-21743-2)
   * Jackson, Alan C., & Fu, Zhen F. (2013). *Pathogenesis*. In **Rabies: Scientific Basis of the Disease and Its Management**, 3rd Edition, Chapter 8, pp. 299–349. Academic Press / Elsevier. [DOI: 10.1016/B978-0-12-396547-9.00008-0](https://doi.org/10.1016/B978-0-12-396547-9.00008-0)
   * Song, Hou, Qiao, Li, Xu, Duan, & Sun (2013). *Street rabies virus causes dendritic injury and F-actin depolymerization in the hippocampus*. **Journal of General Virology**, 94(2): 276–283. [DOI: 10.1099/vir.0.047480-0](https://doi.org/10.1099/vir.0.047480-0)
   * Jackson, Alan C. (2025). *Demise of the Milwaukee Protocol for Rabies*. **Clinical Infectious Diseases**, 81(4): e229–e232. [DOI: 10.1093/cid/ciaf157](https://doi.org/10.1093/cid/ciaf157)
   * Willoughby, Rodney E. (2025). *Premature Demise of the Milwaukee Protocol*. **Clinical Infectious Diseases**, 81(5): e467–e468. [DOI: 10.1093/cid/ciaf275](https://doi.org/10.1093/cid/ciaf275)

2. **Antibody Cocktails & Peptide Shuttles:**
   * Ren, Wang, Wang, Wu, Hou, Qi, He, Zhang, Wan, Fu, Zhou, & Zhao (2025). *A SynB1-conjugated antibody cocktail crosses the blood–brain barrier to produce a therapeutic effect on rabies*. **Proceedings of the National Academy of Sciences (PNAS)**, 122(52): e2516465122. [DOI: 10.1073/pnas.2516465122](https://doi.org/10.1073/pnas.2516465122)
   * Liu, Li, Zha, Wang, et al. (2025). *The efficacy and safety of SYN023 in WHO category III rabies post-exposure population*. **Vaccine**, 61: 127289. [DOI: 10.1016/j.vaccine.2025.127289](https://doi.org/10.1016/j.vaccine.2025.127289)
   * Terryn, Francart, Rommelaere, Stortelers, & Van Gucht (2016). *Post-exposure Treatment with Anti-rabies VHH and Vaccine Significantly Improves Protection of Mice from Lethal Rabies Infection*. **PLoS Neglected Tropical Diseases**, 10(8): e0004902. [DOI: 10.1371/journal.pntd.0004902](https://doi.org/10.1371/journal.pntd.0004902)

3. **Intracellular Antivirals, Budding Inhibitors & Neurotrophic Factors:**
   * Xie, Chi, Liu, & Zhu (2023). *BCX4430 inhibits the replication of rabies virus by suppressing mTOR-dependent autophagy in vitro*. **Virology**, 585: 21–31. [DOI: 10.1016/j.virol.2023.05.012](https://doi.org/10.1016/j.virol.2023.05.012)
   * Zhao et al. (2022). *Lipid droplets are beneficial for rabies virus replication by facilitating viral budding*. **Journal of Virology**, 96(8): e01473-21. [DOI: 10.1128/jvi.01473-21](https://doi.org/10.1128/JVI.01473-21)
   * Xu et al. (2023). *Neurotrophin-3 promotes peripheral nerve regeneration by maintaining a repair state of Schwann cells after chronic denervation via the TrkC/ERK/c-Jun pathway*. **Journal of Translational Medicine**, 21(1): 733. [DOI: 10.1186/s12967-023-04609-2](https://doi.org/10.1186/s12967-023-04609-2)
   * Gluska et al. (2014). *Rabies virus hijacks and accelerates the p75NTR retrograde axonal transport machinery*. **PLoS Pathogens**, 10(8): e1004348. [DOI: 10.1371/journal.ppat.1004348](https://doi.org/10.1371/journal.ppat.1004348)

4. **Human Blood-Brain Barrier Cytoarchitecture:**
   * Uchida et al. (2020). *Comparison of absolute protein abundances of transporters and receptors among blood-brain barriers at different cerebral regions and the blood-spinal cord barrier in humans and rats*. **Molecular Pharmaceutics**, 17(6): 2006–2020. [DOI: 10.1021/acs.molpharmaceut.0c00178](https://doi.org/10.1021/acs.molpharmaceut.0c00178)
   * Hill et al. (2025). *Molecular profiling of brain endothelial cell to astrocyte endfoot communication in mouse and human*. **Nature Communications**. [DOI: 10.1038/s41467-025-65487-4](https://doi.org/10.1038/s41467-025-65487-4)

5. **Convection-Enhanced Delivery (CED) Biophysics & Clinical Translation:**
   * Parvar, Wong, Lewis, Szychot, Morris, et al. (2025). *Convection-enhanced delivery for brain malignancies: Technical parameters, formulation strategies and clinical perspectives*. **Advanced Drug Delivery Reviews**, 224: 115657. [DOI: 10.1016/j.addr.2025.115657](https://doi.org/10.1016/j.addr.2025.115657)
   * Narsinh et al. (2025). *A phase I study of convection-enhanced delivery (CED) of liposomal-irinotecan using real-time magnetic resonance imaging in patients with recurrent high-grade glioma*. **Journal of Neuro-Oncology**, 172(1): 219–227. Used here as technical CED precedent rather than as evidence for rabies treatment. [DOI: 10.1007/s11060-024-04904-y](https://doi.org/10.1007/s11060-024-04904-y)
   * Munjal et al. (2026). *Bilateral Putaminal Convection of Adeno-Associated Virus Vector Serotype 2 Glial Cell Line-Derived Neurotrophic Factor Gene Therapy in Parkinson's Disease May Provide Glial Cell Line-Derived Neurotrophic Factor Transgene Expression to Caudate Nucleus: Potential Role of Perivascular and Other Low Resistance Leakage Pathways*. **Neurosurgery**, 98(6): 1241–1246. [DOI: 10.1227/neu.0000000000003729](https://doi.org/10.1227/neu.0000000000003729)
   * Morgenstern et al. (2018). *Clinical tolerance of corticospinal tracts in convection-enhanced delivery to the brainstem*. **Journal of Neurosurgery**, 131(6): 1812–1818. [DOI: 10.3171/2018.6.JNS18854](https://doi.org/10.3171/2018.6.JNS18854)

---
