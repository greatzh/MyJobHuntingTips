---
description: 深度学习面试
---

# Deep learning

1.  Epoch/Iteration/Batchsize

    batchsize：批次大小，在深度学习里面，一般采用SGD训练，即每次训练在训练集中去batchsize个样本进行训练

    iteration：迭代，1个iteration等于使用batchsize个样本训练一个，一个迭代等于一个正向通过加一个反向通过

    epoch：迭代次数，1个epoch等于使用训练集中全部的样本训练一次，一个epoch等于所有训练样本的一个正向传递和一个反向传递。
2.  CNN的本质和优势

    局部卷积（提取局部特征

    权值共享（降低训练难度

    Pooling（降维

    多层次结构
3.  数据预处理的方法（降低输入数据特征之间冗余，让数据的分布更加符合期望，增强数据的表达能力

    零均值

    归一化

    标准化

    中心化

    PCA和白化

    Batch normalization：加速梯度训练，抑制个各batch之间个位置点像素分布的剧烈变化带来的学习难度。
4.  池化

    平均池化

    最大池化
5.  感受野

    卷积神经网络每一层输出的特征图上的像素点在原始输入图片上映射的区域大小，特征图上的一个点对应原石输入图片上的区域。神经元看到的区域，一般就是要确输出像素的感受野足够大，确保做出决策时没有忽略重要信息。
6.  优化算法

    SGD

    AdaGrad

    Momentum

    RMSProp

    Adam
