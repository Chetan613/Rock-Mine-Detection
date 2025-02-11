# Rock_Mine_Detection


This project focuses on classifying objects as either rocks or mines using machine learning models. The dataset used is the **Sonar Dataset**, which contains information based on sonar signals. The project is aimed at achieving accurate classification through a comparison of different machine learning algorithms.

## Project Overview
- **Domain**: Binary Classification
- **Dataset**: [Sonar Dataset]
- **SDG Goal**: Industry, Innovation, and Infrastructure

## Features
1. **Models Used**:
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
   - Logistic Regression
2. **Metrics Evaluated**:
   - Accuracy
   - Classification Reports
   - Confusion Matrices
3. **Frontend**: KNN results visualized.
4. **Dataset Split**: 90% training data, 10% testing data.

## Tools and Libraries
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Workflow
1. **Data Preprocessing**:
   - Loading the dataset
   - Handling missing/null values (if any)
   - Feature scaling
2. **Model Implementation**:
   - Training and testing each of the four models
   - Comparing performance using metrics
3. **Frontend Integration**:
   - Visualizing KNN model results

## Results
The project provides insights into the performance of different models on the sonar dataset. The confusion matrix and classification report highlight the strengths of each model in identifying rocks and mines accurately.

## How to Use

1. Run the project:
   - For frontend: Navigate to the respective folder and follow instructions.
   - For backend analysis: Execute the Python scripts.

## Files in Repository
- **dataset.csv**: The Sonar Dataset used for training and testing.
- **knn_frontend.py**: Frontend visualization of KNN model results.
- **model_comparison.ipynb**: Notebook with code for training and evaluating all models.
- **requirements.txt**: List of dependencies.

## Future Scope
- Deploying the project on a web platform.
- Incorporating additional advanced machine learning models.
- Fine-tuning the models for improved accuracy.
