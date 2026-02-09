# Computational Design of RNA Thermoswitches (MSc Dissertation)

## 🧬 Scientific Overview
This project replicates and optimises the computational pipeline developed during my MSc in Data Science. The goal is to accelerate the discovery of RNA thermoswitches (RNTs) for high-temperature genetic control in *Bacillus subtilis*.

## 🔬 Technical Achievements
- **Thermodynamic Modeling:** Replicated NUPACK simulation logic for 50,000 synthetic RNA sequences.
- **Biophysical Characteris
ation:** Implemented non-linear curve fitting using the **Hill Equation** to extract Melting Temperature (Tm) and Cooperativity (n).
- **Machine Learning Optimisation:** Upgraded the dissertation's baseline Linear Regression ($R^2=0.30/0.80$) to an **XGBoost Regressor**, achieving an **$R^2$ of 0.90**.
- **High-Throughput Screening:** Reduced the time required to estimate RBS accessibility from hours (simulation) to milliseconds (ML prediction).

## 🚀 Impact
The model successfully identifies "switch-like" candidates with sharp transitions, providing a proof-of-concept for closed-loop synthetic biology design cycles.

## 🛠️ Tools
- **Bioinformatics:** NUPACK (Simulated), SciPy (Hill Fitting)
- **ML Stack:** Python, XGBoost, Scikit-Learn, Matplotlib
