# Diabetes-Prediction-Using-Keras
In this project, we will predict diabetes with a neural network model using the Python Keras library. We'll use libraries like Seaborn and matplotlib to create visualizations, and then evaluate the model.  
This project utilizes a neural network model implemented in Python with the Keras library to predict diabetes in individuals. The model is trained on the Pima Indians Diabetes dataset, which includes features such as pregnancies, glucose levels, blood pressure, and more.

## Features
### Data Preprocessing: 
Handle missing values, and address data skewness and scale features.
### Exploratory Data Analysis (EDA): 
Visualize trends in the dataset, identify correlations, and gain insights into feature distributions.
### Neural Network Model: 
Build a simple neural network using Keras and TensorFlow.
### Model Evaluation: 
Assess model performance using classification metrics and visualizations.

## Dataset
The dataset used for this project is the Pima Indians Diabetes dataset. You can find it [here](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

## Run the Code
```
python Diabetes_Prediction_Using_Keras.py

```
## Dependencies
 * scikit-learn
 * pandas
 * numpy
 * seaborn
 * matplotlib
 * Keras

## Project Structure
```
├── data/
│   └── diabetes.csv
├── model/
│   ├── model.json
│   └── model.h5
├── src/
│   └── Diabetes_Prediction_Using_Keras.py
├── README.md

```
## Visualizations

### Pairplot showing relationships between features and outcomes.

![output](https://github.com/radhika3131/Diabetes-Prediction-Using-Keras/assets/102825662/8d6f598c-48f0-4ec7-8361-2ead6aeb7352)


### correlation matrix for predicting the most relevant variable for linear regression

![output2](https://github.com/radhika3131/Diabetes-Prediction-Using-Keras/assets/102825662/6c955d27-43f2-46ad-a31a-766e55f8615f)


### Distribution plot to see how distribution has changed

![output3](https://github.com/radhika3131/Diabetes-Prediction-Using-Keras/assets/102825662/5ca59dc9-69fd-499e-a5db-dc5a083bbe46)


### plots of the training and validation accuracies and losses with the epochs on the x-axis. 

![output4](https://github.com/radhika3131/Diabetes-Prediction-Using-Keras/assets/102825662/96a694af-d470-4a18-84d7-1a88159f5cc6)


## Result
* Achieved an accuracy of 75.97% on the test set.
* A detailed confusion matrix and classification metrics are available in the 'result' directory.

## Acknowledgments
Thanks to the National Institute of Diabetes and Digestive and Kidney Diseases for providing the dataset.
