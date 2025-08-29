# ML Portfolio Projects 🚀

This repository contains **end-to-end Machine Learning projects** built using real-world datasets from Kaggle.  
Each project is structured for clarity, reproducibility, and deployment (Streamlit/Gradio apps).

---

## 📂 Projects Overview

### 1️⃣ [HR Analytics — Employee Attrition Prediction](./hr-analytics-attrition/)
- **Task:** Classification (Predict whether an employee will leave)
- **Techniques:** Logistic Regression, Random Forest, XGBoost, SMOTE
- **Highlights:** Explainability with SHAP, Streamlit dashboard for HR managers
- **Dataset:** IBM HR Analytics (Kaggle)

---

### 2️⃣ [Student Performance — Regression Analysis](./student-performance-regression/)
- **Task:** Regression (Predict student grades/performance)
- **Techniques:** Linear Regression, Ridge/Lasso, XGBoost
- **Highlights:** What-if simulations (impact of study hours, absences)
- **Dataset:** Student Performance Dataset (Kaggle)

---

### 3️⃣ [Fruit Classification — Computer Vision](./fruit-classification-cnn/)
- **Task:** Image Classification (Identify fruits from images)
- **Techniques:** CNNs from scratch, Transfer Learning (ResNet, EfficientNet)
- **Highlights:** Streamlit/Gradio app → upload fruit image → get classification
- **Dataset:** Fruit Classification Dataset (Kaggle)

---

### 4️⃣ [Netflix Stock Price Forecasting — Time Series](./netflix-stock-forecasting/)
- **Task:** Time-Series Forecasting (Predict future Netflix stock prices)
- **Techniques:** ARIMA, Prophet, LSTMs, GRU
- **Highlights:** Interactive dashboard with forecast visualization
- **Dataset:** Netflix Stock Price History (Kaggle)

---

## ⚙️ Tech Stack

- **Languages:** Python 3.9+
- **Libraries:** scikit-learn, XGBoost, LightGBM, PyTorch, TensorFlow, statsmodels, Prophet, SHAP
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Deployment:** Streamlit, Gradio
- **Experiment Tracking:** Jupyter, Reports, SHAP/LIME

---

## 🛠️ Setup Instructions

```bash
# Clone repo
git clone https://github.com/<your-username>/ml-portfolio-projects.git
cd ml-portfolio-projects

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
```

## 📌 Repo Structure

```bash
ml-portfolio-projects/
│── README.md
│── requirements.txt
│── .gitignore
│── utils/
│── hr-analytics-attrition/
│── student-performance-regression/
│── fruit-classification-cnn/
│── netflix-stock-forecasting/
```
---
- Each project contains:
  - data/ → Raw + processed data
  - notebooks/ → EDA + modeling notebooks
  - src/ → Scripts for training/inference/deployment
  - models/ → Saved models
  - reports/ → Visualizations, SHAP plots, metrics
---

## 📈 Roadmap

- ✅ Phase 1: Tabular Projects (Attrition + Student Performance)
- ✅ Phase 2: Computer Vision (Fruit Classification)
- ✅ Phase 3: Time-Series Forecasting (Netflix Stock Prices)
---

## ✨ Author

### 👤 FutureDevGIT — Machine Learning Engineer
### 📧 Contact: cyphersafe21@gmail.com
