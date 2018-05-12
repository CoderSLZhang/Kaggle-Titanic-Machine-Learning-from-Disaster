![image](https://github.com/CoderSLZhang/Kaggle_Titanic_Machine_Learning_from_Disaster/blob/master/img/titanic_header.jpg)

## 数据分析

### 社会等级与幸存率的关系

![image](https://github.com/CoderSLZhang/Kaggle_Titanic_Machine_Learning_from_Disaster/blob/master/img/Pclass.png)

*社会等级越高，幸存率越高*

### 性别与幸存率的关系

![image](https://github.com/CoderSLZhang/Kaggle_Titanic_Machine_Learning_from_Disaster/blob/master/img/Sex.png)

*女性的幸存率比较高*

### 年龄与幸存率的关系

![image](https://github.com/CoderSLZhang/Kaggle_Titanic_Machine_Learning_from_Disaster/blob/master/img/Age.png)

*可见小孩的幸存率比较高*

### 亲朋好友数量与幸存率的关系

![image](https://github.com/CoderSLZhang/Kaggle_Titanic_Machine_Learning_from_Disaster/blob/master/img/Family_size.png)

*亲属和配偶的数量和父母子女的数量合并为一个特征*

### 票价与幸存率的关系

![image](https://github.com/CoderSLZhang/Kaggle_Titanic_Machine_Learning_from_Disaster/blob/master/img/Fare.png)

*票价越贵，乘客越有钱，幸存几率越大*

### 登船地点与幸存率的关系

![image](https://github.com/CoderSLZhang/Kaggle_Titanic_Machine_Learning_from_Disaster/blob/master/img/Embarked.png)

*可以看到在Cherbourg登陆的乘客幸存几率大*

## 模型训练

### 模型是用tensorflow实现的神经网络，经过简单的超参数搜索，获得以下超参数及学习曲线

lr = 0.002

epochs = 15000

labmd = 15

layers_deep = 7

layers_width = 21

threshold = 0.5

### 训练的成本值曲线，正确率曲线

![image](https://github.com/CoderSLZhang/Kaggle_Titanic_Machine_Learning_from_Disaster/blob/master/img/learn_curve.png)

### 最后提交到kaggle的最高得分是0.77511
