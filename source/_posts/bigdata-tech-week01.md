---
title: BDI-大数据技术半月刊第1期
date: 2016-02-29
---

> ** 小编导读：**
    「地图大数据智能团队」依托地图海量数据资源，运用大数据仓库、大数据计算、大数据可视化等技术，提供智能化的大数据产品与服务，我们时刻关注大数据业界前沿动态与最新技术，倾情为大家推出大数据技术半月刊，本期主要精彩内容包含：
    1.Hadoop,HBase,Spark,Flink等2015年度回顾总结及2016年展望。
    2.Tachyon更名为 Alluxio,并发布1.0版本。
    3.雅虎开源基于Hadoop/Spark分布式深度学习的CaffeOnSpark。
    4.Apache Arrow内存列式的数据结构成为事实性标准。
    5.谷歌大规模分布式跟踪系统Dapper介绍。

## 大数据业界

### [一张图清晰追溯数据库的发展历程](http://www.cbdio.com/BigData/2016-02/24/content_4651751.htm?from=timeline&isappinstalled=0)
"数据库"起源于20世经90年代，当时美国为了战争的需要，把各种情报收集在一起，存储隐藏在计算机内，叫做Data Base(DB)。随着移动互联网的发展，至今已经形成了比较成熟的Apache hadoop, Apache Spark等完善生态。

### [The Apache Software Foundation Operations Summary: November 2015 - January 2016 : The Apache Software Foundation Blog](https://blogs.apache.org/foundation/entry/the_apache_software_foundation_operations3?from=timeline&isappinstalled=0)
Apache官方对Apache基金会2015/11-2016/01期间的发展介绍。

### [Hadoop年度回顾与2016发展趋势](http://h2ex.com/569?utm_source=tuicool&utm_medium=referral)
主要介绍了HDFS和YARN在2015年相关的发展动态，包括HDFS异构存储介质，Truncate操作的支持，异构数据块的支持及YARN基于标签的调度，对长服务的支持，对Docker的支持等。同时，展望2016年YARN在通用资源管理和调度方向发展。

### [Apache HBase 2015 年发展回顾与未来展望](http://www.oschina.net/news/69616/review-and-development-of-apache-hbase)
在 2015 年，HBase 迎来了一个里程碑——HBase 1.0 release，这也代表着 HBase 走向了稳定。并提供了更加清晰的接口定义，新的接口与传统JDBC的逻辑更加相像；支持多个Region副本，Family粒度的Flush及RPC读写队列分离及堆外内存的使用等。

### [Spark 2015年回顾：四个大版本更迭、数以百计的改进](http://geek.csdn.net/news/detail/53919)
过去一年的时间里，发布了4个版本（Spark 1.3到Spark 1.6），各版本都添加了数以百计的改进，本文主要介绍了数据科学API、平台API、流计算等方面的改进和优化。

### [大数据盘点之Spark篇](http://www.thebigdata.cn/QiTa/28848.html)
介绍了Spark最新的特性以及功能,版本演化,具体介绍了在Hulu的实践经验分享。

### [Spark 2.0展望](http://mp.weixin.qq.com/s?__biz=MjM5MDAxNjkyMA==&mid=402493363&idx=2&sn=3bf800e8fa86cb51646cf48e05dd5c18&scene=1&srcid=02265eEfku5OPBFJ3HaP3Un5#rd)
Databricks CTO 马铁（Matei Zaharia）在 Spark Summit East 上做主题演讲,Spark的下一个版本将是2.0，这是该项目的一个较大的里程碑。在演讲中，他介绍了新版本将带来的一些重要特性，以及Spark在2016年的路线图。

## 大数据工具

### [一共81个，开源大数据处理工具汇总（上）](http://mp.weixin.qq.com/s?__biz=MjM5MTYwMjI3Mw==&mid=402437735&idx=1&sn=a6c57af49af292f5a5e53e5eb27aff67&scene=1&srcid=0217KNOGZpUDC07WXNcPcg6r#rd)
### [一共81个，开源大数据处理工具汇总（下），包括日志收集系统/集群管理/RPC等](http://mp.weixin.qq.com/s?__biz=MjM5MTYwMjI3Mw==&mid=402437735&idx=2&sn=41ff743982ce96240d9869f451d04011&scene=1&srcid=0217NMwrblhvlp4UEwYaCBh3#rd)
本文一共分为上下两部分。我们将针对大数据开源工具不同的用处来进行分类，并且附上了官网和部分下载链接，希望能给做大数据的同学做个参考。另外第二部分将整合大数据日志收集系统、消息系统、集群管理、基础设施、监控管理等开源工具。

### [Tachyon更名为 Alluxio，并发布1.0版本](http://geek.csdn.net/news/detail/57243)
近日，人气开源分布式内存文件系统Tachyon正式更名为Alluxio，并发布了1.0版本。自从Alluxio的第一个开源版本发布之后，我们社区的人数从1个迅速增加到200多个，这200多人来自50多个公司，这些公司将Alluxio部署到由成百上千机器构成的生产环境中。

