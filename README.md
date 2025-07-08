# ❤️ HeartDx - Cardiac Disease Prediction App

**HeartDx** is a machine learning-based application built in a Jupyter Notebook to help predict the likelihood of cardiac disease in patients based on clinical data. The model leverages structured health parameters to generate real-time risk assessments.

---

## 📊 Features

- Predicts cardiac disease risk based on standard clinical features
- Uses machine learning models (e.g., Logistic Regression, Random Forest, etc.)
- Visualizations to explain feature importance and predictions
- Interactive input support for simulated real-time prediction
- Easily extendable for integration into web/mobile platforms

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Notebook**: Jupyter (.ipynb)
- **Libraries**:
  - `pandas`, `numpy` for data handling
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for machine learning
  - `joblib` or `pickle` for model serialization (optional)
  - `ipywidgets` (optional) for interactivity

---

## 🧠 Dataset

The notebook uses the popular **UCI Heart Disease dataset**:
- the dataset is linked as csv
---

## 📊 Dataset Overview

The dataset includes the following features:

| Feature     | Description                                    |
|-------------|------------------------------------------------|
| age         | Age of the patient                             |
| sex         | Sex (1 = male; 0 = female)                     |
| cp          | Chest pain type (0–3)                          |
| trestbps    | Resting blood pressure (mm Hg)                 |
| chol        | Serum cholesterol in mg/dl                     |
| fbs         | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| restecg     | Resting electrocardiographic results           |
| thalach     | Maximum heart rate achieved                    |
| exang       | Exercise-induced angina (1 = yes; 0 = no)      |
| oldpeak     | ST depression induced by exercise relative to rest |
| slope       | Slope of the peak exercise ST segment          |
| ca          | Number of major vessels (0–3) colored by fluoroscopy |
| thal        | Thalassemia type (3 = normal; 6 = fixed defect; 7 = reversible defect) |
| target      | Target variable (1 = heart disease, 0 = no disease) |

## 🧠 Goal

Train a classification model to accurately predict the `target` (presence of heart disease) using supervised learning algorithms.

---

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/heartdx.git
   cd heartdx
Install dependencies:

pip install -r requirements.txt
Launch the notebook:

jupyter notebook CardioPredict.ipynb
Run all cells to train the model and make predictions.

📈 Model Performance
Evaluation metrics include:

Accuracy

Precision, Recall, F1-score

ROC-AUC Score

Confusion Matrix

All metrics are displayed after training for transparency.
