# Hello there! Welcome! 👋

My name is **Carla Rodrigues de Moraes**.

---

## 🧬 Bioinformatics Researcher in Training

**Clinical Translational Bioinformatics**  
Focus: Lynch Syndrome, Variant Interpretation & NGS Analysis

*Building open-source tools for clinical genomics*

---

## 🔬 Research Interests

- Clinical Variant Interpretation (ACMG/AMP 2015)
- RNA-Seq Analysis & Differential Gene Expression
- NGS Data Analysis & Quality Control
- Mismatch Repair (MMR) Genes & Lynch Syndrome
- Reproducible Bioinformatics Pipelines
- Machine Learning in Genomics

---
## 🧬 Research Focus

Lynch Syndrome & Mismatch Repair (MMR) Genes

| Gene | Role | Focus |
|------|------|-------|
| **MLH1** | Protein-protein interactions | Primary mismatch recognition |
| **MSH2** | Mismatch recognition complex | DNA damage detection |
| **MSH6** | Fine-tuning detection | Smaller loop recognition |
| **PMS2** | Endonuclease activity | ⭐ Pseudogene interference (my focus) |
| **EPCAM** | Regulatory control | MSH2 expression regulation |

**Related Expertise**: ACMG/AMP 2015 Standards | ClinVar | InSiGHT Database | NGS Analysis

---

## 💻 Technical Skills

| Category | Proficiency |
|----------|------------|
| **Languages** | Python, R, Bash, SQL |
| **Bioinformatics** | RNA-Seq, NGS, Variant Calling, VCF Analysis, Quality Control |
| **Tools & Platforms** | Git, GitHub, Docker, Linux, VSCode, Jupyter Notebooks |
| **Analysis & Visualization** | Statistical Analysis, Data Visualization, Exploratory Data Analysis |
| **Databases & APIs** | ClinVar, gnomAD, InSiGHT, TCGA, GTEx, ensembl |
| **Methodologies** | Test-Driven Development (TDD), Reproducible Research, Clinical Compliance |

---

## 📊 Featured Projects

### VariantFlow-MMR 🧬

**Clinical-Grade QC Pipeline for Lynch Syndrome Variant Analysis**

Open-source Python tool for Lynch Syndrome variant interpretation with specialized focus on PMS2 pseudogene detection and ACMG/AMP 2015 evidence collection.

**Technical Stack**
- Python 3.9+ | TDD with pytest | Type Hints (100%)
- 35+ Unit Tests | ~85% Code Coverage
- Clinical Compliance: CAP/CLIA/ISO 15189

**Core Modules**
- **PMS2Assessor**: Detects pseudogene interference in critical regions
- **ACMGEvidenceCollector**: Automated ACMG/AMP 2015 evidence gathering
- **AuditTrail**: Reproducible clinical-grade logging with SHA256 verification

**Quick Example**

```bash
# Input: VCF file with PMS2 variant
variantflow --vcf sample.vcf --gene PMS2 --output results.json

# Output: Risk assessment + ACMG evidence
{
  "variant": "PMS2:chr7:6012876:C>T",
  "pseudogene_risk": "CRITICAL",
  "acmg_criteria": ["PVS1", "PM2"],
  "interpretation": "Likely Pathogenic (requires geneticist review)",
  "validation_recommended": "Sanger sequencing"
}
```

**Repository & Documentation**
- [→ Main Repository](https://github.com/carla-bioinfo/-variant-flow-mmr)
- [→ Examples & Test Data](https://github.com/carla-bioinfo/-variant-flow-mmr/tree/master/examples)
- [→ Course Documentation](https://github.com/carla-bioinfo/-variant-flow-mmr/blob/master/CURSO_ETAPA_3_PARTE_2_COMPLETO.md)
- [→ Project Summary](https://github.com/carla-bioinfo/-variant-flow-mmr/blob/master/VARIANTFLOW_RESUMO_ETAPA_3_PARTE_2.md)

---

### crisp-mmr-explorer 🔍

**Bioinformatics Platform for MMR & Lynch Syndrome Analysis**

Exploratory analysis and visualization tools for Lynch Syndrome genomic data.

[→ Repository](https://github.com/carla-bioinfo/crisp-mmr-explorer)

---

## 🔬 Selected Analyses & Learning Projects

### RNA-Seq of Lynch Syndrome (TCGA-COAD) *In Progress*
- **Dataset**: 540 colorectal cancer samples, 54,675 genes
- **Objective**: Identify gene expression patterns in MMR-deficient

- 🧬 Research Focus

Lynch Syndrome & Variant Interpretation
🔬 Location

Brasil
📚 Currently Learning

• Advanced bioinformatics pipelines

• Machine learning in genomics

• Clinical-grade software engineering

• Statistical methods for population genetics
🌟 Values

Precision, reproducibility, biological accuracy

---

## 📈 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=carla-bioinfo&show_icons=true&theme=dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=carla-bioinfo&layout=compact&theme=dark&hide_border=true)

---

## 📚 Resources & Learning

- **ACMG/AMP 2015**: [Standards for variant interpretation](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4544753/)
- **InSiGHT Database**: [Lynch Syndrome variants](https://www.insightdatabase.org/)
- **ClinVar**: [Variant interpretation database](https://www.ncbi.nlm.nih.gov/clinvar/)
- **TCGA Project**: [Public genomic datasets](https://www.cancer.gov/ccg/research/genome-sequencing/tcga)

---

## 🤝 Get in Touch

- **Email**: carlabio.biomol@gmail.com
- **Location**: Brasil
- **LinkedIn**: [in/carla-bioinfo](https://linkedin.com/in/carla-bioinfo)

---

**Last Updated**: June 2026  
**Currently Building**: VariantFlow-MMR v0.2.0 🚀

⭐ If you find my work useful, please consider giving my repositories a star!
