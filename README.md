# Decision_Tree_Classifier_Model_on_IRIS_dataset

# 🌸 Decision Tree Classifier on Iris Dataset

This project demonstrates the implementation of a **Decision Tree Classifier** to classify flowers in the famous **Iris dataset** using Scikit-learn. It includes model training, hyperparameter tuning with GridSearchCV, and performance evaluation.

## 📂 Project Structure

├── Decision_Tree_Model.ipynb # Jupyter notebook with code and results
├── iris.csv # Iris dataset file
├── README.md # Project documentation
└── requirements.txt # Python dependencies


## 📊 Dataset

The [Iris dataset](https://www.kaggle.com/datasets/arshid/iris-flower-dataset) is a classical dataset in pattern recognition. It contains 150 rows with 4 numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target classes:
- Setosa
- Versicolor
- Virginica

## 🚀 Model

We use `DecisionTreeClassifier` from `sklearn.tree` and perform hyperparameter tuning using `GridSearchCV`.

### Hyperparameters Tuned:

- `criterion`: `['gini', 'entropy']`
- `max_depth`: `[None, 2, 4, 6]`
- `min_samples_split`: `[2, 5]`
- `max_features`: `[None, 'sqrt', 'log2']`

## 📈 Results

The model is trained and evaluated using cross-validation (`cv=5`). Accuracy and confusion matrix are used to evaluate performance.

## 📦 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Ajay-Kumar-Prasad/Decision_Tree_Classifier_Model_on_IRIS_dataset.git
   cd Decision_Tree_Classifier_Model_on_IRIS_dataset

2.Create and activate a virtual environment 
    python -m venv venv
    source venv/bin/activate   # For Linux/macOS
    venv\Scripts\activate      # For Windows

3.Install required packages:
    pip install -r requirements.txt

