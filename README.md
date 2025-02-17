### 🚢 Titanic Survival Prediction - Machine Learning

## 🚀 About
**Titanic Survival Prediction** is a machine learning project that aims to predict the survival chances of passengers aboard the Titanic using various features such as age, gender, ticket class, and more. The project employs machine learning techniques to analyze the dataset and build a predictive model with high accuracy. This repository serves as a demonstration of data preprocessing, feature engineering, model training, and evaluation. 📊🤖

## ⚡ Features
- **📊 Data Preprocessing**: Cleans and preprocesses the Titanic dataset to handle missing values, categorical variables, and feature scaling.
- **📈 Exploratory Data Analysis (EDA)**: Visualizes data trends, correlations, and distributions to gain insights.
- **🧠 Machine Learning Models**: Implements various models including Logistic Regression, Decision Trees, Random Forest, and Support Vector Machines (SVM) for classification.
- **🏆 Model Evaluation**: Uses accuracy, precision, recall, F1-score, and ROC-AUC metrics to evaluate model performance.
- **🔄 Hyperparameter Tuning**: Optimizes model parameters using Grid Search and Randomized Search.
- **💾 Deployment Ready**: The trained model can be deployed for real-world Titanic survival predictions.

## 🛠️ How to Run

### 📋 Requirements
- Python 3.x
- Jupyter Notebook / Any Python IDE
- Required Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### 💻 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MohamedBoghdaddy/Titanic-Survival-Prediction.git
   cd Titanic-Survival-Prediction
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   Open `titanic_survival.ipynb` and execute the cells to train and evaluate the model.

## 📂 Project Structure
```
📁 Titanic-Survival-Prediction
│── 📂 data                # Dataset files (train.csv, test.csv)
│── 📂 notebooks           # Jupyter Notebooks for analysis & modeling
│── 📂 models              # Saved trained models
│── 📂 reports             # Documentation and model performance reports
│── titanic_survival.py    # Python script for model training & inference
│── requirements.txt       # List of dependencies
│── README.md              # Project documentation
```

## 🧑‍💻 Project Workflow
1. **Load Dataset**: Import Titanic dataset and explore missing values.
2. **Data Cleaning & Feature Engineering**: Handle missing data, encode categorical features, and create new useful features.
3. **EDA**: Visualize relationships, survival rates, and feature importance.
4. **Model Training & Evaluation**: Train multiple machine learning models and evaluate their performance.
5. **Hyperparameter Tuning**: Optimize best-performing model.
6. **Predictions**: Use the trained model to predict survival probabilities.

## 📊 Results & Insights
- Feature importance analysis showed **gender**, **ticket class**, and **age** as strong indicators of survival.
- Random Forest and Logistic Regression achieved the best results with an **accuracy of ~80%**.
- The model is ready for deployment and can be further improved with more advanced techniques.

## 📜 Dataset
The dataset used in this project is the **Kaggle Titanic Dataset**:
- **train.csv**: Used to train the model.
- **test.csv**: Used for final predictions.

## 🤝 Contributing
Feel free to fork the repository, make improvements, and submit pull requests. Any feedback or suggestions are welcome!

## 📄 License
This project is open-source and available under the MIT License.

---
🚀 **Let's predict who survives the Titanic!**
