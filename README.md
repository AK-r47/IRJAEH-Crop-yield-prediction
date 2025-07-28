# IRJAEH-Crop-yield-prediction


Here’s a polished **GitHub README** for the IRJAEH article **“Sustainable Crop Yield Prediction”** (Article ID 998/911). It highlights the paper’s purpose, methods, and implementation—ideal for hosting the code and data:

---

# Sustainable Crop Yield Prediction 🌱

## Overview

This repository accompanies the research paper titled **“Sustainable Crop Yield Prediction”** published in *IRJAEH* (International Research Journal on Advanced Engineering & Technology) ([Irjaeh][1]).

The project uses machine learning to forecast agricultural crop yield using key agronomic and environmental indicators—such as crop type, season, rainfall, fertilizer/pesticide usage, and cultivated area.

---

## 🧠 Objectives

* Develop a **data-driven** system to predict crop yield for better resource planning.
* Identify the **best-performing ML model** among several algorithms.
* Build a **user-friendly web app** (Flask) for interactive yield predictions.
* Support dynamic decision-making for **input optimization**, climate variability, and sustainability.

---

## 🔍 Dataset & Features

Features include:

* Crop type
* Cultivation season and state
* Annual rainfall
* Fertilizer and pesticide usage
* Area under cultivation

The dataset intentionally excludes year-specific yield patterns to ensure generalization to future scenarios ([ResearchGate][2], [MDPI][3]).

---

## 🔧 Tools & Model Architecture

### Machine Learning Algorithms

* Linear Regression
* Random Forest
* Gradient Boosting
* XGBoost

Extensive model comparisons were conducted to find the highest accuracy performer ([ResearchGate][2]).

### Web Interface

A **Flask-based web app** offers features such as:

* Selecting crop/environment parameters and receiving **predicted yield**
* Evaluating the **most suitable crop** given input conditions
* Viewing comparisons across multiple crop outputs
* Suggestions for **optimal land partitioning**

Clean frontend interface integrates seamlessly with the ML backend ([ResearchGate][2]).

---

## 📂 Repository Structure

---
---
├── README.md
├── data/
│   ├── dataset.csv
│   └── preprocess_scripts/
├── src/
│   ├── models/
│   │   ├── train_models.py
│   │   └── model_comparison.ipynb
│   ├── app/
│   │   ├── app.py
│   │   ├── templates/
│   │   └── static/
│   └── utils/
├── requirements.txt
└── LICENSE
---
---

## 🚀 Installation & Usage

### Prerequisites

* Python 3.8+
* pip

### Install dependencies

```bash
pip install -r requirements.txt
```

### Preprocess & train models

```bash
python src/models/train_models.py --data data/dataset.csv
```

### Launch web application

```bash
cd src/app
python app.py
```

Visit `http://localhost:5000` in your browser to interact with the tool.

---

## 📊 Evaluation & Performance

* Model comparisons include key performance metrics like **R²**, **RMSE**, and **MAE**.
* According to the publisher, ensemble methods such as **XGBoost** and **Random Forest** showed top accuracy in yield forecasting ([ResearchGate][2]).

---

## 📝 How to Cite

Sarikonda S. R., Ponugoti V. R., Talasila H. S., Dubbaka M. R., Kadirvelu G. (2025). *Agriculture Data Analysis and Crop Yield Prediction Using Machine Learning*, IRJAEH, 3(05), 2196–2202. DOI: 10.47392/IRJAEH.2025.0322 ([ResearchGate][2])

---

## 🤝 Contributing

Contributions are welcome! To suggest improvements:

1. Fork this repo
2. Create a new branch
3. Submit a pull request with clear description

---

## ⚠️ Disclaimer

This tool serves as a predictive aid—not a substitute for expert agronomic advice. It should be used responsibly in real-world farming decisions.

---

### 🔗 References

* IRJAEH article summary on sustainable crop yield prediction ([ResearchGate][4], [Irjaeh][1])
* Comparison works in literature on ML in yield forecasting (e.g., XGBoost and RF performance) ([ResearchGate][2])

---

Let me know if you'd like code snippets, data schema details, or deployment setup!

[1]: https://irjaeh.com/index.php/journal/article/view/998?utm_source=chatgpt.com "Sustainable Crop Yield Prediction"
[2]: https://www.researchgate.net/publication/391749834_Agriculture_Data_Analysis_and_Crop_Yield_Prediction_Using_Machine_Learning?utm_source=chatgpt.com "Agriculture Data Analysis and Crop Yield Prediction Using Machine ..."
[3]: https://www.mdpi.com/2071-1050/16/21/9437?utm_source=chatgpt.com "Predicting Sustainable Crop Yields: Deep Learning and Explainable ..."
[4]: https://www.researchgate.net/publication/379126754_Empirical_Analysis_of_Crop_Yield_Prediction_Using_Hybrid_Model?utm_source=chatgpt.com "Empirical Analysis of Crop Yield Prediction Using Hybrid Model"
