# Air Quality Analysis and Prediction Using Deep Learning

## Project Overview
This project performs Exploratory Data Analysis (EDA), visualization, data preprocessing, and deep learning-based regression using the UCI Air Quality dataset.

An MLP neural network is used to estimate carbon monoxide concentration (CO(GT)) from other numerical air quality measurements.

## Objectives
- Analyse air quality measurements.
- Identify missing values, duplicates, and potential outliers.
- Visualize pollutant distributions and relationships.
- Train a deep learning regression model.
- Evaluate model performance using regression metrics.

## Dataset
- **Source:** UCI Machine Learning Repository
- **Dataset:** Air Quality
- **URL:** https://archive.ics.uci.edu/dataset/360/air+quality
- **Original observations:** 9,358
- **Original attributes:** 15

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TensorFlow/Keras
- Google Colab

## Model
A Multilayer Perceptron (MLP) regression model is used to estimate CO(GT). The model contains two hidden layers with 64 and 32 neurons, respectively.

## Evaluation Results

| Metric | Test Result |
|---|---:|
| MAE | 0.4542 |
| RMSE | 0.6097 |
| R² | 0.7861 |

These results are from the current notebook run. They should be interpreted in the context of the selected features, preprocessing procedure, and chronological test split.

## How to Run
1. Download the Jupyter notebook from this repository.
2. Open Google Colab.
3. Upload the notebook.
4. Run the cells in sequence.
5. Refer to the UCI dataset source if you need to download the dataset separately.

## Project Files
- `Air_Quality_Analysis_Deep_Learning.ipynb` – Source code and analysis.
- `Project_Report.pdf` – Final project report.
- `Project_Report.docx` – Editable report.
- `requirements.txt` – Python dependencies.

## Limitations
The model estimates measured CO concentration from available inputs. It does not directly forecast future air quality. Results may not generalize to other locations or time periods without additional validation.
