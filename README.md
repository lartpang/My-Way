## 声明

由于几篇文章写的内容对于本人而言非常有用，但是为了防止原作“消失”的情况，这里将其进行了打印，保存成了pdf，如果原作者觉得不妥，请联系我，我会删除。保护版权，人人有责！

* 半小时学会 PyTorch Hook - 尹相楠的文章 - 知乎：https://zhuanlan.zhihu.com/p/75054200
* 14 DESIGN PATTERNS TO IMPROVE YOUR CONVOLUTIONAL NEURAL NETWORKS：https://www.topbots.com/14-design-patterns-improve-convolutional-neural-network-cnn-architecture/
* 移动平均：你知道的与你不知道的 - 石川的文章 - 知乎：https://zhuanlan.zhihu.com/p/38276041


## 机器学习/深度学习基础

+ CS229：https://github.com/afshinea/stanford-cs-229-machine-learning
+ transferlearning：https://github.com/jindongwang/transferlearning
+ 数据挖掘：https://github.com/lyltj2010/DataMining
+ saliency：https://github.com/PAIR-code/saliency
+ 机器学习：https://github.com/allmachinelearning/MachineLearning
+ 论文翻译: https://github.com/SnailTyan/deep-learning-papers-translation
+ 综述论文: https://github.com/mlreview/machine-learning-surveys
+ tensorflow教程：https://github.com/open-source-for-science/TensorFlow-Course#why-use-tensorflow
+ 深度学习500问：https://github.com/scutan90/DeepLearning-500-questions
+ 深度学习面试宝典（含数学、机器学习、深度学习、计算机视觉、自然语言处理和SLAM等方向）:https://github.com/amusi/Deep-Learning-Interview-Book
+ zouxy09博客原创性博文导航：https://blog.csdn.net/zouxy09/article/details/14222605
+ L1和L2范数：http://www.chioka.in/differences-between-l1-and-l2-as-loss-function-and-regularization/
+ DeepLearning ON GPU：https://deeplearningongpu.readthedocs.io/en/latest/
+ CNN可视化：
    - Ways for Visualizing Convolutional Networks：https://buptldy.github.io/2016/09/25/2016-09-25-cnn_vis/
    - CNN-Visualization：https://github.com/scutan90/CNN-Visualization
    - 谷歌的新CNN特征可视化方法，构造出一个华丽繁复的新世界：https://www.leiphone.com/news/201711/aNw8ZjqMuqvygzlz.html
    - How to visualize convolutional features in 40 lines of code：https://towardsdatascience.com/how-to-visualize-convolutional-features-in-40-lines-of-code-70b7d87b0030
        + 中文翻译：https://www.jishuwen.com/d/2Lik
    - 【深度学习系列】CNN模型的可视化：https://www.cnblogs.com/charlotte77/p/8343700.html
+ ML Records in 1110 Lab of BUPT：https://github.com/wmn7/ML_Practice
+ 各种计算机领域资料的合集：https://github.com/ty4z2008/Qix
* 如何理解深度学习分布式训练中的large batch size与learning rate的关系？ - 谭旭的回答 - 知乎：https://www.zhihu.com/question/64134994/answer/216895968
+ 想要算一算Wasserstein距离？这里有一份PyTorch实战：https://www.jiqizhixin.com/articles/19031102

## 行人重识别（ReID）相关资料

+ 较为简单直观的一份行人重识别的代码**教程**： https://github.com/layumi/Person_reID_baseline_pytorch
+ 比较全面完整的一份代码：https://github.com/L1aoXingyu/reid_baseline
+ 行人重识别(ReID)**概述**，将该任务的关键内容介绍了一下：https://blog.csdn.net/weixin_41427758/article/details/81188164
+ 行人重识别重要数据集`DukeMTMC-reID`的一个简单介绍，了解一个任务的数据处理，看数据集的结构是比较直接的一个方法：https://blog.csdn.net/ctwy291314/article/details/83544142

## 弱监督、半监督以及蒸馏等手段

