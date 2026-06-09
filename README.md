# Mahdi Akbarzadeh

**Assistant Professor of Biostatistics**
**Statistical Genetics · Precision Medicine Informatics · Genomic Reporting Systems**

I design reproducible and uncertainty-aware genomic reporting workflows for precision medicine, including polygenic risk scores, pharmacogenomics, ancestry/contextual population structure, genotype quality control, and allele harmonization.

My goal is to connect **statistical genetics** with **production-grade reporting systems** that are transparent, auditable, portable, and clinically cautious.

---

## Current Portfolio Direction

I am building a public portfolio of synthetic-data genomic reporting projects focused on:

* Genotype QC and harmonization utilities
* Genomic report data bundle architecture
* Pharmacogenomics report engines
* PRS validation and calibration workflows
* Ancestry uncertainty and reference-panel bias reporting
* Bioinformatics SaaS architecture for genomic report generation

---

## Focus Areas

* Statistical genetics and genetic epidemiology
* Polygenic risk scores and genomic prediction
* Pharmacogenomics and clinical genomic interpretation
* GWAS, Mendelian randomization, and post-GWAS analysis
* Population structure, ancestry-aware analysis, and uncertainty-aware reporting
* Genotype QC, allele harmonization, and genome-build control
* Reproducible pipelines for precision medicine and translational bioinformatics

---

## What I Build

I design workflows that transform raw or semi-processed genomic data into structured, validated, and interpretable outputs.

Typical workflow architecture:

```text
Genotype / sequencing-derived input
→ input validation
→ genotype QC
→ genome-build control
→ allele and variant harmonization
→ reference overlap audit
→ analysis modules
→ uncertainty and limitation checks
→ report data bundle
→ HTML / PDF / API-ready report
```

Core principles:

* Reproducibility by default
* Transparent quality control
* Genome-build and allele-harmonization awareness
* Explicit uncertainty and limitation reporting
* Clinically cautious interpretation
* Portable and Docker-ready workflows
* Separation between raw computational outputs and final report rendering

---

## Technical Directions

### Genotype QC and Harmonization

Building utilities for:

* Genome TXT, PLINK, and VCF-style input validation
* Duplicate variant detection
* Missingness and call-rate summaries
* Genome-build declaration checks
* Strand ambiguity handling
* Allele matching and harmonization readiness
* Technical HTML reporting

### Genomic Report Bundle Architecture

Designing a structured interface between computational modules and final report generation:

```text
report_data_bundle/
├── manifest/
├── qc/
├── overlap/
├── harmonization/
├── module_status/
├── prs/
├── pgx/
├── ancestry/
├── uncertainty/
├── limitations/
├── figures/
├── tables/
├── render_decision/
└── logs/
```

The goal is to make genomic reports auditable, reproducible, and suitable for research-grade or clinical-facing workflows.

### Pharmacogenomics Reporting

Developing demonstration frameworks for:

* Genotype-to-phenotype interpretation
* Drug-gene rule tables
* Rule provenance and versioning
* Reportable and non-reportable variant logic
* Clinically cautious pharmacogenomic report generation

### PRS Validation

Developing workflows for evaluating polygenic risk score performance using:

* Association models
* Discrimination metrics
* Calibration summaries
* Risk stratification
* Population portability warnings
* Clear limits on clinical interpretation

### Ancestry and Population Structure

Working on uncertainty-aware ancestry and population-structure interpretation using:

* PCA and projection-based context
* Reference-panel-dependent interpretation
* Genetic similarity rather than deterministic identity labels
* Explicit uncertainty and reference-bias reporting

---

## Technical Stack

**Languages and analysis**

* R
* Python
* Shell scripting
* SQL
* Quarto / R Markdown

**Genomics and statistical genetics**

* GWAS
* PRS
* Mendelian randomization
* Pharmacogenomics
* Population structure analysis
* Genotype QC and harmonization

**Engineering and reproducibility**

* Docker
* Git / GitHub
* Reproducible pipelines
* HTML reporting
* Modular workflow design
* Validation logs and audit tables

---

## Featured Project Roadmap

The following portfolio projects are being developed as public, synthetic-data demonstrations:

| Project                           | Purpose                                                                   |
| --------------------------------- | ------------------------------------------------------------------------- |
| `genotype-qc-harmonization-utils` | Genotype input validation, QC, build control, and harmonization readiness |
| `genomic-report-bundle-spec`      | Standardized report data bundle schema and validator                      |
| `pgx-report-engine-demo`          | Synthetic pharmacogenomics report engine with rule provenance             |
| `prs-validation-workbench`        | PRS evaluation, calibration, and clinical-readiness reporting             |
| `ancestry-uncertainty-framework`  | Uncertainty-aware ancestry and population-structure reporting             |
| `bioinformatics-saas-template`    | Minimal API, job, and report architecture for genomic reporting platforms |

---

## Scientific Reporting Philosophy

Genomic reports should not be black boxes.

A scientifically responsible genomic reporting system should make clear:

* What data were analyzed
* What passed QC and what failed
* Which genome build and variant identifiers were used
* How alleles were harmonized
* Which modules were reportable
* Which modules were skipped or downgraded
* What uncertainty remains
* What the report must not be used to claim

This is especially important for PRS, pharmacogenomics, ancestry interpretation, and any clinical or customer-facing genomic report.

---

## Contact

* GitHub: [@akbarzadehms](https://github.com/akbarzadehms)
* Email: [akbarzadeh.ms@gmail.com](mailto:akbarzadeh.ms@gmail.com)

---

**Created by: Mahdi Akbarzadeh**

