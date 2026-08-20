# AI-Powered Customer Churn Prediction & Retention Analytics Platform

An end-to-end **Customer Churn Prediction and Retention Analytics Platform** developed as part of my final-year internship project. The platform uses **Python, Pandas, Scikit-learn, Random Forest, and Power BI** to analyze telecom customer behavior, identify churn patterns, predict customer churn risk, and generate data-driven retention insights.

## About the Project

Customer churn is an important business problem where customers stop using a company's services. Understanding why customers leave can help businesses take proactive steps to improve customer retention.

This project was developed to analyze telecom customer data and build a complete analytics workflow, starting from data preprocessing and exploratory analysis to machine learning-based churn prediction and interactive business intelligence dashboards.

The project was developed using **Visual Studio Code** and follows an end-to-end data analytics workflow.

## Project Objectives

* Clean and preprocess telecom customer data.
* Perform exploratory data analysis to understand customer behavior.
* Identify factors and patterns associated with customer churn.
* Develop a machine learning model for churn prediction.
* Analyze customers based on their churn risk.
* Build an interactive Power BI dashboard.
* Generate insights that can support customer retention strategies.

## Technologies Used

| Technology        | Purpose                                         |
| ----------------- | ----------------------------------------------- |
| **Python**        | Data processing and analysis                    |
| **Pandas**        | Data cleaning and transformation                |
| **NumPy**         | Numerical operations                            |
| **Matplotlib**    | Data visualization                              |
| **Seaborn**       | Exploratory data visualization                  |
| **Scikit-learn**  | Machine learning                                |
| **Random Forest** | Customer churn prediction                       |
| **Power BI**      | Interactive dashboard and business intelligence |
| **VS Code**       | Development environment                         |

## Project Workflow

```text
Telecom Customer Data
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Machine Learning Model
        ↓
Churn Risk Analysis
        ↓
Power BI Dashboard
        ↓
Business Insights
        ↓
Retention Recommendations
```

## Features

### 1. Data Cleaning & Preprocessing

The project begins by preparing the raw telecom customer dataset for analysis and machine learning.

The preprocessing workflow includes:

* Handling missing and inconsistent data
* Converting data types
* Preparing categorical variables
* Removing unnecessary attributes
* Preparing features for machine learning
* Structuring the dataset for analysis

### 2. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand customer behavior and identify patterns related to churn.

The analysis focuses on attributes such as:

* Contract type
* Customer tenure
* Monthly charges
* Technical support usage
* Customer service-related attributes
* Churn behavior

### 3. Customer Churn Prediction

A **Random Forest Classifier** was implemented using Scikit-learn to predict customer churn.

The model helps classify customers based on their likelihood of churning and provides a foundation for identifying customers who may require proactive retention efforts.

### 4. Customer Risk Analysis

Customer behavior and model predictions are used to understand different churn-risk patterns.

This allows the analysis to focus on:

* Customers with higher churn risk
* Factors associated with churn
* Customer behavior patterns
* Potential areas for retention efforts

### 5. Power BI Dashboard

An interactive Power BI dashboard was created to convert the analytical results into business-friendly visualizations.

The dashboard includes:

* KPI reporting
* Customer segmentation
* Churn analysis
* Interactive filters
* Drill-through views
* Custom tooltips
* Customer behavior analysis

## Dashboard

Add screenshots of your Power BI dashboard inside the repository.

Recommended folder:

```text
assets/
└── dashboard.png
```

Then display it in the README using:

```markdown
![Customer Churn Power BI Dashboard](assets/dashboard.png)
```

## Project Structure

Keep your GitHub repository structure according to the files you actually have.

A recommended structure is:

```text
AI-Powered-Customer-Churn-Prediction-Retention-Analytics-Platform/
│
├── data/
│   └── dataset.csv
│
├── src/
│   ├── data_preprocessing.py
│   ├── exploratory_data_analysis.py
│   └── churn_prediction.py
│
├── dashboard/
│   └── churn_dashboard.pbix
│
├── assets/
│   └── dashboard.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

**Important:** Don't create folders or files just to match this README. Your GitHub structure should reflect the files that actually exist in your VS Code project.

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/kanak2004/AI-Powered-Customer-Churn-Prediction-Retention-Analytics-Platform.git
```

### 2. Open the Project

```bash
cd AI-Powered-Customer-Churn-Prediction-Retention-Analytics-Platform
```

Open the project in Visual Studio Code.

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt` yet, create one containing the libraries actually used by your project.

Example:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

### 5. Run the Project

Run the Python files from VS Code or execute the Jupyter Notebook if your project uses one.

The Power BI dashboard can be opened using **Power BI Desktop**.

## Business Insights

The analysis helps identify relationships between customer characteristics and churn behavior.

Factors such as **contract type, tenure, monthly charges, and technical support usage** can be examined to understand customer churn patterns.

These insights can help businesses identify customers who may require additional engagement and develop targeted retention strategies.

## Future Enhancements

Possible future improvements include:

* Comparing multiple machine learning algorithms.
* Hyperparameter tuning for improved model performance.
* Adding customer lifetime value analysis.
* Developing advanced customer segmentation.
* Deploying the churn prediction model as a web application.
* Automating churn-risk reports.
* Connecting the dashboard to a live data source.

## Skills Demonstrated

This project demonstrates practical experience with:

* Python Programming
* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning
* Customer Churn Prediction
* Customer Segmentation
* Data Visualization
* Power BI
* KPI Analysis
* Business Intelligence
* Data-Driven Decision Making

## Author

**Kanak Maghnani**

B.Tech Computer Engineering | Minor in Data Science
D. Y. Patil's Ramrao Adik Institute of Technology

Navi Mumbai, India

[LinkedIn](https://www.linkedin.com/in/kanak-maghnani/) 

