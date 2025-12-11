# Final Project – Infant Mortality Prediction

This repository contains the code, data, and report for our final project in Analytics II. The goal of the project is to build and evaluate machine learning models to predict infant mortality using the NVSS dataset.

## Contents of this Repository

### 1. Software and Platform Requirements

To run the notebooks and code in this repository, you will need:

- **Python:** 3.10+  
- **Environment:** Jupyter Notebook or JupyterLab  
- **Key Python packages:**
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
- **Operating system:**
  - Developed and tested on **macOS** and **Windows**, but should also work on **Linux** with the same Python environment.

### 2. Project Structure (Map of Documentation)

The main structure of this GitHub repository is:

```text
.
├── README.md               # Overview of the project and repository
├── final_report.pdf        # Final written report for the project
│
├── Data/                   # Data files used in the analysis
│   ├── nvss_train.csv      # Training split of NVSS data
│   ├── nvss_val.csv        # Validation split of NVSS data
│   └── nvss_test.csv       # Test split of NVSS data
│   # (Additional data files may be added here)
│
├── NOTEBOOKS/              # Jupyter notebooks for analysis and 
│   ├── 01_data_cleaning_eda.ipynb        # Data loading, 
│   ├── 02_model_training_svm.ipynb       # SVM training and 
│   └── 03_model_comparison_evaluation.ipynb  # Final evaluation and comparison
│   # (Notebook names may change as the project is finalized)
│
└── OUTPUT/                 # Generated outputs from the analysis
    ├── figures/            # Plots and visualizations (e.g., confusion matrices)
    │   ├── svm_confusion_matrix_val.png
    │   └── svm_confusion_matrix_test.png
    ├── metrics/            # Saved metrics or tables (e.g., CSVs with results)
    │   └── svm_classification_report_val.csv
    # (Other output files will be stored here as they are created)
