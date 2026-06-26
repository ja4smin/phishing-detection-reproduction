# URL-Based Phishing Detection Using Machine Learning – Reproduction Project

## Project Description

This project reproduces and critically evaluates the machine learning project "URL-Based Phishing Detection Using Machine Learning". The objective is to classify websites as either legitimate or phishing based on URL and website-related features.

The reproduction process includes dataset exploration, preprocessing analysis, feature engineering evaluation, model training, performance comparison, error analysis, and reproducibility assessment. Multiple machine learning algorithms were evaluated, including Logistic Regression, K-Nearest Neighbors, Naive Bayes, Decision Trees, Random Forests, Support Vector Machines, Multi-Layer Perceptrons, and Gradient Boosting.

The reproduced results confirmed that Gradient Boosting achieved the best overall performance for phishing website detection.

---

## Repository Structure

├── Phishing_Detection_Reproduction.ipynb   # Main notebook
├── phishing.csv                            # Dataset
├── Report.pdf                              # Final report
├── requirements.txt                        # Python dependencies
└── README.md                               # Project overview and results

---

## Final Results Summary

### Model Comparison

| Model | Accuracy |
|---|---:|
| Gradient Boosting | 94.62% |
| Random Forest | 93.93% |
| MLP | 93.93% |
| SVM | 93.85% |
| Logistic Regression | 92.39% |
| Decision Tree | 92.14% |
| KNN | 91.79% |
| Naive Bayes | 66.15% |

### Best Model Performance (Gradient Boosting)

| Metric | Score |
|---|---:|
| Accuracy | 94.62% |
| Precision | 93.75% |
| Recall | 94.62% |
| F1-score | 94.18% |
| MCC | 0.892 |
| ROC-AUC | 0.992 |
| PR-AUC | 0.990 |

---

## Key Findings

- Gradient Boosting achieved the best overall performance.
- HTTPS, AnchorURL, and WebsiteTraffic were identified as the strongest predictors.
- SMOTE provided only modest improvement on this nearly balanced dataset.
- Feature-selection validation suggested that retaining all features produced slightly better performance than the reduced feature set.
- Group-aware evaluation suggested that duplicate-pattern leakage was not a major contributor to the reported performance.
- Threshold analysis and realistic-prevalence analysis demonstrated that benchmark performance may overestimate real-world effectiveness.
- URL-based features provide a useful first layer of defense but should be combined with additional signals in real-world phishing detection systems.

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
pip install -r requirements.txt
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
