# deep-learning-challenge
this challenge will use machine learning and neural networks to help select applicantes for funding who havr a higher prediction rate of success.
PLEASE SEE WORD DOCUMENT WITH FORMATTAING.
1.	Overview of the analysis: Explain the purpose of this analysis.
This analysis will predict which applicants will be successful in their business if Alphabet Soup funds them.
2.	Results: Using bulleted lists and images to support your answers, address the following questions:
•	Data Preprocessing
o	What variable(s) are the target(s) for your model? The target variable are the IS_SUCCESFUL
o	What variable(s) are the features for your model?  The features are all the other columns and does not include IS_SUCCESSFUL
o	What variable(s) should be removed from the input data because they are neither targets nor features? EIN, Name 
•	Compiling, Training, and Evaluating the Model
o	How many neurons, layers, and activation functions did you select for your neural network model, and why? Epochs set to 50 , layers set to 100 and 60, and I set all activation functions to sigmoid. I made these changes to see how they would impact the model accuracy. 
o	Were you able to achieve the target model’s performance? No, I did not achieve the goal of 75. My scores 
n1	73.8
n2	72.9
n3	72.8
o	What steps did you take in your attempts to increase model performance?
Optimization attempt #2
Dropping more or fewer columns. Also Dropped USE_CASE column.
Creating more bins for rare occurrences in columns. 
Optimization attempt #2
Add more neurons to a hidden layer.
Add more hidden layers.
Optimization attempt #3
Use different activation functions for the hidden layers.
Add or reduce the number of epochs to the training regimen.

3.	Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
n1 accuracy of 73.8
 
n3 accuracy of 72.9
 
n2 accuracy of 72.8
 
