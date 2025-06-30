# Task 5 - Decision Trees and Random Forests

## Objective

Learn tree-based machine learning models for classification using Decision Trees and Random Forests. Evaluate and interpret model performance, feature importance, and overfitting.

---

##  Dataset Used

**Heart Disease Dataset**  
Source: [Heart Disease](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
This dataset contains 14 features and a target column indicating presence of heart disease.

---

##  Tools and Libraries

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Graphviz (for decision tree visualization)

---

##  Tasks Performed

1. **Data Loading and Preprocessing**
   - Loaded CSV dataset and split into features (X) and target (y).
   - Performed train-test split.

2. **Decision Tree Classifier**
   - Trained a Decision Tree on the training data.
   - Visualized the tree structure.
   - Analyzed overfitting by plotting accuracy vs. depth.

3. **Random Forest Classifier**
   - Trained a Random Forest with 100 trees.
   - Compared accuracy to Decision Tree.
   - Evaluated using 5-fold cross-validation.

4. **Feature Importance**
   - Extracted and visualized feature importances from the Random Forest.

---

##  Results

- Decision Tree Accuracy: ~[98.53%]  
- Random Forest Accuracy: ~[98.53%]  
- Cross-validation Accuracy: ~[99.70%]  
- Most important features: [e.g., 'cp', 'thalach', 'exang']

---

##  Files Included

- `Task5`: Jupyter Notebook with all code and plots.
- `Heart Disease Dataset`: Dataset.
- `README.md`: This file.

---


