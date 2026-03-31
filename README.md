# Machine Learning Prediction of Young's Modulus in Multi-Component Titanium-Based Biomedical Alloys

This repository contains the dataset and computational framework for predicting the Young's modulus of multi-component titanium (Ti) alloys. By integrating physicochemical properties with high-entropy-inspired thermodynamic descriptors, this project provides a machine learning approach to accelerate the discovery of low-modulus alloys for biomedical applications.

## 📌 Overview

The development of new titanium alloys for medical implants is often slowed by the high cost of experimental synthesis and the limited size of traditional datasets. This study addresses these challenges by:
- Utilizing a comprehensive dataset that includes conventional and high-entropy-inspired designs.
- Implementing an optimized **XGBoost** regression model.
- Introducing **extended thermodynamic descriptors** (such as configurational mixing entropy and molybdenum equivalence) to enhance predictive accuracy.
- Validating the model against independent experimental data to ensure robustness across diverse chemical spaces.

## 🚀 Key Features

- **Predictive Modeling:** High-performance regression using Extreme Gradient Boosting (XGBoost).
- **Feature Engineering:** Inclusion of 17+ descriptors including valence electron concentration (VEC), atomic size difference, and mixing enthalpy.
- **Explainable AI:** Feature importance analysis to identify the primary drivers of alloy stiffness and phase stability.
- **Biomedical Focus:** Specifically targeted toward identifying alloys with a low Young's modulus to prevent "stress shielding" in bone implants.