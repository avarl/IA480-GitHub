
# Report: Predicting Lifespan of Irish Animals Based on Population Data

## 1. Data Source and Description of the Dataset

The dataset used in this study was sourced from Kaggle. It focuses on the population of various animals in Ireland, with particular attention to their lifespan. The dataset contains information regarding different species and their respective population sizes. The goal of this analysis was to explore the relationship between an animal’s population and its lifespan in Ireland.

## 2. Research Question or Objective of the Model

The primary research question driving this analysis is: 
**How can the lifespan of an animal be predicted based on its population size?** 

This question seeks to establish whether there is a correlation between the population of an animal species in Ireland and its maximum lifespan, and if so, how this relationship can be used to predict lifespan for different species.

## 3. Target Variable (Label) and Key Predictor Features

- **Target Variable (Label):**  
  The target variable for this model is the **max lifespan** of an animal. The goal is to predict this value based on the input features available in the dataset.

- **Key Predictor Features:**  
  One of the main predictors used in the analysis was **population size**, which was assumed to influence an animal’s lifespan. The hypothesis is that animals with larger populations might experience different environmental and ecological factors that could affect their lifespan compared to animals with smaller populations.

## 4. Summary of the Data Cleaning Process

No data cleaning process was applied in this analysis, as the dataset was relatively small and did not present significant issues. The dataset appeared to be in a clean and usable format, with no missing or erroneous values that required correction. As a result, the data was directly used for analysis without any modifications.

## 5. Description of the Training Process and Model Evaluation

The training process for this model used a default training program. This approach involved selecting the dataset, specifying the target variable (max lifespan), and fitting the model to the data. The evaluation of the model was based on its performance in predicting the lifespan based on the population data. No specific hyperparameter tuning or advanced training techniques were employed, as the focus was on using a basic model for the analysis.

## 6. Discussion of Model Performance and Potential Improvements

The model’s performance was assessed using a metric that resulted in a score of 9.721% out of 100, indicating a low correlation between the input features (population size) and the target variable (max lifespan). This low score suggests that the relationship between population size and lifespan may not be as strong as initially anticipated.

Several improvements could be made to enhance the model's performance:
- **Feature Engineering:** Additional features could be included to capture other relevant factors influencing lifespan, such as environmental conditions, food sources, or threats to the species' survival.
- **Advanced Models:** Implementing more advanced machine learning techniques, such as decision trees, random forests, or neural networks, could potentially improve the predictive accuracy.
- **Data Expansion:** Gathering more data or including more animal species could help refine the model and lead to better generalization.

In conclusion, while the model demonstrated a low correlation between population size and lifespan, further improvements could be made by refining the features and applying more advanced modeling techniques.
