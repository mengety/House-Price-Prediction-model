# 🏠 Melbourne House Price Prediction

A machine learning project that predicts house prices using the **Melbourne Housing Dataset** from Kaggle.

This project focuses on building a regression model with **Scikit-Learn**, using **Decision Trees** and **Random Forests**, and comparing their performance.

## 📌 Project Overview

The goal of this project is to use historical Melbourne housing data to train a machine learning model that can predict the price of a house based on its available features.

The project was implemented in a **Jupyter Notebook (`.ipynb`)**, making it easy to follow the complete machine learning workflow from data exploration to model evaluation.

## 📊 Dataset

The project uses the **Melbourne Housing Dataset** from Kaggle.

The dataset contains information about properties in Melbourne, including features related to the property, its location, and its characteristics.

The target variable used for prediction is the **house price**.

## 🛠️ Technologies Used

* **Python**
* **Pandas** — data loading, cleaning, and manipulation
* **Scikit-Learn** — machine learning models and evaluation
* **Jupyter Notebook** — development and experimentation

## 🔄 Machine Learning Workflow

The project follows a typical machine learning workflow:

```text
Melbourne Housing Dataset
          ↓
     Data Loading
          ↓
   Data Exploration
          ↓
   Data Preparation
          ↓
   Feature Selection
          ↓
   Train / Validation Split
          ↓
   Decision Tree Model
          ↓
   Random Forest Model
          ↓
   Model Evaluation
          ↓
   Compare Results
```

## 🤖 Models Used

### Decision Tree

I first trained a **Decision Tree Regressor** as a baseline model.

The model produced an error of approximately:

**💰 $20,000**

This provided a useful baseline for comparison.

### Random Forest

I then used a **Random Forest Regressor**, which combines multiple decision trees to produce a stronger and more stable prediction.

The Random Forest model significantly improved the results.

The error dropped from approximately:

```text
Decision Tree
≈ $20,000 error

        ↓

Random Forest
≈ $500 error
```

This was a **dramatic improvement** compared with the single Decision Tree model.

## 📈 Model Comparison

| Model         | Approximate Error |
| ------------- | ----------------: |
| Decision Tree |          ~$20,000 |
| Random Forest |             ~$500 |

The Random Forest model performed substantially better on the evaluation data.

This comparison was particularly useful for understanding why ensemble methods can outperform a single decision tree.

## 🧠 What I Learned

Through this project, I gained practical experience with:

* Loading datasets with Pandas
* Exploring and preparing real-world data
* Selecting features for machine learning
* Splitting data for model evaluation
* Training regression models with Scikit-Learn
* Using Decision Trees
* Using Random Forests
* Comparing machine learning models
* Evaluating regression performance
* Understanding the practical impact of ensemble learning

## 📓 Project Format

The complete project is provided as a **Jupyter Notebook (`.ipynb`)**.

The notebook contains the code, analysis, model training, predictions, and evaluation results.

## 🚀 How to Run

Clone the repository:

```bash
git clone <your-repository-url>
cd <repository-name>
```

Install the required libraries:

```bash
pip install pandas scikit-learn jupyter
```

Start Colab/Jupyter Notebook:

```bash
Jupyter notebook
```

Then open the `.ipynb` file and run the cells.

## 🔮 Future Improvements

Possible improvements include:

* More extensive feature engineering
* Hyperparameter tuning
* Cross-validation
* Comparing additional regression algorithms
* Better handling of missing values and categorical features
* Further investigation into why Random Forest performs significantly better

## 👤 About the Project

This project was built as a practical machine learning exercise to understand how different regression algorithms perform on a real-world housing dataset.

The most interesting result was the comparison between the **Decision Tree** and **Random Forest** models, where Random Forest reduced the prediction error from roughly **$20,000 to $500**.

---

⭐ **If you found this project useful, feel free to explore the notebook and experiment with the models.**
