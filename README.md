# 🐾 Endangered Species Classifier (From Scratch ML)

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Core%20ML-lightblue?style=for-the-badge&logo=numpy)
![SDG](https://img.shields.io/badge/SDG-13%20Climate%20Action-green?style=for-the-badge)

## 🌍 The Challenge: IUCN Red List
More than 41,000 species are threatened with extinction today. This project aims to identify and predict which **terrestrial mammal species** are endangered based on their spatial, environmental, and taxonomic features. 

## 💡 Our Approach: ML From Scratch
Instead of relying on high-level machine learning libraries (like `scikit-learn`), **we built a Logistic Regression model entirely from scratch using NumPy**. 

Why from scratch? 
* **Mathematical Transparency**: Demonstrates core ML mechanics (Sigmoid function, Gradient Descent, Log-Loss).
* **High Interpretability**: Clear weights reveal exactly which features drive extinction risks (avoiding "black-box" models).
* **Probabilistic Output**: Provides actionable risk percentages (e.g., 85% risk) for real-world conservation efforts.

## 🛠️ Tech Stack & Methodology
* **Language & Libraries**: Python, NumPy, Pandas, GeoPandas, Matplotlib
* **Model**: Custom Logistic Regression with L2 Regularization (built from scratch)
* **Validation**: Custom 5-Fold Cross-Validation implementation
* **Dataset**: IUCN Red List Spatial Data (Terrestrial Mammals)
* **Feature Engineering**: Range size extraction, fragmentation indexing, habitat encoding, and taxonomic one-hot encoding.

## 📊 Results & Performance
The model was optimized to prioritize **Recall** to minimize False Negatives (predicting a species is safe when it is actually endangered).

* **Accuracy**: 76.24% (K-Fold Mean: 80.18% ± 2.37%)
* **Recall**: 93.77%
* **F1-Score**: 67.32%

## 📂 Repository Contents
* `/notebooks/` : The complete Jupyter Notebook containing the data pipeline and the custom ML model.
* `/docs/` : The project presentation PDF with detailed methodology and feature importance analysis.

## 👥 Authors
* **Sei BAYLE**
* **Juliette FAURIE**
