# 使用LSTM网络实现简单的智能问答系统

问答系统最重要的一步就是对提问者的问话进行意图分析，只要识别出提问者的意图，就可以调用相应的处理模块进行进一步的信息提取和相应的处理模块进行回答。

使用LSTM神经网络结合百度的中文词嵌入处理，能够在少量数据时，识别出用户的意图，甚至能识别出一些以前没有见过的问题

下面用简单的常见的五个智能助理的功能进行测试和演示，看看lstm网络如何在少量数据时，也能精准识别出用户的问答意图。（哈哈，还是大量数据时更加准确，不过少量时也不比基于规则和基于统计的问答处理差到哪里去，因为使用了词嵌入，所以在一些没见过的问题会识别得更好，这是基于规则和基于统计方法无法比拟的）

#问天气

#导航

#唱歌

#提醒功能

#医疗咨询

下面就是测试结果，五个意图全部测试正确，有些测试问题还是没有见过的。

如果本项目对你有帮助，请点星

最后输出的就是对应的问题属于什么意图的概率

![Image text](https://github.com/blueapplehe/npl/blob/master/234.png)


