
# 数据预处理

### Steps of Data Exploration and Preparation

**Remember the quality of your inputs decide the quality of your output. **

Below are the steps involved to understand, clean and prepare your data for building your predictive model:

* Variable Identification
* Univariate Analysis
* Bi-variate Analysis
* Missing values treatment
* Outlier treatment
* Variable transformation
* Variable creation

##### Variable Identification 变量识别

首先需要识别出 Predictor (Input) and Target (output) 变量，然后，确定变量的数据类型和类别

##### Univariate Analysis 单变量分析

在这个阶段，我们逐个探索变量。 执行单变量分析的方法取决于变量类型是分类还是连续。 我们分别来看这些方法和统计量度的分类和连续变量：

**连续变量：** - 在连续变量的情况下，我们需要了解变量的中心趋势和扩散。 这些使用各种统计度量可视化方法进行测量；

![chart](/assets/image/1508765773622.jpg)

单变量分析也用于突出显示缺失值和异常值；

**分类变量：** - 对于分类变量，我们将使用频率表来了解每个类别的分布。 我们也可以读取每个类别下的值的百分比。 可以使用两个指标来衡量，每个类别的Count和Count％。 条形图可用作可视化。

##### Bi-variate Analysis 双变量分析



### 特别的资料

* [sklearn中关于预处理的部分](http://sklearn.lzjqsdd.com/modules/preprocessing.html)
* [A Comprehensive Guide to Data Exploration](https://www.analyticsvidhya.com/blog/2016/01/guide-data-exploration/)