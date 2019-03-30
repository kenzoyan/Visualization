
# 1900与2000美国人口数据统计可视化

### 闫赓聪 201600162230 16级4班
---
### 图片
 ![logo](./A1.png ) 

---

#### 可视化层次节构
本次可视化主要用三种类型的图片分别用来表示不同的信息，合理的排布在一张图片上显示
* Grid
    * Axis chart
        * Bar Chart ----Population in age groups
        * Line Chart----Sex ratio in age goups
    * Pie Chart
        * Group share in total Population
---

#### Q1：两个年份各个年龄段的人口分布情况

- 描述：
将年龄分组作为X轴，人口数量作为左边Y轴，并且在图标中同时显示1900与2000的情况；采用堆栈的条形图，将男女同时显示在一个长条上可以非常明显的描述出在0-90之间各个年龄组的人口分布情况。
- 数据处理：
因为人口数量数据比较大，达到千万级别，在Y轴上表示精确到个位没有什么用，所以以一千（thousand）为基础单位取整数后进行表示，数字变小一点。
- 信息表达：
    - 1900年与2000年之间的人口数量悬殊十分巨大无论是在哪个年龄分组，100年生活水平有了极大的提高，人口数量有了很大的变化。
    - 1900年的人口数量随着年龄增长在不断下降，2000年是人口数量随着年龄保持稳定，并且30-45岁的人群是数量最多的。
    - 早期生活水平低下，很少有人能活到80岁以上。现在的高龄人口越来越多
- 信息丢失：
    主要着重强调了人口数量在**1900与2000的对比**、**不同年龄分组的对比**这两个维度中的信息。没有表现**男女之间的数量关系**和**人群在总人口中的占比**
----
#### Q2：人群占总人口比例

- 描述：
在折线图中，将年龄分组作为X轴，性别比列（Sex Ratio）作为右边Y轴，并且在图标中同时显示1900与2000的情况；采用折线图可以看出数据在年龄分组之间的变化情况。Y轴中以女性的数量为100为基数，数据显示的是每100个女性对应多少数量的男性。
- 数据处理：
对男女人口数量按照年龄分组进行简单的除法得出数据，保留两位小数
- 信息表达：
    - 2000年是各分组性别比例相对比较稳定，1900年是不是很稳定，在高龄组因为人口数量很少，所以得出数据比较极端，不具有很好的通用性。
    - 在中壮年时期因为劳动力的需要男性会比较多，但是可能女性的平均寿命比男性长，所有在高龄时女性较多，性别比例发生了很大的变化。
    
- 信息丢失：
    只强调了**男女性别比例**在年龄分组中的变化，其他的信息都没有得到表达。

----
#### Q3：人口性别比例

- 描述：
生成两个PIE图，分别是1900年与2000年的数据。讲所有年龄分组都在图中全部表示出来部分太多，会比较杂乱不利观看。所以简单将其分为3个组别 *Under 25*、*21--65*、*Over 65*,可以在Pie图中清晰得知各组占总人口的大致比例。
- 数据处理：
不区分男女按照分组区间的出百分比占比，保留两位小数。
- 信息表达：
    - 1900时超过65岁的人口十分稀少大约占比二十分之一，但是在2000年十分之一的人大于65岁
    - 2000年时青少年占比少于中年人占比，这种人口结构表明人口数量将会开始十分缓慢的增长或者出去人口逆增长    
- 信息丢失：
    只强调了**分组在人口数量中的总占比**，但是没有了2000年与1900年人口基数差异十分巨大的信息。

---
### 总结
条形图能够清楚的对比各组数据之间的多少情况，差距大不大。折线图用于表示一个指标的变化情况较为合适，也就是图中的**男女性别比例**。对于饼图，通过简单的百分比计算，能够清楚的得出**部分与总体**的之间的关系。在颜色上，采用颜色对比强烈红色 蓝色 橙色等让图片中的信息更加清晰。对于坐标轴，要标注相应的轴信息，可以采用不同颜色区别多个坐标轴，更加清楚。
每一个单独的数据块的数据没有默认显示出来，全显示会比较乱，所以采用鼠标浮动到哪里哪里显示数据的行为