### [Spark的下一代引擎-Project Tungsten启示录](http://blog.csdn.net/ytbigdata/article/details/50721174)
ProjectTungsten是为了大幅提升Spark应用使用CPU和Memory的效率，让Spark的性能接近硬件的极限。

### [深入理解Apache Flink核心技术](http://blog.csdn.net/codemosi/article/details/50726616)
Apache Flink（下简称Flink）项目是大数据处理领域最近冉冉升起的一颗新星，其不同于其他大数据项目的诸多特性吸引了越来越多人的关注。本文将深入分析Flink的一些关键技术与特性，希望能够帮助读者对Flink有更加深入的了解，对其他大数据系统开发者也能有所裨益。本文假设读者已对MapReduce、Spark及Storm等大数据处理框架有所了解，同时熟悉流处理与批处理的基本概念。

### [中文版：Apache Flink ：回顾2015，展望2016](http://geek.csdn.net/news/detail/55618)
### [英文版：Flink 2015: A year in review, and a lookout to 2016](http://flink.apache.org/news/2015/12/18/a-year-in-review.html)
回顾2015，总体而言Flink在功能方面已经从一个引擎发展成为最完整的开源流处理框架之一。与此同时，Flink社区也从一个相对较小，并且地理上集中的团队，成长为一个真正的全球性的大型社区，并在Apache软件基金会成为最大的大数据社区之一。

### [一些基于Kafka Connect的开源连接器](http://geek.csdn.net/news/detail/57267)
在Apache Kafka 0.9版本中，Kafka Connect特性被添加让Kafka可以建立可扩展和安全的流数据管道。

### [Druid：一个用于大数据实时处理的开源分布式系统](http://mp.weixin.qq.com/s?__biz=MjM5NzAyNTE0Ng==&mid=401980067&idx=2&sn=1cc8e69daefdc7d1b9d8a5ea645b125c&scene=4#wechat_redirect)
Druid是一个用于大数据实时查询和分析的高容错、高性能开源分布式系统，旨在快速处理大规模的数据，并能够实现快速查询和分析。

### [雅虎开源CaffeOnSpark：基于Hadoop/Spark的分布式深度学习](http://www.thebigdata.cn/QiTa/29235.html)
深度学习同学福音，雅虎认为，深度学习应该与现有的支持特征工程和传统（非深度）机器学习的数据处理管道在同一个集群中，创建CaffeOnSpark意在使得深度学习训练和测试能被嵌入到Spark应用程序。

### [中文版：Apache Arrow：内存列式的数据结构标准](http://www.iteblog.com/archives/1582) 
### [英文版：Apache Arrow unifies in-memory Big Data systems](http://www.zdnet.com/article/apache-arrow-unifies-in-memory-big-data-systems/?from=timeline&isappinstalled=0)
大数据领域又一新星，Apache Arrow项目为列式内存存储的处理和交互提供了规范。目前来自Apache Hadoop社区的开发者们致力于将它制定为大数据系统项目的事实性标准。

### [Apache Kudu 0.7.0 发布，Hadoop 存储系统](http://www.oschina.net/news/71061/apache-kudu-0-7-0) 
Apache Kudu 0.7.0 发布，该项目目前是Apache基金会的孵化项目，这也是加入Apache孵化器后的首个发布的版本。该版本包含众多的新特性和改进。高CPU效率，最大化先进处理器的效能；高IO性能，充分利用永久存储介质；对数据扫描(scan)和随机访问(random access)同时具有高性能。

### [Dapper：谷歌的大规模分布式跟踪系统](http://blog.jobbole.com/69642/)
开发Dapper是为了收集更多的复杂分布式系统的行为信息，然后呈现给Google的开发者们。这样的分布式系统有一个特殊的好处，因为那些大规模的低端服务器，作为互联网服务的载体，是一个特殊的经济划算的平台。想要在这个上下文中理解分布式系统的行为，就需要监控那些横跨了不同的应用、不同的服务器之间的关联动作。

### [55种开源数据可视化工具简介](http://mp.weixin.qq.com/s?__biz=MjM5MTYwMjI3Mw==&mid=402437735&idx=4&sn=d28183cedf3b9f2f00decbfece36fd15&scene=1&srcid=0226Z0QIAmYwlh1iCi5bgNcv#rd)
数据时代数据可视化成为理解和表达数据的有效甚至是唯一的手段。本文对55个流行的数据可视化工具开源协议，主页，文档，案例等资源的进行简单介绍。


## 大数据案例

### [扩展ElasticSearch：实现分片并可用于存储亿万文档的实践](http://mp.weixin.qq.com/s?__biz=MjM5MDAxNjkyMA==&mid=402483429&idx=1&sn=e0a1c6b790a6302e059da909bc6c04f0&scene=1&srcid=02269eQ1cRUTCp2eibB5dsGH#rd)
在本文中，将会介绍ElasticSearch相关心得：如何在扩展ElasticSearch同时，保持为公司内部与外部的商业用户提供服务，让他们可以在SignalFx中继续搜索。

### [Spark GraphX原理介绍](http://blog.csdn.net/tanglizhe1105/article/details/50740295)
GraphX是构建在Spark之上的图计算框架，它使用RDD来存储图数据，并提供了实用的图操作方法。

