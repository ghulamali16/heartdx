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
