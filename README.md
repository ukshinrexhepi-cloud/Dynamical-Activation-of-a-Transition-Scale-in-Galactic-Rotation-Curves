# Dynamical Activation of a Transition Scale in Galactic Rotation Curves

This repository contains the data, analysis code, and figures used in the paper:

**"Dynamical Activation of a Transition Scale in Galactic Rotation Curves"**  
Ukshin Q. Rexhepi (2026)

---

## Overview

This work analyzes the structure of galactic rotation curves and identifies a dynamically activated transition scale \( q \), which emerges only when the acceleration profile exhibits sufficient structural reorganization.

The repository provides all necessary components to reproduce the main results of the paper, including:

- construction of acceleration profiles
- computation of dynamical descriptors (turnover \( T \), curvature)
- fitting of the transition scale \( q \)
- analysis of dynamical regimes
- generation of all figures used in the manuscript

---

## Repository Structure

Dynamical-Activation-of-a-Transition-Scale-in-Galactic-Rotation-Curves/
│
├── data/
│ ├── activation_threshold_analysis.csv
│ ├── corpus_activation_results.csv
│ └── rotation_curve_corpus_v7.json
│
├── figures/
│ ├── activation_schematic.png
│ ├── activation_examples_real_galaxies.png
│ ├── activation_examples_fixed_galaxies.png
│ ├── q_vs_turnover.png
│ ├── mdar_regimes.png
│ ├── btfr_regimes.png
│ ├── dynamical_boost_clean.png
│ └── regime_map.png
│
├── notebook/
│ └── Dynamical_Activation_of_a_Transition_Scale_in_Galactic_Rotation_Curves.ipynb
│
└── README.md


---

## Reproducibility

The analysis is fully reproducible using the provided notebook.

### Requirements

- Python 3.10+
- NumPy
- SciPy
- Pandas
- Matplotlib

### Running the analysis

1. Open the notebook in Google Colab or a local Jupyter environment
2. Ensure the `data/` directory is available
3. Run all cells sequentially

The notebook will:

- reconstruct the dynamical quantities
- compute the activation relation
- generate all figures in `figures/`

---

## Data Sources

The analysis is based on publicly available datasets, including:

- SPARC database (Lelli et al. 2016)
- THINGS survey (de Blok et al. 2008)
- LITTLE THINGS survey (Oh et al. 2015)

Additional processed data are included in this repository for convenience.

---

## Notes on Methodology

The transition scale \( q \) is obtained from fits to rotation curve profiles, while the turnover parameter \( T \) is derived directly from the logarithmic slope of the acceleration.

The relation between \( T \) and \( q \) should be interpreted as an empirical structural relation within the data rather than a fully independent predictive model.

---

## Figures

All figures used in the paper are included in the `figures/` directory, including:

- activation schematic
- representative galaxy profiles
- \( q \) vs. \( T \)
- MDAR by regime
- BTFR by regime
- dynamical boost distributions

---

## License

This repository is provided for scientific transparency and reproducibility.

---

## Author

Ukshin Q. Rexhepi  
Independent Researcher  
Tübingen, Germany  

GitHub: https://github.com/ukshinrexhepi-cloud
