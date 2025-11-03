# Credit-Classification-ROC-and-PR-Curve-Notebook

This repository contains an annotated Jupyter notebook exploring classifier evaluation using ROC and Precision-Recall (PR) curves. The analysis uses a public credit dataset and compares performance between AdaBoost and Logistic Regression models, with both theoretical discussion and empirical results visualized.

## Project Overview

- **Objective:**  
  Investigate the relationship between ROC and PR curves, both analytically and empirically, for binary classification models on a credit dataset.
- **Dataset:**  
  The dataset is fetched directly from the OpenML repository (ID: 31 - "credit") and focuses only on numerical features for analysis.
- **Models Compared:**  
  - AdaBoostClassifier  
  - LogisticRegression
- **Outputs:**  
  - ROC and PR curves for both models
  - Area Under the Curve (AUC and Average Precision) metrics
  - Discussion on when true negatives matter for model evaluation

## Notable Features

- Provides a proof and discussion on the one-to-one correspondence between ROC and PR curve points for a given binary classification task.
- Feature selection, model training, results visualization, and metric calculations are all included in the notebook.
- Both the code and markdown cells are thoroughly documented.

## Repository Structure

- **`Catalin_Botezat_cb5330_problem3_HW1.ipynb`**  
  This is the main notebook containing all markdown explanations, code, and outputs.
- No external scripts or modules; all work is self-contained in the notebook.

## How to Use

1. **Clone the repository:**  
   ```bash
   git clone <your-repo-url>
   cd <repo-directory>
   ```

2. **Install dependencies:**  
   The notebook relies on the following Python packages:
   - openml
   - pandas
   - numpy
   - scikit-learn
   - matplotlib

   Install them using pip:
   ```bash
   pip install openml pandas numpy scikit-learn matplotlib
   ```

3. **Run the notebook:**  
   Open the notebook in Jupyter or Google Colab and run all cells sequentially for a complete walkthrough.

## Cell and Function Guide

- **Data Loading:**  
  Downloads and prepares the dataset from OpenML (ID: 31).
- **Preprocessing:**  
  Selects only numerical columns.
- **Train-Test Split:**  
  Standard split with 80/20 ratio.
- **Modeling:**  
  Trains AdaBoost and Logistic Regression classifiers.
- **Evaluation:**  
  Computes ROC and PR curve data, including AUC and Average Precision, for both models.
- **Visualization:**  
  Plots ROC and PR curves side by side.
- **Theory/Discussion:**  
  Contains markdown with theoretical insights and proofs connecting ROC and PR curves.

## Outputs

- Side-by-side plots of ROC and PR curves for both classifiers
- Printed shape and head of the numerical data
- Evaluation metric values for each model
- Mathematical argumentation and proofs regarding curve correspondence

## Credits

Notebook and analysis by Catalin Botezat.

