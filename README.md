# Abraham Trueba

**Computational biology · Drug-target discovery · Open science**

Chemical biology at UC Berkeley (Cal), bioinformatics at Brandeis, and an incoming MD student (MS1) in UAG's International MD program. I build open-source computational pipelines that ask whether a drug target is actually real — and I try as hard to prove myself wrong as to prove myself right. Every project ships with a pre-registered, falsifiable hypothesis, content-addressed (SHA-locked) verdicts so results can't quietly drift, and null results published alongside the positive ones. Most of it runs end-to-end on free Kaggle GPUs.

**Focus areas:** target validation · direction-of-effect · GWAS locus-to-cell-type mapping · variant-effect model calibration · neglected-disease drug discovery

---

## Selected work

**[falsifiable-targets](https://github.com/crisprking/falsifiable-targets)** — A SHA-locked audit engine for drug-target direction-of-effect (inhibit vs. activate), built on Open Targets colocalization data and benchmarked against 19 approved drug–target pairs. 50% coverage, 83% accuracy on covered calls, and 75% gene-level burden×coloc concordance — with the three failure modes it *can't* yet handle documented rather than hidden. The production layer, [falsifiable-targets-workflow](https://github.com/crisprking/falsifiable-targets-workflow), adds batch auditing, Nextflow + Snakemake DAGs, and a Docker image.

**[nav17-asymmetry](https://github.com/crisprking/nav17-asymmetry)** — Why the best genetically validated pain target keeps failing in the clinic. Makes the case for a *genetic–pharmacological asymmetry*: lifelong genetic loss of Nav1.7 is cardiovascular-silent, while acute pharmacological block causes on-target autonomic toxicity. Single-cell atlas analysis, a leaky homeostatic-compensation model, and gnomAD / ClinVar / Open Targets genetics, converging on three independent 2024 publications.

**[esm-trust](https://github.com/crisprking/esm-trust)** — When can you trust ESM-C's zero-shot variant-effect rankings, and when can't you? A small, reproducible benchmark showing that a model's self-consistency across sizes does *not* predict its accuracy — plus a calibration tool for deciding when to rely on it.

**[t1d-celltype-of-action](https://github.com/crisprking/t1d-celltype-of-action)** — Maps 145 type-1-diabetes GWAS loci to the pancreatic cell types they likely act in, using cell-type specificity (τ-based) in the HPAP scRNA-seq atlas, and cross-validates against autoantibody-positive pre-clinical transcriptional changes. 21 high-confidence calls survive.

**[madurella-target-discovery](https://github.com/crisprking/madurella-target-discovery)** — Runs a standard ChEMBL-driven target pipeline on *Madurella mycetomatis*, a neglected fungal pathogen nobody had mapped — and catches the pipeline's own artifact: the "top" gene was really 384 records of HDAC4. 10,707 proteins triaged down to a hardened 7-gene shortlist, with the audit that caught the error shipped alongside it.

**[cruzain-in-silico-pipeline](https://github.com/crisprking/cruzain-in-silico-pipeline)** — An eight-stage open drug-discovery pipeline for Chagas disease targeting the *T. cruzi* protease cruzain: three parallel scoring tracks fused into a consensus, a selectivity counter-screen against three human cathepsins, and ADMET filtering. Runs on a free Kaggle T4.

**[degradomap](https://github.com/crisprking/degradomap)** — An empirical evaluation of which public-data features actually predict PROTAC E3-ligase tractability.

Also: **[ncbi-bioscraper](https://github.com/crisprking/ncbi-bioscraper)** (zero-cost PubMed + OpenAlex + open-access full-text mining), **[target-confidence-card](https://github.com/crisprking/target-confidence-card)**, **[miniprotein_genai](https://github.com/crisprking/miniprotein_genai)**, and a handful of TypeScript side projects including an [MCAT concept-practice app](https://github.com/crisprking/MCAT-study-app) for premeds.

---

## How I work

- Pre-registered, falsifiable hypotheses — fixed *before* the analysis runs.
- Content-addressed, SHA-locked verdicts, so a result can't silently change.
- Refusal-first: the pipeline is allowed to say "not enough evidence," and gaps are documented rather than smoothed over.
- Null results shipped next to the positive ones.
- Reproducible on free compute (Kaggle T4), in self-contained notebooks.

**Stack:** Python · Jupyter / Kaggle · Nextflow + Snakemake · Docker
**Data:** gnomAD · ClinVar · Open Targets · HPAP · CellxGene · ChEMBL · ESM-C

---

## Elsewhere

- GitHub — [@crisprking](https://github.com/crisprking)
- Write-ups — *add your Substack URL here*
- X — *add your handle here*
