# Deep-Learning-challenge

1. Overview/Purpose of the analysis:

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively


2. Results:

Data Preprocessing:
  What variable(s) are the target(s) for your model?
  What variable(s) are the features for your model?
  What variable(s) should be removed from the input data because they are neither targets nor features?
  
Compiling, Training, and Evaluating the Model:
  1) How many neurons, layers, and activation functions did you select for your neural network model, and why?
       My final optimization contained three hidden layers, two with "relu" activation functions and one "sigmoid, in addition to one output layer with a sigmoid activation function.
       The hidden layers had 8:16:24 neurons. Lastly, I set the model at 100 epochs.
  
  2) Were you able to achieve the target model performance? Yes!
  
  3) What steps did you take in your attempts to increase model performance? In order to increase the model performance, I kept the 'NAME" column and put it into       bins. 
        I then binned the "APPLICATION_TYPE" column, and kept in the "CLASSIFICATION" bin from the first model. Finally, I added a third hidden "sigmoid" layer to the             model, assigned them input features of 8:16:24.

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.




