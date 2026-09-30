# MDM2 Potency Prediction

QSAR machine-learning workflow for predicting **pIC50** of MDM2 inhibitors using curated ChEMBL bioactivity data, molecular descriptors, scaffold-aware evaluation, and Extra Trees regression.

## Project Overview

This project focuses on MDM2 inhibitor potency prediction using cheminformatics and classical machine learning.

## Workflow

1. Bioactivity data preparation
2. Molecular feature generation
3. QSAR modeling
4. Exploratory data analysis
5. Active/inactive classification
6. Applicability-domain assessment

## Model

- Target: pIC50
- Final model: ExtraTreesRegressor
- Test R²: 0.732
- Test RMSE: 0.612
- Evaluation: scaffold-aware split

## Repository Structure

MDM2-Potency-Prediction/
- notebooks/
- data/
- results/
- figures/
- README.md
- requirements.txt
- .gitignore

## Technologies

Python · RDKit · scikit-learn · QSAR · ChEMBL · Extra Trees · Molecular Descriptors
