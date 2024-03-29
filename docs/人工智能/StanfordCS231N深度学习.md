课号：[Stanford CS231N](http://cs231n.stanford.edu/)

教授：Feifei Li等

评论贡献者：[Zhang-Each](https://github.com/Zhang-Each)

- [X] Videos：B站上到处都是，还有字幕
- [X] Assignment * 3，每个Assignment工作量都比较大，可以分割成更小的
- [X] AutoGrader：每个notebook中自带一些测试用例，足够验证代码的正确性
- [X] Slides & Reading：见课程网站

## 课程信息

- 深度学习导论课程，非常经典的入门课，从机器学习开始一步步讲到深度学习，神经网络，从MLP逐渐扩展到CNN，RNN，LSTM，GAN，Transformer等模型，对于深度学习中的CV和NLP均有所涉猎
- 3个assignment的工作量比较大，使用Python和Jupyter Notebook完成，**大部分内容都是基于numpy从底层开始实现**，少部分任务可以直接使用pytorch等深度学习框架，每个lab的具体内容主要有：

| Assignment编号 | 具体内容                                                     |
| -------------- | ------------------------------------------------------------ |
| 1              | 实现SVM和线性分类器算法，实现KNN算法，实现神经网络全连接层和激活函数层的前向传播和反向传播算法并搭建一个两层的MLP |
| 2              | 实现卷积层、池化层、标准化层和Dropout层的前向传播和反向传播，并组成一个有标准化层的MLP和一个有三层的CNN，使用pytorch或tensorflow实现一个CNN，测试的task都是图片分类 |
| 3              | 实现RNN和LSTM层的前向传播和反向传播并组成循环网络，测试在Image Caption任务中的表现，实现Transformer模型的关键组件并测试Transformer模型在Image Caption任务中的表现，实现GAN并测试其在手写数字生成任务中的表现，实现深度学习可视化相关的一些函数 |

- 同时作业**配备了相当数量的测试点**，基本每写一个关键函数都会提供一个单元测试来判断有没有写错，一般误差在标准范围内就可以放心进行下一步了

## 适合人群

- 深度学习入门并且具有一定的数学基础和Python编程能力的人(主要是numpy等库的api需要掌握的比较熟练)

## 课程评价

- 个人认为**深度学习入门神课这一称号当之无愧**，上课内容是一个方面，我认为这门课最大的价值在于它的3个assignment，做完之后不仅对课上讲到的各种概念有了更底层的理解，也非常锻炼Python编程能力，并且能帮助你掌握numpy和pytorch等库中的关键api
- 实现一系列神经网络中的经典模型是一件比较有成就感的事情，这些assignment做的过程也非常愉快
- 同时notebook中配备的大量测试点也可以提供及时的反馈信息，我认为要完成这些作业很重要的一点就是要将slides中将的公式和实际代码相结合，并且反向传播部分的作业中需要进行大量的求梯度推导，个人认为需要一定的数学能力

## 非官方资料推荐

- 深度学习中的经典论文，详情见课程网站
- Github上也有很多公开的课程笔记，可以选择性使用
- 给自己的[博客](https://zhang-each.github.io/)引个流，博客中的【手写神经网络】系列的博客是我在完成assignments时的一些心得体会和公式推导，希望能够帮到您

## 后续课程推荐

- CS224N 基于深度学习的自然语言处理
- CS224W 图机器学习(实际上是图神经网络导论)

## 文件列表

- StanfordCS231N深度学习
