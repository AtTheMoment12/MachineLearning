# MachineLearning
## 线性回归


### 线性回归的基本要素
#### 模型  
假设简单的函数，房价：面积（平方米）、房龄（年）。线性回归假设输出与各个输入之间是线性关系

#### 数据集  
训练数据集（training data set）  
样本（sample）  
标签（label）  
特征（feature）
#### 损失函数  
在模型训练中，我们需要衡量价格预测值与真实值之间的误差。通常我们会选取一个非负数作为误差，且数值越小表示误差越小。一个常用的选择是平方函数。  
#### 优化函数--随机梯度下降  
优化函数的有以下两个步骤：  
(i)初始化模型参数，一般来说使用随机初始化；  
(ii)我们在数据上迭代多次，通过在负梯度方向移动参数来更新每个参数。  
#### 矢量计算  
在模型训练或预测时，我们常常会同时处理多个数据样本并用到矢量计算。在介绍线性回归的矢量计算表达式之前，让我们先考虑对两个向量相加的两种方法。  
1.向量相加的一种方法是，将这两个向量按元素逐一做标量加法。  
2.向量相加的另一种方法是，将这两个向量直接做矢量加法。  

### 线性回归模型实现步骤
生成数据集  
读取数据集
初始化模型参数
定义模型  
定义损失函数  
定义优化函数  
训练  

## softmax和分类模型  
1.softmax回归的基本概念  
2.如何获取Fashion-MNIST数据集和读取数据  
3.softmax回归模型的从零开始实现，实现一个对Fashion-MNIST训练集中的图像数据进行分类的模型  
4.使用pytorch重新实现softmax回归模型  

### softmax的基本概念
分类问题  
权重矢量  
神经网络图  
### 交叉熵损失函数
