# Machine Learning Project: Copa América 2024 Prediction

This project is a comprehensive analysis and prediction model for the Copa América 2024 tournament. The project follows a detailed workflow including data visualization, exploration, model training, and evaluation. Below is the detailed table of contents for easy navigation.

<hr style="height:2.4pt">

### Table of Contents
1. [Project Flow Chart](#flowchart)
1. [Problem Statement](#problemstatement)
1. [Visualization/EDA/Analysis](#eda)
    1. [Import Libraries](#lib)
    1. [Import Data](#data)
    1. [Web Scraping for Advanced Stats](#scraping)
    1. [Missing Data and Feature Selection](#missingandfeatures)
    1. [Visualization and Feature Description](#viz)
1. [Modeling and Training](#model)
    1. [Logistic Regression Model](#lr)
    1. [Bagging Logistic Regression Model](#lrbag)
    1. [Decision Tree Model](#dt)
    1. [Bagging Decision Tree Model](#dtbag)
    1. [Gradient Descent Model](#gd)
    1. [AdaBoost Model](#ada)
    1. [Random Forest Model](#rf)
    1. [Model Selection](#selection)
1. [Results](#results)
    1. [Simulation Setup](#sim)
    1. [Copa América 2024 Prediction](#ca24)
1. [Conclusion, Inferences, Limitations](#conclusion)
1. [Future Work and Scope of Improvement](#future)

<hr style="height:2.4pt">

## <a id="flowchart"></a>1. Project Flow Chart
- Overview of the project workflow, highlighting key steps from data collection to final prediction.

## <a id="problemstatement"></a>2. Problem Statement
- Description of the problem this project aims to solve, including the importance and relevance of predicting the Copa América 2024 outcome.

## <a id="eda"></a>3. Visualization/EDA/Analysis
- Detailed exploration of the dataset, including initial data checks, handling missing values, and feature selection.

### <a id="lib"></a>3.1. Import Libraries
- List of all the libraries and packages used in the project. For easy installation, use the provided `requirements.txt` file.

### <a id="data"></a>3.2. Import Data
- Description of how the data was imported and any preprocessing steps taken.

### <a id="scraping"></a>3.3. Web Scraping for Advanced Stats
- Details on the web scraping process to gather additional statistics and data for model enhancement.

### <a id="missingandfeatures"></a>3.4. Missing Data and Feature Selection
- Discussion on how missing data was handled and the rationale behind the selected features.

### <a id="viz"></a>3.5. Visualization and Feature Description
- Visualization techniques used to better understand the data and the selected features.

## <a id="model"></a>4. Modeling and Training
- Explanation of the different machine learning models used, including hyperparameter tuning and training.

### <a id="lr"></a>4.1. Logistic Regression Model
- Details of the Logistic Regression model, including performance metrics.

### <a id="lrbag"></a>4.2. Bagging Logistic Regression Model
- Description and performance analysis of the Bagging Logistic Regression model.

### <a id="dt"></a>4.3. Decision Tree Model
- Overview and performance of the Decision Tree model.

### <a id="dtbag"></a>4.4. Bagging Decision Tree Model
- Analysis of the Bagging Decision Tree model.

### <a id="gd"></a>4.5. Gradient Descent Model
- Implementation and performance of the Gradient Descent model.

### <a id="ada"></a>4.6. AdaBoost Model
- Details on the AdaBoost model and its results.

### <a id="rf"></a>4.7. Random Forest Model
- Discussion on the Random Forest model, including feature importance.

### <a id="selection"></a>4.8. Model Selection
- Process of selecting the best model based on performance metrics.

## <a id="results"></a>5. Results
- Summary of the results from the different models and their performance on the test data.

### <a id="sim"></a>5.1. Simulation Setup
- Explanation of the simulation environment and parameters.

### <a id="ca24"></a>5.2. Copa América 2024 Prediction
- Final prediction results for Copa América 2024, based on the chosen model.

## <a id="conclusion"></a>6. Conclusion, Inferences, Limitations
- Summary of the findings, inferences drawn from the results, and discussion on the limitations of the current approach.

## <a id="future"></a>7. Future Work and Scope of Improvement
- Suggestions for future work and potential improvements to the model or methodology.

<hr style="height:2.4pt">

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

```bash
git clone https://github.com/fiidalgo/copa-america-ml.git
cd copa-america-ml
```

2. **Create a virtual environment:**

```bash
python -m venv venv
```

3. **Activate the virtual environment:**

* On Windows:

```bash
venv\Scripts\activate
```

* On macOS and Linux:

```bash
source venv/bin/activate
```

4. **Install the required libraries:**

```bash
pip install -r requirements.txt
```

5. **Run the project:***

```bash
python predict.ipynb
```