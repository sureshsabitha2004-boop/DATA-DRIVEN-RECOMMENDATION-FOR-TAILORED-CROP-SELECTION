# 🌱 Data-Driven Recommendation for Tailored Crop Selection

## 📌 Project Overview

The **Data-Driven Recommendation for Tailored Crop Selection** project is a Machine Learning-based agricultural recommendation system designed to help farmers select suitable crops based on soil properties and environmental conditions.

The system analyzes agricultural parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, rainfall, and soil pH to identify suitable crops.

The project uses data analysis, exploratory data analysis (EDA), and multiple Machine Learning algorithms to improve crop selection and support smart agriculture.

## 🎯 Project Objectives

- Recommend suitable crops based on soil and environmental conditions.
- Analyze soil nutrient levels and climatic factors.
- Apply Machine Learning algorithms for crop classification.
- Compare different algorithms based on model performance.
- Improve agricultural decision-making through data-driven insights.
- Promote sustainable and precision agriculture.

## ⚙️ Key Features

- Agricultural dataset analysis.
- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Soil nutrient analysis (NPK).
- Correlation analysis and heatmap visualization.
- Machine Learning model training.
- Crop recommendation and prediction.
- Model performance comparison.
- Confusion matrix and classification report.
- Feature distribution visualization.

## 🛠️ Technologies Used

**Programming Language**

- Python

**Python Libraries**

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

**Development Tools**

- Google Colab

## 🤖 Machine Learning Algorithms

The project explores multiple Machine Learning algorithms:

1. Random Forest Classifier
2. Decision Tree Classifier
3. Logistic Regression
4. Support Vector Machine (SVM)

The Random Forest Classifier achieved the best performance among the models listed in the experimental results.

## 📊 Dataset Parameters

| Parameter      | Description                |
| -------------- | -------------------------- |
| Nitrogen (N)   | Soil nitrogen level        |
| Phosphorus (P) | Soil phosphorus level      |
| Potassium (K)  | Soil potassium level       |
| Temperature    | Environmental temperature  |
| Humidity       | Atmospheric humidity       |
| Rainfall       | Rainfall measurement       |
| pH             | Soil acidity or alkalinity |

## 🔄 Project Workflow

1. Dataset Collection: Collect soil and weather data, including N, P, K, pH, temperature, rainfall, and humidity.
2. Data Splitting: Split the dataset into training (70–80%) and testing (20–30%) data.
3. Feature Extraction: Identify important soil nutrients and environmental features.
4. Ensemble Model: Train and compare Random Forest, Decision Tree, KNN, SVM, and other machine learning models.
5. Rules Induction: Generate decision rules based on trained models.
6. Crop Recommendation: Apply the derived rules to recommend suitable crops.
7. Crop Yield Prediction: Display the recommended crop and expected yield.

## 📈 Model Performance Results

The following results are reported in the project research paper:

| Machine Learning Model | Accuracy |
| ---------------------- | -------: |
| Random Forest          |   99.19% |
| Decision Tree          |   98.38% |
| Logistic Regression    |   97.57% |
| Support Vector Machine |   97.30% |

**Best Performing Model:** Random Forest Classifier

Random Forest achieved the highest accuracy of **99.19%** in the reported experiment.

## 📉 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Cross-Validation

Additional visualizations include:

- Model accuracy comparison.
- Correlation heatmap.
- Confusion matrix.
- Classification report.
- Feature distribution plots.

## 🌾 Applications

- Smart Agriculture
- Precision Farming
- Crop Selection
- Agricultural Decision Support
- Sustainable Farming
- Data-Driven Agricultural Planning

🚀 Conclusion

This project demonstrates the application of Machine Learning in agriculture to support intelligent crop selection. By analyzing soil nutrients and environmental conditions, the system identifies suitable crop recommendations.

The experimental results demonstrate that the Random Forest Classifier achieved the highest accuracy of 99.19% among the models compared in the research paper.

The project highlights the potential of data science and predictive modeling in improving agricultural decision-making and supporting sustainable farming practices.

---

