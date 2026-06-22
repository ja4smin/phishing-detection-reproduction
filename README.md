# URL-Based Phishing Detection Using Machine Learning – Reproduction Project

## Project Description

This project reproduces and critically evaluates the machine learning project "URL-Based Phishing Detection Using Machine Learning". The objective is to classify websites as either legitimate or phishing based on URL and website-related features.

The reproduction process includes dataset exploration, preprocessing analysis, feature engineering evaluation, model training, performance comparison, error analysis, and reproducibility assessment. Multiple machine learning algorithms were evaluated, including Logistic Regression, K-Nearest Neighbors, Naive Bayes, Decision Trees, Random Forests, Support Vector Machines, Multi-Layer Perceptrons, and Gradient Boosting.

The reproduced results confirmed that Gradient Boosting achieved the best overall performance for phishing website detection.

---

## Selected Article / Blog / Tutorial

Selected Source:

https://github.com/BusamSumanjali/URL-Based-Phishing-Detection-using-machine-Learning

Note: The selected source is a GitHub repository rather than a separate article or blog post. Therefore, the same source serves as both the tutorial/documentation and the original code repository.

---

## Original GitHub Repository

https://github.com/BusamSumanjali/URL-Based-Phishing-Detection-using-machine-Learning

---

## Dataset Source

The dataset used in this project was obtained from the original GitHub repository and is provided as the file `phishing.csv`.

Dataset file:

* phishing.csv

Source repository:

https://github.com/BusamSumanjali/URL-Based-Phishing-Detection-using-machine-Learning

According to the original project documentation, the dataset was downloaded from Kaggle:

https://www.kaggle.com/eswarchandt/phishing-website-detector

The dataset contains URL and website-related cybersecurity features used to classify websites as either legitimate or phishing websites.

---

## Execution Instructions

### Requirements

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

### Running the Project

1. Clone or download the repository.
2. Ensure that `phishing.csv` is located in the project directory.
3. Open `Phishing_Detection_Reproduction.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all notebook cells sequentially from top to bottom.
5. Review the generated visualizations, model evaluation metrics, and analysis sections.

### Expected Output

The notebook will:

* Load and preprocess the phishing dataset.
* Perform exploratory data analysis (EDA).
* Apply feature selection and scaling.
* Evaluate the impact of SMOTE oversampling.
* Train multiple machine learning models.
* Compare model performance using Accuracy, Precision, Recall, F1-score, MCC, and ROC-AUC.
* Identify Gradient Boosting as the best-performing model.
