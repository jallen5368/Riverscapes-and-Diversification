# Amazonian Apteronotidae Biogeography

This repository contains the datasets and model files used in our study of the evolutionary diversification of electric fishes (family Apteronotidae) across the Amazon Basin, with a focus on evaluating three key hypotheses: the Riverine Barrier Hypothesis (RBH), River Network Hypothesis (RNH), and River Capture Hypothesis (RCH).

## Contents

### 1. `data/`
- `apteronotidae_distribution.csv`: Occurrence dataset for Apteronotidae species across Amazonian river basins.
- `stream_order_data.csv`: Stream order and hydrological classification for each distribution locality.
- `river_capture_events.csv`: Paleogeographic dataset marking hypothesized river capture events from the Neogene period.

### 2. `phylogeny/`
- `apteronotidae_tree.tre`: Time-calibrated species-level phylogeny in Newick format.
- `subclade_trees/`: Individual clade trees used in lineage-specific analyses.

### 3. `models/`
- `biogeobears_models/`: R scripts and model output files from BioGeoBEARS analyses, including:

### 4. `results/`
- `model_support_summary.csv`: Model comparison metrics (AIC, likelihoods, etc.)
- `ancestral_range_estimates/`: Output from BioGeoBEARS ancestral range reconstructions.

## Getting Started

To explore or reproduce the analysis:
1. Clone this repository.
2. Open the `models/` folder to view BioGeoBEARS configuration scripts.
3. Load the `apteronotidae_tree.tre` into R script and run.

## Citation

If you use these data or models, please cite:

> Allen and Albert, (2025). *Riverscape dynamics and habitat utilization structure evolutionary diversification in a clade of Amazonian electric fishes*. In review.

## Contact

For questions or collaborations, please contact jallen5368@gmail.com or open an issue on this repository.

---
