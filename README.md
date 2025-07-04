# 🌸 Iris Flower Classification - Machine Learning Project

This is a classification project done as part of the IBI Machine Learning Internship (July 2025). The goal is to classify iris flowers into three species: Setosa, Versicolor, and Virginica based on features like sepal and petal measurements.

---

## 📁 Dataset

We used the **Iris dataset** provided by Scikit-learn. It contains 150 samples with the following features:

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)
- Target (0 = Setosa, 1 = Versicolor, 2 = Virginica)

---

## 🧹 Preprocessing Steps

- Checked for missing values (none found)
- Standardized the feature values using `StandardScaler`
- Split dataset into **80% training** and **20% testing**

---

## 🧠 Models Used

We used 3 basic supervised classification models:

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ✅        |
| K-Nearest Neighbors (KNN) | ✅ |
| Decision Tree Classifier | ✅ |

---

## 📊 Evaluation Metrics

For each model, we evaluated using:

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix (visualized using heatmap)

---

## 🔧 Hyperparameter Tuning

- **KNN**: Tuned `n_neighbors` using `GridSearchCV`
- **Decision Tree**: Tuned `max_depth` using `GridSearchCV`

---

## 🎨 Visualizations

- Scatter plot for Sepal Length vs Petal Length
- PCA (2D projection of 4D data) for class separability visualization
- Confusion matrices (for each model)

---

## 📦 Requirements

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
