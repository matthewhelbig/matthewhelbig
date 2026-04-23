# Matthew Helbig Data Analyst Portfolio

Data analyst with a master's degree in data analytics, specializing in SQL, Python, and data visualization. I focus on transforming complex datasets into actionable insights.

---

## Featured Projects

### Capstone Project
[View Project](https://github.com/matthewhelbig/D214_DataAnalyticsGraduateCapstone)

End-to-end analysis using statistical modeling to identify key drivers and predict outcomes based on historical data.

---

### D213 - Advanced Data Analysis
[View Project](https://github.com/matthewhelbig/D213_AdvancedDataAnalysis)

Built a logistic regression model to predict outcomes, including feature engineering and performance evaluation.

---

### D212 - Advanced Data Mining & Predictive Analytics
[View Project](https://github.com/matthewhelbig/D212_DataMining2)

### [Task 1](https://github.com/matthewhelbig/D212_DataMining2/blob/main/D212%20Task%201%20Performance%20Assessment.ipynb) - K-Means Clustering Analysis for Patient Segmentation

**Tools: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn** 

**Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Unsupervised Machine Learning, K-Means Clustering, Feature Scaling (Standardization), Cluster Evaluation (Elbow Method, Silhouette Score), Data Visualization**  

- Performed unsupervised machine learning analysis using K-Means clustering to identify distinct patient segments based on demographic and socioeconomic variables
- Selected and refined key continuous variables to improve cluster separation and interpretability  
- Applied data preprocessing techniques, including standardization using `StandardScaler`, to meet model assumptions and ensure equal variance across features  
- Determined the optimal number of clusters using within-cluster sum of squares (WCSS), silhouette score, and centroid analysis 
- Identified three distinct clusters:  
  - Low Population / Low Income  
  - High Population / Low Income  
  - Low Population / High Income 
- Interpreted clustering results to generate actionable healthcare insights, including identifying underserved populations and strategic opportunities for hospital expansion  
- Evaluated limitations of K-Means clustering, including reliance on continuous variables and reduced ability to incorporate categorical data

### [Task 2](https://github.com/matthewhelbig/D212_DataMining2/blob/main/D212%20Task%202%20Performance%20Assessment.ipynb) - Principal Component Analysis (PCA) for Dimensionality Reduction  

**Tools: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn**

**Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Feature Scaling, Principal Component Analysis (PCA), Variance Explained Analysis, Data Visualization**

- Applied Principal Component Analysis (PCA) to reduce dimensionality in a healthcare dataset while preserving the majority of variance  
- Performed data preprocessing, including handling missing values, encoding categorical variables, and scaling features to ensure PCA effectiveness  
- Standardized variables to ensure equal contribution across features prior to transformation  
- Computed principal components and evaluated explained variance ratios to determine the optimal number of components  
- Reduced the dataset to a smaller set of components while retaining the most informative structure in the data  
- Visualized component relationships using scatter plots and variance plots to interpret underlying data patterns  
- Identified key feature groupings and latent structures driving variation in the dataset  
- Demonstrated how PCA can improve model efficiency, reduce multicollinearity, and enhance interpretability for downstream analytics

## [Task 3](https://github.com/matthewhelbig/D212_DataMining2/blob/main/D212%20Task%203%20Performance%20Assessment.ipynb) - Market Basket Analysis & Association Rule Mining

**Tools: Python, Pandas, mlxtend**  
**Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Data Transformation, Market Basket Analysis, Association Rule Learning, Apriori Algorithm, Frequent Itemset Mining, Model Evaluation (Support, Confidence, Lift), Data Visualization**  

- Performed market basket analysis to identify relationships between commonly co-occurring medications within a healthcare dataset
- Transformed transactional data into a one-hot encoded format suitable for association rule mining  
- Applied the Apriori algorithm to generate frequent itemsets using a minimum support threshold  
- Generated association rules from frequent itemsets to identify meaningful relationships between medications  
- Evaluated rule strength using support, confidence, and lift, quantifying the frequency and predictive power of item relationships  
- Interpreted association rules to uncover patterns in medication co-occurrence, supporting insights into treatment combinations and prescribing behavior  
- Validated findings based on the underlying assumption that frequently co-occurring items represent meaningful relationships, while acknowledging limitations of the method 
- Delivered data-driven insights to support healthcare analytics, including identifying complementary medications and potential areas for further investigation  

---

### D211 - Advanced Data Acquisition
[View Project](https://github.com/matthewhelbig/D211_AdvancedDataAcquisition)

Analyzed data distributions, trends, and relationships using visualizations and statistical summaries.

---

### D210 - Tableau Healthcare Dashboard & Data Visualization
[View Project](https://github.com/matthewhelbig/D210_RepresentationAndReporting)

[Tableau Dashboard](https://public.tableau.com/app/profile/matthew.helbig/viz/D210PerformanceAssessment_17081151912580/Story1#1)

**Tools: Tableau Public, Python, Pandas** 

**Techniques: Data Cleaning, Data Integration, Dashboard Development, Data Visualization, Business Intelligence (BI), KPI Reporting, Healthcare Analytics, Stakeholder Communication**  

- Built an interactive Tableau dashboard using combined healthcare datasets to support visual analysis and stakeholder decision-making
- Cleaned and prepared multiple data sources in Python/Pandas, including a WGU medical dataset and an external hospital readmissions dataset from Kaggle 
- Combined cleaned datasets into a single Tableau-ready file to streamline dashboard development and improve usability   
- Published the dashboard to Tableau Public, allowing users to access the interactive visualization without local installation   
- Designed visualizations to communicate healthcare trends, readmission-related insights, and key relationships across patient variables  
- Created a dashboard workflow that connects data preparation, visualization, and business intelligence reporting* 
- Delivered a user-facing analytics product designed to make healthcare data more accessible, interpretable, and actionable  

---

### D209 - K-Nearest Neighbor and Decision Tree Classification
[View Project](https://github.com/matthewhelbig/D209_DataMining1)

**Tools: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn** 

**Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Supervised Machine Learning, Classification Modeling, K-Nearest Neighbors (KNN), Decision Tree Classification, Feature Engineering, Model Training & Testing, Model Evaluation (Accuracy, Confusion Matrix, ROC/AUC), Data Visualization**    

### [Task 1](https://github.com/matthewhelbig/D209_DataMining1/blob/main/D209%20Task%201%20Performance%20Assessment.ipynb) - K-Nearest Neighbors (KNN) Classification

- Developed a K-nearest neighbors (KNN) classification model to predict whether a patient would be readmitted, addressing a real-world healthcare decision-making problem  
- Trained and evaluated the model using KNeighborsClassifier, selecting an optimal value of k = 8 to improve classification performance  
- Assessed model performance using a confusion matrix, calculating an overall accuracy score of 0.97 on the test dataset   
- Evaluated classification quality using ROC/AUC analysis, achieving an AUC of approximately 0.994, indicating excellent separation between readmission classes  
- Applied classification modeling techniques to distinguish between binary healthcare outcomes and support predictive decision-making   
- Interpreted model results in a healthcare context to identify how patient characteristics can be used to estimate the likelihood of readmission  
- Generated actionable insights to support healthcare risk prediction and organizational planning  

### [Task 2](https://github.com/matthewhelbig/D209_DataMining1/blob/main/D209%20Task%202%20Performance%20Assessment.ipynb) - Decision Tree Classification and Predictive Modeling

- Performed end-to-end data analysis and machine learning workflow on a healthcare dataset, including data preprocessing, transformation, and validation  
- Conducted exploratory data analysis (EDA) to identify trends, distributions, and relationships between variables prior to modeling  
- Developed a Decision Tree Classifier to predict healthcare-related outcomes based on multiple input features  
- Implemented feature engineering and data preprocessing techniques (encoding, scaling, and variable selection) to improve model performance  
- Split data into training and testing sets to validate model generalization and prevent overfitting  
- Evaluated model performance using classification metrics such as accuracy, precision, recall, and confusion matrix  
- Visualized and interpreted the decision tree structure to understand feature importance and decision paths  
- Generated actionable insights by identifying key variables influencing predicted outcomes, supporting data-driven decision-making  

---

### D208 - Regression and Classification Modeling
[View Project](https://github.com/matthewhelbig/D208_PredictiveModeling)

**Tools: Python, Pandas, NumPy, SciPy, Statsmodels, Scikit-learn, Seaborn, Matplotlib**

**Techniques: Data Cleaning, EDA, Multiple Linear Regression, Logistic Regression, Feature Selection, Multicollinearity (VIF), Model Evaluation, Classification Metrics** 

### [Task 1](https://github.com/matthewhelbig/D208_PredictiveModeling/blob/main/D208%20Task%201%20Performance%20Assessment.ipynb): Multiple Linear Regression (Predictive Modeling)
- Conducted multiple linear regression analysis to identify which variables significantly influence additional healthcare charges and quantify their impact
- Built and interpreted a multivariate regression model, analyzing coefficients to determine the directional and magnitude effect of each independent variable on the dependent variable  
- Evaluated key model assumptions including linearity, independence, multicollinearity, and model fit to ensure statistical validity of results
- Performed feature selection using statistical significance (p-values) and Variance Inflation Factor (VIF) to reduce multicollinearity and refine the model  
- Assessed overall model performance using metrics such as R-squared and p-values, determining that the model lacked statistical and practical significance
- Identified limitations in the analysis, including weak relationships between variables and potential issues with feature selection reducing model effectiveness
- Provided data-driven recommendations, including transforming variables, revising feature selection, and exploring alternative variable relationships to improve future modeling outcomes

### [Task 2](https://github.com/matthewhelbig/D208_PredictiveModeling/blob/main/D208%20Task%202%20Performance%20Assessment.ipynb): Logistic Regression (Classification Modeling)
- Conducted logistic regression analysis to model the probability of a binary healthcare outcome (e.g., patient readmission) based on multiple predictor variables
- Built a classification model to estimate the likelihood of an event occurring, interpreting results through odds ratios and probability output 
- Evaluated model assumptions specific to logistic regression, including binary dependent variable structure and probabilistic interpretation of outcomes
- Performed feature selection and multicollinearity reduction using statistical significance and Variance Inflation Factor (VIF)  
- Assessed model performance using a confusion matrix and classification metrics to evaluate predictive accuracy  
- Conducted outlier detection and data preparation using Z-scores, visualizations, and statistical methods to improve model reliability  
- Provided actionable insights by identifying key factors influencing the likelihood of healthcare outcomes, supporting data-driven decision-making
---

### D207 - Chi-Square Hypothesis Testing on Healthcare Variables
[View Project](https://github.com/matthewhelbig/D207_ExploratoryDataAnalysis)

**Tools: Python, Pandas, SciPy**

**Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Contingency Tables, Chi-Square Test of Independence, Hypothesis Testing, Statistical Analysis, Data Interpretation**  

- Performed data analysis on healthcare variables to evaluate whether a statistically significant relationship existed between Anxiety and Complication Risk  
- Built a contingency table to summarize counts across categorical variables prior to hypothesis testing  
- Applied the Chi-Square Test of Independence to assess whether the two categorical variables were dependent or independent 
- Interpreted key statistical outputs including chi-square statistic, p-value, degrees of freedom, and expected frequencies to support findings  
- Determined that the results were not statistically significant, so the null hypothesis was not rejected and the variables were considered independent   
- Evaluated methodological limitations of chi-square analysis, including its restriction to categorical variables and limited ability to measure strength of relationship
- Generated a data-driven recommendation that no actionable relationship was demonstrated between the selected healthcare variables based on this analysis

---

### D206 - Medical Data Analysis & Dimensionality Reduction Using PCA
[View Project](https://github.com/matthewhelbig/D206_DataCleaning)

**Tools: Python, Pandas, NumPy, Scikit-learn, Matplotlib**

**Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Outlier Detection, Feature Engineering, Principal Component Analysis (PCA)**

- Performed end-to-end data analysis on a healthcare dataset, including data cleaning, transformation, and validation
- Identified and handled missing values, incorrect data types, and outliers using statistical techniques (z-scores, histograms, box plots)
- Conducted Exploratory Data Analysis (EDA) to uncover patterns and assess data distributions
- Applied Principal Component Analysis (PCA) to reduce dimensionality and identify key drivers of variance
- Determined high-impact variables (e.g., Age, Total Charges, Vitamin D levels) contributing to principal components
- Improved dataset efficiency for machine learning model readiness by reducing noise and redundant features
- Delivered insights to support data-driven decision-making and analytical modeling

---
## Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- SQL
- Excel
- Tableau
- Data Visualization (Matplotlib, Seaborn)
