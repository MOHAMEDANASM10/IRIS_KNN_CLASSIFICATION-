# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📌 Objective
To build a simple machine learning model that predicts the species of an iris flower based on features like:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## 📊 Dataset
We use the built-in **Iris dataset** from `sklearn.datasets`.

### Target Classes:
- Setosa
- Versicolor
- Virginica

## 🛠️ Tools Used
- Python
- Google Colab / Jupyter Notebook
- Libraries: pandas, matplotlib, seaborn, sklearn

## ✅ Steps Followed

1. **Load the dataset** from sklearn.
2. **Convert to DataFrame** using `pandas`.
3. **Explore the data**: first 5 rows, pairplot visualization.
4. **Split the data** into training and testing sets.
5. **Train a KNN model** with `k = 3`.
6. **Make predictions** on test data.
7. **Evaluate** using accuracy score and confusion matrix.
8. **(Optional)** Compare different k values.

## 📈 Results
- **Accuracy with k=3:** ~97%
- Confusion matrix shows correct classification across all species.

## 📷 Visualizations
- Seaborn pairplot for feature distribution
- Confusion matrix for performance evaluation

## 📎 How to Run
1. Clone the repo or download the notebook.
2. Open `Iris_KNN_Classification.ipynb` in Jupyter or Google Colab.
3. Run all cells sequentially.
