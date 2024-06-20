# Description
This analysis is about to predict whether income exceeds $50K/yr based on census data, also known as "Census Income" dataset.
**XGBoost** is used to perform **binary classification**. This project involves data preparation, model training, evaluation, and prediction.

# Dataset Reference 
Becker,Barry and Kohavi,Ronny. (1996). Adult. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20.

# Dataset description

**Variable Name**: **Type**, **Demographic**
- **age:**	            Integer,            Age
- **workclass:**	    Categorical,	    Income
- **fnlwgt:**	        Integer,	-
- **education:**	    Categorical,	    Education Level
- **education-num:**    Integer,	        Education Level
- **marital-status:**	Categorical,	    Other
- **occupation:**	    Categorical,	    Other
- **relationship:**	    Categorical,	    Other
- **race:**	            Categorical,	    Race
- **sex:**	            Binary	            Sex
- **capital-gain:**	    Integer,	-
- **capital-loss:**	    Integer,	-
- **hours-per-week:**	Integer,	-
- **native-country:**	Categorical,	    Other
- **income:**	        Binary, 	        Income

# Model Performance
- Weighted Average Precision: 0.86
- Accuracy: 0.87