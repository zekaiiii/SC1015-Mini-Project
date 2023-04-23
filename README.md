## World Happiness Analysis
## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on [world happiness analysis](https://www.kaggle.com/datasets/unsdsn/world-happiness).
## Contributor
School of Computer Science and Engineering, NTU Singapore 
AY2022/23 SC1015 W132 Group 1
- Hoon Zi Yan - Data Extraction, Data Cleaning, Decision Tree Classifier. 
- Tan Jia Chyi - Explortory Data Analysis, , Data Visulisation, Random Forest Classifier.
- Ng Ze Kai - Linear regression, Random Forest Regression, Logistics Regression.
## Problem Definition
- Which continents in the world have greater happiness?
- What are the most significant factors that contribute to the happiness of people in different regions of the world?
- Which machine learning is the best in predicting happiness score? Can the data be used to predict the happiness score of countries that are not included in the dataset? 

## Data Visualisation Tools
- Boxplot
- Histogram
- KDE
- Violin PLot
- Correlation Table
- Heatmap
- Pairplot
- Stripplot
- Plotly

## Machine Learning Used
- Linear Regression
- Random Forest Regression
- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression
- Grid Search Cross-Validation


## Conclusion
- Europe has the greatest happiness score out of the 7 continents in the world 
- **Economy (GDP per capita) and Family Support** are the two significant predictors with higher correlation values
- Best regression model (numeric vs numeric variables) was built using **random forest regression** 
- Best classification model (numeric vs categorical variables) was built using **logistic regression**
- Hyperparamater tuning improved model performance and reduced overfitting
- Yes, it is possible to predict a country's happiness based on the factors in the model with acceptable amount of accuracy

## What did we learn from this project?
- New Machine Learning:
  - Regression: Random Forest Regression
  - Classification: Random Forest Classifier, Logistic Regression
  - Utility Model: Grid Search CV, KFold, ROC curve and AUC.
 - New Visualisation Tool:
   - Plotly
 - Resampling Data 

## Reference
- https://www.kaggle.com/datasets/unsdsn/world-happiness
- https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
- https://www.mygreatlearning.com/blog/cross-validation/
- https://towardsdatascience.com/decision-tree-classifier-explained-in-real-life-picking-a-vacation-destination-6226b2b60575
- https://python-visualization.github.io/folium/.
- https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc
- https://towardsdatascience.com/random-forest-regression-5f605132d19d
