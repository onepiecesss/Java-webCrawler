# 多线程爬虫和ES数据分析

它是一个
- 代码风格优良
- 语义化标准
- 逻辑代码和数据库操作分离
- 有接口
- 几乎没有本地依赖，全由pom拉取
- Checkstyle/SpotBugs自动监测
- 实现flyway数据自动迁移

的爬虫

这意味着

- 你可以很快的通过Crawler知道它到底是如何运作的
- 每一个方法和类你只需要看名称就知道它在干嘛，并不需要注释
- 完全可以爬取其他站点的数据，只要你稍稍改动已经写好归为方法的筛选机制
- 若想连接其他的数据库，只需要按照CrawlerDao接口编写即可
- ElasticSearch【7.5】相关的操作已经编写，但并不完全。
