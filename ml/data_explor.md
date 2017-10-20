# Data Exploration

在这一步要做的基本就是 EDA (Exploratory Data Analysis)，也就是对数据进行探索性的分析，从而为之后的处理和建模提供必要的结论。

我们常用到的工具是：`pandas`, `matplotlib`, `seaborn` and so on

通常我们在做数据探索时会做很多图表，用来可视化的分析数据的分布及特点，常见图表如下：

* 查看目标变量的分布
* 绘制变量之间两两的分布及相关度
* 对 Numerical Variable，可以用 _Box Plot_ 来直观地查看它的分布。
* 对于坐标类数据，可以用 Scatter Plot 来查看它们的分布趋势和是否有离群点的存在
* 对于分类问题，将数据根据 Label 的不同着不同的颜色绘制出来，这对 Feature 的构造很有帮助


这里有一篇关于数据可视化的例子，[在iris数据集上做的可视化分析](https://www.kaggle.com/benhamner/python-data-visualizations)，非常详细

### QA

* 数据探索的目的？要达到的效果？到什么状态才算是合格的？

仅仅是加载数据后，做些简单的可视化，分析一下吗？那分析那些东西呢，怎么才能看出来一些东西呢？