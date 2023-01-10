
# 刘一恒+2022103802+期末作业

本ipynb文件是2022-2023第一学期中国人民大学大数据学院专硕生编程基础期末作业

本文件对万柳PM2.5数据进行分析，数据来源：https://archive.ics.uci.edu/ml/datasets/Beijing+Multi-Site+Air-Quality+Data

选取其中的csv：PRSA_Data_Wanliu_20130301-20170228.csv 进行分析
## 作者

- [@Jiangswitch](https://github.com/Jiangswitch)


## 版本

使用的版本为3.6.5 |Anaconda, Inc.| (default, Mar 29 2018, 13:32:41) [MSC v.1900 64 bit (AMD64)]
    
## 环境

本ipynb所在的环境为 

`C:\\ProgramData\\Anaconda3\\python36.zip`
`C:\\ProgramData\\Anaconda3\\DLLs`
`C:\\ProgramData\\Anaconda3\\lib` 
`C:\\ProgramData\\Anaconda3`
`C:\\Users\\江思微\\AppData\\Roaming\\Python\\Python36\\site-packages`
`C:\\ProgramData\\Anaconda3\\lib\\site-packages`
`C:\\ProgramData\\Anaconda3\\lib\\site-packages\\win32`
`C:\\ProgramData\\Anaconda3\\lib\\site-packages\\win32\\lib`
`C:\\ProgramData\\Anaconda3\\lib\\site-packages\\Pythonwin`
`C:\\ProgramData\\Anaconda3\\lib\\site-packages\\IPython\\extensions`
`C:\\Users\\江思微\\.ipython`



## 项目实现功能简介
PM2.5变量相关图：矩阵散点图、直方图、箱线图、相关系数热力图

PM2.5时间序列模型：部分数据的拟合和预测

PM2.5SVM回归：数据拟合
## 代码复现
以ipynb从上到下顺序复现，先构造类和函数再代入数据库

可以自行使用类似的其它数据库，如同一个链接内的其它数据库，但类只实现24小时季节性和365年季节性的处理

对于其它数据库，可能存在的问题：列名不一致，预测功能无法正确复现

若复现错序可能导致：类函数不存在，DF处理不存在的列，对不存在的数据进行可视化
