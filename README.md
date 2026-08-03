# Support Vector Machines (SVM) Project

## 📌 Overview
This project explores the **Support Vector Machines (SVM)** algorithm for classification tasks. The goal is to predict target labels based on various features using SVM with different kernels. The dataset is preprocessed, visualized, and used to train multiple SVM models to compare their performance.

## 📂 Project Structure
```
├── data/                  # Dataset used for training and testing
├── notebooks/             # Jupyter notebooks with step-by-step implementations
├── src/                   # Python scripts for model training and evaluation
├── results/               # Outputs, plots, and model performance metrics
├── visualizations/        # Visual representations of results
├── README.md              # Project documentation
└── requirements.txt       # Dependencies required to run the project
```

## 📊 Dataset
The dataset used in this project is the **Iris Flower Dataset**, which consists of 150 samples from three species:
- **Iris Setosa**
- **Iris Versicolor**
- **Iris Virginica**

Each sample has **four features** measured in centimeters:
- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

## 🚀 Installation
### 1️⃣ Clone the repository:
```bash
git clone https://github.com/27abhishek27/Support-Vector-Machines-Project.git
cd Support-Vector-Machines-Project
```

### 2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

## 🔍 Methodology
### 1. **Data Preprocessing**
- **Handling Missing Values**: Checked for missing values and handled them appropriately.
- **Feature Scaling**: Applied standardization to ensure better model performance.
- **Train-Test Split**: Split the dataset into training and testing sets.

### 2. **Exploratory Data Analysis (EDA)**
- **Class Distribution**: Visualized the target class distribution.
- **Feature Correlations**: Identified relationships between features.
- **Pairplots & Boxplots**: Explored data distribution and outliers.

### 3. **Model Training**
- **Linear SVM**: Trained a baseline linear SVM model.
- **Polynomial Kernel SVM**: Implemented an SVM with a polynomial kernel.
- **RBF Kernel SVM**: Applied the radial basis function (RBF) kernel for complex decision boundaries.
- **Hyperparameter Tuning**: Used `GridSearchCV` to optimize SVM parameters.

### 4. **Model Evaluation**
- **Accuracy, Precision, Recall, F1-score**: Measured model performance.
- **Confusion Matrix**: Assessed false positives and false negatives.
- **Decision Boundaries**: Visualized how SVM separates different classes.

## 📊 Visualizations
All generated plots and graphs are stored in the `visualizations/` folder. These include:
- **A pairplot of the data set. Which flower species seems to be the most separable**: ![Most separable](https://github.com/27abhishek27/Support-Vector-Machines-Project/blob/main/Support%20Vector%20Machines%20Project%20png/pairplot%20for%20which%20flower%20species%20seems%20.png)
- **A kde plot of sepal_length versus sepal width for setosa species of flower**: ![setosa species of flowers](https://github.com/27abhishek27/Support-Vector-Machines-Project/blob/main/Support%20Vector%20Machines%20Project%20png/kde%20plot%20of%20sepal_length%20versus%20sepal%20width.png)

## 🛠️ Technologies Used
- **Python**
- **Scikit-learn**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Jupyter Notebook**

## 📌 Future Improvements
- **Feature Engineering**: Create new features for improved predictions.
- **Comparison with Other Models**: Implement decision trees, logistic regression, and neural networks.
- **Deployment**: Convert the model into a Flask or FastAPI service for real-world use.


"# Support-Vector-Machine-Implementation-from-Scratch" 
