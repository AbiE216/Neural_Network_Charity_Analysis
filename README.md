# Neural_Network_Charity_Analysis
## Overview
This project was to gain familiarity with Deep learning through neural networks. 
### Purpose 
We were tasked with creating a neural network that could accurately predict if a charity was real and would legitamately use the funds given to it, 75% of of the time. 

## Results
### Data Preprocessing
  - The target variable for this analysis was, Is_Successful, however Status also could have been used for analysis. 
  - The feature variables for this data set are: the Ask Amount, Application type, Income amount, and special considerations; here the status was used as a feature. 
  - We removed EIN and Name, as they had no relevance to this type of analysis. 
### Compiling, Training, and Evaluating the Model
  - In my most successful model, I used two hidden layers, the first hidden layer had 90 neurons, and the second had 50 neurons, however, the additional neurons performed no better than the 8 and 5 neurons per layer. I attempted relu, sigmoid, and tanh. Sigmoid was the most successful, whereas the tanh performed the worst. 
  - I did not achieve target performance with this model. 
  - I attempted to increase the hidden layers, increase the neurons, I tried different activation functions. I tried different numbers of epochs, there was no discernable difference, between 50, 100, and 150 epochs. There was no increase in performance in using more neurons or hidden layers. 
## Summary 
The model predicted correctly 73% of the time, what charities are worth funding. However it did not reach the target of 75%. It is worth exploring other models, to see if greater accuracy can be acheived. I think SVM could be a viable option, because this question could be classified as a binary classification, as it is either successful or not successful, then an SVM might bea better fit. It is also good with outliers, and when examining the clusters, there was singular point independent of all the other points, SVM might be able to compensate for this. 
