Iris Species Classification using KNN

This project builds a machine learning model to classify Iris flower species (Setosa, Versicolor, and Virginica) using sepal and petal measurements from the Iris dataset.

The dataset contains 150 samples and four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

## Project Objective
The goal of this project is to develop a predictive model that can accurately identify the species of an unseen Iris flower using machine learning techniques.

## Methodology
1. Data Loading and Exploration using pandas
2. Data Preprocessing and train-test split
3. Model Training using K-Nearest Neighbors (KNN)
4. Model Evaluation using accuracy

## Results
The KNN model achieved **96.7% accuracy** on the test dataset.

## Technologies Used
- Python
- pandas
- scikit-learn
- NumPy
- Matplotlib

## Project Structure
data/ → Dataset used for training  
src/ → Machine learning model code  
notebooks/ → Jupyter notebook for analysis  

## How to Run the Project

1. Install required libraries
pip install -r requirements.txt

2. Run the model
python src/knn_model.py

## Future Improvements
- Hyperparameter tuning
- Compare with other algorithms
- Add visualization and confusion matrix
- Improve model performance
