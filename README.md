字段熟悉
======
了解每个字段含义</br>
找到重点字段，查看该字段下缺失率</br>
是否能用其他非关键字段推出关键字段的值</br>
过滤与贷款无关的字段</br>
  
  

数据清洗
======
尽可能填填补失字段
根据数据之间的关系规则
根据非关键字段可设置默认值
去除重复数据
如何判断数据重复（时间戳？账户余额？）
如何解决重复数据非关键信息不相等？
去除僵尸数据
如何判断数据是僵尸数据（现金流？交易次数？交易时间？）



初步分析
======
数据大致分为哪些层面？
垂直，水平，时间
数据是否存在抽样偏差？
是否可以忽略？
是否需要bootstrap采样？（或删除特定数据）
是否需要特征组合？（或是否存在隐含变量）
哪个层面的数据需要特征组合？
新特征生成方式？（树模型+启发式算法，结构化特征组合)


数据预处理
======
#归一化分析
  不同指标如何归一化？

#降维
  PCA
  正则
  神经网络


