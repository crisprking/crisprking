<div align="center">

# Abraham Trueba

**Computational biology · drug-target discovery · open science**
Chemical biologist &amp; bioinformatician · MD in progress

UC Berkeley, Chem Bio · Brandeis, MS Bioinformatics · UAG International MD (MS1)

[**▶ View the full portfolio site**](https://crisprking.github.io) &nbsp;·&nbsp; [Email](mailto:abrahamtrueba@berkeley.edu)

`reproducible · SHA-locked · nulls published`

</div>

---

## Is the drug target real?

I build open-source computational pipelines that interrogate whether a drug target is **actually real** — and try as hard to falsify a hypothesis as to confirm it. Every project ships a **pre-registered hypothesis**, **content-addressed (SHA-locked) verdicts** so results can't quietly drift, and **null results published** next to the positive ones. Most of it runs end-to-end on **free Kaggle GPUs**.

> pre-registered hypotheses · content-addressed verdicts · gaps documented, not smoothed · free compute

---

## 🔬 What I'm working on

- **Nav1.7 (SCN9A) — the genetic–pharmacological asymmetry of a "perfect" pain target.** Why lifelong genetic loss of Nav1.7 abolishes pain at no cardiovascular cost, yet acute pharmacological block keeps failing in the clinic — biophysics, expression, and human-genetics arms converging on a two-sided constraint. → [`crisprking/nav17-asymmetry`](https://github.com/crisprking/nav17-asymmetry)
- **Medical school — MS1, UAG International MD.** Training clinically while keeping an active open-source computational research line.
- **Open drug-target auditing.** Extending [`falsifiable-targets`](https://github.com/crisprking/falsifiable-targets) — pre-registered, SHA-locked verdicts on whether a target's genetics actually support the proposed direction of effect.

---

## 🧪 Frameworks &amp; methods

*Reusable tools for deciding whether a target — or a model's claim about it — can be trusted.*

| Repo | Signal | What it does |
|---|---|---|
| [**falsifiable-targets**](https://github.com/crisprking/falsifiable-targets) | `83% acc · 50% cov` | Content-addressed audit engine for drug-target direction-of-effect (inhibit vs. activate), built on Open Targets colocalization and benchmarked against approved drug–target pairs — with its failure modes documented, not hidden. Production layer: batch auditing, Nextflow + Snakemake DAGs, Docker image. **Known gaps: 3 documented failure modes.** |
| [**esm-trust**](https://github.com/crisprking/esm-trust) | `self-consistency ≠ accuracy` | When can you trust ESM-C's zero-shot variant-effect rankings — and when can't you? A reproducible benchmark showing a model's self-consistency across sizes does *not* predict its accuracy, plus a calibration tool. |
| [**nav17-asymmetry**](https://github.com/crisprking/nav17-asymmetry) | `Nav1.7 · SCN9A` | Why the best genetically validated pain target keeps failing in the clinic. Argues a *genetic–pharmacological asymmetry*: lifelong genetic loss is cardiovascular-silent, acute block causes on-target autonomic toxicity. Single-cell atlas, a leaky homeostatic-compensation model, and gnomAD / ClinVar / Open Targets genetics. |

## 🎯 Target-discovery pipelines

*Public data to a defensible shortlist, end-to-end, on free compute.*

| Repo | Signal | What it does |
|---|---|---|
| [**t1d-celltype-of-action**](https://github.com/crisprking/t1d-celltype-of-action) | `21 calls · 145 loci` | Maps type-1-diabetes GWAS loci to the pancreatic cell types they likely act in, using τ-based cell-type specificity in the HPAP scRNA-seq atlas, cross-validated against autoantibody-positive pre-clinical change. |
| [**madurella-target-discovery**](https://github.com/crisprking/madurella-target-discovery) | `10,707 → 7` | A standard ChEMBL-driven target pipeline on *Madurella mycetomatis*, a neglected fungal pathogen nobody had mapped — and it catches its own artifact: the "top" gene was really 384 duplicate records of HDAC4. |
| [**cruzain-in-silico-pipeline**](https://github.com/crisprking/cruzain-in-silico-pipeline) | `8 stages · cruzain` | Eight-stage open drug-discovery pipeline for Chagas disease targeting the *T. cruzi* protease cruzain: three parallel scoring tracks fused into a consensus, a selectivity counter-screen against three human cathepsins, ADMET filtering. Runs on a free Kaggle T4. |
| [**enpp1**](https://github.com/crisprking/enpp1) | `selectivity counter-screen · ENPP1` | Structure-based paralog selectivity counter-screen for the immuno-oncology target ENPP1: dock candidates into ENPP1 and its cousins *ENPP2 (autotaxin)* and *ENPP3* with one identical zinc-centered box, rank by cross-paralog margin. The top affinity binder reversed to an off-target liability. Runs on a free Kaggle T4. |
| [**degradomap**](https://github.com/crisprking/degradomap) | `PROTAC · E3` | Empirical evaluation of which public-data features actually predict PROTAC E3-ligase tractability. |

## 🛠 Tools

[ncbi-bioscraper](https://github.com/crisprking/ncbi-bioscraper) (zero-cost PubMed + OpenAlex + open-access full-text mining) · [target-confidence-card](https://github.com/crisprking/target-confidence-card) · [miniprotein_genai](https://github.com/crisprking/miniprotein_genai) · [MCAT-study-app](https://github.com/crisprking/MCAT-study-app) (MCAT concept-practice app for premeds)

---

## 🎓 Education

- **MD — in progress** · UAG International MD · MS1
- **MS, Bioinformatics** · Brandeis · 2025 · GPA 3.85 — biomathematics, bioinformatics, and computational biology.
- **BS, Chemical Biology** · UC Berkeley · 2020 · GPA 3.67 — genetics, genomics &amp; cell biology; immunochemistry and cell culture. Thesis: *Refining the epigenome through CRISPR-mediated techniques to establish a programmable system for transcriptional memory.*

<details>
<summary><b>Research, lab &amp; industry experience</b></summary>

**Research &amp; lab**
- **2018–21 — Pines Lab Undergraduate Researcher, UC Berkeley.** Zero- to ultra-low-field (ZULF) NMR and imaging; laser-polarized xenon molecular sensors, solid-state NMR of NV-diamond materials, optical hyperpolarization, miniaturized NMR detectors for portable bioimaging.
- **2021–22 — Medical Technician, Discover Labs.** Real-time PCR panels and automated RNA extraction under CLIA/HIPAA, antimicrobial-treatment guidance, QC-workflow improvements.
- **2022 — Microbiology Technician, Varian.** Non-invasive cancer therapies; viable / non-viable cleanroom monitoring under GLP with supporting analysis.
- **2018 — Research Assistant, Tecnológico de Monterrey (Centro del Agua).** Microalgae bioprocessing: spirulina cultivation, phycocyanin and DHA microencapsulation, a microalgae-based UV-protective cream.

**Industry &amp; commercial**
- **2024–25 — Inside Sales Specialist, EditCo Bio (CRISPR).** Sole inside rep across 30 states — a bench-trained scientist supporting researchers through their experiments.
- **2022–23 — Sales Account Manager, GenScript.** Synthetic-biology portfolio; custom gene-synthesis projects across pharma, biotech, and academia.
- **2022 — Consultant, PSC Biotech (Moderna).** IQ/OQ equipment qualification, sterilizer SOPs, cleanroom QC under FDA and SAP guidelines.
- **2020–22 — Founder &amp; CEO, Creative Science.** Cross-border resale of lab and medical equipment (US / Mexico).

</details>

---

## How I work

▸ Pre-registered, falsifiable hypotheses — fixed *before* the analysis runs.
▸ Content-addressed, SHA-locked verdicts, so a result can't silently change.
▸ Refusal-first — the pipeline may say "not enough evidence," and gaps are documented, not smoothed.
▸ Null results shipped next to the positive ones.
▸ Reproducible on free compute (Kaggle T4), in self-contained notebooks.

---

<div align="center">

`stack: python · jupyter / kaggle · nextflow + snakemake · docker`
`data: gnomad · clinvar · open targets · hpap · cellxgene · chembl · esm-c`

**[abrahamtrueba@berkeley.edu](mailto:abrahamtrueba@berkeley.edu) · [github.com/crisprking](https://github.com/crisprking) · [crisprking.github.io](https://crisprking.github.io)**

*// runs on free hardware — verdicts content-addressed — nulls published*

</div>
