# recsyspy
经典推荐算法实现
* 基于scipy 稀疏矩阵构建数据模型
* 算法过程模块化，易于扩展
* 使用k折交叉验证测试算法

## 算法
| 矩阵分解模型 | RMSE     | MAE
| :-------- | :-------- | :-------- |
| Baseline  | 0.946|0.742 
| SVD|0.931|0.731|
| SVDPlusPlus|0.927|0.726
| Explicit ALS  |1.199|0.903
| Implicit ALS |2.752|2.525

|邻居模型 |RMSE|MAE
| :-------- |:--------|:-------- |
|Itemcf|1.029|0.802
|WeightedSlopOne|1.043|0.835|


## 数据集
* MovieLens 

## 依赖
* scipy
* numpy

## 参考paper
* Yehuda Koren. Factorization meets the neighborhood: a multifaceted collaborative filtering model
* Matrix factorization techniques for recommender systems
* Advances in Collaborative Filtering
* Slope one predictors for online rating-based collaborative filtering