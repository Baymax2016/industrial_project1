# industrial_projetc1

#项目背景：某生产线窑头以及窑尾工段投放垃圾会影响熟料煅烧过程温度的控制，特别是分解炉出口温度控制在窑尾工段投放垃圾时产生非常大的波动（15%-20%），因此在APC控制时主要参考C5出口温度进行控制。

#项目需求：用三个测量变量te514，te708，mmyw_ai1预测C5出口温度te506未来5s内的值

#jutaijiancai.ipynb:在juypter notebook中做数据预处理和初步数据分析

#jutaijiancai.py:实现数据预处理，训练和预测以及最后输出的类

#new.py：实现类对象的新建和方法调用实现最后一天的预测
