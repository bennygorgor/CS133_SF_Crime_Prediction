**SF Crime Forecasting \- CS133 Final Project**

This project was completed for \*\*CS133: Introduction to Data Visualization\*\* at San Jose State University.    
We explored and predicted crime patterns in San Francisco using police incident reports from \*\*2018 to 2025\*\*. The project focused on both regression (crime count prediction) and classification (top 5 crime categories).

\---

**Team Members**  
\- Ruiyuan Li    
\- Tang Ho Lam  

\---

Project Objectives  
\-  Predict \*\*hourly crime counts\*\* using machine learning  
\-  Classify the \*\*top 5 most frequent crime categories\*\*  
\- Visualize spatial and temporal crime patterns

\---

Files Included  
SF\_Crime\_Forecasting code.ipynb — Main notebook (Colab-ready)  
Final Report.pdf — Written report (8-section structure)  
Final Presentation.pdf — 10-slide summary presentation

\---

How to Run the Code

1\. Install Python Libraries  
   Use the following in Colab or Jupyter:  
   bash  
   pip install pandas seaborn matplotlib folium geopy scikit-learn scipy  
**Run the Notebook**  
 Open SF\_Crime\_Forecasting code.ipynb in Google Colab.  
 It performs:

* Data cleaning

* Feature engineering (e.g., cyclical time)

* Regression (Linear, Random Forest, Decision Tree)

* Classification (Random Forest Classifier)

* Evaluation (MAE, RMSE, R², confusion matrix)

**Dataset Source**

* Police Department Incident Reports (2018–Present)

[https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about\_data](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about_data)

