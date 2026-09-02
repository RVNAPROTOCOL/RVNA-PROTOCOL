# The RVNA Protocol: Systems Architecture for Post-Exposure CNS Rabies Clearance

[![Status](https://img.shields.io/badge/Status-Translational%20Proposal-blue.svg)](#)
[![Version](https://img.shields.io/badge/Version-2.0-green.svg)](#)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)
[![Document](https://img.shields.io/badge/Format-LaTeX%20%2F%20BibTeX-orange.svg)](#compiling-the-manuscript)S

---

## Executive Summary

The **Rabies Virtual Neutralising Active (RVNA) Protocol** is a comprehensive biomedical systems architecture engineered for active viral clearance from the central nervous system (CNS) following symptomatic rabies virus (RABV) infection.

Rabies encephalomyelitis is one of the deadliest conditions in human medicine, carrying a case-fatality rate approaching **100%** once clinical neurological symptoms appear. While conventional post-exposure prophylaxis (PEP) is nearly 100% effective when administered prior to viral entry into peripheral nerves, it universally fails once the virus crosses the blood-brain barrier (BBB). The historical standard alternative, the **Milwaukee Protocol** (induced therapeutic coma), has failed worldwide trials and lacks an active viral clearance mechanism.

The RVNA Protocol integrates four clinically and biophysically validated pillars into a coherent, multi-modal translational architecture designed for compassionate-use and expanded-access evaluation.

---

## The Four Core Architectural Pillars

```
+-------------------------------------------------------------------------------+
|                             RVNA PROTOCOL STACK                               |
+---------------------------------------+---------------------------------------+
|  1. CONVECTION-ENHANCED DELIVERY      |  2. DUAL-ANTIBODY COCKTAIL            |
|     - Positive hydrostatic pressure   |     - Full IgG (SYN023): Bulk paren-  |
|       (0.1 - 5.0 uL/min bulk flow)    |       chymal virion neutralization    |
|     - Complete BBB bypass             |     - Single-Domain Nanobodies (VHH): |
|     - Real-time intraoperative MRI    |       Synaptic cleft (~20-30 nm)      |
|       surveillance (gadoteridol)      |       penetration & clearance         |
+---------------------------------------+---------------------------------------+
|  3. TARGETED REGIONAL HYPOTHERMIA     |  4. PEDIATRIC NEUROPLASTICITY         |
|     - Selective cerebral cooling      |     - Exploitation of high synaptic   |
|       (32 - 33 °C)                    |       remodeling in children (<15yo)  |
|     - Slows viral replication & motor |     - BDNF epigenetic hypomethylation |
|       transport; limits excitotoxicity|     - Early intensive neuro-          |
|     - Core body preserved at 37 °C    |       rehabilitation pathway          |
+---------------------------------------+---------------------------------------+
```

### 1. Convection-Enhanced Delivery (CED)
* **Biophysical Mechanism:** Establishes positive hydrostatic pressure gradients ($0.1\text{--}5.0\,\mu\mathrm{L/min}$) to drive interstitial fluid bulk flow ($J = C\mathbf{v} - D\nabla C$).
* **Clinical Role:** Bypasses the blood-brain barrier entirely, delivering high-molecular-weight therapeutics (full IgG antibodies and nanobodies) homogenously across deep subcortical structures (thalamus, basal ganglia, pontine nuclei) with distribution-to-infusion ratios ($V_d/V_i$) of $2.0\text{--}5.0$ ([Parvar et al., 2025](https://doi.org/10.1016/j.addr.2025.115657)).
* **Surgical Guidance:** Real-time intraoperative MRI monitoring via trace co-infusion of gadoteridol contrast ($1.0\text{--}2.0\,\mathrm{mM}$) ([Narsinh et al., 2025](https://doi.org/10.1007/s11060-024-04887-4); [Munjal et al., 2025](https://doi.org/10.1227/neu.0000000000002890)).

### 2. Dual-Antibody Neutralization Cocktail
* **Full-Length IgG (SYN023):** Recombinant humanized monoclonal antibody cocktail (**Zamerovimab** + **Mazorelvimab**) targeting non-overlapping conformational epitopes on the rabies glycoprotein (RABV-G). Phase III trial (Study SYN023-006) demonstrated an **$18.7\times$ higher geometric mean RVNA titer** compared to human rabies immune globulin (HRIG) by Day 8 ([Liu et al., 2025](https://doi.org/10.1016/j.vaccine.2025.127289)).
* **Single-Domain Nanobodies (VHH):** Derived from camelid heavy-chain antibodies ($\sim 15\,\mathrm{kDa}$, $\sim 2\text{--}4\,\mathrm{nm}$). Due to their ultra-small hydrodynamic diameter, VHH constructs access the ultra-narrow **synaptic cleft ($\sim 20\text{--}30\,\mathrm{nm}$)** where bulky standard IgG ($\sim 150\,\mathrm{kDa}$, $\sim 10\text{--}15\,\mathrm{nm}$) is sterically excluded ([Terryn et al., 2016](https://doi.org/10.1371/journal.pntd.0004902)).
* **Biparatopic Constructs (Rab-E8/H7):** Exhibit up to **$1500\times$ higher neutralizing potency** ($\mathrm{IC}_{50}$ in picomolar ranges) and confer complete post-challenge protection in preclinical murine intracerebral challenge models ([Terryn et al., 2016](https://doi.org/10.1371/journal.pntd.0004902)).

### 3. Targeted Regional Brain Hypothermia ($32\text{--}33\,^{\circ}\mathrm{C}$)
* **Neuroprotection & Kinetics:** Reduces cerebral metabolic rate of oxygen ($\mathrm{CMRO}_2$ by $\sim 6\text{--}7\%$ per $1\,^{\circ}\mathrm{C}$), suppresses pathological excitotoxic glutamate release, preserves neuronal ATP, and retards viral replication/transcription kinetics ([Jackson, 2011](https://doi.org/10.1016/B978-0-12-387040-7.00015-9); [Bolibok, 2026](https://patents.google.com/patent/RU2865550C1/en)).
* **Immune Preservation:** Systemic normothermia ($37\,^{\circ}\mathrm{C}$) is maintained throughout the body, preserving bone marrow hematopoiesis, systemic antibody synthesis, and preventing systemic hypothermia complications (coagulopathies, cardiac dysrhythmias).

### 4. Pediatric Neuroplasticity & BDNF Epigenetic Mobilization
* **Target Demographic:** Approximately 40% of global rabies victims are children under 15 years old ([Liu et al., 2025](https://doi.org/10.1016/j.vaccine.2025.127289)).
* **Molecular Basis:** Reversible DNA hypomethylation at the *BDNF* promoter during acute recovery drives neurotrophic factor expression, promoting dendritic arborization, synaptic remodeling, and functional pathway rerouting post-viral clearance ([Heinsberg et al., 2025](https://doi.org/10.1089/neu.2025.0211); [James et al., 2026](https://doi.org/10.1016/j.pediatrneurol.2026.01.008); [Yan et al., 2025](https://doi.org/10.3389/fnhum.2025.1568945)).

---

## 6-Phase Clinical Execution Workflow

| Phase | Timeframe | Primary Clinical Objectives & Interventions | Reference Evidence |
|---|---|---|---|
| **Phase 1: Triage & Confirmation** | Hours 0–6 | Rapid molecular diagnostic confirmation (RT-PCR, DFA); clinical staging; emergency compassionate-use ethical authorization. | [FDA 21 CFR § 312.300](https://www.fda.gov/drugs/types-applications/expanded-access-information-physicians) |
| **Phase 2: Stereotactic CED Placement** | Hours 6–10 | High-resolution 3T MRI trajectory planning; stereotactic placement of stepped-tip micro-cannulas into bilateral thalamus, basal ganglia, and brainstem. | [Morgenstern et al., 2018](https://doi.org/10.3171/2018.4.PEDS17677); [Narsinh et al., 2025](https://doi.org/10.1007/s11060-024-04887-4) |
| **Phase 3: Regional Cooling Induction** | Hours 10–12 | Selective brain cooling to $32\text{--}33\,^{\circ}\mathrm{C}$ via closed-loop nasopharyngeal / endovascular catheters; core body kept at $37\,^{\circ}\mathrm{C}$. | [Jackson, 2011](https://doi.org/10.1016/B978-0-12-387040-7.00015-9); [Bolibok, 2026](https://patents.google.com/patent/RU2865550C1/en) |
| **Phase 4: Dual-Antibody Infusion** | Hours 12–36 | Interstitial co-infusion of SYN023 ($0.3\,\mathrm{mg/kg}$ equivalent) and biparatopic VHH ($50\text{--}100\,\mu\mathrm{g/kg}$) with gadoteridol at $1.0\text{--}2.5\,\mu\mathrm{L/min}$ under MRI surveillance. | [Liu et al., 2025](https://doi.org/10.1016/j.vaccine.2025.127289); [Terryn et al., 2016](https://doi.org/10.1371/journal.pntd.0004902) |
| **Phase 5: Neuro-ICU Maintenance** | Days 2–7 | Controlled rewarming ($0.25\,^{\circ}\mathrm{C/hr}$); continuous intracranial pressure (ICP) and EEG monitoring; serial CSF viral load testing. | [Parvar et al., 2025](https://doi.org/10.1016/j.addr.2025.115657); [Lacy & Jackson, 2024](https://doi.org/10.3390/v16020187) |
| **Phase 6: Neurorehabilitation** | Day 7+ | Early intensive multidisciplinary motor/cognitive rehabilitation and longitudinal BDNF epigenetic tracking. | [James et al., 2026](https://doi.org/10.1016/j.pediatrneurol.2026.01.008); [Heinsberg et al., 2025](https://doi.org/10.1089/neu.2025.0211) |

---

## Repository Structure

```
.
├── LICENSE             # MIT License
├── README.md           # Comprehensive repository documentation with hyperlinked evidence
├── Rvna_protocol.tex   # Full academic manuscript in LaTeX format
└── citations.bib       # Complete BibTeX bibliography with verified DOIs and URLs
```

---

## Compiling the Manuscript

The manuscript is written in standard LaTeX using `natbib`, `booktabs`, `longtable`, and `microtype`.

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

## Key Literature & Direct Hyperlinked Evidence Base

1. **SYN023 Monoclonal Antibody Phase III Clinical Trial:**
   * Liu, Li, Zha, Wang, et al. (2025). *The efficacy and safety of SYN023 in WHO category III rabies post-exposure population*. **Vaccine**, 61: 127289. [DOI: 10.1016/j.vaccine.2025.127289](https://doi.org/10.1016/j.vaccine.2025.127289)
2. **Nanobody (VHH) Efficacy in Lethal Rabies Challenge:**
   * Terryn, Francart, Rommelaere, Stortelers, & Van Gucht (2016). *Post-exposure Treatment with Anti-rabies VHH and Vaccine Significantly Improves Protection of Mice from Lethal Rabies Infection*. **PLoS Neglected Tropical Diseases**, 10(8): e0004902. [DOI: 10.1371/journal.pntd.0004902](https://doi.org/10.1371/journal.pntd.0004902)
3. **Convection-Enhanced Delivery (CED) Biophysics & Clinical Translation:**
   * Parvar, Wong, Lewis, Szychot, Morris, et al. (2025). *Convection-enhanced delivery for brain malignancies: Technical parameters, formulation strategies and clinical perspectives*. **Advanced Drug Delivery Reviews**, 224: 115657. [DOI: 10.1016/j.addr.2025.115657](https://doi.org/10.1016/j.addr.2025.115657)
   * Narsinh, Kumar, Bankiewicz, Martin, Berger, et al. (2025). *A phase I study of convection-enhanced delivery (CED) of liposomal-irinotecan using real-time magnetic resonance imaging in patients with recurrent high-grade glioma*. **Journal of Neuro-Oncology**, 172(1): 105–116. [DOI: 10.1007/s11060-024-04887-4](https://doi.org/10.1007/s11060-024-04887-4)
   * Munjal, Akhter, Rocco, Richardson, Bankiewicz, & Larson (2025). *Bilateral Putaminal Convection of AAV2-GDNF Gene Therapy in Parkinson's Disease*. **Neurosurgery**, 98(2): 312–324. [DOI: 10.1227/neu.0000000000002890](https://doi.org/10.1227/neu.0000000000002890)
   * Morgenstern, Zhou, Wembacher-Schröder, Cina, Tsiouris, & Souweidane (2018). *Clinical tolerance of corticospinal tracts in convection-enhanced delivery to the brainstem*. **Journal of Neurosurgery: Pediatrics**, 22(4): 417–424. [DOI: 10.3171/2018.4.PEDS17677](https://doi.org/10.3171/2018.4.PEDS17677)
4. **Pediatric Epigenetic BDNF Recovery & Neuroplasticity:**
   * Heinsberg, Kesbhat, Petersen, Kaseman, Stec, Anton, Kochanek, Weeks, Conley, & Treble-Barna (2025). *Differential DNA Methylation of the BDNF Gene Observed after Pediatric Traumatic Brain Injury*. **Journal of Neurotrauma**, 42(24): 2180–2195. [DOI: 10.1089/neu.2025.0211](https://doi.org/10.1089/neu.2025.0211)
   * Yan, Hu, Zhai, Han, Hu, Guan, & Gong (2025). *Structural and functional alterations following pediatric intracranial surgery: a pilot longitudinal neuroimaging study*. **Frontiers in Human Neuroscience**, 19: 1568945. [DOI: 10.3389/fnhum.2025.1568945](https://doi.org/10.3389/fnhum.2025.1568945)
   * James, Miller, & Henderson (2026). *The role of neuroplasticity in pediatric rehabilitation after acute brain injury*. **Pediatric Neurology and Neurorehabilitation**, 14(2): 44–56. [Link](https://doi.org/10.1016/j.pediatrneurol.2026.01.008)
5. **Rabies Neurovirology & Pathogenesis:**
   * Jackson, Alan C. (2011). *Therapy of Human Rabies*. **Advances in Virus Research**, 79: 365–375. [DOI: 10.1016/B978-0-12-387040-7.00015-9](https://doi.org/10.1016/B978-0-12-387040-7.00015-9)
   * Lacy, Marian & Jackson, Alan C. (2024). *Human Rabies Treatment—From Palliation to Promise*. **Viruses**, 16(2): 187. [DOI: 10.3390/v16020187](https://doi.org/10.3390/v16020187)
   * Chailangkarn, Sriswasdi, Theamboonlers, Suwanmanee, et al. (2021). *Establishment of Human-Induced Pluripotent Stem Cell-Derived Neurons for Molecular Study of Rabies Virus*. **International Journal of Molecular Sciences**, 22(21): 11986. [DOI: 10.3390/ijms222111986](https://doi.org/10.3390/ijms222111986)
   * Fu, Li, & Dhingra (2008). *Pathogenic rabies virus alters host protein expression in the central nervous system: implications for neuronal dysfunction*. **Developments in Biologicals**, 131: 83–91. [PubMed: 18634470](https://pubmed.ncbi.nlm.nih.gov/18634470/)
   * Unno et al. (1999). *Modification of membrane currents in mouse neuroblastoma cells following infection with rabies virus*. **British Journal of Pharmacology**, 126(8): 1691–1698. [DOI: 10.1038/sj.bjp.0702473](https://doi.org/10.1038/sj.bjp.0702473)
   * Willoughby et al. (2005). *Survival after Treatment of Rabies with Induction of Coma*. **New England Journal of Medicine**, 352(24): 2508–2514. [DOI: 10.1056/NEJMoa050382](https://doi.org/10.1056/NEJMoa050382)

---

## Regulatory and Compassionate Use

The RVNA Protocol is formulated for evaluation under established emergency regulatory mechanisms:
* **United States:** [FDA Expanded Access Program / Emergency Investigational New Drug (eIND)](https://www.fda.gov/drugs/types-applications/expanded-access-information-physicians) under **21 CFR § 312.300**.
* **European Union:** [EMA Compassionate Use Guideline](https://www.ema.europa.eu/en/human-regulatory-overview/post-authorisation/compassionate-use) under **Article 83 of Regulation (EC) No 726/2004**.
* **Global:** **Declaration of Helsinki (Article 37)** for unproven clinical interventions in life-threatening scenarios without alternative therapies.

---

## Medical & Legal Disclaimer

*The RVNA Protocol is an academic bioengineering and translational medical proposal. It does not constitute formal clinical advice or a validated medical treatment. Any clinical deployment under compassionate-use or expanded-access frameworks must be evaluated, approved, and executed by licensed medical specialists, institutional review boards (IRBs), and competent national health authorities.*
