# Pokémon Data Analysis and Classification Project
This project was undertaken as part of a hackathon provided by Unstop. The primary objectives were to perform an in-depth exploratory data analysis (EDA) on the Pokémon dataset and to develop predictive models to classify Pokémon as either legendary or non-legendary based on their attributes.

Project Overview
In this project, we aimed to uncover interesting insights from the Pokémon dataset and build predictive models to classify Pokémon. The tasks involved in the project included:

Data Understanding:

Providing a clear overview of the dataset, including the number of Pokémon, the types of attributes, and any missing values.
Exploratory Data Analysis (EDA):

Visualizing distributions of Pokémon attributes such as types, base stats (HP, Attack, Defense, etc.), and generation.
Identifying interesting patterns or correlations in the data.
Comparing and contrasting different generations of Pokémon.
Analyzing the relationship between Pokémon types and their base stats.
Exploring how attributes like weight, height, and abilities correlate with base stats.
Predictive Modeling:

Developing and fine-tuning machine learning models to classify Pokémon as legendary or non-legendary.
Comparing the performance of different classification algorithms, including Random Forest and Support Vector Machine (SVM).
Optimizing the models by tuning hyperparameters using grid search.
Detailed Analysis and Modeling
1. Data Understanding
The Pokémon dataset contains various attributes for each Pokémon, such as base stats, type, generation, and whether it is legendary. The initial steps included loading the dataset, displaying its structure, and checking for missing or duplicated values.

2. Exploratory Data Analysis (EDA)
a. Correlation Matrix
We calculated the correlation matrix for numeric attributes and visualized it using a heatmap to identify relationships between different base stats.

b. Distribution of Pokémon Types
We visualized the distribution of primary and secondary Pokémon types to understand the commonality of each type.

c. Special Attacks Across Types
Box plots were used to compare the distribution of special attack values across different Pokémon types, revealing the variations in special attack strengths.

d. Speed Across Generations and Types
We analyzed the speed attribute across different generations and types of Pokémon, using box plots to highlight the differences.

e. Legendary vs Non-Legendary Comparison
We compared the base stats of legendary and non-legendary Pokémon, focusing on special attack, special defense, and speed attributes. Box plots were used for visualization.

f. Scatter Plots for Relationships Between Stats
Scatter plots were generated to show the relationships between different base stats, providing insights into how different stats correlate with each other.

3. Predictive Modeling
a. Random Forest Classifier
A Random Forest classifier was developed and tuned using GridSearchCV to find the best hyperparameters. The model's performance was evaluated using accuracy, precision, recall, and F1 score metrics.

b. Support Vector Machine (SVM)
A Support Vector Machine classifier was also trained and evaluated to compare its performance with the Random Forest classifier. Performance metrics were calculated and compared.

Summary of Findings
The EDA revealed significant patterns and correlations in the Pokémon dataset, such as the relationship between different base stats and the distribution of Pokémon types.
The predictive models, including Random Forest and SVM, were effective in classifying Pokémon as legendary or non-legendary, with the Random Forest model performing slightly better after hyperparameter tuning.
