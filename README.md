# Breast Cancer Predictor

## Dataset Information

- Used the **Breast Cancer Wisconsin (Diagnostic) Dataset**
- **Source**: Kaggle dataset [here](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data).
- **Features**: 
  - **Tumor size**
  - **Cell shape**
  - **Texture and smoothness of cells**
  - **Perimeter and area of the tumor**
  - **Mitotic count** (related to the number of cell divisions)

## Data Preprocessing  

To optimize model performance, i included these preprocessing steps :  

- **Handling Missing Values**: Imputed or removed missing data.  
- **Feature Scaling**: Used **Min-Max scaling** for uniformity.  
- **Encoding Categorical Variables**: Label-encoded diagnosis (B → 0, M → 1).  
- **Train-Test Split**: 80% training, 20% testing for model evaluation.  

## Model Development  

Various ML models were tested, with **Logistic Regression** emerging as the best after hyperparameter tuning. Other models explored:  
- **SVM, Decision Tree, Random Forest, Naive Bayes, XGBoost**  

## Evaluation Metrics  

Key evaluation metrics used to ensure the model's effectiveness: 

- **Accuracy**: Overall correctness.  
- **Precision**: Correct malignant predictions.  
- **Recall**: Crucial for minimizing false negatives.  
- **F1-Score**: Balances precision & recall.  
- **ROC-AUC**: Assesses class differentiation ability.  

## Results

After Evaluation: 

- **Precision**: 0.9913
- **Recall**: 0.9912
- **Accuracy**: 0.9912
- **F1-Score**: 0.9912
- **ROC-AUC**: 0.9884

# Clone the repository
git clone https://github.com/Reshmagvs/Breast-Cancer-Predictor-ml

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook breast_cancer_prediction.ipynb
```
