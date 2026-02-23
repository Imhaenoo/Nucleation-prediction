# NuMaPS: Nucleation Prediction Framework for Polymorph Selection

![license](https://img.shields.io/badge/license-MIT-blue.svg)
![python](https://img.shields.io/badge/python-3.10%2B-blue)
![notebooks](https://img.shields.io/badge/Jupyter-Notebooks-orange)

NuMaPS is a nucleation-based framework for predicting polymorph selection during vapor deposition by comparing relative nucleation behavior under different processing conditions.

## Highlights
- Predicts relative nucleation tendencies for competing polymorphs.
- Covers homogeneous and heterogeneous nucleation scenarios.
- Provides reproducible notebook-based workflows for each modeling route.

## Quickstart

### Option A) Conda (recommended)
```bash
conda env create -f environment.yml
conda activate numaps
jupyter lab
```

### Option B) pip
```bash
pip install -r requirements.txt
jupyter lab
```

## Repository Structure
- `homo_prediction.ipynb` — homogeneous nucleation predictions.
- `hetero_alpha_prediction.ipynb` — heterogeneous nucleation predictions for the alpha polymorph case.
- `hetero_kappa_prediction.ipynb` — heterogeneous nucleation predictions for the kappa polymorph case.
- `hetero_kappa_prediction(chamber_pressure).ipynb` — pressure-dependent kappa polymorph nucleation analysis.
- `hetero_tio2_prediction.ipynb` — heterogeneous nucleation analysis with TiO2-related conditions.

## Method Overview
The framework evaluates polymorph competition using nucleation-theory-informed descriptors, including thermodynamic driving force, interfacial effects, and process-dependent conditions. Each notebook focuses on a specific scenario and computes comparative trends that support polymorph selection analysis.

## Data Availability
Example workflow inputs and outputs are included directly in each notebook. If you use this repository for research, please cite the related publication and this code repository.

## Citation
See [`CITATION.cff`](CITATION.cff) for software citation metadata.

## License
MIT License. See [`LICENSE`](LICENSE).
