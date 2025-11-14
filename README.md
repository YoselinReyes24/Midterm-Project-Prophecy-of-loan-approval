# Project: Reproduction and Analysis of Classification Models

This repository contains the full implementation of a machine learning project in which a research paper's methodology was reproduced using a clean pipeline of data preprocessing, model training, and model evaluation.  
All work is implemented in Python using Jupyter Notebook, following best practices in data cleaning, feature preparation, model selection, and performance interpretation.

The notebook walks through the entire workflow: loading the dataset, preparing the data, building multiple classification models (Logistic Regression, KNN, Decision Tree), and comparing their performance.  
The conclusions describe how the reproduced results align with or differ from those presented in the original paper.

---

##  Repository Structure

```
├── README.md                 # Project overview and documentation
├── requirements.txt
├── data/
│   └── data.csv              # Dataset used for the analysis (your .csv file)
│
├── models/
│   └── final_notebook.ipynb  # Jupyter notebook containing all ML modeling work
│
└── **Presentation Link:** *[Insert your link here]*
```


---

##  Project Summary

The primary objective of this project is to reproduce the modeling workflow described in a research study and to evaluate how closely the reproduced results match the original authors' findings.  
Using the given dataset, the notebook performs:

1. **Data Preprocessing**  
   - Handling redundant identifiers  
   - Dealing with categorical features  
   - Scaling numerical variables  
   - Encoding target variables  
   - Ensuring correct sequencing of transformations  

2. **Model Development**  
   The following classification models were implemented and optimized:
   - Logistic Regression  
   - k-Nearest Neighbors (KNN)  
   - Decision Tree Classification  

   Hyperparameters were tuned where appropriate (e.g., elbow method for KNN).

3. **Model Evaluation**  
   Metrics include:
   - Accuracy  
   - Cross-Validation performance  
   - ROC–AUC Curve analysis  
   - Interpretation of the results for each model  

4. **Comparison With Research Paper Results**  
   The notebook concludes with a discussion explaining:
   - Why the reproduced results differ from the original  
   - Which model performed best in this implementation  
   - Practical interpretation of the evaluation metrics  

---

##  Technologies Used

- Python  
- NumPy / Pandas  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

##  How to Run This Project

1. Clone the repository:

```
git clone https://github.com/YoselinReyes24/Midterm-Project-Prophecy-of-loan-approval
```

2. Install dependencies (recommended: create a virtual environment):

```
pip install -r requirements.txt
```

3. Open the notebook:

```
jupyter lab
```

4. Run all cells to reproduce preprocessing steps, model training, and evaluation results.


---

## Results Overview

Inside the notebook (located in the **models** folder), you will find:

- Optimized models using Logistic Regression, KNN, and Decision Trees  
- ROC–AUC comparison  
- Accuracy and cross-validation scores  
- Final interpretation and recommendations  

The conclusion section summarizes which algorithm performed best for this dataset, why the results differ from those in the original paper, and what this implies for real-world applications.






