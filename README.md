# 🔥 Calorie Burnt Prediction Model

## 📌 Overview

This project is a Machine Learning-based system that predicts the number of calories burned during physical activities based on user inputs such as age, gender, height, weight, duration, heart rate, and body temperature.

The goal of this project is to apply software design principles and build a structured, modular, and efficient prediction system.

---

## 🚀 Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Model training using XGBoost Regressor
* Performance evaluation using metrics
* Predicts calories burned based on input parameters

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib & Seaborn
* Scikit-learn
* XGBoost

---

## 📂 Project Structure

```
ML-project.ipynb     # Main Jupyter Notebook
calories.csv        # Dataset (calories)
exercise.csv        # Dataset (exercise data)
README.md           # Project documentation
```

---

## ⚙️ Working of the Project

1. **Data Collection**
   Data is collected from CSV files containing exercise and calorie data.

2. **Data Processing**

   * Combining datasets
   * Handling missing values
   * Preparing features

3. **Exploratory Data Analysis**
   Visualization is done using graphs to understand patterns.

4. **Model Training**
   The model is trained using XGBoost Regressor.

5. **Evaluation**
   Performance is evaluated using metrics like Mean Absolute Error.

---

## 🧠 Software Design Concepts Used

### 🔹 Modularity

The project is divided into different parts like data loading, preprocessing, training, and evaluation.

### 🔹 Abstraction

Complex ML operations are handled using libraries like Scikit-learn and XGBoost.

### 🔹 Low Coupling

Each step (data processing, training, evaluation) works independently.

### 🔹 High Cohesion

Each module performs a specific task.

---

## 📊 Model Performance

The model is evaluated using regression metrics such as:

* Mean Absolute Error (MAE)
* Accuracy comparison

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/calorie-burn-prediction.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook:

```
jupyter notebook
```

---

## 📌 Future Improvements

* Add web interface (UI design)
* Deploy model using Flask or Streamlit
* Improve accuracy with more data

---

## 📖 Conclusion

This project demonstrates how machine learning and software design principles can be combined to build an efficient and scalable prediction system.

---

## 👨‍💻 Author

Eva Soni