### [大型企业如何实现实时计算和流数据处理](http://mp.weixin.qq.com/s?__biz=MjM5Njc2NDA0MQ==&mid=402614763&idx=1&sn=4e047eebdcea6d969433a6b6a7357bb7&scene=1&srcid=0227fGV8Z2vgcdUrGtHDnFZa#rd)
对于大型企业来说，拥有着海量的数据，并且每秒中会产生大量的新数据，面对这种情况，利用大数据的实时计算来处理数据，就显得尤为重要了。对于金融行业，大量的交易账单数据，可以考虑使用实时计算。本文从头梳理一下实时计算、流式处理以及实时平台的架构和实现方案。

### [大型网站架构系列：消息队列](http://www.cnblogs.com/itfly8/p/5156155.html)
主要介绍JMS消息服务及一些常用消息中间件，主要分享JMS消息服务，常用消息中间件（Active MQ，Rabbit MQ，Zero MQ，Kafka）

### [如何用消息系统避免分布式事务](http://blog.jobbole.com/89140/)
前阵子从支付宝转账1万块钱到余额宝，这是日常生活的一件普通小事，但作为互联网研发人员的职业病，我就思考支付宝扣除1万之后，如果系统挂掉怎么办，这时余额宝账户并没有增加1万，数据就会出现不一致状况了。

### [支付宝红包的高并发挑战及解决思路](http://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=409454189&idx=1&sn=f73a7ad42aa5a4e01cb6a5e20540a5d3#rd)
本次分享系统地介绍红包对于2015年双11的准备工作，从容量评估、性能优化、稳定性保证方面解答上述问题的应对。 容量评估：基于全链路的压测手段、数据分布的模拟方法、关键场景调用量预估方法； 性能：拆分vs合并、读写分离、异步化、DB操作优化； 稳定性：削峰、降级和体验的权衡。

### [腾讯大数据平台纵览](http://mp.weixin.qq.com/s?__biz=MzA5NzkxMzg1Nw==&mid=405041351&idx=1&sn=9357f1bb16ffec5411ed5f61ffafcf81&scene=4#wechat_redirect)
腾讯业务产品线众多，拥有海量的活跃用户，每天线上产生的数据超乎想象，必然会成为数据大户。特别是随着传统业务增长放缓，以及移动互联网时代的精细化运营，对于大数据分析和挖掘的重视程度高于以往任何时候，如何从大数据中获取高价值，已经成为大家关心的焦点问题。本文主要对腾讯各个业务线数据服务基于的底层大数据平台进行了详细介绍。

### [腾讯计费平台部分布式 MySQL 数据库 TDSQL 架构分析](http://mp.weixin.qq.com/s?__biz=MzA5ODM5MDU3MA==&mid=402311796&idx=1&sn=b9bcd5cb0d1f6b8b4bb931b68f9c065c&scene=1&srcid=0225cw5Gr40aiQu0PfzbJuqY#rd)
腾讯计费平台部托管着公司90%以上的虚拟账户，如QB、Q点、包月服务、游戏的二级账户等，为了保证能顺畅支撑公司各大业务的实时在线交易，并且在各种灾难场景下数据是一致并且可用的，对系统的可用性、一致性切换要求非常高，因此计费团队历来都非常重视高一致性存储系统的建设。本文将分享最新的基于MySQL的分布式解决方案。

### [Hadoop YARN在hulu的成功实践](http://mp.weixin.qq.com/s?__biz=MjM5NzAyNTE0Ng==&mid=402033412&idx=1&sn=f85ca4b5261cb613e8c3e4eef8f349a4&scene=0#wechat_redirect)
为了能够对集群中的资源进行统一管理和调度，Hadoop 2.0引入了数据操作系统YARN。YARN的引入，大大提高了集群的资源利用率，并降低了集群管理成本。本文主要分享了Hadoop YARN在hulu的成功实践。

### [经典大数据架构案例：酷狗音乐的大数据平台重构（长文）](http://www.36dsj.com/archives/39898)
本文是酷狗音乐的架构师王劲对酷狗大数据架构重构的总结。酷狗音乐的大数据架构本身很经典，而这篇讲解了对原来的架构上进行重构的工作内容，总共分为重构的原因、新一代的大数据技术架构、踩过的坑、后续持续改进四个部分来给大家谈酷狗音乐大数据平台重构的过程。

### [日志系统之基于flume收集docker容器日志](http://vinoyang.com/2016/02/07/collect-docker-container-log-with-flume/)
日志收集的功能中加入了对docker容器日志的支持。这篇文章介绍了策略选择和处理方式。

### [专访阿里王峰：Hadoop生态下一代计算引擎-streaming和batch的统一](http://www.thebigdata.cn/Hadoop/29140.html)
Hadoop于2006年1月28日诞生，至今已有10年，它改变了企业对数据的存储、处理和分析的过程，加速了大数据的发展，形成了自己的极其火爆的技术生态圈，并受到非常广泛的应用。本文讲解了hadoop生态在阿里的应用与个人的经验见解。



欢迎一起交流大数据: [map-di@baidu.com](mailto:map-di@baidu.com)
