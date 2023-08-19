
- The target variable is the 'IS_SUCCESSFUL' column from application_df

- The feature variables are all columns from the original dataframe application_df except 'IS_SUCCESSFUL'

- Both 'EIN' and 'NAME' columns were dropped.


Compiling, Training, and Evaluating the Mode
- In the first attempt, i used 80 nodes in layer1 and 30 nodes layer 2

- The 3 models did not achieve the 75% accuracy target

- I changed the layers and hidden nodes combination in an attempt to achieve higher model accuracy. 

Summary

Overall, the deep learning model was around 73% accurate in predicting the classification problem. Additional data processing is needed to achieve higher accuracy
