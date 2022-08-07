# Neural_Network_Charity_Analysis
Neural Network challenge 

# Overview
This analysis was conducted to predict if applicants would be successful after receiving funding from AlphabetSoup, using a neural network model.

# Results
### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- IS_SUCCESSFUL Feature
What variable(s) are considered to be the features for your model?
- All features aside from IS_SUCCESSFUL, NAME, and EIN have some importance to the prediction. However, if I were to run the model again, I would also test drop STATUS and SPECIAL_CONSIDERATION
What variable(s) are neither targets nor features, and should be removed from the input data?
- NAME and EIN are informational rather than relational to the target feature, and were therefore dropped.
### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
- In the end I used three hidden layers, with 40 nodes for the first, 25 nodes for the second, and 15 nodes for the third. I kept all nodes under the size of the input layer (43) after doing some reading on rules for choosing layers and nodes.
Were you able to achieve the target model performance?
- I was able to get close to the target model performance (75%) and missed it by 5 percentage points.
What steps did you take to try and increase model performance?
- I added 1 hidden layer and applied 15 nodes to it, I also increased nodes for the original first and second layers. Also, I tightened the bin limits for the TYPE and CLASS features.

# Summary
- This particular model shows some success, and if tweaked by someone with a better understanding of the model and neural networks, I think it could be properly optimized. 
- With my limited understanding, however, my recommendation would be to try a forest model. I make this recommendation more off instinct than any imperical knowledge. 