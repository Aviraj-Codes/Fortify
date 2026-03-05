## Fortify - Credit Card Fraud Detection System

## Project Overview

This project implements a Credit Card Fraud Detection System using Machine Learning with a FastAPI backend and an interactive frontend interface.
A fraud detection model is trained externally on Kaggle using a real-world credit card transaction dataset. The trained model is exported and integrated into this application strictly for inference and prediction, not for training.
The system analyzes transaction attributes and determines whether a transaction is fraudulent or legitimate, returning a risk probability score that is displayed through an animated scanning interface.
The project demonstrates a complete machine learning deployment pipeline, including model integration, API development, and frontend visualization.

## Objectives

* Identify fraudulent credit card transactions using a machine learning model
* Deploy a pretrained model without local retraining
* Build a prediction API using FastAPI
* Connect a frontend interface with the backend service
* Visualize fraud risk through an interactive scanning interface
* Maintain a clean and structured GitHub project architecture

## Dataset Information

Dataset: Credit Card Transactions Fraud Dataset
Source: Kaggle
Problem Type: Binary Classification
Dataset Characteristic: Highly imbalanced dataset

## Technologies Used

* Python Ecosystem: Python, Pandas, NumPy, Scikit-learn
* Backend: FastAPI, Uvicorn
* Frontend: HTML, CSS, JavaScript
* Version Control: Git, GitHub

## System Workflow

1. A fraud detection model is trained using the Kaggle credit card dataset.
2. The trained model and preprocessing objects are exported as serialized artifacts.
3. The FastAPI backend loads these artifacts during server startup.
4. Transaction data is submitted from the frontend via a REST API request.
5. The backend performs model inference and calculates a fraud probability score.
6. The prediction result is returned to the frontend.
7. The interface visualizes the result using an animated fraud detection scan.

## License

This project is licensed under the MIT License.

The MIT License is a permissive open-source license that allows anyone to use, modify, distribute, and even use this software commercially, provided that the original copyright notice and license are included.

See the [LICENSE](LICENSE) file for full details.
