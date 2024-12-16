# Email Spam Detection using Machine Learning

This project involves building a machine learning model to detect spam emails from a dataset using various algorithms and techniques, such as Naive Bayes, Logistic Regression, and Support Vector Machines (SVM).

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset used for spam classification (e.g., `spam_data.csv`).
- `notebooks/`: Colab notebooks with code for data exploration, model training, and evaluation.
- `requirements.txt`: List of dependencies required to run the project.
- `README.md`: Project description and instructions.
- `LICENSE`: License for the project.

## Project Description

This project uses the **SMS Spam Collection** dataset, which contains labeled SMS messages (spam or ham) and builds machine learning models to classify messages as spam or non-spam.

The steps involved in the project are:
1. **Data Preprocessing**: Cleaning the dataset and preparing it for training.
2. **Feature Extraction**: Converting text messages into numerical representations (e.g., using TF-IDF).
3. **Model Training**: Training multiple machine learning models, such as Naive Bayes, Logistic Regression, and Support Vector Machines.
4. **Model Evaluation**: Evaluating model performance using accuracy, precision, recall, and F1-score metrics.

## Requirements

The following libraries are required to run the project. Install them using:

```bash
pip install -r requirements.txt
