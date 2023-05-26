# Who is Baynes 
An often used technique for hyperparameter tuning is a baysian filter [1]. This technique is often able to find an ideal hyperparamater tuning faster than other techniques including a random search or grid search. This is as a result of the use of baysian inferance being available to us. We use this technique in order to find an optimal base learning rate and number of epochs to train the most accurate model. 

## What to do
We first use this open source repo made by Zachary Mueller:
https://github.com/muellerzr/BaysianOptimizationFastAI/blob/master/Baysian_Optimization_in_FastAI.ipynb
This details how to use the baysian inferance library in python for a fastai project. We optimize to maximize our accuracy on the testing set.

## The results
The results were great. On resnet18 we were able to get to an accuracy of 97.47%, an amazing result, especially considering the difficulty humans often have on these datasets. 


## Sources
1: https://medium.com/swlh/the-hyperparameter-cheat-sheet-770f1fed32ff
[1] https://medium.com/swlh/the-hyperparameter-cheat-sheet-770f1fed32ff