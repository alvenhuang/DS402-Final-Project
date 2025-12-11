# Diabetes Risk Prediction Final Project — README (DS402)

Hello and Welcome! This repository contains our final version of our Diabetes Risk Prediction project that we developed for DS402. All of our code, modeling, and results are all contained within one Jupyter Notebook:

- **DS402FinalProject.ipynb**

---

## Project Overview

So the main goal of this project was to build and evaluate machine learning models that predict whether an individual is at risk of diabetes based on health/demographic features. We chose this topic because early detection of diabetes is a very important real-world problem, as it can support preventative care and better long-term health outcomes. We explored how both traditional and neural-network-based classification models perform on our chosen dataset.

---

## What This Project Includes

Our final notebook covers the full machine learning pipeline, including:

- Data loading and preprocessing  
- Baseline classification models  
- Multilayer Perceptron (MLP) implementation  
- Model evaluation using a variety of classification metrics  
- Visual analysis of results  


---

## Dataset

The dataset used in this project is the **Early-Stage Diabetes Risk Prediction Dataset**, available on Kaggle.

- **Link:** https://www.kaggle.com/datasets/ishandutta/early-stage-diabetes-risk-prediction-dataset/data  


---

## Running the Notebook

To run the notebook successfully, please download the dataset CSV file and place it in the same directory as the notebook or in the project’s data directory (the `sample_data/` folder)

Our notebook reads the data using the following line:

df = pd.read_csv("Early stage diabetes risk prediction dataset (1).csv")

---


## Extra Notes

- All required dependencies are either standard Python libraries or are installed directly within the notebook using pip.
- The notebook is self-contained and can be run top-to-bottom to reproduce results.


---

Thank You,


Qasim Ansari and Alven Huang
