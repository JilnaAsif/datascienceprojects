This notebook walks through the data cleaning, preprocessing, and visualization steps to explore the dataset for income prediction. It includes:
* Handling missing values
* Handling duplicate values
* Correlation analysis
* Univariate and bivariate analysis
* Visualization using plots and graphs

Dataset

Name: IncomeData.csv
Source: Kaggle, UCI Machine Learning Repository
Rows: 32561
Columns:15

Tools & Libraries Used

Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

Objectives

* To understand the relation of each features provided in the dataset with the income prediction.
* Identify missing or anomalous values
* Visualize relationships between variables
* Generate hypotheses for further analysis or modeling
* 
Description

* This data set contains workclass,fnlwgt,education,education-num,marital-status,occupation,relationship,race,sex,capital-gain,capital-loss,hours-per-week	and native-country as atrributes.
* In this EDA, I found out that how these attributes influences the  income of individuals.
* for that first step is to clean the data.
* removed the duplicate values.
* Replaced incostitant data mode value
* visualized relation between each attribute with the income and made inferences

Conclusion

The conclusions from this EDA are:
* Higher number of individuals are earning <=50k salary.
* Private sectors are providing more employment opertunities for individuals.They provide both high income and low income jobs.
* Most high-income individuals are working as Executive-manager, prof-specialty,craft repair or sales.
* Higher income ( >50K ) is more common among people aged 35–55.
* Individuals with Bachelors, Masters, and Doctorate degrees have a higher proportion of >50K income.
* Lower education levels (like HS-grad, Some-college, or 11th) are mostly associated with ≤50K income.
* Education is a strong determinant of income, and can be a powerful feature for predictive modeling.
* More hours doesn't guarantee higher income, but many high earners do work longer hours.
