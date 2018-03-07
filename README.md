# Recommondation-System
一些传统推荐算法的实现，包括基于内容的推荐，协同过滤，矩阵分解


### 测试数据

测试数据使用的是movielens数据集



### 实现算法

* 基于内容的推荐算法
* 协同过滤推荐算法
* 矩阵分解的推荐算法



### 代码结构

main.py  这是各种算法的入口

----data_preprocessing  对原始数据进行预处理的代码

----CB_recommendation  包含基于内容的推荐算法实现代码

----CF_recommendation  包含协同过滤推荐算法实现代码

----MF_recommendation  包含矩阵分解推荐算法实现代码

----measure  一些用于计算度量的方法



### 算法结果

| 算法        | MSE        | RMSE       |
| --------- | ---------- | ---------- |
| 基于内容的推荐算法 | 0.96124462 | 0.98043083 |
| 协同过滤推荐算法  | 1.25509244 | 1.12030908 |
| 矩阵分解推荐算法  | 0.95787807 | 0.97871245 |



### To do

* 算法代码结构的优化
* 基于图的推荐算法
