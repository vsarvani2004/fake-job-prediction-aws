# Fake Job Prediction System Using AWS SageMaker Canvas

## Project Overview

The Fake Job Prediction System is an AWS-based machine learning project designed to classify online job postings as genuine or potentially fraudulent. It uses the Fake Job Postings dataset and Amazon SageMaker Canvas to build a machine learning classification model with minimal coding.

The project aims to help job seekers identify suspicious job advertisements and make more informed decisions when applying for jobs.

## Objectives
* Identify potentially fraudulent job postings.
* Prepare and validate job posting data before model training.
* Use AWS cloud services for data storage and machine learning.
* Evaluate model performance using standard classification metrics.

## Technologies Used
* **Amazon SageMaker Canvas** — Visual machine learning model development and prediction.
* **Amazon S3** — Cloud storage for the processed dataset.
* **AWS IAM** — Access and permission management.
* **Python** — Data preprocessing and validation.
* **Google Colab** — Data preparation and experimentation.
* **Kaggle** — Source of the Fake Job Postings dataset.

## Project Workflow
1. **Dataset Collection:** Obtain the Fake Job Postings dataset from Kaggle.
2. **Data Preprocessing:** Use Python to handle missing values, duplicates, and inconsistent data.
3. **Cloud Storage:** Upload the processed dataset to Amazon S3.
4. **Model Development:** Import the dataset into SageMaker Canvas and configure a binary classification model using the `is_fake` target column.
5. **Model Evaluation:** Review classification metrics such as accuracy, precision, recall, F1-score, and the confusion matrix.
6. **Prediction:** Use the trained model to classify job postings as genuine or potentially fraudulent.

## System Architecture
Kaggle Dataset → Python Data Preprocessing → Amazon S3 → Amazon SageMaker Canvas → Model Evaluation → Job Posting Prediction

## Expected Outcome
The system demonstrates how AWS cloud services and machine learning can be used to support job-posting fraud detection. Its predictions can help flag potentially fraudulent listings for further verification.

## Limitations
* Predictions depend on the quality and representativeness of the dataset.
* Model performance may vary on new or unseen job postings.
* Predictions should be treated as indicators rather than definitive proof of fraud.

## Future Enhancements
* Develop a web interface for submitting job descriptions.
* Integrate an automated prediction workflow.
* Explore additional features and model evaluation techniques.
* Deploy the solution for easier access by job seekers.

## Project Status

Academic major project — AWS-based machine learning classification using SageMaker Canvas.

**Note:** This repository documents the project workflow. Add the actual preprocessing notebook, dataset source, architecture diagram, and model evaluation evidence as available.
