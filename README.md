# Medical Insurance Forecasting
The project aims to predict medical expenses through variables shown in the data: age, sex, BMI, Children, smoking, and region – to increase accurate results for medical insurance companies. This research is related to finding the average medical care expenses and it is beneficial for insurance companies. It is crucial to forecast medical expenses for the insured population. Medical expenses are difficult to estimate because the costliest conditions are rare and seemingly random. Still, some conditions are more prevalent for certain segments of the population.

# Table of Contents
-  [General Info](<#general-information>)
-  [Technologies Used](#technologies-used)
-  [Setup](#setup)
-  [Features](#features)
-  [Usage](#usage)
-  [Project Status](#project-status)

# General Information
This research is related to finding the average medical care expenses and it is beneficial for insurance companies. For example, we’ve chosen the sum of people’s age in all regions and the sum of medical charges to generate a comparative line chart. We clearly see a trend that people who smoke are having more medical expenses. Also, the visualization result tells us age is also a driving factor to determine the premiums.
Additionally, by analyzing the correlation between a smoker and medical charges, we did further research on medical expenses. Meanwhile, the dataset also allows us to inspect the relationship between BMI and charges. This study helps medical insurance companies to predict medical expenses and decide the insurance premiums and therefore reduce losses. 

# Technologies Used
Python libraries: Scikit-learn, Numpy, Pandas, Matplotlib, Seaborn, Statmodels

# Setup
The project requirements/dependencies are listed in the import statements at the beginning of the code:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - sklearn
  - Statmodels

To set up your local environment and get started with the project, you need to follow these steps:

1. Install Python on your computer if you haven't already done so. You can download Python from the official website:https://www.python.org/downloads/.
   
2. Open a command prompt or terminal window and navigate to the directory where you want to store the project files.

3. Clone the project repository using Git or download the project files directly from the repository.

4. Install the required dependencies by running the following commands in your command prompt or terminal window: pip install numpy pandas matplotlib seaborn sklearn statmodels yellowbricks.

5. Once the dependencies are installed, you can open the Jupyter Notebook file containing the project code and run the code cells to execute the project.

# Features
  - From the regression analysis, we ﬁnd that region and gender do not bring signiﬁcant difference on charges.
  - Age, BMI, number of children and smoking are the ones that drive the charges.
  - Smoking seems to have the most inﬂuence on the medical charges
  - We trained in Multiple Linear Regression and Random Forest algorithm. The multiple linear regression model performed well with 74% accuracy and Random Forest Regression model gave       the accuracy of 83%. 

# Usage
This analysis provides useful insights for health insurance company to make money, it needs to collect more in yearly premiums than it spends on medical care for its beneficiaries by knowing the effect of people's age, sex, BMI, Children, smoking, and region on medical expenses such as diagnosis, treatment and drug costs.

# Project Status
Project is: Complete

