# Titanic-Data-Analysis
Project Overview
This project explores the famous Titanic dataset to analyze passenger survival patterns and apply preprocessing, visualization, and machine learning techniques.  
The analysis covers data cleaning, exploratory data analysis (EDA), visualization, and survival prediction models.
Dataset Information
- Source:[Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)  
- Description:Contains details of 891 passengers including:
  - Passenger ID, Name, Age, Gender
  - Ticket class, Cabin, Fare
  - Embarkation point
  - Survival status (0 = Did not survive, 1 = Survived)

Objectives
- Clean and preprocess Titanic dataset  
- Handle missing values & categorical encoding  
- Perform Exploratory Data Analysis (EDA)  
- Visualize trends in survival by *gender, age, class, fare, embarkation*  
- Build machine learning models to predict survival  

Technologies & Libraries Used
- Language: Python 3  
- Libraries:
  - Data Handling → pandas, numpy
  - Visualization → matplotlib, seaborn
  - Machine Learning (optional) → scikit-learn

Data Preprocessing
Steps performed:
1. Handling missing values(Age, Cabin, Embarked)  
2. Encoding categorical features(Sex, Embarked)  
3. Creating new features(Family Size, Title, etc.)  
4. Scaling and normalizing numerical features
   
Exploratory Data Analysis (EDA)
Some insights discovered:
- Gender: Women had a much higher survival rate than men.  
- Class:Passengers in *1st class* survived more compared to 3rd class.  
- Age:Children had a higher chance of survival than adults.  
- Embarkation Point:Passengers from port "C" had higher survival rates.

Project Description

The Titanic Survival Prediction project is a comprehensive data science project aimed at building a predictive model to determine whether a passenger survived the tragic Titanic disaster of 1912. The project focuses not only on model building but also on data exploration, preprocessing, feature engineering, and visualization, giving a complete overview of the end-to-end machine learning workflow.

Key highlights of the project include:

1. Exploratory Data Analysis (EDA)
   * Identifies patterns, trends, and relationships between features and survival outcome.
   * Uses visualizations like histograms, bar charts, heatmaps, and pair plots to gain insights.
   * Explores how factors such as age, gender, passenger class, and family size influenced survival rates.

2. Data Cleaning and Preprocessing
   * Handles missing values using imputation techniques.
   * Removes or transforms irrelevant or redundant features.
   * Creates new features like `FamilySize` and `Title` from existing data to improve model performance.
   * Converts categorical variables into numeric format suitable for machine learning models.
   * Ensures all features are scaled and normalized when necessary.

3. Feature Engineering
   * Extracts meaningful features that improve the predictive power of the model.
   * Transforms raw data into actionable insights for ML algorithms.
   * Examples:
     * `FamilySize`: Combines SibSp and Parch to understand family presence.
     * `Title`: Extracts social titles like Mr., Mrs., Miss, and rare titles to capture social hierarchy and survival likelihood.

4. Machine Learning Models
   * Implements multiple classification algorithms including:
     * Logistic Regression – interpretable model to understand feature impact.
     * Random Forest Classifier – ensemble method for robust predictions.
   * Evaluates models using accuracy, precision, recall, F1-score, and confusion matrices.
   * Compares model performance to select the best predictor.

5. Visualization and Insights
   * Uses advanced plots to show feature importance, correlations, and survival trends.
   * Provides actionable insights about which features significantly influence survival probability.
   * Helps in understanding the story behind the data, beyond just prediction.

6. End-to-End Machine Learning Workflow
   * Demonstrates real-world ML pipeline: data loading → exploration → cleaning → feature engineering → model training → evaluation → visualization.
   * Ensures reproducibility and scalability by structuring code in modular scripts/notebooks.

7. Learning Outcomes
   * Understand how to preprocess messy real-world data.
   * Learn to engineer features to improve model performance.
   * Gain practical experience implementing multiple ML algorithms.
   * Interpret results and derive meaningful insights from data.
   * Prepare for real-world data science and ML projects.

Example Visualizations
- Bar plots of survival by gender and class  
- Violin plots for age distribution across classes  
- Heatmaps of feature correlations  

Modeling 
- Logistic Regression
- Random Forest


