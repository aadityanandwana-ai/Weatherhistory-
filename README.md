# Weatherhistory-
# 🌦️ Weather History Classification Using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to analyze historical weather data and classify weather conditions. It implements **Random Forest** and **Gradient Boosting** algorithms to compare classification performance and identify influential weather features.

## 🎯 Objectives

- Analyze historical meteorological data.
- Clean and preprocess weather datasets.
- Classify weather conditions into meaningful categories.
- Train and evaluate machine learning models.
- Compare model accuracy and feature importance.
- Visualize weather patterns and classification results.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Development Environment:** Jupyter Notebook / Google Colab

## 🤖 Machine Learning Models

**1. Random Forest Classifier**

An ensemble learning algorithm that combines multiple decision trees to improve classification performance.

**2. Gradient Boosting Classifier**

An ensemble learning algorithm that builds models sequentially to improve prediction accuracy.

## 📊 Model Performance

| Algorithm | Accuracy |
|---|---|
| Random Forest | 86.16% |
| Gradient Boosting | 85.24% |

**Best Overall Accuracy: Random Forest — 86.16%**

Models were evaluated using an 80/20 stratified train-test split, classification reports, and confusion matrices.

## 📈 Data Visualization

The project includes:

- Weather category distribution
- Confusion matrix analysis
- Random Forest feature importance
- Machine learning model accuracy comparison

📄 [View Project Visualizations](weather_ml_visualizations.pdf)

## 📂 Repository Files

- `WEATHERHISTORY.ipynb` — Complete machine learning implementation
- `weather_ml_visualizations.pdf` — Project graphs and visualizations
- `README.md` — Project documentation

## ▶️ How to Run

1. Download or clone this repository.
2. Open `WEATHERHISTORY.ipynb` in Google Colab or Jupyter Notebook.
3. Obtain the required `weatherHistory.csv` dataset.
4. Update the dataset path if necessary.
5. Install the required Python libraries.
6. Run the notebook cells sequentially to reproduce the analysis.

## 🔍 Key Findings

- Random Forest achieved the highest overall classification accuracy.
- Feature importance analysis helps identify influential weather variables.
- Weather category imbalance affects classification performance, particularly for less frequent categories.
- Accuracy alone does not fully represent performance across every weather category.

## 🚀 Future Improvements

- Improve classification of minority weather categories.
- Experiment with additional algorithms and hyperparameter tuning.
- Develop an interactive weather classification application.
- Explore deployment as a predictive machine learning service.

## 📌 Conclusion

This project demonstrates practical applications of Python, data preprocessing, exploratory data analysis, supervised machine learning, and model evaluation for weather classification.

The results highlight the importance of model comparison and class-level evaluation when building data-driven classification systems.
