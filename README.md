# AI-ML_Iris_task6
A simple machine learning project using K-Nearest Neighbors (KNN) to classify Iris flower species based on petal and sepal measurements. Includes data preprocessing, visualization, feature scaling, model training, hyperparameter tuning, and evaluation with scikit-learn.

KNN Classification on Iris Dataset

This project implements the K-Nearest Neighbors (KNN) classification algorithm using the Iris flower dataset. It demonstrates end-to-end machine learning pipeline including data exploration, visualization, feature scaling, model training, hyperparameter tuning, and evaluation.

---

📁 Dataset
- Classes:
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica
- Features:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm

---

📌 Objective

To classify Iris flower species using the KNN algorithm based on their petal and sepal measurements.

🛠️ Technologies Used

- Python
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Scikit-learn

---

📊 Workflow

1. Import Libraries  
2. Load the Dataset(`Iris.csv`)
3. Initial Data Inspection (info, describe, null checks, class distribution)
4. Data Cleaning
   - Drop unnecessary `Id` column
5. Data Visualization
   - Pairplot to see relationships
   - Countplot for class balance
6. Feature Selection
   - Separate features (X) and target (y)
7. Feature Scaling
   - Use `StandardScaler` to normalize features
8. Train/Test Split
   - 80% train, 20% test (stratified)
9. Train KNN Model (k=5)
10. Model Evaluation
    - Accuracy
    - Confusion Matrix
    - Classification Report
11. Hyperparameter Tuning
    - Loop from k=1 to 20
    - Plot accuracy vs. k
12. Final Model Training with Best K
13. Final Evaluation

---

✅ Key Learnings

- How KNN uses distance to classify samples
- Why feature scaling is important for distance-based algorithms
- How to visualize and evaluate classification models
- How to select the best hyperparameter using validation techniques


