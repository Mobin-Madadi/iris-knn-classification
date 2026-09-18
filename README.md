# 🌸 Iris Classification using K-Nearest Neighbors

A Machine Learning classification project that uses the **K-Nearest Neighbors (KNN)** algorithm to classify Iris flowers into different species based on their physical features.

This project focuses on practicing the fundamental workflow of a **Machine Learning classification problem**, including data exploration, feature preprocessing, model training, prediction, and evaluation.

---

## 📌 Project Overview

The goal of this project is to predict the species of an Iris flower using four numerical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The classification is performed using the **K-Nearest Neighbors (KNN)** algorithm.

---

## 📊 Dataset

The project uses the well-known **Iris dataset**, containing **150 samples** from three different Iris species.

Each sample contains four numerical features:

| Feature      | Description         |
| ------------ | ------------------- |
| Sepal Length | Length of the sepal |
| Sepal Width  | Width of the sepal  |
| Petal Length | Length of the petal |
| Petal Width  | Width of the petal  |

The `target` column represents the Iris flower class.

---

## ⚙️ Machine Learning Workflow

The project follows these main steps:

1. Load the dataset
2. Explore the data
3. Analyze the target class distribution
4. Select features and target
5. Split the data into training and testing sets
6. Scale the features using `StandardScaler`
7. Train the KNN classifier
8. Make predictions
9. Evaluate model performance
10. Test different values of `K`

---

## 🤖 K-Nearest Neighbors

**K-Nearest Neighbors (KNN)** is a supervised Machine Learning algorithm used for classification and regression.

For classification, KNN determines the class of a new data point based on the classes of its nearest neighbors.

The `K` parameter determines how many neighboring data points are considered when making a prediction.

In this project, multiple values of `K` are tested to observe their effect on model accuracy.

---

## 📈 Model Evaluation

The model performance is evaluated using **Accuracy Score**.

Accuracy represents the proportion of correctly classified samples out of all test samples.

Different values of `K` are also compared to analyze how the choice of `K` affects the model's performance.

---

## 📊 Results

The model achieved an accuracy of **100%** on the test set for the selected train/test split.

---

## 🛠️ Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 📁 Project Structure

```text
iris-knn-classification/
│── data/
|   └── iris.csv
|
├── notebooks/
│   └── iris_knn.ipynb
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Mobin-Madadi/iris-knn-classification.git
```

### 2. Navigate to the project directory

```bash
cd iris-knn-classification
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
notebooks/iris_knn.ipynb
```

---

## 🎯 Learning Objectives

Through this project, I practiced:

* Machine Learning classification
* K-Nearest Neighbors
* Feature scaling
* Train/Test splitting
* Model training and prediction
* Model evaluation
* Hyperparameter experimentation with `K`
* Data visualization

---

## 📚 Future Improvements

Possible improvements for this project include:

* Adding a confusion matrix
* Adding a classification report
* Experimenting with different distance metrics
* Comparing KNN with other classification algorithms

---

## 👨‍💻 Author

**Mobin Madadi**

Python Developer | Machine Learning Developer in Progress

🔗 [GitHub Profile](https://github.com/Mobin-Madadi)
