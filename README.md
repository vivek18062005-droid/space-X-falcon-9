🚀 IBM Data Science Capstone Project – SpaceX Falcon 9 Landing Prediction
📌 Introduction

The SpaceX Falcon 9 rocket is designed with a reusable first stage, significantly reducing launch costs. While SpaceX advertises launches at approximately $62 million, other providers charge $165 million or more per launch.

The primary reason for this cost advantage is first-stage reusability. If the rocket lands successfully, it can be refurbished and reused—leading to major savings.

In this project, we take on the role of a Data Scientist working for a competing aerospace startup. The goal is to leverage historical launch data to predict whether the Falcon 9 first stage will land successfully.

💼 Business Problem

The ability to predict landing success directly impacts launch cost estimation.

✅ Successful landing → Lower cost (reusability)
❌ Failed landing → Higher cost (no reuse)

By building an accurate prediction model, the startup can:

Make competitive bids against SpaceX
Optimize pricing strategies
Reduce financial risk in launch contracts
🎯 Objective

The main objectives of this project are:

Apply the data science lifecycle, including:
Data collection
Data wrangling
Exploratory Data Analysis (EDA)
Data visualization
Model development
Model evaluation
Build machine learning classification models to predict landing success
Extract insights from the data to support business decision-making
📊 Business Metric

The performance of the predictive model will be evaluated using classification accuracy, defined as:

𝐴
𝑐
𝑐
𝑢
𝑟
𝑎
𝑐
𝑦
=
𝑇
𝑃
+
𝑇
𝑁
𝑇
𝑃
+
𝐹
𝑃
+
𝑇
𝑁
+
𝐹
𝑁
Accuracy=
TP+FP+TN+FN
TP+TN
	​


Where:

TP (True Positive): Correctly predicted successful landings
TN (True Negative): Correctly predicted failures
FP (False Positive): Incorrectly predicted success
FN (False Negative): Incorrectly predicted failure

Additionally, a confusion matrix will be used to analyze model performance in detail.

📦 Deliverables

The final outputs of this project include:

🔹 1. Predictive Models
Machine learning algorithms capable of accurately predicting landing outcomes
Comparison of multiple models (e.g., Logistic Regression, Decision Trees, SVM)
🔹 2. Data Insights
Key factors influencing landing success (e.g., payload mass, launch site, orbit type)
🔹 3. Business Report
Clear and actionable insights for stakeholders
Cost implications based on predicted landing outcomes
Recommendations for competitive bidding strategy
🚀 Expected Impact

By successfully completing this project, the startup will be able to:

Estimate launch costs more accurately
Improve bid competitiveness
Make data-driven strategic decisions
