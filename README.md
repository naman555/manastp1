# manastp1

# Machine Learning Basics Assignment

## Not Regressing Forward, Just Subtracting Ahead

This repository contains implementations of **Linear Regression and Logistic Regression from scratch** using Python and NumPy. The project focuses on understanding the mathematical foundations of machine learning, including cost functions, gradients, Gradient Descent, and model evaluation.

## 📌 Project Overview

The assignment contains two tasks:

### 1. Linear Regression

**Objective:** Predict the closing price (`Close`) using the provided training and testing datasets.

**Key concepts:**

* Linear Regression model: \(\hat{y}=Xw+b\)
* Data preprocessing and missing-value handling
* One-Hot Encoding for categorical features
* Feature standardisation
* Mean Squared Error (MSE) cost function
* Gradient calculation and Gradient Descent
* Training over multiple epochs
* Cost-versus-epoch visualisation
* Model evaluation using regression metrics

**Evaluation metrics:** Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and \(R^2\), where implemented in the notebook.

### 2. Logistic Regression

**Objective:** Predict whether a crime case is closed using the provided crime datasets.

**Key concepts:**

* Binary classification
* Sigmoid function
* Probability estimation and decision threshold
* Binary Cross-Entropy (BCE) loss
* Gradient calculation and Gradient Descent
* Training over multiple epochs
* Training and testing accuracy
* Loss and accuracy visualisations

**Evaluation metric:** Classification accuracy, with additional metrics where implemented.

## 🛠️ Technologies Used

* **Python** for implementation
* **NumPy** for numerical calculations and matrix operations
* **Pandas** for data loading and preprocessing
* **Matplotlib** for visualisation
* **Jupyter Notebook** for development, experimentation, and documentation

The core regression models and their training algorithms are implemented from scratch rather than relying on prebuilt regression estimators.

## 📂 Repository Structure

```text
ML-Basics-Assignment/
│
├── README.md
│
├── Linear_Regression_from_Scratch.ipynb
├── train.csv
├── test.csv
│
├── Logistic_Regression_from_Scratch.ipynb
├── crime_train.csv
└── crime_test.csv
```

*The structure above assumes that all four CSV files are uploaded alongside their respective notebooks.*

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd ML-Basics-Assignment
```

Replace `<YOUR_GITHUB_REPOSITORY_URL>` with your repository's actual URL.

### 2. Install the dependencies

```bash
python -m pip install numpy pandas matplotlib jupyter
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

Open either notebook in Jupyter and execute the cells in order.

## 🔬 Methodology

Both implementations follow the general machine learning workflow:

1. Load the training and testing datasets.
2. Inspect and preprocess the data.
3. Handle missing values and encode categorical variables where necessary.
4. Fit preprocessing transformations using training data only.
5. Initialise model parameters.
6. Calculate predictions and the relevant cost function.
7. Calculate gradients and update parameters using Gradient Descent.
8. Repeat training over multiple epochs.
9. Record the required metrics and visualise training progress.
10. Evaluate the trained model on the separate test dataset.

The test datasets are reserved for evaluation and are not used to fit the model parameters.

## 📈 Learning Outcomes

Through this assignment, the project explores:

* The mathematical foundations of regression algorithms
* The role of features, weights, and bias
* Cost functions and optimisation
* Gradients and the learning rate
* Epochs and iterative model training
* One-Hot Encoding and feature standardisation
* The difference between regression and classification
* Training versus testing performance
* Model evaluation and visualisation

## 📚 Learning Resources

* [Machine Learning Specialization by Andrew Ng on Coursera](https://www.coursera.org/learn/machine-learning)
* [Andrew Ng's Machine Learning Specialization YouTube playlist](https://www.youtube.com/playlist?list=PLkDaE6sCZn6FNC6YRfRQc_FbeQrF8BwGI)
* [Stanford CS229 Machine Learning lectures](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU)
* [CS229 lecture notes](https://github.com/maxim5/cs229-2018-autumn)
* [Machine Learning Specialization notes](https://github.com/greyhatguy007/Machine-Learning-Specialization-Coursera)

## 👨‍💻 Author

Machine Learning Basics Assignment

**Project:** Not Regressing Forward, Just Subtracting Ahead
