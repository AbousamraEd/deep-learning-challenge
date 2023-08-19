
- The target variable is the 'IS_SUCCESSFUL' column from application_df

- The feature variables are all columns from the original dataframe application_df except 'IS_SUCCESSFUL'

- Both 'EIN' and 'NAME' columns were dropped.


Compiling, Training, and Evaluating the Mode
- In the first attempt, i used 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2 -- these were just random guesses from which to iterate upon in the second try.

- I was not able to achieve the 75% model accuracy target

- I changed the layers and hidden nodes combination and switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy. 

Summary

Overall, the deep learning model was around 73% accurate in predicting the classification problem. Additional data processing is needed to achieve higher accuracy
