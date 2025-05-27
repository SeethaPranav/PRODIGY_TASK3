# PRODIGY_TASK3
# 🌳 Task 3: Decision Tree Classifier – Predicting Customer Purchase Behavior
This repository contains the third task of my Data Science Internship at Prodigy InfoTech, where I built and evaluated a Decision Tree Classifier to predict whether a customer will make a purchase based on demographic and behavioral data.

# 📌 Objective
The goal of this task is to:

Build a machine learning model using a Decision Tree Classifier.

Predict customer purchase behavior (Revenue) using session-level data.

Evaluate the model's accuracy and visualize the decision logic.

# 🧪 Steps Performed
Loaded and explored the dataset using .info() and .describe().

Applied Label Encoding to convert categorical and boolean features into numeric format.

Split the data into training and testing sets (80/20).

Trained a Decision Tree Classifier with a maximum depth of 5.

Evaluated the model using accuracy score and classification report.

Visualized the decision tree structure for better interpretability.

# 📊 Visualizations Included
Decision Tree plot showing the model's decision rules

# 🛠️ Tools Used
Python

Pandas

NumPy

Scikit-learn

Matplotlib

# 📁 Dataset Description
The dataset contains session-based data of online shoppers with the following features:

Page visit counts (Administrative, Informational, ProductRelated)

Time spent on pages (*_Duration)

Session metrics (BounceRates, ExitRates, PageValues)

Visitor metadata (Month, OperatingSystems, Browser, Region, TrafficType, VisitorType, Weekend)

Revenue: Target variable indicating whether a purchase was made

# 🔗 Outcome
This task helped me strengthen my skills in:

Supervised learning using Decision Trees

Feature encoding and model evaluation

Visual interpretation of decision paths in classification models
