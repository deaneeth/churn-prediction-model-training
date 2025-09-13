# 🚀 Customer Churn Prediction – Model Training & Evaluation Pipeline

Welcome to the **model training and evaluation** phase of the **Customer Churn Prediction** project! This repo follows the data preprocessing pipeline from [**Customer Churn Prediction – EDA & Data Preprocessing Pipeline**](https://github.com/deaneeth/churn-prediction-data-pipeline), where we prepared the data for churn modeling. Here, we focus on training machine learning models, evaluating their performance, and saving the trained models for future use.


🚀 **This repo is updated weekly** with:
- Clean, progressive Jupyter notebooks
- Raw & processed datasets
- Practical steps using Python, pandas and scikit-learn
- Real-world-style applied model Training & Evaluation for a customer churn analysis

---

### 📋 What's Inside?

This repo covers the complete **model training and evaluation pipeline**, built step-by-step:

| Notebook                          | Description                                                                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| `0_data_preparation.ipynb`        | Preparing the data for model training and evaluation. It includes loading datasets and applying necessary transformations.  |
| `1_base_model_training.ipynb`     | Traning the base machine learning model for the analysis using Logistic regression, and plotting confusion_matrixes.        |
| `2_kfold_validation.ipynb`        | Performing K-Fold cross-validation to evaluate model performance, calculate metrics, and ensure generalization.             |
| `3_multi_model_training.ipynb`    | Training and evaluating multiple machine learning models to compare performance and select the best approach.               |
| `4_hyperparameter_tuning.ipynb`   | Optimizing model performance through hyperparameter tuning using search techniques to find the best parameter settings.     |
| `5_threshhold_optimization.ipynb` | Adjusting the classification threshold to improve performance metrics and align predictions with specific objectives.       |

---

### 📁 Folder Structure:

```
📂 artifacts/ → Model training results, including training/test data (X, Y) saved as .npz files
📂 processed/ → Processed data used for model training
📂 raw/ → Raw input data and initial notebook for data preparation
📓 Notebooks → Notebooks to prepare data for training, testing and evaluation
```

---

### 🔧 Tools Used:

- Python, Pandas, Scikit-learn
- Matplotlib, Seaborn
- NumPy
- Jupyter Notebooks

---

### 🎯 Goals:

- Train machine learning models on the churn prediction dataset
- Evaluate models' performance using various metrics
- Save and export model artifacts (X_train, X_test, Y_train, Y_test)
- Provide a solid template for future machine learning projects

---

## 📌 Steps Followed from the Previous Repo

If you haven’t already gone through the **Data preprocessing steps**, make sure to check out the [Customer Churn Prediction – EDA & Data Preprocessing Pipeline](https://github.com/deaneeth/churn-prediction-data-pipeline) repo first. This repo focuses on preprocessing the data, including handling missing values, encoding features, and scaling the dataset, which are essential steps before model training.

---

## 🚀 Getting Started

To get started with this repo, clone the repository and install the required dependencies:

```
git clone https://github.com/deaneeth/churn-prediction-model-training.git
cd churn-prediction-model-training
pip install -r requirements.txt
```

---

## 🌟 Why You’ll Like It:

- 📚 Easy-to-follow structure for model building and evaluation
- 🧠 Consistent with the preprocessing steps from the previous repo
- 🧼 Learn how to build, evaluate, and save machine learning models in Python
- 💾 Continuous weekly updates with new models, techniques, and results

---

## 🤝 Contribute or Follow Along

This repo is updated **weekly**, with new models, evaluation metrics, and results. Star ⭐ the repo to stay updated, and fork 🍴 it to experiment with your own models. Contributions & feedback are always welcome — just make sure to check the [contributing guidelines](CONTRIBUTING.md) before submitting any pull requests.

---

### 👀 Want to continue building real-world models for churn prediction?

You're in the right place! Let's train some powerful models together and predict customer churn like a pro.

---

_Created with ❤️ by [deaneeth](https://github.com/deaneeth)_
