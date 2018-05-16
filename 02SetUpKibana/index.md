# 准备

本节讲的是如何设置并运行Kibana，其中包含：

- 下载
- 安装
- 启动
- 配置
- 更新

## 平台支持

kibana提供了针对Linux,Darwin(mac)和Windows的测试(换句话说这几个平台比较靠谱)。
由于Kibana在Node.js上运行，因此我们为这些平台提供了必需的Node.js二进制文件。 不支持针对单独维护的Node.js版本运行Kibana。

## ElasticSearch(后简称es)版本

官方推荐使用和es版本相同的Kibana。

不支持使用不同主版本(major version)的Kibana和es(例如K5.x和E2.x)，同样的也不支持比es次版本更高的Kibana(如k5.1和es5.0)。

次版本比es高的kibana通常允许使用(如k5.0和es5.1)，其目的是鼓励您升级es。这种情况下的Kibana会在启动时记录一条警告，将Kibana升级到和es相同版本之后就会消失。

虽然次版本不同的Kibana和es通常可以同时使用，但我们还是鼓励使用相同版本的Kibana和es。

下一节->[安装](01InstallingKibana.md)