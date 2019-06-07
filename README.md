# Big Data Analytics Homework2



我對Microsoft Malware 2015 Dataset的資料:

LargeTrain.csv
LargeTest.csv

## 資料分析

對於使用Xgboost:

我得到 Accuracy: 99.41%

Thresh=0.006, n=33, Accuracy: 99.39% < br>
Thresh=0.005, n=42, Accuracy: 99.41%
Thresh=0.003, n=88, Accuracy: 99.44%
Thresh=0.002, n=135, Accuracy: 99.41%
Thresh=0.001, n=259, Accuracy: 99.41%
Thresh=0.001, n=398, Accuracy: 99.39%
Thresh=0.000, n=1803, Accuracy: 99.41%

的結果

對於使用Gradient Boosting:

我得到 Accuracy: 99.16%

Thresh=0.006, n=17, Accuracy: 99.25%
Thresh=0.005, n=23, Accuracy: 99.25%
Thresh=0.003, n=49, Accuracy: 99.19%
Thresh=0.002, n=92, Accuracy: 99.25%
Thresh=0.001, n=196, Accuracy: 99.25%
Thresh=0.001, n=344, Accuracy: 99.14%
Thresh=0.000, n=1803, Accuracy: 99.11%

的結果

雖然兩者演算法的分析精準率都高達 99%

但Xgboost 的精準率 往往比 Gradient Boosting 要來的高 0.2%以上

可見得 Xgboost 分析出來的精準率 還是比 Gradient Boosting 高
