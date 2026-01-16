# Placement Predictor (CGPA & IQ)

## Overview

This project is a beginner-friendly machine learning application that predicts whether a student is likely to be placed based on their **CGPA** and **IQ**.
It is built as a **toy project** to understand and practice the complete **end-to-end machine learning workflow**, from data preprocessing to model evaluation and export.


## Objectives

* Understand data preprocessing techniques
* Perform exploratory data analysis (EDA)
* Visualize relationships using scatter plots
* Build and evaluate a classification model
* Export the trained model for reuse


## Tech Stack

* **Language:** Python
* **Libraries:**

  * NumPy
  * Pandas
  * Matplotlib
  * Scikit-learn
* **Environment:** Jupyter Notebook


## Workflow

The project follows a structured ML pipeline:

1. **Preprocessing**

   * Data cleaning
   * Feature scaling

2. **Exploratory Data Analysis (EDA)**

   * Understanding data distribution
   * Visualizing trends and patterns

3. **Visualization**

   * Scatter plots between CGPA and IQ
   * Placement outcome analysis

4. **Feature Selection**

   * Selecting relevant input features

5. **Input & Output Extraction**

   * Input: CGPA, IQ
   * Output: Placement status

6. **Train-Test Split**

   * Splitting data for training and evaluation

7. **Model Training**

   * Training a classification model

8. **Model Evaluation**

   * Accuracy score calculation
   * Performance analysis

9. **Model Export**

   * Saving the trained model for future use
  

## Dataset

The dataset contains student information with the following features:

* **CGPA** – Academic performance indicator
* **IQ** – Cognitive ability measure
* **Placement** – Target variable (Placed / Not Placed)

> Note: This dataset is used purely for learning and demonstration purposes.



## Results

* The model predicts placement status based on CGPA and IQ.
* Accuracy is evaluated using standard metrics from `scikit-learn`.



## Limitations

* This is a toy project intended for learning purposes.
* The dataset is small and not suitable for real-world deployment.
* The model should not be used for actual placement decisions.
