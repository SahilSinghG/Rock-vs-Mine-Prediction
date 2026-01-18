# Sonar Rock vs Mine Prediction

This project uses **Machine Learning** to classify underwater objects as either **Rocks** or **Mines** based on sonar frequency responses. This is a binary classification problem using a dataset of 60 different sonar signal frequencies.



## 📋 Project Overview
The model is designed to assist in naval navigation and safety by identifying potentially hazardous mines. Using a Logistic Regression algorithm, the model learns the patterns in sonar data to distinguish between the solid, irregular surfaces of rocks and the metallic, structured surfaces of mines.

- **Dataset:** 208 observations with 60 feature columns.
- **Target:** 'R' for Rock, 'M' for Mine.
- **Algorithm:** Logistic Regression.

## 🛠️ Technologies Used
- **Python 3.x**
- **Pandas** & **NumPy** (Data processing)
- **Scikit-Learn** (Machine Learning)
- **Matplotlib** (Visualization)
- **Git/GitHub** (Version Control)

## 📁 Repository Structure
```text
├── Copy of sonar data.csv       # Dataset file
├── Rock vs Mine Prediction.ipynb # Main project notebook
├── .gitignore                   # Files ignored by Git
└── README.md                    # Project documentation

## Model Performance
The data was split into Training (90%) and Test (10%) sets using stratification to maintain class balance.

Training Accuracy: ~83%

Test Accuracy: ~76% (Note: Accuracy may vary slightly depending on random_state settings).

Prediction System
The project includes a dedicated section for real-time prediction. By providing a 60-element array of sonar frequency data, the system will output:

Result: "The object is a Rock"

Result: "The object is a Mine"
