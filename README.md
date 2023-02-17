 ![saudi-aramco-logo](https://user-images.githubusercontent.com/123948477/218477892-99afc7f7-c54e-4673-9412-ac4dac672bc6.png)
 # Home task solved by Alexander Bessonov for the job of data scientist intern in Aramco Inn.
 
 ## Task
This home task is for an intern data scientist. The task is to build a multioutput regression model. Link to the data: https://disk.yandex.com/d/-n1_UXqKXJw1_g

1. Create baseline model of your choice. This should be a simple model that can be used to compare the performance of more complex models
2. Create a multioutput regression model to predict multiple outputs from a given dataset. This could be a linear regression model, a neural network, or any other suitable model
3. Use appropriate techniques to preprocess the data, such as normalization, feature selection, and feature engineering
4. Evaluate the performance of the model using appropriate metrics and appropriate cross-validation strategy. Compare it to the baseline
5. Tune the model's hyperparameters to optimize the model's performance (if applicable)
6. Visualize the results of the model to provide insights into the data
7. Suggest the improvements to the model. This should include any insights gained from the model and any recommendations for further improvements
8. Provide a brief summary of the model and the results (1 paragraph of text maximum)
Good luck!

## Preprocessing 
In this section, we should examine the data, separate target and non-target variables, remove omissions, and replace categorical factors.
> ![image](https://user-images.githubusercontent.com/123948477/218475812-03b37bf6-7f39-4ac5-9156-f0b04d13a1fc.png)

## Overfitting Check
Dividing the dataset into training, validation, and test parts to check the overfitting hypothesis.


## Feature Selection
In this section, we build histograms and decide to eliminate some non-target factors before training and testing the model.

## Model Initialization and Evaluating
Several different models have been created in the project. Then their quality is checked by common metrics.

## Comparison
> ![image](https://user-images.githubusercontent.com/123948477/219690053-43c0b481-c525-4efa-9c3a-9ef4e22f4b3a.png)

## Submit 
The best model predicts the values of the target factors of the test file and records the [results](https://github.com/bezzonov/Aramco/blob/main/data/submit.csv).

## Conclusion
We get not so good performance. I think the main reason is the size of the data. After all, it is very difficult to train a model very well when the training dataset is so small. I can suggest what more could have been tried for future improvement of the model:

1. Building new non-target factors or increase the number of rows in the dataset.

2. Automatically select the best parameters for the model using technologies such as gridsearch, shap, etc.

3. Cross-validation.

## You can see the full version of the solution [here](https://github.com/bezzonov/Aramco/blob/main/solution/Aramco_task.ipynb)
Thank you very much for the interesting test assignment!

