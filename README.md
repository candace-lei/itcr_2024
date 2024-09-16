Here's a generated README based on the provided code:

# Acute Myeloid Leukemia Heatmap Analysis

## Project Overview

This project analyzes RNA-seq data from acute myeloid leukemia (AML) model mice using heatmaps. It adapts an existing analysis from refine.bio to create visualizations of gene expression patterns across different AML subtypes and treatments.

## Software and Dependencies

- R
- RStudio
- pheatmap package
- magrittr package
- readr package
- dplyr package
- tibble package
- sessioninfo package

To install required packages, run:

```r
install.packages(c("pheatmap", "magrittr", "readr", "dplyr", "tibble", "sessioninfo"), update = FALSE)
```

## Last Updated

This project was last updated on October 2021.

## Goals of the Project

1. Visualize gene expression patterns in acute myeloid leukemia model mice.
2. Identify genes with high variability across samples.
3. Cluster samples and genes based on their expression profiles.
4. Annotate the heatmap with sample-specific information (mutation status and treatment).

## Additional Information

- The analysis uses RNA-seq data from 19 AML model mice samples.
- Data is sourced from Shih et al., 2017 [2].
- The dataset contains RNA-seq results for different AML subtypes under controlled treatment conditions.
- Pre-processed data is obtained from refine.bio [3].

## Usage Instructions

1. Clone the repository or download the R script.
2. Ensure you have the necessary R packages installed (see Software and Dependencies section).
3. Run the script in RStudio or another R environment.

## Output

The script generates:
- A TSV file containing top 90 variable genes (`top_90_var_genes.tsv`)
- An annotated heatmap visualization (`aml_heatmap.png`)
- Session information output

## References

[2] Shih, A. H., et al. (2017). Mutant IDH2 activates haematopoietic stem cell self-renewal. Nature, 549(7672), 273–276. https://doi.org/10.1038/nature23665

[3] refine.bio. (n.d.). https://www.refine.bio/

## Contact

For any questions or feedback about this project, please contact Candace Savonen.

---

This README provides an overview of the project, including its purpose, requirements, and expected outputs. It also includes references to the original research paper and data source, which helps users understand the context of the analysis. The contact information allows users to reach out with questions or feedback.

Citations:
# README
