# 股市舆情情感分类可视化系统

此Web基于Django+Bootstrap+Echarts等工具，调用了Tushare接口来获取个股交易行情数据。对于舆情文本数据采取先爬取东方财富网股吧论坛词语设置机器学习训练集，在此基础上运用机器学习朴素贝叶斯方法构建文本分类器。通过Django Web框架，将所得数据传递到前端经过Bootstrap渲染过的html，对数据使用Echarts进行图表可视化处理</br>

#### 目前的功能：

* 个股历史交易行情
* 个股相关词云展示
* 情感字典舆情预测
* 朴素贝叶斯舆情预测


-------

## Todo

* [ ] Web优化
* [ ] 横向拓展多股吧
* [ ] 横向拓展多分类器

# 系统结构
![系统架构设计](media/%E7%B3%BB%E7%BB%9F%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1.png)

# Quick Start
在项目当前目录下：
`
$ python manage.py runserver
`
</br>
浏览器打开127.0.0.1:8000

PC端实例：
![屏幕快照 2018-05-19 01.56.34](media/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202018-05-19%2001.56.34.png)
移动端：

![屏幕快照 2018-05-19 01.58.15](media/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7%202018-05-19%2001.58.15.png)
# 运行效果

##### 情感字典舆情预测：
![情感字典舆情预测1](media/%E6%83%85%E6%84%9F%E5%AD%97%E5%85%B8%E8%88%86%E6%83%85%E9%A2%84%E6%B5%8B1.png)
![情感字典舆情预测2](media/%E6%83%85%E6%84%9F%E5%AD%97%E5%85%B8%E8%88%86%E6%83%85%E9%A2%84%E6%B5%8B2.png)

##### 机器学习舆情预测：
![机器学习舆情预测1](media/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E8%88%86%E6%83%85%E9%A2%84%E6%B5%8B1.png)
![机器学习舆情预测2](media/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E8%88%86%E6%83%85%E9%A2%84%E6%B5%8B2.png)