+ 让机器“一叶知秋”：弱监督视觉语义分割：https://zhuanlan.zhihu.com/p/37488849
+ 介绍了CVPR19的一篇使用蒸馏处理语义分割的论文：https://segmentfault.com/a/1190000018493751
+ 半监督深度学习小节：https://zhuanlan.zhihu.com/p/33196506
   + https://github.com/iBelieveCJM/pseudo_label-pytorch
+ 半监督深度学习又小结之Consistency Regularization：https://zhuanlan.zhihu.com/p/46893709
+ Attention算法调研(弱监督语义分割)：https://zhuanlan.zhihu.com/p/53218967

## 常用工具

### PyTorch

+ 统计模型运算量和参数量的pytorch-OpCounter：https://github.com/Lyken17/pytorch-OpCounter
+ 一些PyTorch的技巧，但是似乎有些旧了：https://github.com/kevinzakka/pytorch-goodies
+ PyTorch Autograd：Understanding the heart of PyTorch’s magic：https://towardsdatascience.com/pytorch-autograd-understanding-the-heart-of-pytorchs-magic-2686cd94ec95
- 一款特征可视化工具：https://github.com/MisaOgura/flashtorch
+ 高级封装：
    - https://github.com/blue-season/pywarm
+ 训练提速：
    - 简单两步加速PyTorch里的Dataloader - 巽二的文章 - 知乎：https://zhuanlan.zhihu.com/p/68191407
    - 给训练踩踩油门——Pytorch加速数据读取 - MrTian的文章 - 知乎：https://zhuanlan.zhihu.com/p/80695364

### Editor

+ SublimeText：本身没啥问题，而且随着版本的更新，原本在linux上的各种问题基本上也被解决，但是有个关键的问题，在使用GPU跑代码的时候，ST会特别卡顿，只好舍弃，转投VSCode了
+ VSCode：微软的产品，还不错，性能问题逐渐得到优化，是肉眼可见的提升与改进，颜值可以很高
+ Vim：终端修改文件必备，偶尔看看文件，或者远程通过ssh使用Vim写写代码，但是用的不是很痛快，终究还是被PyCharm这样的IDE惯坏了
   
### IDE

+ PyCharm：写Python必备，前提是电脑配置不要太拖后腿，时常卡顿，但是功能强大又贴心，实在无法替代
+ wingide：流畅是流畅，但是一来要激活，二来在我的Ubuntu上无法输入中文，而且创建项目的诡异流程让我怀疑这玩意是怎么想的:(，弃之

### Linux

+ ubuntu16.04安装NIVIDIA显卡驱动，cuda8.0，cuDNN6.0以及基于Anaconda安装Tensorflow-GPU：https://blog.csdn.net/pursuit_zhangyu/article/details/79362128
+ 【解决】Ubuntu安装NVIDIA驱动(咨询NVIDIA工程师的解决方案)：https://blog.csdn.net/u012759136/article/details/53355781#commentBox
+ [专业亲测]Ubuntu16.04安装Nvidia显卡驱动（cuda）--解决你的所有困惑：https://blog.csdn.net/ghw15221836342/article/details/79571559
+ 最全面解析 Ubuntu 16.04 安装nvidia驱动 以及各种错误：https://blog.csdn.net/u014561933/article/details/79958017
+ ubuntu安装nvidia显卡驱动:https://blog.csdn.net/acelove40/article/details/69257574
+ Ubuntu 15.10 使用 Xorg.conf 修改分辨率：https://segmentfault.com/a/1190000004510095

## 基础书籍

### 线性代数

+ Matrix Analysis and Applied Linear Algebra：http://www.cse.zju.edu.cn/eclass/attachments/2015-10/01-1446085870-145420.pdf
   + https://book.douban.com/subject/1479316/
+ Introduction to Linear Algebra（4th）：http://www.math.hcmus.edu.vn/~bxthang/Linear%20algebra%20and%20its%20applications.pdf
   + https://book.douban.com/subject/3582335/

### ML&DL

+ 吴恩达新书: http://nooverfit.com/wp/wp-content/uploads/2018/10/Ng-MLY01-12.pdf

## 文字编辑

* 中英混排中的标点符号问题：https://thetype.com/2018/02/14211/
