# programming_fundamental_finalwork 徐子诚
这是编程基础期末作业仓库
在本次作业中使用dry bean数据集，筛选特征，并进行了多变量Logistic拟合和随机森林模型拟合
在代码后端，编写了一个dry_bean类
在初始化dry_bean类时需要输入两个dataframe
一个是要预测的dataframe，一个是用于模型拟合的数据集
并且添加了一个报错，当要预测的dataframe有值是超出了定义域的就会报错，提示输入的值超出范围
