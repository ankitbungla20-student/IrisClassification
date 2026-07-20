# Iris Flower Classification 🌸

## Project Overview
This project builds a Machine Learning classification model to predict the species of an Iris flower based on its physical measurements.

The dataset contains four flower measurements:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable is the flower species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## Dataset

Dataset Used:
- IRIS.csv

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target:
- Species

---

## Project Workflow

1. Upload Dataset
2. Import Required Libraries
3. Load Dataset using Pandas
4. Perform Exploratory Data Analysis (EDA)
5. Visualize Data using:
   - Pair Plot
   - Correlation Heatmap
6. Encode Target Labels
7. Split Dataset into Training and Testing Sets
8. Train Multiple Machine Learning Models:
   - K-Nearest Neighbors (KNN)
   - Logistic Regression
   - Decision Tree
9. Compare Model Accuracy
10. Save the Best Model using Joblib
11. Predict Species for New Flower Samples

---

## Machine Learning Models Used

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree Classifier

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Results

The project compares the accuracy of multiple classification algorithms and automatically saves the best-performing model as:

```
best_iris_model.joblib
```

---

## Files

```
IRIS.csv
IrisClassification.ipynb
best_iris_model.joblib
README.md
requirements.txt
```

---

## How to Run

1. Clone the repository

```bash
git clone <repository-link>
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook IrisClassification.ipynb
```

or upload the notebook to Google Colab.

4. Run all cells.

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Model Deployment using Flask or Streamlit
- Interactive Web Application

---

## Author

Ankit Singh Bungla
B.Tech CSE (AI & ML)
