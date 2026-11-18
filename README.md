# Iris Species Classification with SVM

Classifies iris flowers into **setosa, versicolor and virginica** from four measurements: sepal length and width, petal length and width.

> 📚 **Course project:** completed while following the Udemy course *Python for Data Science and Machine Learning Bootcamp* (Pierian Data). The dataset and task come from the course.

## Approach
1. Loaded the Iris data set (`seaborn.load_dataset('iris')`) and explored it with pair plots and KDE plots
2. Trained a **Support Vector Classifier** (scikit-learn `SVC`)
3. Tuned `C` and `gamma` with **GridSearchCV**
4. Evaluated with a confusion matrix and a classification report

## Results (test set: 45 flowers)

| Model | Accuracy |
|---|---|
| SVC (default parameters) | **0.98** |
| SVC tuned with GridSearchCV | **0.98** |

## Tech
Python · pandas · NumPy · scikit-learn · Matplotlib · Seaborn · Jupyter

## Run it
```bash
git clone https://github.com/Aniket1103200/SVM-Iris-Classification_project.git
cd SVM-Iris-Classification_project
pip install -r requirements.txt
jupyter notebook svm_iris_classification.ipynb
```
