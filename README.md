# spark-poc
## 总述

分为两个poc项目 spark-onlyjava和spark-springboot。都是用IntelliJ IDEA建立的maven project。

## 细述

spark-onlyjava 是纯java程序，以main方法运行。在InelliJ IDEA中直接运行（我已经配置好了Run）就可以看到运用spark对《巴黎圣母院》英文版小说的单词统计数。

spark-sprinboot 是使用springboot来发布Restful的微服务提供了两个接口 http://localhost:9191/api/wordcout 和 http://localhost:9191/api/test 现在在InetlliJ中能直接运行（我已经配置好了Run），但有serializable的错误，由于时间原因，有时间再来解决。
