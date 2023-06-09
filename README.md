# Heart_disease_prediction_using_AI
# Heart Disease Prediction using AI

This project aims to predict heart disease using AI. It utilizes a dataset containing clinical records of heart failure patients and builds a machine learning model to predict the likelihood of death events.

## Notebook Information

The Jupyter Notebook file "Heart_disease_prediction_using_AI.ipynb" is the main file for this project. It was originally created in Colaboratory and can be accessed at the following link: [Heart_disease_prediction_using_AI.ipynb](https://colab.research.google.com/github/rishuvro/Heart_disease_prediction_using_AI/blob/main/Heart_disease_prediction_using_AI.ipynb)

## Getting Started

To run the notebook locally, please follow the instructions below:

1. Clone the repository: `git clone https://github.com/rishuvro/Heart_disease_prediction_using_AI.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open the notebook in Jupyter or a compatible environment.(Google Colab)

## Dataset

The dataset used in this project is named "heart_failure_clinical_records_dataset.csv". It contains various clinical features of heart failure patients, including age, ejection fraction, serum creatinine levels, and more. The target variable is "DEATH_EVENT", indicating whether the patient experienced a death event or not.

## Model Training

The notebook describes the process of building a deep learning model using the Keras library. The model architecture consists of multiple dense layers with dropout regularization. The model is trained using the Adam optimizer and binary cross-entropy loss. Early stopping is implemented to prevent overfitting.

## Evaluation

The validation accuracy of the trained model is calculated and printed. Predictions are made on the test set, and a confusion matrix is generated to evaluate the model's performance. The confusion matrix is visualized as a heatmap using the seaborn library.

## Acknowledgements

The original notebook for this project was created by [rishuvro](https://github.com/rishuvro) and can be found in the repository [Heart_disease_prediction_using_AI](https://github.com/rishuvro/Heart_disease_prediction_using_AI).


