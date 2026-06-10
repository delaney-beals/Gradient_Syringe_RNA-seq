# Gradient syringe RNA-seq analysis

Analysis scripts associated with:

> Beals DG and Puri AW. Linking methanotroph phenotypes to genotypes using a simple spatially resolved model ecosystem. *The ISME Journal* (2024). https://doi.org/10.1093/ismejo/wrae060

This repository contains example R scripts used for visualization and exploratory analysis of differential gene expression data from gradient syringe RNA-seq experiments.

The complete RNA-seq dataset is available through NCBI GEO accession: GSE243827. 

## Scientific Background

Aerobic methanotrophs naturally inhabit environments containing opposing gradients of methane and oxygen. To better replicate this spatial structure in the laboratory, we developed a simple "gradient syringe" model ecosystem that establishes a methane–oxygen counter gradient.

When grown in this system, methanotrophs formed distinct horizontal bands at the intersection of the gradients. We hypothesized that cells occupying different positions within the syringe experienced different environmental conditions and therefore exhibited distinct physiological states.

To investigate these spatially resolved responses, RNA was collected from regions above the band, within the band, and below the band. Transcriptomic analysis was used to identify genes and pathways associated with growth within the gradient environment and to link observed phenotypes with their underlying genetic determinants.

The analyses in this repository focus primarily on visualization of differential gene expression results, including heatmaps and volcano plots used to compare transcriptional responses across syringe regions.

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

## Notes and Project Status

These scripts are provided primarily for reference and reproducibility. They reflect the analysis and figure-generation workflows used during manuscript preparation and may require modification to run on new datasets or computing environments. For additional information regarding the underlying biological questions, experimental methods, or original datasets, please contact [Aaron Puri](https://www.chemistry.utah.edu/faculty/aaron-w-puri/) at the University of Utah or the associated [publication](https://doi.org/10.1093/ismejo/wrae060).
