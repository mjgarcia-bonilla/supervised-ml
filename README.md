<div align="center">

# 🎯 Supervised Machine Learning Portfolio

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-AA0000?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

*Supervised Machine Learning projects developed during the MSc in Systems and Computing Engineering — Universidad de los Andes, Colombia*

</div>

---

## 📁 Repository Structure

```
supervised-ml/
├── 00-final-exam/                       # ⭐⭐ Final project — Hospital Mortality Prediction
├── 01-supervised-learning-intro/        # Introduction to supervised learning
├── 02-training-data-dependency/         # Training data dependency analysis
├── 03-neural-networks/                  # Neural networks & MLP
├── 04-model-selection-regularization/   # Model selection & regularization
├── 05-kernel-methods-svr/               # Kernel methods & SVR
├── 06-ensemble-methods-xgboost/         # Ensemble methods & XGBoost
└── 07-imbalanced-classification/        # Imbalanced classification
```

---

## 🗂️ Projects

### 🏥 00 · Final Exam — Hospital Mortality Prediction
> End-to-end supervised ML project predicting in-hospital mortality for critically ill patients using clinical and physiological variables (9,105 records).

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`hospital-mortality-prediction.ipynb`](./00-final-exam/hospital-mortality-prediction.ipynb) ⭐⭐ | Full ML pipeline: EDA, preprocessing, SMOTE balancing, logistic regression, hyperparameter tuning, ROC & Precision-Recall curves | Clinical dataset (9,105 records) |

**Concepts:** SMOTE · Class imbalance · ROC-AUC · Precision-Recall · Logistic regression · Hyperparameter tuning · Clinical ML

---

### 🧠 01 · Introduction to Supervised Learning
> Emotion classification from images — identifying appropriate use cases for supervised learning.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`emotion-classification-supervised-learning.ipynb`](./01-supervised-learning-intro/emotion-classification-supervised-learning.ipynb) | Binary emotion classification using supervised learning fundamentals | Image dataset |

**Concepts:** Supervised learning · Binary classification · Problem framing · Feature extraction

---

### 📊 02 · Training Data Dependency Analysis
> Analyzing how model performance varies with different training set sizes and compositions.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`training-data-dependency-analysis.ipynb`](./02-training-data-dependency/training-data-dependency-analysis.ipynb) | Binary classification with varying training data to study model dependency | Custom dataset |

**Concepts:** Train/test split · Learning curves · Data dependency · Overfitting · Underfitting

---

### 🔗 03 · Neural Networks & Binary Classification
> Solving a binary classification problem using a Multilayer Perceptron (MLP) with backpropagation.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`neural-network-binary-classification.ipynb`](./03-neural-networks/neural-network-binary-classification.ipynb) | MLP classifier with architecture comparison and hyperparameter selection | Custom dataset |

**Concepts:** MLP · Backpropagation · Activation functions · Architecture selection · Neural network evaluation

---

### ⚖️ 04 · Model Selection & Regularization
> Solving a binary classification problem by comparing multiple models and selecting the best one.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`model-selection-regularization.ipynb`](./04-model-selection-regularization/model-selection-regularization.ipynb) | Compare and tune multiple classifiers to minimize overfitting/underfitting | Custom dataset |

**Concepts:** Model selection · Regularization · Overfitting · Underfitting · Cross-validation · Complexity analysis

---

### 🔵 05 · Kernel Methods & SVR
> Regression problem solved using Support Vector Regression (SVR) with kernel functions.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`svr-regression-kernels.ipynb`](./05-kernel-methods-svr/svr-regression-kernels.ipynb) | SVR hyperparameter tuning for optimal regression performance | Custom dataset |

**Concepts:** SVR · SVM · Kernel functions · RBF · Hyperparameter tuning · Regression evaluation

---

### 🌲 06 · Ensemble Methods & XGBoost
> Credit default prediction using XGBoost ensemble method for banking classification.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`xgboost-credit-default-prediction.ipynb`](./06-ensemble-methods-xgboost/xgboost-credit-default-prediction.ipynb) ⭐ | XGBoost classifier for bank customer default prediction | Banking dataset |

**Concepts:** XGBoost · Gradient boosting · Ensemble methods · Feature importance · Classification metrics

---

### ⚠️ 07 · Imbalanced Classification
> Industrial machinery fault detection with highly imbalanced classes using cost-sensitive learning.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`imbalanced-classification-industrial-faults.ipynb`](./07-imbalanced-classification/imbalanced-classification-industrial-faults.ipynb) ⭐ | Fault detection system for industrial machinery with class imbalance handling | Industrial dataset |

**Concepts:** Class imbalance · Cost-sensitive learning · SMOTE · Recall optimization · Industrial ML

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3.x |
| Machine Learning | scikit-learn, XGBoost |
| Deep Learning | TensorFlow / Keras |
| Data handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Imbalanced data | imbalanced-learn (SMOTE) |
| Environment | Jupyter Notebook, Google Colab |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/mjgarcia-bonilla/supervised-ml.git
cd supervised-ml

# Install dependencies
pip install pandas numpy scikit-learn xgboost tensorflow imbalanced-learn matplotlib seaborn jupyter

# Launch Jupyter
jupyter notebook
```

---

## 👩‍💻 Author

**María J. García-Bonilla** — AI Engineer | MSc Universidad de los Andes

[![GitHub](https://img.shields.io/badge/GitHub-mjgarcia--bonilla-7B00CC?style=flat-square&logo=github&logoColor=white)](https://github.com/mjgarcia-bonilla)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-María_García--Bonilla-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mar%C3%ADa-jos%C3%A9-garc%C3%ADa-bonilla-ab5688267/)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-García--Bonilla-00CCBB?style=flat-square&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Maria-Garcia-Bonilla-3)
