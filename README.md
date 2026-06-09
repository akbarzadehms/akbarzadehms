# Mahdi Akbarzadeh

**Assistant Professor of Biostatistics**  
**Statistical Genetics · Precision Medicine Informatics · Genomic Reporting Systems**

I work at the intersection of **statistical genetics**, **biostatistics**, **translational bioinformatics**, and **reproducible genomic software engineering**.

My current focus is designing scientific-grade workflows that connect genotype, GWAS, PRS, pharmacogenomics, ancestry/contextual population structure, and clinical interpretation into transparent and reproducible reporting systems.

---

## Focus Areas

- Statistical genetics and genetic epidemiology
- Polygenic risk scores and genomic prediction
- Pharmacogenomics and clinical genomic reporting
- Genotype quality control and allele harmonization
- GWAS, Mendelian randomization, and post-GWAS interpretation
- Population structure, ancestry-aware analysis, and uncertainty-aware reporting
- Reproducible pipelines for precision medicine and translational bioinformatics

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

- Reproducibility by default
- Transparent quality control
- Genome-build and allele-harmonization awareness
- Explicit uncertainty and limitation reporting
- Clinically cautious interpretation
- Portable and Docker-ready workflows
- Separation between raw computational outputs and final report rendering

---

## Technical Directions

### Genotype QC and Harmonization

Building utilities for:

- Genome TXT, PLINK, and VCF-style input validation
- Duplicate variant detection
- Missingness and call-rate summaries
- Genome-build declaration checks
- Strand ambiguity handling
- Allele matching and harmonization readiness
- Technical HTML reporting

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

Developing demo frameworks for:

- Genotype-to-phenotype interpretation
- Drug-gene rule tables
- Rule provenance and versioning
- Reportable and non-reportable variant logic
- Clinically cautious PGx report generation

### PRS Validation

Developing workflows for evaluating PRS performance using:

- Association models
- Discrimination metrics
- Calibration summaries
- Risk stratification
- Population portability warnings
- Clear limits on clinical interpretation

### Ancestry and Population Structure

Working on uncertainty-aware ancestry and population-structure interpretation using:

- PCA / projection-based context
- Reference-panel-dependent interpretation
- Genetic similarity rather than deterministic identity labels
- Explicit uncertainty and reference-bias reporting

---

## Technical Stack

**Languages and analysis**

- R
- Python
- Shell scripting
- SQL
- Quarto / R Markdown

**Genomics and statistical genetics**

- GWAS
- PRS
- Mendelian randomization
- Pharmacogenomics
- Population structure analysis
- Genotype QC and harmonization

**Engineering and reproducibility**

- Docker
- Git / GitHub
- Reproducible pipelines
- HTML reporting
- Modular workflow design
- Validation logs and audit tables

---

## Featured Project Roadmap

The following portfolio projects are being developed as public, synthetic-data demonstrations:

| Project | Purpose |
|---|---|
| `genotype-qc-harmonization-utils` | Genotype input validation, QC, build control, and harmonization readiness |
| `genomic-report-bundle-spec` | Standardized report data bundle schema and validator |
| `pgx-report-engine-demo` | Synthetic pharmacogenomics report engine with rule provenance |
| `prs-validation-workbench` | PRS evaluation, calibration, and clinical-readiness reporting |
| `ancestry-uncertainty-framework` | Uncertainty-aware ancestry and population-structure reporting |
| `bioinformatics-saas-template` | Minimal API/job/report architecture for genomic reporting platforms |

---

## Scientific Reporting Philosophy

Genomic reports should not be black boxes.

A scientifically responsible genomic reporting system should make clear:

- What data were analyzed
- What passed QC and what failed
- Which genome build and variant identifiers were used
- How alleles were harmonized
- Which modules were reportable
- Which modules were skipped or downgraded
- What uncertainty remains
- What the report must not be used to claim

This is especially important for PRS, pharmacogenomics, ancestry interpretation, and any clinical or customer-facing genomic report.

---

## Contact

- GitHub: [@akbarzadehms](https://github.com/akbarzadehms)
- Email: akbarzadeh.ms@gmail.com

---

**Created by: Mahdi Akbarzadeh**
