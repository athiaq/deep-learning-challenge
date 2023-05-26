# deep-learning-challenge
## Overview
Machine learning and neural networks were used to develop a model that can predcit whether applicants will be successful if funded by Alphabet Soup. The data was first preprocessed using pandas and scikit-learn's StandardScaler(), then the model was compiled, trained, and evaluated. Lastly, the model was optimized to attempt to acheive a target predictive accuracy higher than 75%.

## Results
* Data Preprocessing
  * The target variable is the column IS_SUCCESSFUL.
  * The features used were AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT,     
    SPECIAL_CONSIDERATIONS, ASK_AMT.
  * The variables that should be removed from the input data because they are neither targets nor features are EIN 
    and NAME.
 * Compiling, Training, and Evaluating the Model
  * In the initial optimization model the number of nodes selected were 100, 30, and 10. I wanted to add another 
    hidden layer to see if there was any difference in accuracy scores. 
  * In the second optimization model, the nodes for layer 1 was 80 and the nodes for layer 2 was 30. 
  * In the third optimization model, four layers were added and the nodes for layer 1 was 150, for layer two 80,    
    layer 3 30, and for layer 4 10. 
  * The activation functions selected for the neural network models were relu and sigmoid because they work well  
    for binary classfication models.
  * I was not able to achieve the target model performance.
  * To attempt to increase the model performance, I tried dropped both more and fewer cloumns, increased/decreased    
    the number of values for each bin, added more neurons to a hidden layer, added more hidden layers, and 
    added/reduced the number of epochs to the training regimen. 
    
 ## Summary
 The highest accuracy score I was able to reach was about 72%. To achieve a higher accuracy score, I would try adding more hidden layers as well as adding the number of epochs to the training regimen. 
