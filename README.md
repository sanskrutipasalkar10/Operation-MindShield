
## **Project Title**

**Operation MindShield: AI-Powered PTSD Risk Prediction, Automated Alerts & Dashboard for Soldier Well-being**

---

## **Project Overview**

**Operation MindShield** is a comprehensive AI-powered mental health analytics solution developed to assess and monitor Post-Traumatic Stress Disorder (PTSD) risk levels among soldiers. The project integrates the entire data science lifecycle—from data preprocessing and predictive modeling to real-time automation and business intelligence visualization. The goal is to support mental health intervention strategies by enabling early detection of PTSD through data-driven insights.

By combining machine learning with automation and interactive dashboards, the system provides defense decision-makers and healthcare professionals with powerful tools to identify high-risk individuals, understand psychological trends, and deploy timely support.

---

## **Key Objectives**

* **Predict** PTSD risk levels (Low, Medium, High) using supervised learning models trained on psychological and behavioral features.
* **Automate** email alerts for soldiers identified as high risk to enable proactive intervention.
* **Visualize** critical metrics (e.g., mental health scores, risk distribution, demographic factors) through a multi-page Power BI dashboard.
* **Schedule and automate** the model execution using Windows Task Scheduler for daily or routine risk assessments.
* **Design a robust data pipeline** starting with raw data cleaning using Excel Power Query.

---

## **Tech Stack & Tools**

* **Python (Jupyter Notebook)**: Data preprocessing, feature engineering, EDA, ML model building (Random Forest, etc.)
* **Pandas, Scikit-learn, Matplotlib, Seaborn**: Used for data manipulation, training, evaluation, and visual analysis.
* **Excel + Power Query**: For raw data cleaning, missing value handling, formatting, and preparing analysis-ready datasets.
* **Power BI**: Created a 4-page interactive dashboard with 20+ visuals including KPIs, heatmaps, soldier-level drill-throughs, and risk factor trends.
* **Windows Task Scheduler**: For automating periodic model execution and alert workflows.
* **SMTP (Email Automation)**: Automatically sends email alerts when high PTSD risk is detected based on model output.

---

## **Core Features & Implementation**

* **Data Pipeline**: Cleaned raw health and service data using Power Query; standardized formats, encoded categorical variables, handled missing values, and built structured datasets for modeling.
* **Exploratory Data Analysis**: Performed in-depth EDA on key features such as anxiety, depression, sleep disorder scores, injury history, alcohol consumption, and support systems.
* **Model Training**: Trained multiple classifiers (focus on Random Forest) and evaluated their performance, achieving \~90% accuracy in predicting PTSD risk levels.
* **Feature Importance Analysis**: Used model explainability tools to identify key contributors like Flashbacks Frequency, Anxiety Score, and Depression Score.
* **Real-time Automation**: Scheduled Python scripts with Task Scheduler to continuously monitor updated data and trigger email alerts for high-risk soldiers.
* **Dashboard Design**:

  * **Page 1 – Executive Summary**: High-level KPIs, PTSD distribution, gender breakdown, high-risk alerts.
  * **Page 2 – Risk Drivers**: Visuals showing relationships between risk and combat exposure, support strength, injury history, and alcohol use.
  * **Page 3 – Mental Health Analysis**: Trends and comparisons of anxiety, depression, sleep disorder scores, including correlation charts and heatmaps.
  * **Page 4 – Soldier-Level Drill-down**: Table of all soldiers with slicers and high-risk filters, including actionable profile data.

---

## **Impact & Value**

* Enables early detection of PTSD risk in military environments using data-driven insights.
* Reduces manual monitoring efforts by implementing automation and scheduled alerts.
* Helps mental health teams prioritize cases based on model-driven predictions.
* Improves data visibility and decision-making through a professional, interactive dashboard.
* Offers high reusability and scalability for deployment in real-time defense health systems.

---

## **Sample Visuals & Key Insights**

* **Top Contributing Factors to PTSD** shown via feature importance chart.
* **Dynamic heatmaps and scatter plots** to show psychological score trends.
* **Gauge visuals and high-risk counters** for real-time alert summaries.
* **Drill-through soldier profiles** for in-depth case analysis and personalized support planning.


