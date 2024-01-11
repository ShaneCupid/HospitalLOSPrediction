# Hospital Length of Stay (LOS) Prediction

## Overview
This repository contains parts 1 and 2 of the Hospital Length of Stay (LOS) Prediction project. The goal is to use machine learning to predict the length of stay for patients in a hospital setting. The project leverages historical patient data to train predictive models, aiming to assist in resource allocation and operational planning.

## Technologies Used
- [Python 3](https://www.python.org/doc/) - A powerful programming language used for data science and machine learning tasks.
- [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/) - An open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text.
- [Pandas](https://pandas.pydata.org/docs/) - A fast, powerful, flexible and easy to use open-source data analysis and manipulation tool, built on top of the Python programming language.
- [Scikit-Learn](https://scikit-learn.org/stable/user_guide.html) - A free software machine learning library for Python that features various classification, regression and clustering algorithms.
- [TensorFlow](https://www.tensorflow.org/learn) - An end-to-end open-source platform for machine learning that has a comprehensive, flexible ecosystem of tools, libraries, and community resources.
- [Keras](https://keras.io/) - A deep learning API written in Python, running on top of the machine learning platform TensorFlow.
- [Matplotlib](https://matplotlib.org/stable/contents.html) - A plotting library for the Python programming language and its numerical mathematics extension NumPy.
- [Seaborn](https://seaborn.pydata.org/) - A Python data visualization library based on matplotlib that provides a high-level interface for drawing attractive and informative statistical graphics.


## Description
The project is divided into two main parts, each encapsulated in its respective Jupyter notebook:

- Part 1 involves data preprocessing, exploratory data analysis, and feature engineering.
- Part 2 focuses on model building, evaluation, and hyperparameter tuning.

### Hospital_LOS_Prediction_Part_1.ipynb
- **Input**: Dataset containing various patient metrics and previous LOS records.
- **Process**: 
  - Cleaning and normalizing the data.
  - Performing statistical analysis to understand the data's characteristics.
  - Feature engineering to prepare the data for machine learning models.

### Hospital_LOS_Prediction_Part_2.ipynb
- **Input**: Preprocessed data from Part 1.
- **Process**: 
  - Building and training different machine learning models.
  - Evaluating model performance with metrics like RMSE, MAE, and R².
  - Hyperparameter tuning to optimize the models.

## How It Works

### Data Preparation and Exploration (Part 1)
- Detailed cleaning and preprocessing of the hospital dataset.
- Visual and statistical analysis to extract insights and identify patterns.
- Feature engineering to enhance model performance.

### Model Building and Evaluation (Part 2)
- Implementation of various regression models using Scikit-Learn and TensorFlow/Keras.
- Comparison of model performance to select the best predictor.
- Tuning of model parameters for optimal predictions.

## Setup/Installation Requirements
1. Install Python 3 and the necessary libraries with `pip install jupyter pandas scikit-learn tensorflow matplotlib seaborn`.
2. Clone the repository to your local machine.
3. Run Jupyter Notebook and navigate to the `Hospital_LOS_Prediction_Part_1.ipynb` and `Hospital_LOS_Prediction_Part_2.ipynb` to view and run the notebooks.

## Contact Information
For any further queries or discussions, please contact me at cupidconsultingllc@gmail.com.

## License
The content of this project is licensed under the MIT License.
