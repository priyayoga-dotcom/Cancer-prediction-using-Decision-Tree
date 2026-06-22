# Cancer Prediction Using Decision Tree

##  Project Overview
This project uses a Decision Tree Classifier to predict whether a breast cancer tumor is malignant or benign using the Breast Cancer Wisconsin dataset available in Scikit-learn.

The project includes:
- Data Loading
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Train-Test Split
- Decision Tree Model Training
- Prediction and Evaluation
- Visualization of Results

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Dataset

The dataset is loaded directly from Scikit-learn:

```
from sklearn.datasets import load_breast_cancer

```

##  Project Workflow

# 1. Import Libraries

Required libraries such as Pandas, NumPy, Scikit-learn, Seaborn, and Matplotlib are imported.

# 2. Load Dataset

The Breast Cancer dataset is loaded using Scikit-learn.

# 3. Create DataFrame

Dataset features are converted into a Pandas DataFrame for easier analysis.

# 4. Data Analysis

* Check dataset shape
* Check missing values
* Check duplicate records
* Generate statistical summary
* View sample records

# 5. Data Splitting

Dataset is split into:

* Training Data (80%)
* Testing Data (20%)

# 6. Model Training

A Decision Tree Classifier is trained using the training dataset.

# 7. Prediction

The trained model predicts cancer diagnosis on unseen test data.

# 8. Model Evaluation

Performance is evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

# 9. Visualization

* Heatmap of Confusion Matrix
* Pie Chart Visualization

# Evaluation Metrics

The model performance is measured using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Visualizations

# Heatmap

Displays actual vs predicted classifications.

<img width="505" height="470" alt="image" src="https://github.com/user-attachments/assets/b059525c-6382-4753-9754-f697a58fe116" />


# Pie Chart

Shows classification distribution from the confusion matrix.

<img width="405" height="427" alt="image" src="https://github.com/user-attachments/assets/d6987af8-c3b3-4512-8ab3-d60b6d963a11" />


## How to Run

* Clone this repository
* git clone https://github.com/priyayoga-dotcom/Cancer-Prediction-Using-Decision-Tree.git
* Install required libraries
* pip install pandas numpy scikit-learn matplotlib seaborn
* Open Jupyter Notebook
* jupyter notebook
* Run the notebook
* Cancer_Prediction_using_Decision_Tree.ipynb

## Project Outcome

The Decision Tree model successfully predicts breast cancer diagnosis using medical attributes and provides performance evaluation through various metrics and visualizations.

## Author

**Pattammal M**

B.E. Computer Science and Engineering (AIML)
