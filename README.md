# Cod Fish Distribution & Sensitivity Prediction  
### Supervised Machine Learning Project (AgroParisTech, 2025)

This repository contains two notebooks exploring the use of **supervised machine learning models** to predict the **distribution** and **environmental sensitivity** of the Atlantic cod (*Gadus morhua*) based on ecological and oceanographic variables.

The project was completed as part of the Machine Learning module at **AgroParisTech (specialisation IODAA – Data & AI)**.  
All comments inside the notebooks are in French, while the code remains fully accessible to any user familiar with Python and scikit-learn.

---

## Objective

Build and evaluate classification models predicting cod presence/absence or sensitivity classes using variables such as:

- temperature  
- salinity  
- dissolved oxygen  
- nutrients  
- geospatial or depth indicators
- ...

The goal was to test classical supervised learning approaches and analyse their performance and interpretability.

---

## Notebooks

- `François_F_Morue_01.ipynb`: dataset exploration, preprocessing, first baseline models  
- `François_F_Morue_02.ipynb`: improved modelling, performance comparison, discussion  

The notebooks include **French explanations** for clarity and scientific reasoning.

---

## 🛠️ Methods

The notebooks implement:

- **Data preprocessing** (cleaning, encoding, normalization)  
- **Feature analysis** (correlations, visualisations)  
- **Supervised ML models** using scikit-learn, including:  
  - Logistic Regression  
  - RandomForestClassifier  
  - k-Nearest Neighbors  
  - Support Vector Machines  
- **Train/test evaluation**, accuracy scoring, confusion matrices  
- **Interpretation** of model behaviour and limitations

The workflow follows standard good practices:  
train/test split, reproducibility, incremental modelling, and documented reasoning.

---

## Results (Summary)

The different supervised models were compared to assess:

- predictive performance  
- robustness  
- sensitivity to feature scaling  
- ecological interpretability  

Full results, graphs, and comments are available directly in the notebooks.

