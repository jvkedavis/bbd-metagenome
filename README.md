# The Metagenome of Black Band Disease

This project investigates the microbial community associated with black band disease (BBD) in the coral *Acropora hyacinthus* using nanopore metagenomic data, for [Workshop 4](https://mb5370.bioinformatics.guide/workshop4.html) of MB5370 Marine Genomics.

The workflow covers assembly, binning, genome quality, taxonomy, gene annotation and metabolic pathway predictions. Among 14 selected genome candidates, `metabat.26` was classified as *Roseofilum*, a cyanobacterial genus associated with black band disease. These computational predictions do not directly establish metabolic activity.

## Full report

- [Combined Workshop 4 report (HTML)](index.html) — all six analysis stages in one document
- [Combined report source (R Markdown)](index.Rmd)

## Analysis

1. [Assembly](01_assembly.html)
2. [Binning](02_binning.html)
3. [Bin quality](03_bin_quality.html)
4. [Taxonomy](04_taxonomy.html)
5. [Gene annotation](05_gene_annotation.html)
6. [Metabolic pathways](06_metabolic_pathways.html)

## Repository layout

Each step has a numbered RMarkdown file at the top of the repository and a folder where its commands are run.

| Step | Notes | Folder | Tool |
| --- | --- | --- | --- |
| Assembly | `01_assembly.Rmd` | `flye/` | Flye |
| Binning | `02_binning.Rmd` | `metabat/` | MetaBAT 2 |
| Bin quality | `03_bin_quality.Rmd` | `checkm/` | CheckM |
| Taxonomy | `04_taxonomy.Rmd` | `gtdbtk/` | GTDB-Tk |
| Gene annotation | `05_gene_annotation.Rmd` | `prokka/` | Prokka |
| Metabolic pathways | `06_metabolic_pathways.Rmd` | `minpath/` | MinPath |

The combined HTML report and six individual HTML reports are linked above. The R Markdown source files document the corresponding methods and analyses.

