# 基于EM算法推导K-means算法

## **K_means算法推导**

K-means算法是EM算法的特例，它的算法流程及其与GMM,EM的关系如下
![](1.png)

![](2.png)

推导过程如下

![](3.png)

本质上来说，就是将数据分布假设为正态分布，再用EM算法估计每个正态分布的均值

## 实现对19个样本进行聚类，聚为两个簇<br>
![](4.png)

运行代码
```
python k_means1.py
```

## 聚类结果展示：
![img_4.png](5.png)

## 实现对Mnist手写体3，6，9三类别数字进行聚类，
原数据存储于Sample.csv中
聚类结果分别存储于index1，index2，index3中

运行代码
```
python k_means2.py
```
## 聚类结果展示：
index1：
![img_1.png](6.png)

index2：
![img_2.png](7.png)

index3：
![img_3.png](8.png)
