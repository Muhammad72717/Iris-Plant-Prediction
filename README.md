[readme.md](https://github.com/user-attachments/files/26821938/readme.md)
# 🌸 Iris Flower Classification

## 📁 Files

- **`Iris.csv`** – Dataset with 150 samples, 4 features (sepal length/width, petal length/width), and 3 species labels.
- **`main.ipynb`** – Jupyter notebook for EDA, model training (KNN & SVM), and hyperparameter tuning using GridSearchCV & RandomizedSearchCV.

## 📊 Dataset

- 150 rows, 6 columns (Id, 4 measurements, Species)
- Species: `Iris-setosa`, `Iris-versicolor`, `Iris-virginica`

## 🔧 Steps

1. Load and explore data
2. Split features (`X`) and target (`y`)
3. Train `KNeighborsClassifier` and `SVC` models
4. Tune hyperparameters with `GridSearchCV` and `RandomizedSearchCV`
5. Compare cross-validation scores

## 📈 Best Results

- **KNN** – Manhattan distance, n_neighbors=9 → ~92% accuracy
- **SVM** – Linear kernel, C=1 → ~87% accuracy

## 📦 Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
