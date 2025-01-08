## Project Insight
This project focuses on predicting the salaries of individual in the AI job market..... Focus would be on checking the correlation of each data variables and very importantly being to predict very well enough the base payment for such individual . The evaluation metrics of this problem would be Mean_square_Error, as well as acc_score for the accuracy of the model....This problem is a Regression problem.. The intended model to use for this problem based on the size of our dataset is Linear regression
### libraries 
- import pandas as pd
- import matplotlib.pyplot as plt
- %matplotlib inline
- import seaborn as sns
#### DATA CLEANING 
The data was coverted to numerical variables as machine model deals with numbers and not words, the following encoding techniques were used 
- frequency Encoding
- Target Encoding
- Label Encoding.
  ### Model
  Linear regression was used for this problem, evalauted using mean_squared_error.The model gave a MSE of 490406223.6732681 
  ### Outcome
- Location_d and Automation_Risk_d are the two most impactful variables, with Location_d having a positive effect and Automation_Risk_d having a negative one.
- Variables related to AI adoption, job growth projections, and required skills also significantly contribute to the outcome, though their influence is smaller than the top two.
- Other features, such as Job_Title_d, Remote_Friendly_d, Company_Size_d, and Industry_d, play lesser roles but still contribute to the model's output.
