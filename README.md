# Water Quality Prediction - RMS

## Project Description

This project aims to predict multiple water quality parameters using machine learning techniques, specifically employing `MultiOutputRegressor` wrapped around a `RandomForestRegressor`. Developed as part of the **AICTE Virtual Internship** sponsored by Shell in **June 2025**.

---

## 📝 Overview

**Clean water** is a critical global resource, and predicting various water quality metrics can help in early detection of pollution. This project focuses on the following steps:

1. **Data Collection & Preprocessing**:
    - Collected real-world water quality datasets.
    - Cleaned, normalized, and prepared the data for machine learning.

2. **Modeling**:
    - Used **supervised machine learning** techniques for multi-target regression.
    - Built a prediction pipeline using **`MultiOutputRegressor`** wrapped around **`RandomForestRegressor`**.

3. **Evaluation**:
    - Evaluated the model's performance using the **R² Score** and **Mean Squared Error (MSE)** metrics.

---

## 💻 Technologies Used

- **Python 3.12** – Programming Language
- **Pandas, NumPy** – Data Handling
- **Scikit-learn** – Machine Learning & Model Evaluation
- **Matplotlib, Seaborn** – Data Visualization
- **Jupyter Notebook** – Interactive Development Environment

---

## 🌊 Predicted Water Quality Parameters

The model predicts the following water quality parameters:

- **NH₄**: Ammonium
- **BOD₅**: Biochemical Oxygen Demand
- **Colloids**: Colloidal Particles
- **O₂**: Dissolved Oxygen
- **NO₃**: Nitrate
- **NO₂**: Nitrite
- **SO₄**: Sulfate
- **PO₄**: Phosphate
- **Cl**: Chloride

---

## 📊 Model Evaluation

### Performance Metrics:

- **R² Score**: Measures the proportion of variance in the target variable that is predictable from the model.
- **Mean Squared Error (MSE)**: Quantifies the difference between predicted and actual values. Lower values are preferred.

The model showed **acceptable performance** across all the predicted parameters.

---

## 🔗 Model Access

Access the trained model through the link below:  
[Download Model](https://drive.google.com/file/d/18RE5GQ9XdKZZCGr-Ii_UzUVDqIJBz3pL/view?usp=drive_link)

---

## 🏫 Internship Details

- **Internship Type**: AICTE Virtual Internship
- **Sponsor**: Shell
- **Duration**: June 2025 (1 Month)
- **Focus Area**: Machine Learning for Environmental Monitoring

---

## 🚀 Future Enhancements

1. **Model Refinement**: Experiment with other models and hyperparameters to improve prediction accuracy.
2. **Real-Time Monitoring**: Deploy the model for real-time predictions using live sensor data.
3. **Expand Parameters**: Predict additional water quality parameters such as pH and heavy metals.

---

## 🙏 Acknowledgments

- **AICTE** for providing the opportunity to work on meaningful environmental problems.
- **Shell** for sponsoring the internship and supporting environmental monitoring initiatives.

---
