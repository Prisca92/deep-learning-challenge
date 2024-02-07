# deep-learning-challenge

Alphabet Soup, a nonprofit organization, needed a way to choose which applicants to fund for their projects. The purpose of this analysis is to make predictions in order to determine which charities are "SUCCESSFUL". To do this, we developed a deep-learning neural network. This program was created to decide whether they're likely to succeed if they get funding.

Results:

Data Processing:
Target Variable for the model : IS_SUCCESFULL 
Features for model: 43
Variables removed: EIN and Name columns


Compelling,Training, and Evaluating the Model:

To increase model performance in the first attempt I dropped a couple columns. In the second attempt I added third hidden layer, added more neurons to hidden layer, changed all activation functions for hidden layers to "sigmoid". In the third and final attempt I also added a third hidden layer, added more neurons to the hidden layer, and I also added the number of epochs to the training regimen from 100 to 200.

Baseline( (First Attempt) -Accuracy score:73%
Optimization # 2 -Accuracy score: 72%
Optimization # 3 - Accuracy score: 73%

 Summary:

 Overall, I was not able to achieve the target model performance, the base model and tihrd attempt both had the best accuary score of 73%. If I were to perform another optimazation I would simply keep the same amount of hidden layers(2), change the neurons and keep the activation functions as (relu,relu,sigmoid)
