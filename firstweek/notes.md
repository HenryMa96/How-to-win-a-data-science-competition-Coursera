## skills  checklist：
[ ] how to preprocess the data,
[ ]  extract features,
[ ]  how to set up the validation correctly 
[ ] and optimize the given metric. 
[ ] You should know the potential sources of data leakages,
[ ]  what parameters to tune in your favorite models,
[ ]  how to generate powerful features, 
[ ] how to ensemble the models. 

## content in first week:

	* difference between real life data analyse and data science competition,
	* hardware and software usually used
	* commonly used models in competition
	* data preprocessing
	* the impact of model in feature extraction

## important issues of competition
	1. data
	2. model
	3. prediction/submission
	4. evaluation function: accuracy; logitic loss; AUC; RMSE;  MAE
	5. leaderboard


## kaggle interface:  
  kernal is very intereting, it is a online notebook

### the insight unserstanding of data is very important.

### It is ok to use heuristic and manual data analysis, And do not be afraid of complex solutions, advanced feature engineering and doing huge calculation

### GBDT and netual network is usually used, but sometimes KNN and linear model may be better.


进阶:极端随机树：Extremely randomized trees
ET或Extra-Trees（Extremely randomized trees，极端随机树）是由PierreGeurts等人于2006年提出。该算法与随机森林算法十分相似，都是由许多决策树构成。但该算法与随机森林有两点主要的区别：
1、随机森林应用的是Bagging模型，而ET是使用所有的训练样本得到每棵决策树，也就是每棵决策树应用的是相同的全部训练样本；
2、随机森林是在一个随机子集内得到最佳分叉属性，而ET是完全随机的得到分叉值，从而实现对决策树进行分叉的。

各种算法得到的图像？


