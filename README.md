# Dynamic Regression Model

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [ETL Process](#etl-process)
- [EDA Process](#eda-process)
- [Data Analysis](data-analysis)
- [Results](results)

  ## Project Overview
 Develop a Smart Regression Model to Uncover HomeStay Price Trends for Residential Properties.

  ## Data Source
Residential Properties Data:
The primary dataset for this analysis is the "Air_BNB.xlsx" file, which includes comprehensive details about residential properties available for short-term rentals. This dataset encompasses various features such   as price, amenities, and property characteristics, providing a solid foundation for developing the regression model.

  ## Tools
- Anaconda Navigator: For managing packages and environments.
- Jupyter Notebook: For interactive coding and data visualization.
- Excel: For documenting dataset results and initial analysis.

  ## ETL Process
### Step 1: Extract
- Objective: Retrieve the dataset.
- Action: Load the dataset from the "Air_BNB.xlsx" file into the analysis environment.
  
### Step 2: Transform 
- Objective: Clean and prepare the data for analysis:
1. Handling Null Values.
2. Removing Duplicates.
3. Standardizing Formats.
4. Encoding Categorical Variables.

### Step 3: Load
- Objective: Prepare the cleaned dataset for analysis.
- Action: Save the transformed dataset for further analysis.

## EDA Process
Include some interesting insights and findings:
1. Dataset Overview: Summary of dataset size and structure.
2. Imputation: Used mean, median, and mode to fill in missing entries based on feature characteristics.
3. Unique Values: Explored distinct categories in key features.
4. Descriptive Statistics: Reviewed mean, median, and mode to understand central tendencies.
5. Outlier Treatment: Identified and handled outliers using methods like IQR or z-score for more accurate analysis.
6. Price Distribution: Analyzed price ranges and visualized outliers.

 ## Data Analysis
Include some interesting code/features worked with:

1. Data Visualization: Histogram of price distribution.
2. Correlation Analysis: Identified feature relationships.
3. Descriptive Statistics: Summary of dataset characteristics.
4. Linear Regression Model: Predicting home stay prices.
5. Feature Importance: Analyzed influential features.
6. Predictive Analysis: Price prediction for listings.

## Results
The model evaluations yielded the following accuracies:

- KNN Model: Achieved 44% accuracy, indicating that while it can provide some predictions, there’s significant room for improvement.
- Mean Imputation with Outlier Treatment: Improved performance to 50% accuracy, demonstrating that handling missing values with mean imputation while treating outliers enhances model reliability.
- Median Imputation with Outlier Treatment: Similar to the mean approach, this also reached 50% accuracy, suggesting that using median values for imputation is just as effective in this context.
- KNN with Outlier Treatment: Slightly outperformed the other methods with 50.3% accuracy, indicating that applying KNN while addressing outliers provides a marginal improvement.



   
