## ML学习笔记

**第一阶段学习**

- [ ] Andrew Ng斯坦福机器学习公开课
- [ ] 李航统计学习方法
- [ ] 机器学习实战
- [ ] 西瓜书
- [ ] 花书
- [ ] MLAPP
- [ ] ApacheCN 机器学习课程

**第二阶段**

- [ ] 推荐系统实战

**第三阶段**

持续学习

## 机器学习专业术语

* 模型（model）：计算机层面的认知
* 学习算法（learning algorithm），从数据中产生模型的方法
* 数据集（data set）：一组记录的合集
* 示例（instance）：对于某个对象的描述
* 样本（sample）：也叫示例
* 属性（attribute）：对象的某方便表现或特征
* 特征（feature）：同属性
* 属性值（attribute value）：属性上的取值
* 属性空间（attribute space）：属性张成的空间
* 样本空间/输入空间（samplespace）：同属性空间
* 特征向量（feature vector）：在属性空间里每个点对应一个坐标向量，把一个示例称作特征向量
* 维数（dimensionality）：描述样本参数的个数（也就是空间是几维的
* 学习（learning）/训练（training）：从数据中学得模型
* 训练数据（training data）：训练过程中用到的数据
* 训练样本（training sample）:训练用到的每个样本
* 训练集（training set）：训练样本组成的集合
* 假设（hypothesis）：学习模型对应了关于数据的某种潜在规则
* 真相（group-true）:真正存在的潜在规律
* 学习器（learner）：模型的另一种叫法，把学习算法在给定数据和参数空间的实例化
* 预测（prediction）：判断一个东西的属性
* 标记（label）：关于示例的结果信息，比如我是一个“好人”。
* 样例（example）：拥有标记的示例
* 标记空间/输出空间（label space）：所有标记的集合
* 分类（classification）：预测时离散值，比如把人分为好人和坏人之类的学习任务
* 回归（regression）：预测值时连续值，比如你的好人程度达到了0.9，0.6之类的
* 二分类（binary classification）：只涉及两个类别的分类任务
* 正类（positive class）：二分类里的一个
* 反类（negative class）：二分类里的另外一个
* 多分类（multi-class classification）：涉及多个类别的分类
* 测试（testing）：学习到模型之后对样本进行预测的过程
* 测试样本（testing sample）：被预测的样本
* 聚类（clustering）：把训练集中的对象分为若干组
* 簇（cluster）：每一个组叫簇
* 监督学习（supervised learning）：典范--分类和回归
* 无监督学习（unsupervised learning）：典范--聚类
* 未见示例（unseen instance）：“新样本“，没训练过的样本
* 泛化（generalization）能力：学得的模型适用于新样本的能力
* 分布（distribution）：样本空间的全体样本服从的一种规律
* 独立同分布（independent and identically distributed，简称i,i,d.）:获得的每个样本都是独立地从这个分布上采样获得的。

## 机器学习实战

1. kNN

归一化数值计算方法：newValue = (oldValue-min)/(maxValue-minValue)

2. 决策树

## Andrew Ng斯坦福机器学习公开课

1. 机器学习的动机与应用

机器学习的定义：
Arthur Samuel：在不直接针对问题进行编程的情况下赋予计算机学习能力的一个领域。
Tom Mitchell：对于一个计算机程序来说，给它一个任务T和一个性能测量方法P，如果在经验E的影响下，P对T的测量结果得到改进，那么就是程序从E中学习。

西洋棋中经验E对应程序和自己下棋的经历，任务T是下棋，P和人类棋手对弈的胜率。

监督学习：回归问题，分类问题 例子：房产 肿瘤

非监督学习：聚类问题 例子：鸡尾酒会问题

强化学习

2. 监督学习应用：梯度下降

线性回归

梯度下降