# AI-based Reservoir Property Estimation

This project predicts **porosity, permeability, and water saturation (Sw)** from well log and core data using Machine Learning.

---

## Project Features
- Synthetic core data generation
- Log data cleaning
- Feature engineering
- Model training using XGBoost
- log10 permeability transformation
- Evaluation (R2 score, RMSE, MAE)
- Model saving and future prediction

---

## How to Run

### 1️⃣ Clone this repo
git clone https://github.com/Ashutos0762/AI-Reservoir-Property-Estimation.git

### 2️⃣ Install dependencies
pip install -r requirements.txt

### 3️⃣ Open Jupyter Notebook
jupyter notebook

---

## Models Used
- Random Forest Regressorr
- XGBoost Regressor
- LGBM Regressor
- Log-transformed permeability and Logit transformed saturation for better accuracy
  
---

## Datasets
- log data: Sybthetically generated
- synthetic core data generated via Gaussian sampling

---

## Future Improvements
- Include LSTM/Transformer for sequence modelling
- Improve Sw accuracy using ensemble regression
- Add uncertainty quantification

