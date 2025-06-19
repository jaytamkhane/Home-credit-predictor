# 🏦 Home Credit Default Risk Predictor

A machine learning project to predict the probability of a loan applicant defaulting, using financial, demographic, and behavioral features. This end-to-end solution includes data processing, model training, evaluation, and deployment using **Flask** and **Render.com**.

> ⚡ **Note:** App may take 10–15 seconds to load on Render due to cold start.

---

## 📁 Project Structure

```
home-credit-predictor/
├── .vscode/            # VSCode settings
├── artifacts/          # Saved models, artifacts, etc.
├── config/             # Configuration files (e.g., YAML)
├── notebooks/          # Jupyter notebooks for EDA and prototyping
├── src/                # Source code: pipeline, preprocessing, utils
├── templates/          # HTML templates for Flask app
├── tests/              # Test scripts (unit/integration)
├── app.py              # Flask application
├── requirements.txt    # Python dependencies
├── .gitignore          # Git ignore rules
└── README.md           # Project documentation
```

---

## 🔍 Problem Statement

Home Credit aims to broaden access to credit. However, many potential clients have little or no credit history. The goal is to build a model that can predict the **likelihood of a loan being repaid**, improving risk assessment and loan approval decisions.

---

## 🔧 Features

- 📊 EDA and visualization of customer and loan data
- 🧼 Data cleaning, encoding, and feature engineering
- 📈 Model training with algorithms like Logistic Regression, RandomForest, XGBoost
- 📉 Performance evaluation using metrics like AUC-ROC, Accuracy, F1
- 💾 Model persistence and versioning
- 🌐 Deployment with Flask on Render

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/home-credit-predictor.git
cd home-credit-predictor
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows
```

### 3. Install Requirements
```bash
pip install -r requirements.txt
```

### 4. Run Locally
```bash
python app.py
```

---

## 🌐 Deployed App

🔗 **Live URL**: [https://your-app-name.onrender.com](https://your-app-name.onrender.com)  
🕒 *May take 10–15 seconds to load initially*

---

## 📊 Model Metrics

| Model             | Accuracy | AUC-ROC | F1 Score |
|------------------|----------|---------|----------|
| LogisticRegression | 0.76     | 0.79    | 0.74     |
| RandomForest       | 0.81     | 0.85    | 0.80     |
| XGBoost            | 0.83     | 0.87    | 0.82     |

> *(Sample scores — replace with your actual results)*

---

## 🧠 Tech Stack

- Python
- Pandas, NumPy, Scikit-learn
- XGBoost, RandomForest
- Matplotlib, Seaborn
- Flask (API & Web Interface)
- HTML/CSS (for simple UI)
- Render (for deployment)

---

## 📌 To-Do

- [ ] Add Streamlit UI (optional)
- [ ] Dockerize the app
- [ ] Add CI/CD pipeline
- [ ] Unit tests for all modules

---

## 👨‍💻 Author

**Jay Kumar**  
📧 [your.email@example.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)

---

## 📜 License

This project is licensed under the MIT License.
