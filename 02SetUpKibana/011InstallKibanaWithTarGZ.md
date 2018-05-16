# 通过tar.gz安装Kibana

Kibana为linux和macOS提供了一个tar.gz格式的安装包。这是使用Kibana最简单的格式。

Kibana最新稳定版可以在[下载](https://www.elastic.co/downloads/kibana)页面找到，其它版本可以在[旧版本](https://www.elastic.co/downloads/past-releases)页面找到。

## 下载并安装Linux64位安装包

可以使用下面方式下载并安装适用于Linux的Kibana6.2.4版本:

```shell
wget https://artifacts.elastic.co/downloads/kibana/kibana-6.2.4-linux-x86_64.tar.gz
shasum -a 512 kibana-6.2.4-linux-x86_64.tar.gz 
tar -xzf kibana-6.2.4-linux-x86_64.tar.gz
cd kibana-6.2.4-linux-x86_64/ 
```

## 下载并安装macOS系统的安装包

可以使用下面方式下载并安装适用于macOS的Kibana6.2.4版本:

```
curl -O https://artifacts.elastic.co/downloads/kibana/kibana-6.2.4-darwin-x86_64.tar.gz
shasum -a 512 kibana-6.2.4-darwin-x86_64.tar.gz 
tar -xzf kibana-6.2.4-darwin-x86_64.tar.gz
cd kibana-6.2.4-darwin-x86_64/ 
```

## 通过命令行启动Kibana:

Kibana可以使用如下命令在命令行中启动：

```
./bin/kibana
```

默认情况下Kibana被运行在前台，以默认的输出方式打印日志(stdout)，可以使用 *Ctrl-C* 停止运行。

## 通过配置文件方式配置Kibana

