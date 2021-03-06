# Machine-learning & NLP-learning

关于ML（偏NLP方向）这门学科的入门过程，因为我是转行过来半路出家，中间走了不少弯路，但也有宝贵的经验，整理记录下来，方便自己反思，也可以帮助其他新来的人。
- - -  
## 1. 机器学习入门  

机器学习教材和资料很多，经常会东一下西一下，搞得乱而且没条理。要沉心，把材料耐心看完。
学习效率：写课后作业>看课堂笔记>课程notes>课程lecture>看书>课程视频   

coursera上视频太慢，大多数时候不建议。

### 1.1 看过的公开课和书
- [jindongwang的github](https://github.com/jindongwang/MachineLearning)，介绍了很多入门的内容.  
- andrew Ng 机器学习 coursera公开课。入门级别 作业matlab。简单，通俗，极其适合作为入门级别的第一门课。
- 统计学习基石&技法 林轩田 youtube。可以补充Ng没有讲过的内容，ensenble method一大类Ng讲得很少。但是因为没有做作业所以收获感觉不大。
- 机器学习 周志华。 目前为止看到最好的一本书，前八九章讲得深浅适中，看书理解效率高。概率图和PCA和半监督学习那几章都是简单介绍入门吧，在后面就是更多纯理论东西，暂时看不大懂。
- CS231N FeiFei。 Stanford 课质量有保证，对神经网络讲得深入透彻，主要是写了一遍作业感觉还很有收获。
- CS224 （正在看，待补充）   
课后作业答案or笔记: [链接 1](https://github.com/bogatyy/cs224d), [链接 2](http://blog.csdn.net/han_xiaoyang/article/details/51760923), [链接 3](  https://wugh.github.io/posts/2016/02/cs224d-notes1-word2vec/)   
- 统计学习方法 李航。 大家都说好，看了几天，过于精炼和抽象，没有example，感觉看不大懂（扔了）。
- PRML & MLAPP 。 大部头，概率讲得太多，而且数学推导太多，看了前几章，感觉过于纠结一下数学上的tips，不是很适合我。而且目前最火的NN基本没讲。暂时先放了。 [PRML中英文下载](http://ddl.escience.cn/f/Iwoo#)
- [CMU 10715](https://www.cs.cmu.edu/~epxing/Class/10715/) 数学（概率方面）讲得很多，和PRML结合着看，在beyas和EM方面讲得还很不错，例如在概率的角度来理解LR和SVM方法。


### 1.2 开源project

动手写永远是最重要的。   

主要是以kaggle比赛为主。因为刚刚入门，大多还停留在熟悉各种语法和研究各位大神kernel的阶段。[一些当时做的笔记](https://github.com/liufeng900204/Kaggle-Notebook/wiki)   
kaggle 的问题在于数据过于干净了，相对实际应用场合还是会有各种问题，但相对来说，作为初学者已经很好了。

### 1.3 框架学习&系统配置搭建

这个过程走了许多弯路，包括学习keras/Theona/tensorflow，然后换操作系统到ubuntu，折腾GPU和显卡。这些内容琐碎，而且到处都是坑。因为转行过来的，开始习惯写blog，写github，用markdown等程序员必备。

github 初初初初级入门：[建立项目&push&pull](http://blog.csdn.net/tina_ttl/article/details/51326684)   

- - -


## 2. NLP 问题

### 2.1 神经网络：CNN or RNN   

[使用CNN RNN Attention解决大规模文本分类问题](http://www.sohu.com/a/130492867_642762)

有助于理解CNN处理NLP问题的案例（from 杨老师）   
http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/
http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/

有助于理解RNN处理NLP问题的案例（from 杨老师）    
https://github.com/tensorflow/models/tree/master/tutorials/rnn   
https://github.com/tensorflow/models/tree/master/tutorials/rnn/ptb

[Minimal character level language model](https://github.com/weixsong/min-char-rnn)
100行的代码，建立了一个model，不考虑单词本身的含义，只考虑字母之间的排列顺序。（类似于词袋模型？）

 
### 2.2 LDA算法   

[通俗理解LDA主题模型](http://blog.csdn.net/v_july_v/article/details/41209515)
[火光摇曳的blog](http://www.flickering.cn/tag/lda/)
