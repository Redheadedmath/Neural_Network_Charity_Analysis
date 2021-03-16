# Neural_Network_Charity_Analysis

## Analysis Overview
This analysis sought to create a predictive model for a specific bank’s customer database for whether a given loan would be paid back successfully. The model consisted of a Neural Network created via Tensorflow’s Keras package in python. The model took into account several different features, such as type of loan, various demographic information about the customer, and features relating to the respective loans taken by those customers. 

## Data Processing
<ul>
    <li><strong>What variable(s) are considered the target(s) for your model?</strong> <br />
    The target of the model was the "IS_SUCCESSFUL" feature. That is, the loan was paid back successfully.</li>
    <li><strong>What variables are considered features for your model?</strong> <br />
    While this list of potential features was updated throughout the testing phase in order to try to optimize the network, the following list were the final features for the model. 
    <img src="Resources/features.png" alt="List of features" /> </li>