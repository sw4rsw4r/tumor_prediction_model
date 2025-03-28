# Tumor prediction model

## Overview

This project aims ..


## File Structure
```
.
├── config.yaml
├── data
│   ├── downloaded
│   └── processed
├── models
├── notebooks
│   ├── 01_data_exploration.ipynb
│   ├── 02_model_training.ipynb
│   └── 03_evaluation.ipynb
├── README.md
├── env.yaml
├── results
│   └── plots
└── src
```
- **`data/`** : Contains raw and processed datasets.
- **`models/`** : Stores trained models.
- **`notebooks/`** : Jupyter notebooks for data exploration, training, and evaluation.
- **`results/`** : Stores output results and visualization plots.
- **`src/`** : Source code for data processing, model training, and evaluation.
- **`config.yaml`** : Configuration file for the project. This includes dataset paths, data preprocessing parameters, and model configurations. This insures consistency across different scripts and notebooks.
- **`env.yaml`** : Conda environment configuration for the project, specifying the dependencies.


## Usage
### 1. Activate the Conda environment
```
conda env create -f env.yaml
conda activate tumor_prediction_model
```

### 2. Launch jupyter notebook
```
jupyter notebook --ip=0.0.0.0 --port=8889 --NotebookApp.password=''
```
Then, open the relevant notebooks from the `notebooks/` directory.
