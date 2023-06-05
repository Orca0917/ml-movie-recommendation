# Movie Rating Prediction
### 👋🏻 Introduction
This code aims to predict movie ratings based on various features using different regression models. The dataset used contains information about movies, such as genre, budget, and runtime.

<br/>

### ✅ Getting Started
First, please prepare Movielens dataset. The method currently learned uses 'ml-latest-small.zip' data from the movielens dataset. Other data are also available, and depending on the data used, there may be variations in learning time.

https://grouplens.org/datasets/movielens/  
https://grouplens.org/datasets/movielens/latest/

Please place the data in the same directory afterwards. Above, you can place the data in the same location as the ipynb file.


*development principal environment*
- `python >= 3.9`
- `matplotlib >= 3.7.1`
- `pandas >= 1.5.3`
- `sklearn >= 1.2.2`

OR you can use `requirements.txt` to install all package versions
```console
pip install -r requirements.txt
```

Experiment in a simple Google colab environment.  
https://colab.research.google.com/drive/1Y5QwG8r4Ky_kFuaCV6a4RYMrc00VIuJN?usp=sharing

<br/>

### 🛒 Data Preparation
- Load the dataset and perform necessary preprocessing steps such as handling missing values and encoding categorical variables.

### 📊 Exploratory Data Analysis
- Perform exploratory data analysis to gain insights into the distribution of movie ratings and relationships between features.

## ⚙ Model Training and Evaluation
### Linear Regression
- Train a linear regression model using the preprocessed dataset.
- Evaluate the model's performance using cross-validation and calculate the root mean squared error (RMSE).
- Provide interpretations of the model's coefficients and any insights gained.

### Random Forest Regression
- Train a random forest regression model using the preprocessed dataset.
- Evaluate the model's performance using cross-validation and calculate the RMSE.
- Generate feature importance rankings and visualize them using a bar plot.
- Discuss the advantages and limitations of the random forest model.

### XGBoost Regression
- Train an XGBoost regression model using the preprocessed dataset.
- Evaluate the model's performance using cross-validation and calculate the RMSE.
- Plot the learning curve to analyze the model's training progress.
- Discuss the advantages and limitations of the XGBoost model.

### Gradient Boosting Regression
- Train a gradient boosting regression model using the preprocessed dataset.
- Evaluate the model's performance using cross-validation and calculate the RMSE.
- Plot the feature importance rankings and discuss the significance of each feature.

### LightGBM Regression
- Train a LightGBM regression model using the preprocessed dataset.
- Evaluate the model's performance using cross-validation and calculate the RMSE.
- Compare the results with previous models and highlight any differences or improvements.

### AdaBoost Regression
- Train an AdaBoost regression model using the preprocessed dataset.
- Evaluate the model's performance using cross-validation and calculate the RMSE.
- Discuss the strengths and weaknesses of the AdaBoost model.

## Results and Conclusion
- Summarize the findings from the different regression models.
- Compare the performance of each model based on the RMSE scores.
- Provide insights and recommendations based on the analysis.

By structuring the code in this format and incorporating clear headings, explanations, and result interpretations, users will find it easier to understand and utilize the code for movie rating prediction.
