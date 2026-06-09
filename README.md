# Gradient Syringe RNA-seq Analysis

Analysis scripts associated with:

> Beals DG and Puri AW. Linking methanotroph phenotypes to genotypes using a simple spatially resolved model ecosystem. *The ISME Journal* (2024). https://doi.org/10.1093/ismejo/wrae060

This repository contains example R scripts used for visualization and exploratory analysis of differential gene expression data from gradient syringe RNA-seq experiments.

The complete RNA-seq dataset is available through NCBI GEO:

- GEO accession: GSE243827

## Repository Contents

### Heatmaps

| File | Description |
|--------|-------------|
| `RNA_seq_heatmap.R` | Example workflow for generating RNA-seq heatmaps from normalized expression data. |

### Volcano Plots

| File | Description |
|--------|-------------|
| `volcano_plot_example.R` | Basic volcano plot generation from differential expression results. |
| `volcano_plot_line_vs_above.R` | Volcano plot comparing cells collected from the band region versus the region above the band. |
| `volcano_plot_line_vs_below.R` | Volcano plot comparing cells collected from the band region versus the region below the band. |
| `volcanoplots_grid.R` | Combines multiple volcano plots into a single figure panel. |

## Notes

These scripts are provided primarily for reference and reproducibility. They reflect the analysis and figure-generation workflows used during manuscript preparation and may require modification to run on new datasets or computing environments.
