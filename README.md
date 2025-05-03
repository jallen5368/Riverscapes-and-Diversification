# Amazonian Apteronotidae Biogeography

This repository contains the datasets and model files used in our study of the evolutionary diversification of electric fishes (family Apteronotidae) across South America, with a focus on evaluating three key hypotheses: the Riverine Barrier Hypothesis (RBH), River Network Hypothesis (RNH), and River Capture Hypothesis (RCH).

## Contents

### 1. `data/`
- `Apteronotid_distribution_dataset_SO1_10.csv`: Occurrence dataset for apteronotid species across South American by Strahler Stream Order (SO)
- `River_data_collection.xlsx`: River metrics by stream order for each major river basin at Hybas_lev_5. Data extracted from HydroSHEDS. Species diversity metrics based on distribution dataset.

### 2. `phylogeny/`
- `Apteronotidae_phylogeny.newick`: Time-calibrated species-level phylogeny in Newick format.
- `Navajini_phylogeny.newick/`: Individual clade tree used in lineage-specific analyses.
- `Apteronotini_phylogeny.newick/`: Individual clade tree used in lineage-specific analyses.

### 3. `models/`
- `biogeobears_models/`: R scripts and model output files from BioGeoBEARS analyses, including:
- `Rscript_BioGeoBEARS.txt/`: R scripts for running the Biogeographic analyses
- `Apteronotidae_range_biogeobears.txt/`: distribution file for apteronotid species using the TGBLOWN model
- `Geography_navajini.txt/`: distribution file for Navajini species using the GBLOWN model
- `2TS_matrix.txt/`: Dynamic landscape model with 7 biogeographic regions 
- `2_periods.txt/`: two time period txt file corresponding with Mega river capture c. 10 Ma
- `Dispersal_matrices_2TS_Navajini.txt/`: Dynamic landscape model with 6 biogeographic regions for Navajini analysis
- `SS_matrix.txt/`: Stepping stone model with 7 biogeographic regions

## Getting Started

To explore or reproduce the analysis:
1. Clone this repository.
2. Open the `models/` folder to view BioGeoBEARS configuration scripts.
3. Load the `Apteronotidae_phylogeny.newick` into R script and run.

## Citation

If you use these data or models, please cite:

> Allen and Albert, (2025). *Riverscape dynamics and habitat utilization structure evolutionary diversification in a clade of Amazonian electric fishes*. In review.

## Contact

For questions or collaborations, please contact jallen5368@gmail.com or open an issue on this repository.

---
