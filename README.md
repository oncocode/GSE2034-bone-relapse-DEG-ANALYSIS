# GSE2034 Breast Cancer Bone Relapse - Differential Gene Expression Analysis

Overview

This project presents a bioinformatics analysis of gene expression data from GSE2034, a publicly available breast cancer dataset from the NCBI Gene Expression Omnibus (GEO).

The analysis focuses on identifying genes and biological pathways associated with bone relapse in breast cancer using differential gene expression analysis and downstream functional enrichment analysis.

This project was developed as a research-oriented bioinformatics portfolio project using R.

---

Research Question

Which genes and biological pathways are differentially expressed in breast cancer samples associated with bone relapse?

The aim is to identify molecular patterns that may help improve understanding of the biological processes associated with breast cancer bone relapse.

---

Dataset

- GEO accession: GSE2034
- Organism: Homo sapiens
- Disease: Breast cancer
- Platform: GPL96 — Affymetrix Human Genome U133A Array
- Data source: NCBI Gene Expression Omnibus (GEO)

The dataset is publicly available through the NCBI GEO database.

Dataset: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE2034

---

Analysis Workflow

The analysis includes the following steps:

1. Retrieval and preparation of the GSE2034 expression dataset
2. Pre-processing and normalization of gene expression data
3. Definition of the comparison groups
4. Differential gene expression analysis
5. Identification of significantly differentially expressed genes
6. Principal component analysis (PCA)
7. MA plot generation
8. Volcano plot generation
9. Heatmap visualization of selected genes
10. Gene Ontology (GO) enrichment analysis
11. KEGG pathway enrichment analysis
12. Export of analysis results and visualizations

---

Statistical Analysis

Differential gene expression analysis was performed using the limma framework in R.

The analysis evaluates differences in gene expression between the relevant breast cancer groups and identifies genes showing statistically significant expression changes.

The exact filtering thresholds and statistical parameters are documented in the analysis script where applicable.

---

Visualizations

The repository contains several visualizations generated during the analysis:

Principal Component Analysis

"GSE2034_PCA_plot.png"

Used to visualize overall variation and clustering patterns among samples.

MA Plot

"GSE2034_MA_plot.png"

Used to visualize the relationship between average expression and differential expression.

Volcano Plot

"GSE2034_volcano_plot.png"

Used to visualize statistical significance and magnitude of differential gene expression.

Heatmap

"GSE2034_top_DEG_heatmap.png"

Used to visualize expression patterns of selected differentially expressed genes across samples.

Functional Enrichment

GO and KEGG dot plots are included to explore biological processes and pathways associated with the identified gene sets.

---

Results

The analysis generated:

- A list of significantly differentially expressed genes
- Summary statistics of the differential expression analysis
- Selected genes for heatmap visualization
- GO enrichment results
- KEGG pathway enrichment results
- PCA, MA, volcano, and heatmap visualizations

The complete numerical results are provided in the CSV files included in this repository.

---

Repository Structure

GSE2034-bone-relapse-DEG-ANALYSIS/
│
├── README.md
│
├── GSE2034_analysis.R
│
├── GSE2034_analysis_summary.csv
├── GSE2034_significant_unique_genes.csv
├── GSE2034_KEGG_downregulated.csv
│
├── GSE2034_PCA_plot.png
├── GSE2034_MA_plot.png
├── GSE2034_volcano_plot.png
├── GSE2034_top_DEG_heatmap.png
│
├── GSE2034_GO_lower_in_bone_relapse_dotplot.png
├── GSE2034_KEGG_downregulated_dotplot.png
├── GSE2034_KEGG_lower_in_bone_relapse_dotplot.png
└── GSE2034_KEGG_upregulated_dotplot.png

The repository structure may be updated as the project becomes more reproducible.

---

Tools and Technologies

- R
- RStudio
- limma
- GEOquery
- Bioconductor
- ggplot2
- pheatmap
- clusterProfiler
- NCBI GEO

---

Reproducibility

The goal of this project is to make the analysis reproducible from the publicly available GSE2034 dataset.

The R analysis script will document the computational workflow used to generate the results and visualizations.

Raw data are not redistributed in this repository because the dataset is already publicly available through NCBI GEO.

---

Limitations

This is a computational analysis of a publicly available microarray dataset.

The identified genes and pathways represent associations within the analyzed dataset and should not be interpreted as proof of causation.

Further validation using independent datasets and experimental studies would be required to confirm biological significance.

---

Research Interests

This project reflects my interest in:

- Cancer biology
- Breast cancer
- Cancer genomics
- Bioinformatics
- Transcriptomics
- Differential gene expression
- Molecular mechanisms of cancer metastasis
- Computational cancer research

---

Author

Farhat Monjur Mahi

MBBS | Aspiring Cancer Researcher & Bioinformatician

GitHub: https://github.com/oncocode

---

Acknowledgements

This project uses publicly available data from the NCBI Gene Expression Omnibus (GEO).

The analysis is intended for educational and research portfolio purposes.